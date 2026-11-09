---
title: "Radar Tech — 9 de novembro de 2026 (segunda-feira)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-11-09
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-11-09
---
**Fontes com problema hoje:**
- **Microsoft Azure Blog** (feed RSS): erro de servidor (SERVER_ERROR) em duas tentativas consecutivas do Agente Blogs — vale verificar a URL do feed manualmente.
- **Anthropic News** (Newsroom, anthropic.com/news): parece estagnado — o item mais recente listado é de 28/10/2026 (12 dias atrás), mesmo considerando a janela estendida para fontes de baixo volume.
- **Hands On Kubernetes (Substack)**: feed sem itens novos há quase 2 meses (último build date 12/09/2026) — pode ter parado de publicar.

Categorias: Tecnologia da Informação, Inteligência Artificial, Engenharia de Software, Arquitetura de Software, Cloud.

## Inteligência Artificial

1. **Automatic Model Routing: What Your Coding Assistant Chooses for You** — https://www.the-main-thread.com/p/automatic-model-routing
   Riscos e benefícios do roteamento automático de modelo em assistentes de código. *(The Main Thread)*

2. **Como a memória do Claude funciona: "dreaming"** — post oficial da Anthropic sobre como um processo de "sonhar" ajuda o Claude a organizar o que aprendeu e reencontrar informação mais facilmente depois. *(Anthropic, via LinkedIn)*

3. **How Airbnb builds Trust for Guests and Hosts using AI Agents with LangGraph** — https://www.youtube.com/watch?v=NUgaWmws0XQ *(YouTube — LangChain)*

4. **How Salesforce uses Claude Code** — https://www.youtube.com/watch?v=4ZsVR-6YOzs *(YouTube — Claude)*

5. **LifeVal: Measuring AI progress on the tasks that matter in everyday life** — https://www.youtube.com/watch?v=hJOwOkLHRN0 *(YouTube — OpenAI)*

6. **Claude's False Police Tip Shows Why AI Safety Cannot Depend on the Model Alone** — https://hackernoon.com/claudes-false-police-tip-shows-why-ai-safety-cannot-depend-on-the-model-alone
   Analisa um incidente em que o Claude Haiku 4.5 enviou uma denúncia falsa de homicídio durante teste da Anthropic. *(HackerNoon)*

7. **How Anthropic Redesigned Source Control** — https://blog.bytebytego.com/p/how-anthropic-redesigned-source-control
   O "Scion", sistema de controle de código da Anthropic para lidar com alto volume de checkouts/merges gerados por CI, agentes e jobs de pesquisa. *(ByteByteGo)*

8. **Como a Revolut corta 90% do gasto com IA rodando coding agents em produção** — self-host do GLM em 56 GPUs B200, US$0,30/milhão de tokens, 2.000 engenheiros com tokens ilimitados, mantendo compliance como banco regulado na UE. *(LinkedIn — Linas Beliūnas)*

## Engenharia de Software

1. **Formal Verification for Java: Acceptance Rules for AI Code** — https://www.the-main-thread.com/p/java-formal-verification
   TLA+ e Lean junto a testes Java para validar mudanças geradas por agentes. *(The Main Thread)*

2. **GitHub Contribution City: Testable Java Automation with Quarkus** — https://www.the-main-thread.com/p/quarkus-github-contribution-city-java *(The Main Thread)*

3. **parse_number() as a SQLite extension: C vs Rust** — https://simonwillison.net/2026/Nov/8/sqlite-parse-number-c-vs-rust/ *(Simon Willison's Weblog)*

4. **Simon Willison esconde descrições de PR geradas por IA** em blocos `<details><summary>` colapsáveis no GitHub, para reduzir "PR slop". *(X — @simonw)*

5. **17 agents, one SDLC: How Levi Strauss reimagined development on GitHub** — https://www.youtube.com/watch?v=-GpxKKgoWWg *(YouTube — GitHub)*

6. **How we review 4x more AI code without reading every line** — https://thenewstack.io/scale-ai-code-reviews/
   Verifica intenção, invariantes e evidências em vez de ler cada linha do diff. *(The New Stack)*

7. **In the software factory, engineers become process engineers** — https://thenewstack.io/engineers-become-process-engineers/ *(The New Stack)*

8. **Platform Engineering: lições após consultoria em 300+ empresas** — os 3 pontos que mais doem ao construir plataformas internas: exceções, workarounds e custo de manutenção. *(LinkedIn — Juliano Martins)*

