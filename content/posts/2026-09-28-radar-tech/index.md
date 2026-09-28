---
title: "Radar Tech — 28 de setembro de 2026 (segunda-feira)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-09-28
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-09-28
---

Resumo diário de notícias de Tecnologia da Informação, Inteligência Artificial, Engenharia de Software, Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn.

**Fontes com problema hoje:** nenhuma falha técnica. As 23 fontes de `blogs_rss` responderam normalmente — algumas sem item na janela de 24-48h (AWS Blog, Azure Blog, Google Cloud Blog, Medium - tag Kubernetes) e outras filtradas por baixa relevância (Hacker News Frontpage, Medium - tag Artificial Intelligence); os 28 canais do YouTube carregaram sem erro (só 8 tiveram vídeo novo nas últimas ~48h, totalizando 15 vídeos); as timelines "Para você" e "Seguindo" do X carregaram normalmente, sem tela de login (a "Para você" veio dominada por anúncios de produtos de IA, filtrados); o feed do LinkedIn carregou normalmente, sem tela de login. Um link de vídeo do canal GitHub veio com um caractere suspeito no ID (possível erro de captura) e foi descartado da seleção por precaução. Checagem pontual opcional de contas/perfis específicos não foi executada por restrição de tempo (X, passo 5) ou cobriu só a página da Anthropic e Rodrigo Branas no LinkedIn (sem novidade técnica recente deste último). **Deduplicação:** 14 candidatos (incluindo o lançamento do Claude Opus 5.5, a descoberta do sistema enzimático da Anthropic, o benchmark IBM Bob code-review-graph e o post "Emerging Standards Behind AI Agents") já haviam sido publicados nos últimos 14 dias e foram descartados da seleção de hoje. **Assistir Mais Tarde:** publicado hoje — 26 vídeos novos (ver post/seção separada). **Bookmarks:** não publicado hoje (0/15 novos — o snapshot semanal em `collected/bookmarks-latest.md` segue com data de 21/09, sem itens novos desde a última publicação em 22/09; vale checar se a Tarefa Agendada de sincronização de bookmarks no Windows ainda está rodando).

## Inteligência Artificial

