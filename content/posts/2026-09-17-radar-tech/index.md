---
title: "Radar Tech — 17 de setembro de 2026 (quinta-feira)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-09-17
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-09-17
---

Resumo diário de notícias de Tecnologia da Informação, Inteligência Artificial, Engenharia de Software, Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn.

**Fontes com problema hoje:** nenhuma falha técnica — os 4 agentes (Blogs, YouTube, X, LinkedIn) retornaram normalmente, sem tela de login nem disputa de abas. Assistir Mais Tarde não publicado hoje (0/10 novos — os ~30 vídeos mais recentes da playlist são os mesmos de 15-16/09). Bookmarks não publicado hoje (0/15 novos — snapshot ainda é o de 14/09). Vários posts do X hoje não expuseram permalink direto de post individual; usamos o link do perfil do autor como alternativa. Observação técnica: um item de hoje do perfil @bcherny colidiu, pelo cálculo de id, com um item antigo que usou o mesmo link de perfil como referência — tratado como notícia nova por conteúdo claramente distinto (vale revisar essa regra de geração de id no playbook).

## Inteligência Artificial

- **[Anthropic unifica Claude Chat e Cowork em uma única interface](https://simonwillison.net/2026/Sep/16/one-claude/)** — Anthropic elimina a escolha entre modos e passa a gerenciar automaticamente o tipo de trabalho. (Simon Willison's Weblog, prioridade alta; tema Claude)
- **[Claude ganha Docs, Slides e Design em toda conversa](https://x.com/bcherny)** — Boris Cherny (criador do Claude Code) anuncia que o Claude passa a gerar e editar documentos, apresentações e designs diretamente na conversa. (X, Boris Cherny, prioridade alta; tema Claude Code)
- **[GPT-6 Astra ajuda o Devin (Cognition) a validar seu próprio trabalho](https://x.com/OpenAIDevs)** — Post fixado da OpenAI Developers mostra o GPT-6 Astra gerando testes automaticamente antes do agente Devin enviar código. (X, OpenAI Developers, prioridade alta; temas OpenAI, Codex)
- **[Harnesses de coding agent nem sempre ajudam o modelo](https://x.com/hwchase17)** — Harrison Chase comenta pesquisa que avaliou 7 modelos rodando em Claude Code, Codex e outros harnesses: nem sempre há benefício em usar um harness nativo. (X, Harrison Chase, prioridade alta; temas Harness Engineering, Claude Code)
- **[O agente de codificação não é o gargalo, sua especificação é](https://medium.com/write-a-catalyst/the-coding-agent-isnt-the-bottleneck-your-spec-is-6052f8bf465c)** — Defende que specs precisas são o fator crítico em workflows agentic de desenvolvimento. (Medium - tag AI; tema Spec Driven Development)
- **[Anthropic congelou 89 pins de plugins Claude, 27 não batem mais com o repositório](https://aiadvances.org/anthropic-froze-89-claude-plugin-pins-27-no-longer-match-the-repo-they-point-at-5a63b2fc0266)** — Inconsistências identificadas no marketplace de plugins do Claude. (Medium - tag AI; tema Claude)
- **[Building Codex with Tibo Sottiaux](https://newsletter.pragmaticengineer.com/p/building-codex-with-tibo-sottiaux)** — Criador do Codex discute a evolução da ferramenta em entrevista. (The Pragmatic Engineer; tema Codex)
- **[Dream-RSI: auto-melhoria recursiva via mundos evolutivos](https://arxiv.org/abs/2609.14858)** — Pesquisa sobre agentes que se auto-aprimoram rodando em ambientes simulados evolutivos. (Hacker News)

## Engenharia de Software

- **[IBM Bob em GitHub Actions: build para publicação em Markdown](https://www.the-main-thread.com/p/github-pages-ibm-bob-markdown-site)** — Gera site estático a partir de Markdown via GitHub Actions. (The Main Thread, prioridade alta)
- **[Modern CI/CD: Docker Optimization & Zero-Downtime Deployments](https://dev.to/mtahir27/modern-cicd-automated-audits-docker-optimization-zero-downtime-deployments-4nl1)** — Pipeline CI/CD integrando SonarQube/Trivy e rolling updates no Kubernetes. (Dev.to - tag Kubernetes, prioridade alta)
- **[GitHub Copilot: agent runtime reescrito de TypeScript para Rust](https://x.com/brunoborges)** — Thread detalha o custo de tokens (~US$ 120 mil) e a migração do CLI/SDK para "Runtime/SDK". (X, @brunoborges, não catalogado; tema GitHub Copilot)
- **[Nova skill "/pr" para Claude Code](https://x.com/mattpocockuk)** — Skill pensada para gerar PRs revisáveis rapidamente, reaproveitando a linguagem de domínio do time. (X, @mattpocockuk, não catalogado; tema Workflows de desenvolvimento com IA)
- **Stanford lança "Shepherd", runtime tipo Git para agentes** — Versiona processo e filesystem de um agente (copy-on-write); elevou a taxa de sucesso em pair-coding de 28,8% para 54,7% no CooperBench. (LinkedIn, Daily Dose of Data Science; tema Agentic AI — sem link direto)
- **Viktor Gamov cria tavily-java, SDK Java 21 para Tavily** — SDK com agente de exemplo em Quarkus + LangChain4j usando Claude. (LinkedIn, Viktor Gamov; temas Java, Quarkus — sem link direto)
- **["Paid Media Agent": agente open-source com Managed Deep Agents (LangChain)](https://x.com/amal_irgashev)** — Agente open-source para análise e gestão de campanhas pagas, construído sobre o framework Managed Deep Agents da LangChain. (X, @amal_irgashev, não catalogado; tema LangChain)
- **Sergio Bergmann sobre reduzir gasto de tokens em engenharia agentic** — Trata contexto como recurso de engenharia: carregar instruções por escopo, comprimir artefatos, compactar logs. (LinkedIn, Sergio Bergmann — sem link direto)

## Arquitetura de Software

- **[Dropbox evolui plataforma Riviera para cargas de IA](https://www.infoq.com/news/2026/09/dropbox-riviera-ai-platform/)** — Suporte a 300+ formatos com fluxos de IA e RAG. (InfoQ)
- **[DDD e Arquitetura Hexagonal na era da IA](https://sahinyelkenci.medium.com/ai-çağında-anlama-yüzeyini-küçültmek-ddd-ve-hexagonal-mimari-ile-aradığımızı-kolayca-bul-0837172af657)** — Uso de DDD + arquitetura hexagonal para reduzir a superfície de complexidade de entendimento de sistemas. (Medium - tag Software Architecture; tema DDD)
- **[Scaling Telco Autonomy com GNNs e Distributed GraphFlow](https://cloud.google.com/blog/products/databases/run-gnns-at-scale-with-ease-introducing-distributed-graphflow/)** — Digital twin em Spanner Graph com redes neurais de grafos para autonomia em telecom. (Google Cloud Blog)
- **[How LLMs Can Find a Needle in a Haystack](https://blog.bytebytego.com/p/how-llms-can-find-a-needle-in-a-haystack)** — Como LLMs localizam informação relevante via embeddings e busca vetorial. (ByteByteGo)
- **[Do LLMs Have the Memory of a Goldfish?](https://blog.bytebytego.com/p/do-llms-have-the-memory-of-a-goldfish)** — Diferencia memória do modelo vs. memória gerenciada pela aplicação. (ByteByteGo)
- **[Fragments: September 16](https://martinfowler.com/fragments/2026-09-16.html)** — Reflexões de Martin Fowler sobre ataques de agentes de IA (incidente RubyGems) e autonomia de sistemas. (Martin Fowler)
- **[Workflows duráveis no Postgres sem orquestrador externo](https://x.com/InfoQ)** — Uso de SKIP LOCKED para trabalho concorrente, checkpoints para idempotência e leases para recovery de falhas. (X, @InfoQ, não catalogado; tema Back-End)
- **Quando usar cada padrão de arquitetura de agente** — Compara single-shot, loop ReAct, separar planejamento de execução, reflexão e camada de verificação separada para ações consequentes. (LinkedIn, Alex Wang — sem link direto)

## Cloud

- **[AWS reimagines the getting started experience](https://aws.amazon.com/blogs/aws/aws-reimagines-the-getting-started-experience/)** — Nova experiência simplificada para iniciantes, com créditos e permissões geridas. (AWS Blog)
- **[Introducing new session management tools (Google Cloud)](https://cloud.google.com/blog/products/identity-security/introducing-new-session-management-tools-with-native-granular-controls/)** — Controles granulares de sessão via Terraform, gcloud CLI e APIs. (Google Cloud Blog)
- **[Best practices for handling cloud reliability incidents](https://cloud.google.com/blog/topics/developers-practitioners/cloud-reliability-incident-handling-best-practices/)** — Ciclo Verificar → Investigar → Relatar → Resolver → Revisar para incidentes. (Google Cloud Blog)
- **[Cloudflare lança primeiro "modelo stealth" no AI Gateway](https://x.com/CloudflareDev)** — Modelo "Union Alpha" busca o melhor custo-benefício entre os modelos disponíveis no AI Gateway. (X, @CloudflareDev, não catalogado)
- **AWS GameDay ao vivo: "Real Estate Adventure"** — Construção colaborativa de um time de agentes de IA usando Amazon Bedrock, AgentCore e Strands Agents SDK. (LinkedIn, AWS — sem link direto)

## Tecnologia da Informação

- **[Zed lança Delta, alternativa ao GitHub baseada em agentes](https://thenewstack.io/zed-delta-github-alternative/)** — Zed apresentou o Delta, plataforma que substitui pull requests por threads colaborativas para agentes de IA. (The New Stack)
- **[Java 27 é lançado com criptografia pós-quântica](https://www.infoq.com/news/2026/09/java27-released/)** — Nova versão traz criptografia pós-quântica, Helidon 27 e JavaFX 27. (InfoQ; tema Java)
- **[Shopify abandona React Native por Swift/Kotlin](https://www.infoq.com/news/2026/09/shopify-drops-react-native/)** — Shopify reescreve apps nativos citando ganhos de produtividade trazidos por IA. (InfoQ)
- **[Modelo de 4B gera planos de query 81% mais rápidos que o Postgres](https://rohanbansal.com/qorl)** — Modelo de IA especializado otimiza planos de execução de banco de dados, superando o otimizador nativo do Postgres. (Hacker News; tema Back-End)
- **[Pequenos truques de programação que importam](https://will-keleher.com/posts/small-programming-tricks-matter/)** — Coleção de técnicas práticas de baixo custo que têm grande impacto na qualidade do código no dia a dia. (Hacker News)
