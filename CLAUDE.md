# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

A static site built with [Roq](https://iamroq.dev), a static site generator built on Quarkus (Java). This is a content/config-driven site, not a Java application with custom source code — there is no `src/` directory. Content, templates, data, and styling drive the build; Roq and its default theme (from Maven dependencies) do the rendering.

For full Roq framework context (available page/template variables, plugin docs, Qute syntax specifics), point to https://iamroq.dev/llms.txt or the Roq docs at https://iamroq.dev/docs/. Quarkus Web Bundler details: https://quarkus.io/guides/web-bundler. Qute template reference: https://quarkus.io/guides/qute-reference.

## Commands

```bash
roq start      # Dev mode with live-reload, served at http://localhost:8080 (use -p to change port)
roq generate   # Build the static site
roq serve      # Preview the generated static site
roq add plugin:tagging   # Add a Roq plugin
roq add theme:default    # Add/change a Roq theme
roq update               # Update to the latest Roq version
```

If the `roq` CLI isn't available, the underlying Maven/Quarkus commands work too (`./mvnw quarkus:dev`, etc.), but prefer `roq` commands since this repo has no custom Java code to justify raw Maven invocations.

There are no application tests in this repo (no `src/test`); `skipITs=true` is set in `pom.xml` by default.

## Structure

- `content/` — pages and collections. Top-level `.html`/`.md` files are pages (`index.html`, `about.md`, `blog.html`, `404.html`); `content/posts/` is the blog post collection. Each post lives in its own directory (`content/posts/<date>-<slug>/`) containing an `index.md` and any co-located assets (e.g. `blog.avif`) referenced by relative path in front matter (`image: blog.avif`).
- Every content file starts with YAML front matter (`title`, `description`, `layout`, plus page-specific fields like `image`, `tags`, `author`, or `paginate`). `layout` selects a theme layout (`home`, `page`, `blog`, `404`, etc.) — there's no local `templates/` override in this repo, so layouts come from the `quarkus-roq-theme-default` dependency.
- Templates use Qute syntax. Special Roq component tags like `{#roq/hero}`, `{#roq/featureCard}`, `{#roq/authorCard}` come from the theme. Page variables (`page.data.*`, `page.date`, `site.url`) and CDI-backed data lookups (`cdi:authors.get(id)`) are available inside content and templates — see the Roq docs for the full variable reference.
- `data/` — structured YAML data available to templates (e.g. `authors.yml` for blog author profiles, `menu.yml` for site navigation). Reference via `cdi:<filename-stem>` in templates (e.g. `cdi:authors`).
- `public/` — static assets served as-is (favicons, logos, images not tied to a specific content item).
- `web/` — JS/CSS sources bundled by the Quarkus Web Bundler. `_custom.css` overrides theme Tailwind CSS variables (e.g. `--color-accent-*`) and adds small style tweaks; see https://iamroq.dev/theme/default/#css-customization.
- `config/application.properties` — Quarkus config. Notably `quarkus.http.root-path`, which must match the GitHub Pages subpath the site is served under (currently `/quarkus-roq`) — internal links in content (e.g. `/quarkus-roq/blog`) must include this prefix.
- `.github/workflows/deploy.yml` — builds the Roq site via the `quarkiverse/quarkus-roq` GitHub Action and deploys to GitHub Pages on push to `main`, on a daily schedule, and via manual dispatch.

## Adding a blog post

Create a new directory under `content/posts/` named `<YYYY-MM-DD>-<slug>`, add an `index.md` with front matter (`title`, `description`, `image`, `tags`, `author` matching a key in `data/authors.yml`), and place any referenced images alongside it in the same directory.

## Roq skills

The README documents pulling detailed Roq skill files out of the `*-deployment` JARs for the installed `io.quarkiverse.roq` extensions:

```bash
mvn dependency:list -DincludeGroupIds=io.quarkiverse.roq -DoutputAbsoluteArtifactFilename=true
# then, for each *-deployment JAR listed:
unzip -p PATH_TO_JAR META-INF/quarkus-skill.md > .claude/skills/SKILL_NAME.md
```

Run this if deeper Roq-specific guidance is needed than what's summarized here.
