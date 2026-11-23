---
title: "Radar Tech — 23 de novembro de 2026 (segunda-feira)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-11-23
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-11-23
---
**Categorias de hoje:** Inteligência Artificial (7) · Engenharia de Software (7) · Arquitetura de Software (7) · Cloud (7) · Tecnologia da Informação (6) — 34 itens no total, coletados de blogs/RSS, YouTube, X e LinkedIn.

## Inteligência Artificial

- **[Anthropic completa IPO a US$ 83/ação na Nasdaq](https://www.anthropic.com/news/ipo-close)** — Encerramento da oferta pública inicial, com 1,127 bilhão de ações Classe A. *(Anthropic News, via LinkedIn e X)*
- **[Introducing GPT-6.2 Astra and GPT-6.2 Sol](https://openai.com/index/introducing-gpt-6-2-astra-sol)** — Novos modelos da OpenAI: Astra para trabalho profissional/programação e Sol, mais barato, para workflows agênticos. *(OpenAI News, via LinkedIn e X)*
- **[The Harness Is the New Operating System](https://www.infoq.com/news/2026/11/harness-new-operating-system/)** — QCon SF: o "harness" em torno do modelo define o comportamento seguro de um agente, tese reforçada por paper do MIT CSAIL visto no X. *(InfoQ)*
- **Addy Osmani (Anthropic) anuncia o Code Mode do Claude Code** — Recurso experimental deixa o Claude orquestrar chamadas de ferramenta escrevendo e executando JavaScript. *(LinkedIn — Addy Osmani)*
- **[Claude Code vazou segredos via "Don't Ask Again"](https://www.infoq.com/news/2026/11/claude-code-leaking-secrets/)** — Apiiro encontrou segredos expostos em repositórios públicos por causa do armazenamento de permissões. *(InfoQ)*
- **[Inside the Codex sandbox](https://openai.com/index/inside-the-codex-sandbox)** — Como o Codex limita acesso a sistema de arquivos e rede em macOS, Linux e Windows. *(OpenAI News)*
- **[The Most Dangerous AI Agent Is an Overly Helpful One](https://www.youtube.com/watch?v=k87Iqft91j8)** — Cole Medin discute os riscos de agentes excessivamente "prestativos" em produção. *(YouTube, Cole Medin)*

## Engenharia de Software

- **O "Agentic Engineering Stack" em 5 camadas** — Pavan Belagatti descreve Model, Harness, Loop, Graph e Agentic SDLC como as camadas das "software factories" de 2027. *(LinkedIn — Pavan Belagatti)*
- **[Software factories and code reviews with Harjot Gill](https://newsletter.pragmaticengineer.com/p/software-factories-and-code-reviews)** — CEO da CodeRabbit conta como gastou US$250 mil/mês em agentes e construiu CI próprio em uma semana. *(The Pragmatic Engineer, via LinkedIn)*
- **Satya Nadella: desacoplar harness, memória e modelo evita lock-in** — Gergely Orosz entrevista o CEO da Microsoft sobre software factories internas. *(LinkedIn — Gergely Orosz, também em vídeo no canal The Pragmatic Engineer)*
- **[IBM Bob Hooks in Java: Check Agent Actions Before Issuing a Build Permit](https://www.the-main-thread.com/p/ibm-bob-hooks-java-jbang-game)** — Hooks determinísticos liberam/bloqueiam ações de agentes antes do build. *(The Main Thread, Markus Eisele)*
- **JLib Inspector v1.0.1** — Bruno Borges lança ferramenta Java que mostra quais JARs uma aplicação carrega em runtime. *(X — Bruno Borges)*
- **[Evals for AI Engineers](https://blog.bytebytego.com/p/evals-for-ai-engineers)** — Modelo "Three Gulfs" mapeia onde o desenvolvimento com LLMs costuma falhar. *(ByteByteGo Newsletter)*
- **9 dicas de performance com PostgreSQL, JPA e Hibernate** — Vlad Mihalcea detalha isolamento de transações e outras otimizações. *(X — Vlad Mihalcea)*

## Arquitetura de Software

- **[Data Contracts](https://martinfowler.com/articles/data-contracts.html)** — Simon Harrer e Arif Wider aplicam práticas de design de API a contratos de dados. *(Martin Fowler)*
- **[Deterministic Simulation Testing](https://martinfowler.com/articles/deterministic-simulation-testing.html)** — Unmesh Joshi simula relógio/rede/storage para tornar reproduzíveis testes distribuídos, com exemplo em Java. *(Martin Fowler)*
- **Werner Vogels: AWS Well-Architected Framework reorganizado** — Em "Cloud Foundations" e "Cloud Workloads", revisável por humanos e agentes de IA. *(LinkedIn — Werner Vogels)*
- **[What DORA Found: AI Amplifies Good and Bad Systems Alike](https://www.youtube.com/watch?v=iF_JsNZSTo4)** — Como a IA acelera tanto boas quanto más práticas arquiteturais. *(YouTube, InfoQ)*
- **[Distributed by Design, Not by Deployment](https://medium.com/@jeronimo.lopez.ledesma/distributed-by-design-not-by-deployment-24c6832a0a3f)** — Fronteiras de domínio devem moldar o sistema antes do deployment. *(Medium — tag Software Architecture)*
- **Harrison Chase comenta lacunas do "Agent platform 2027"** — Observability/evals e governance como lacunas em aberto. *(X — Harrison Chase)*
- **[Find Distributed Systems Bugs Before You Write Code](https://www.youtube.com/watch?v=v-0G54nmEtM)** — Técnicas para encontrar bugs de sistemas distribuídos na fase de design. *(YouTube, InfoQ)*

## Cloud

- **[AWS Lambda agora suporta instâncias GPU para Event Functions](https://aws.amazon.com/blogs/aws/aws-lambda-now-supports-gpu-instances-for-event-functions-on-lambda-managed-instances/)** — Provisionamento gerenciado de GPU para inferência de ML, mídia e renderização. *(AWS Blog, também em InfoQ)*
- **[Google doa Agent Substrate e gVisor à CNCF](https://www.infoq.com/news/2026/11/google-substrate-gvisor-cncf/)** — Coloca infraestrutura de agentes de IA sob governança open source neutra. *(InfoQ)*
- **[Google rastreia timeouts de API do GKE até bug do kernel Linux](https://www.infoq.com/news/2026/11/gke-kernel-network-bug/)** — Três bugs combinados bloquearam cerca de 800 desenvolvedores. *(InfoQ)*
- **AWS: British Airways moderniza 750 repositórios legados com IA agêntica** — Caso de modernização enterprise em escala. *(LinkedIn — AWS)*
- **[Azure Cobalt 200: VMs GA otimizadas para workloads agênticos](https://msft.it/6047xEb0V)** — Disponibilidade geral de VMs para cargas agênticas. *(LinkedIn — Microsoft Azure)*
- **Gravações do Cloud Native AI + Inference Day 2026 (KubeCon)** — Palestras sobre rodar workloads de IA/inferência em Kubernetes. *(X — Yuan Tang)*
- **Queda global do Outlook/M365 por mais de 6 horas** — Microsoft enfrentou o "thundering herd problem" ao restaurar servidores. *(LinkedIn — Gergely Orosz)*

## Tecnologia da Informação

- **[PostgreSQL 19 lançado](https://www.infoq.com/news/2026/11/postgresql-19-released/)** — Reorganização de tabelas sem downtime e novos controles de planejamento de consultas. *(InfoQ)*
- **[What we learned operating auth for 1k APIs](https://nango.dev/blog/lessons-from-operating-api-auth-for-900-apis/)** — Lições de operar autenticação para cerca de mil APIs externas. *(Hacker News)*
- **[0rwx — A simple model of AI usage, inspired by Unix permissions](https://0rwx.com/)** — Modelo de controle de uso de IA inspirado em permissões Unix. *(Hacker News)*
- **[Localcode, open source agentic coding on your Mac](https://github.com/mjwsolo/localcode)** — Agente de programação local acionável com um único comando. *(Hacker News)*
- **[What Happened to Silicon Valley?](https://www.oreilly.com/radar/what-happened-to-silicon-valley/)** — Análise das mudanças recentes no ecossistema do Vale do Silício. *(Hacker News)*
- **[GL.iNet Security Notice 2026-11-20](https://www.gl-inet.com/en-us/blogs/blog/glinet-security-notice-2026-11-20)** — Aviso de segurança sobre vulnerabilidades em roteadores GL.iNet. *(Hacker News)*

## Fontes com problema hoje

- **Lacuna de 6 dias**: a rotina não gerou resumo entre 18/11 e 22/11/2026 — a última edição antes desta era a de 17/11/2026. Janela de coleta ampliada para ~6-7 dias para compensar; dedup contra o registro (14 dias) não descartou nenhum candidato.
- **Microsoft Azure Blog** — falhou de novo (bloqueado por `robots_disallowed`).
- **Dev.to - tag Kubernetes**, **HackerNoon** e **Hands On Kubernetes** (Substack) — sem conteúdo relevante na janela (parecem estagnados, não é falha de coleta).
- **Assistir Mais Tarde**: não publicado hoje — só 7 vídeos novos desde a última publicação (limiar: 10).
- **Bookmarks**: não publicado hoje — 13 bookmarks novos desde a última publicação (limiar: 15). O snapshot semanal continua datado de 09/11/2026, 14 dias sem atualização — vale checar a Tarefa Agendada local.
