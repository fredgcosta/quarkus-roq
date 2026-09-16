---
title: "Radar Tech — 16 de setembro de 2026 (quarta-feira)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-09-16
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-09-16
---

**Fontes com problema hoje:** nenhuma falha técnica — os 4 agentes (Blogs, YouTube, X, LinkedIn) retornaram normalmente, sem tela de login nem disputa de abas. Bookmarks não publicado hoje (0/15 novos desde 14/09 — abaixo do limiar). Medium (tag Kubernetes) segue desatualizado. Alguns posts do X/LinkedIn não expõem permalink direto; usamos o link do perfil/página como alternativa.

## Inteligência Artificial

- **[Apresentando Claude Opus 5](https://www.anthropic.com/news/claude-opus-5)** — Novo modelo da Anthropic com melhorias significativas para agentes de longa duração e codificação. (Anthropic News)
- **[OpenAI renova o programa "Codex for Open Source" com planos Pro grátis para mantenedores](https://x.com/charliermarsh/status/2099965140233847246)** — Seis meses após o lançamento, o programa é renovado para dar acesso gratuito ao Codex a mantenedores de projetos open source. (X, via @OpenAIDevs)
- **[Cognition ajuda o Devin a testar seu próprio trabalho com GPT-6 Astra](https://openai.com/index/cognition-devin-testing-with-astra)** — Reduz esforço de revisão manual de código e acelera entregas. (OpenAI News)
- **[Brownfield agentic engineering: até onde deixar agentes mexerem em código legado](https://www.linkedin.com/in/addyosmani/)** — Addy Osmani (Anthropic) propõe um framework de zonas verde/amarela/vermelha para delimitar autonomia de agentes de IA em codebases legadas. (LinkedIn, Addy Osmani)
- **[Gemini Live em áudio](https://simonwillison.net/2026/Sep/15/gemini-live/)** — Simon Willison constrói uma interface web para os modelos Gemini 3.8 Live do Google via WebSocket. (Simon Willison's Weblog)
- **[Dario Amodei em conversa com Marc Benioff no Dreamforce](https://x.com/salesforce/status/2099928888407216321)** — O CEO da Anthropic discutiu o futuro da IA agêntica em ambiente corporativo. (X, @salesforce)
- **[Tool, skill ou subagent? Decompondo um agente que superou seu prompt](https://www.youtube.com/watch?v=mWvtOHlZM-I)** — Vídeo do canal Claude sobre quando dividir a lógica de um agente em ferramentas, skills ou subagentes. (YouTube, Claude)
- **[Nosso posicionamento sobre modelos de pesos abertos](https://www.anthropic.com/news/position-open-weights-models)** — A Anthropic detalha sua visão sobre riscos e benefícios de modelos open-weight. (Anthropic News)

## Engenharia de Software

- **[Por dentro da fábrica de software agêntica da OpenAI](https://newsletter.pragmaticengineer.com/p/openai-software-factory)** — Como o Codex transformou as práticas de desenvolvimento e engenharia da OpenAI em escala. (The Pragmatic Engineer)
- **[O que está acontecendo com as revisões de código?](https://newsletter.pragmaticengineer.com/p/what-is-happening-with-code-reviews)** — Como o code review muda à medida que cresce a proporção de PRs gerados por IA. (The Pragmatic Engineer)
- **[Quarkus Community Call — 15 de setembro: Quarkus & Gradle](https://www.youtube.com/watch?v=mM_OpUfQtdI)** — Gravação da call mensal da comunidade Quarkus. (YouTube, Quarkus)
- **[Quarkus Banner: crie seu primeiro banner FIGlet de inicialização](https://www.the-main-thread.com/p/quarkus-banner-build-time)** — Extensão para gerar banners ASCII customizados no start-up de aplicações Quarkus. (The Main Thread)
- **[Negociação de conteúdo e conversores de mensagem (Jackson)](https://dev.to/ankit_verma_e2fa7fb2aa95d/content-negotiation-message-converters-jackson-233m)** — Como o Spring converte objetos Java em JSON via negociação de conteúdo. (Dev.to - tag Java)
- **[Todo bug real que encontrei veio de rodar o código, nunca de lê-lo](https://dev.to/mohamedessamessmat/every-real-bug-i-found-came-from-running-the-code-never-from-reading-it-4oe1)** — Defeitos reais só aparecem ao executar os endpoints de fato. (Dev.to - tag Java)
- **[Java 27 lançado: Compact Object Headers, G1 como GC padrão, TLS quantum-safe](https://www.linkedin.com/in/leandroleitetech/)** — Resumo dos principais JEPs de produção da nova versão. (LinkedIn, Leandro Leite)
- **[Vite reescreve seu dev server em Rust, com 4x menos uso de memória](https://x.com/evanyou/status/2100047319261745526)** — Evan You comenta a remoção do Node.js do dev server em favor de Rust. (X, @evanyou)

## Arquitetura de Software

- **[Como o turnstile do Solaris influenciou designs de sistemas modernos](https://www.infoq.com/news/2026/09/turnstile-system-design/)** — Inovações de lock do Solaris moldaram estratégias de concorrência atuais. (InfoQ)
- **[Seu teste de carga não vai encontrar essas quatro lacunas](https://hackernoon.com/your-load-test-wont-find-these-four-gaps-learnings-from-openais-habitat)** — Aprendizados do Habitat da OpenAI sobre coordenação em escala. (HackerNoon)
- **[Dados exatos não devem passar pelo LLM](https://www.linkedin.com/in/alberto-souza-953b0b7/)** — Alberto Souza defende anexar referências determinísticas após a resposta do modelo. (LinkedIn, Alberto Souza)
- **[Como a Delphi faz 100+ deploys de produção por dia com apenas 10 engenheiros](https://x.com/vercel/status/2099952028521029820)** — Case da Vercel sobre Workflows e Queues. (X, @vercel)
- **[Orçamento de avaliação de IA antes da seleção de modelo](https://dmytronasyrov.medium.com/ai-evaluation-budget-before-model-selection-8d08dfb47fef)** — Abordagem estruturada para alocar recursos de avaliação (evals). (Medium)
- **[Guia de um desenvolvedor sobre arquitetura de banco de dados e performance](https://hackernoon.com/a-developers-guide-to-database-architecture-and-performance-fundamentals)** — SQL, indexação, transações, ACID, PostgreSQL e MongoDB. (HackerNoon)

## Cloud

- **[CNCF pede participação em pesquisa 2026 sobre workloads cloud native](https://x.com/cra/status/2099941848886202839)** — Resultados apresentados no KubeCon. (X, @cra/CNCF)
- **[Kubernetes Scheduling 101: o que realmente acontece antes do seu pod rodar](https://dev.to/siddharthajmore/kubernetes-scheduling-101-what-really-happens-before-your-pod-runs-3khk)** — Passo a passo do scheduler do Kubernetes. (Dev.to - tag Kubernetes)
- **[Lição 79: Network Policies — bloqueando comunicação pod-a-pod em produção](https://handsonk8s.substack.com/p/lesson-79-network-policies-locking)** — Como restringir tráfego entre pods. (Hands On Kubernetes)
- **[A economia da otimização de agentes: governança de IA controla custo e comprova ROI](https://azure.microsoft.com/en-us/blog/the-economics-of-agent-optimization-how-ai-agent-governance-controls-cost-and-proves-roi/)** — Visibilidade e limites de gasto no Microsoft Foundry. (Microsoft Azure Blog)
- **[Analytics prontos para agentes: BigQuery com funções de análise aumentada](https://cloud.google.com/blog/products/data-analytics/bigquery-augmented-analytics-tvfs/)** — Seis novas funções para automatizar investigação de dados. (Google Cloud Blog)
- **[Instâncias Amazon EC2 R9g e R9gd com Graviton5 já disponíveis](https://aws.amazon.com/blogs/aws/amazon-ec2-r9g-and-r9gd-instances-powered-by-aws-graviton5-processors-are-now-generally-available/)** — 25% mais performance e memória DDR5. (AWS Blog)
- **[DigitalOcean disponibiliza DeepSeek-V4.1-Flash no Inference Engine](https://x.com/digitalocean/status/2099899408422756740)** — Nova arquitetura causal encoder-decoder supera o DeepSeek-V4-Pro. (X, @digitalocean)

## Tecnologia da Informação

- **[IA ajuda a Microsoft a corrigir mais de 1.000 vulnerabilidades em um mês](https://www.infoq.com/news/2026/09/microsoft-ai-security-patch/)** — Pesquisa de segurança orientada por IA permitiu corrigir ~2.750 vulnerabilidades ao longo do ano. (InfoQ)
- **[Conseguimos acesso de admin ao GitHub de produção da Baseten em 25 minutos](https://www.strix.ai/blog/baseten-harbor-github-pat-takeover)** — Pesquisa de segurança expõe falha crítica via token exposto. (Hacker News / Strix)
- **[A violação de dados de carteiras de motorista dos EUA é um desastre de segurança nacional](https://www.lawfaremedia.org/article/america%27s-drivers-licence-breach-is-a-national-security-disaster)** — Análise do impacto de um vazamento massivo de dados. (Hacker News / Lawfare)
- **[CISA e NIST publicam recomendações para proteger tokens de identidade](https://x.com/CISACyber/status/2099874287700087092)** — Relatório interagências final contra falsificação e uso indevido de tokens. (X, @CISACyber)
- **[O presidente da OpenAI diz: "o computador deve estar aí para te dar poder"](https://thenewstack.io/computer-use-agent-connectors/)** — Greg Brockman argumenta que devs devem deixar agentes de IA usarem computadores como humanos. (The New Stack)
- **[Meta permite que Claude e Codex configurem WhatsApp Business via MCP](https://thenewstack.io/meta-mcp-whatsapp-business-claude/)** — Novo servidor MCP da Meta habilita onboarding via agentes. (The New Stack)
- **[25 anos de vigilância em massa já é suficiente](https://www.schneier.com/blog/archives/2026/09/25-years-of-mass-surveillance-is-enough.html)** — Bruce Schneier reflete sobre duas décadas e meia de vigilância digital. (Hacker News / Schneier)