- **[Muse, o agente pessoal de IA da Meta, assume responsabilidade por falha em entrega automática](https://simonwillison.net/2026/Sep/28/muse-ai-agent/)** — Simon Willison comenta o primeiro caso documentado do agente Muse assumindo responsabilidade por um erro operacional. (Simon Willison's Weblog, prioridade alta, temas Python/Agentic AI)
- **[2026 in LLMs (so far)](https://simonwillison.net/2026/Sep/27/2026-in-llms-so-far/)** — Panorama dos principais desenvolvimentos em LLMs em 2026, incluindo incidentes de segurança com agentes. (Simon Willison's Weblog, prioridade alta, temas Python/Agentic AI)
- **[Proaction usa Codex e GPT-6 Astra para acelerar operações de frota](https://openai.com/index/proaction)** — Caso de uso de produção com Codex e GPT-6 Astra, com ganho de 60% em vendas e 75+ horas economizadas. (OpenAI News, prioridade alta, temas OpenAI/Codex)
- **[Organizações de saúde usam Claude no combate a surto de Ebola na RDC](https://www.anthropic.com/features/ebola-response)** — Aplicação do Claude em resposta a emergência de saúde pública. (Anthropic News, prioridade alta, temas Anthropic/Claude)
- **[Hamel Husain e Shreya Shankar: FAQ sobre validar LLM-como-juiz contra rótulos confiáveis](https://x.com/HamelHusain)** — Guia prático sobre avaliação de classificadores e juízes LLM, com foco em confiabilidade do processo de avaliação. (X, @HamelHusain/@sh_reya, prioridade alta, tema Eval Driven Development)
- **[Claude: Building verification loops in Claude Code](https://www.youtube.com/watch?v=mQZB0l-rhxE)** — Vídeo do canal oficial sobre construir loops de verificação em fluxos de trabalho com Claude Code. (YouTube - Claude, prioridade alta, temas Claude/Anthropic)
- **[Cole Medin: The Biggest AI Coding Agent Upgrade Is Already on Your Machine?!](https://www.youtube.com/watch?v=td52e2tQFIU)** — Análise de uma atualização relevante para agentes de codificação com IA. (YouTube - Cole Medin, prioridade alta, temas Agentic AI/Workflows de desenvolvimento com IA)
- **[Nick Saraev: Stop Listening To AI News](https://www.youtube.com/watch?v=x55Fj_syFcI)** — Reflexão contrária ao excesso de hype/ruído nas notícias de IA, com foco em o que realmente importa para quem constrói. (YouTube - Nick Saraev, prioridade alta, temas Claude Code/Codex/Workflows de desenvolvimento com IA)

## Engenharia de Software

- **[IBM Bob ACP em Quarkus: um control plane local, não um chat compartilhado](https://www.the-main-thread.com/p/ibm-bob-acp-quarkus-web)** — Cliente web via Agent Client Protocol sobre Quarkus, com aprovação humana no loop. (The Main Thread, prioridade alta, temas Quarkus/Java/Workflows de desenvolvimento com IA)
- **[jqwik Property-Based Testing: adicione properties ao lado dos exemplos JUnit](https://www.the-main-thread.com/p/quarkus-jqwik-property-based-testing)** — Testes baseados em propriedades em app Quarkus revelam defeitos de arredondamento não vistos em testes tradicionais. (The Main Thread, prioridade alta, temas Quarkus/Java)
- **[Como proteger uma aplicação Spark Java com OIDC usando pac4j](https://dev.to/jleleu/how-to-secure-a-spark-java-client-application-with-openid-connect-oidc-using-pac4j-1nb1)** — Passo a passo de integração OIDC em app Spark Java. (Dev.to - tag Java, prioridade alta, tema Java)
- **[Reader-Writer Lock em Java: resolvendo o problema da biblioteca em LLD](https://dev.to/machinecodingmaster/reader-writer-lock-in-java-solving-the-library-problem-in-lld-omj)** — Implementação de `ReentrantReadWriteLock` para cenários read-heavy em design de baixo nível. (Dev.to - tag Java, prioridade alta, tema Java)
- **[Oracle Developers: Build with Oracle AI Database and ORDS MCP Servers](https://www.youtube.com/watch?v=Ep79vySXxvU)** — Como construir com o banco de dados de IA da Oracle e servidores MCP via ORDS. (YouTube - Oracle Developers, prioridade alta, temas Java/Cloud Native)
- **[GitHub: How to use GitHub Copilot with WSL on Windows](https://www.youtube.com/watch?v=4VnQGyKtMk0)** — Guia de uso do GitHub Copilot em ambiente WSL no Windows. (YouTube - GitHub, prioridade alta, tema GitHub Copilot)
- **[Java News Roundup: TornadoVM 7.0, Groovy 6.0, GraalVM, Hibernate, Quarkus, Gradle, Maven](https://www.infoq.com/news/2026/09/java-news-roundup-sep21-2026/)** — Roundup semanal do ecossistema Java com GA do TornadoVM 7.0 e Groovy 6.0. (InfoQ)
- **[O agente não quebrou seus controles de segurança. Ele os contornou.](https://thenewstack.io/inside-out-agent-security/)** — Controles de segurança tradicionais não alcançam agentes autônomos que operam "por dentro" do sistema. (The New Stack)

## Arquitetura de Software

- **[Graph Engineering: como construir sistemas de agentes de IA que não quebram em escala](https://x.com/KirkDBorne)** — Artigo compartilhado por Kirk Borne sobre desenhar sistemas de agentes como grafos, não como linha reta, para escalar sem quebrar. (X, @KirkDBorne, não catalogado)
- **[KodeCapsule (parte 3): migrando de monólito para microsserviços sem quebrar produção](https://www.linkedin.com/feed/)** — Série sobre o Strangler Fig Pattern, extração incremental de capacidades de negócio, estratégia de migração de dados e rollback, com exemplos em Java/Spring Boot. (LinkedIn, KodeCapsule)

*Dia mais fraco que o normal em Arquitetura de Software: a maioria dos candidatos encontrados hoje (CobbleDB na Perplexity, "Diagnosticando débito técnico", "One key, one order") já havia sido publicada nos últimos 14 dias.*

## Cloud

- **[Uber separa intenção de escalonamento da execução em sua plataforma Kubernetes](https://www.infoq.com/news/2026/09/uber-kubernetes-scaling/)** — Novo controlador ServiceScale da Uber para múltiplos orquestradores no K8s. (InfoQ)
- **[AWS introduz restrições de chave estrangeira no Aurora DSQL](https://www.infoq.com/news/2026/09/aurora-dsql-foreign-keys/)** — Suporte nativo a foreign keys no banco distribuído Aurora DSQL. (InfoQ)
- **[Snapshots de pods no GKE cortam tempo de carregamento de modelos em até 89%](https://www.infoq.com/news/2026/09/gke-pod-snapshots-benchmarks/)** — Uso de snapshots de pods para reduzir latência de inicialização de cargas de IA no GKE. (InfoQ)
- **[OpenTelemetry e Prometheus estão se entendendo melhor — o que ainda falta?](https://thenewstack.io/opentelemetry-prometheus-observability-interoperability/)** — Interoperabilidade melhora, mas modelos de dados de observabilidade ainda estão desalinhados. (The New Stack)
- **[Red Hat e NVIDIA: guardrails de modelo sozinhos não protegem IA autônoma](https://x.com/RedHat)** — Anúncio de controles de segurança estendidos por cloud híbrida para cargas de IA autônoma. (X, @RedHat, não catalogado)
- **[Vercel disponibiliza modelo Ember-1 (Fireworks) no AI Gateway](https://x.com/vercel_dev)** — Novo modelo com 1M tokens de contexto e suporte a input de imagem e tool use. (X, @vercel_dev, não catalogado)

## Tecnologia da Informação

- **[Evitando vendor lock-in com uma abordagem open-source: a perspectiva de um desenvolvedor](https://thenewstack.io/avoiding-vendor-lock-in/)** — Como software aberto preserva opções arquiteturais frente a dependências invisíveis. (The New Stack)
- **[InfoQ: a revolução da IA falha sem segurança psicológica para desenvolvedores](https://www.youtube.com/watch?v=l0tlBS_BB74)** — Conversa sobre como a adoção de IA no desenvolvimento depende de ambientes psicologicamente seguros para os times. (YouTube - InfoQ)
- **[McKinsey: o hiato entre tecnologias transformadoras e os sistemas para realizá-las pode fechar mais rápido com IA](https://x.com/McKinsey)** — Peça de opinião sobre adoção acelerada de tecnologia via IA. (X, @McKinsey, não catalogado)