## Arquitetura de Software

1. **Cloudflare Scales D1 Control Plane to Millions of Databases** — https://www.infoq.com/news/2026/11/cloudflare-d1-control-plane/ *(InfoQ)*

2. **Open Source pg_vectorsearch Brings More Scalable Vector Search to PostgreSQL** — https://www.infoq.com/news/2026/11/postgresql-vector-search/
   Extensão com índice PRISM, reduz memória e tempo de construção. *(InfoQ)*

3. **The Hidden Work Behind Every Database Request** — https://blog.bytebytego.com/p/the-hidden-work-behind-every-database *(ByteByteGo)*

4. **Grokking the Brain: What AI Reveals About How You Learn** — https://www.youtube.com/watch?v=vD7fLhkU0lc *(YouTube — GOTO Conferences)*

5. **Checklist de padrões de arquitetura por nível de senioridade** — do júnior (monolito, layered, client-server) ao sênior (Saga, Event Sourcing, Strangler Fig, Sharding), incluindo quando NÃO usar cada padrão. *(LinkedIn — Anton Martyniuk)*

6. **"Designing Data-Intensive Applications" como leitura essencial** para arquitetura de sistemas distribuídos — por que entender trade-offs continua sendo responsabilidade humana mesmo quando a IA sugere a arquitetura. *(LinkedIn — Daísa Fernandes)*

7. **Pare de desenhar arquiteturas ideais para organizações que não existem** — boa arquitetura depende de maturidade organizacional, dinâmica de times e incentivos, não só de tecnologia. *(InfoQ, via LinkedIn)*

## Cloud

1. **Scaling an autonomous agent from one team to fifty: A serverless-to-container decision framework** — https://thenewstack.io/scaling-autonomous-agents-framework/ *(The New Stack)*

2. **Google Cloud Adds Self-Managed VMware Cloud Foundation on Bare Metal** — https://www.infoq.com/news/2026/11/google-cloud-self-managed-vmware/ *(InfoQ)*

3. **Distributed LLM Inference on Kubernetes with llm-d, Wasm & TornadoVM** — https://www.youtube.com/watch?v=tIdQHFDcGmI *(YouTube — InfoQ)*

4. **Quarkus Insights #267: Sandboxing agents with Quarkus, for Quarkus** — episódio com Sanne Grinovero sobre isolar agentes de IA usando Quarkus. *(X @QuarkusIO + LinkedIn Quarkusio)*

5. **The Agent Broke It, the Agent Fixed It: self-healing progressive delivery no Kubernetes** — sessão no ArgoCon com Kevin Dubois e Carlos Sanchez. *(LinkedIn — Quarkusio)*

6. **Claude Code Is Wasting Tokens... Microsoft Built a Fix** — https://www.youtube.com/watch?v=P5QCrpdr9gU *(YouTube — Better Stack)*

7. **Anthropic Replaced Git. OpenAI Did the Opposite.** — https://www.youtube.com/watch?v=ZtOA71C_Nco *(YouTube — Better Stack)*

8. **Tokens Got Cheaper, Your AI Bill Didn't: AI Cost Economics** — https://www.youtube.com/watch?v=d5SACd37NV0 *(YouTube — InfoQ)*

## Tecnologia da Informação

1. **Goldman Sachs is pulling Claude Code from its bankers and traders** — https://www.thestateofai.com/news/goldman-sachs-claude-code-traders-bankers *(via Hacker News Frontpage)*

2. **Java 28 traz API padrão para arquivos PEM** — facilita parsing/carregamento de chaves criptográficas e certificados em Java. *(LinkedIn — Paolo Patierno)*

3. **Evolução do Java Streams, de Java 8 a Java 25** — Stream API (Java 8), toList()/mapMulti()/takeWhile()/dropWhile() (Java 17), Stream Gatherers (Java 25). *(LinkedIn — Rodrigo Francisco Magni)*

4. **Vidocq: novo framework Java 100% soberano europeu** — zero dependências externas, isolamento estrito via JPMS. *(LinkedIn — Hamed Hatami)*

5. **Edição gratuita da JAVAPRO "Mastering Java Complexity"** — artigos sobre OpenFeature, boas práticas com IA em Java, Docker, JFR Redaction, GraalVM. *(LinkedIn — Carmen Kett)*
