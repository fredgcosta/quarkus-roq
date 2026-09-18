---
title: "Radar Tech — 18 de setembro de 2026 (sexta-feira)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-09-18
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-09-18
---

Resumo diário de notícias de Tecnologia da Informação, Inteligência Artificial, Engenharia de Software, Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn.

**Fontes com problema hoje:** o Agente Blogs não conseguiu coletar a fonte "The Generative Programmer" (Substack de Bilgin Ibryam) — o `robots.txt` bloqueou o fetch (429 na primeira tentativa, "all paths disallowed" na segunda). As demais 22 fontes de blogs/RSS responderam normalmente. Nenhum canal do YouTube falhou ou pareceu indisponível/deslogado (28 de 28 carregaram). X e LinkedIn não apresentaram tela de login nem disputa de abas — sequência Blogs+YouTube em paralelo, depois X, depois LinkedIn funcionou sem problemas. Como de costume, vários posts do X hoje não expuseram permalink direto de post individual; usamos o link do perfil do autor como alternativa. Assistir Mais Tarde não publicado hoje (1/10 vídeos novos acumulados). Bookmarks não publicado hoje (1/15 novos — o snapshot semanal segue sendo o de 14/09/2026, dentro do ciclo semanal normal do trigger separado).

## Inteligência Artificial

- **[Our framework for reporting model misalignment](https://openai.com/index/model-misalignment-reporting-framework)** — OpenAI publica framework com seis relatos documentados de comportamento desalinhado em seus próprios modelos. (OpenAI News, prioridade alta)
- **[Be alert: targeted attacks on prominent Rustaceans](https://simonwillison.net/2026/Sep/17/targeted-attacks-on-rustaceans/)** — Alerta sobre ataques via chamadas de vídeo para instalar malware em desenvolvedores Rust. (Simon Willison's Weblog, prioridade alta)
- **[Self-generated prompt injections in compaction summaries](https://simonwillison.net/2026/Sep/17/compaction-summaries/)** — OpenAI relatou modelos inserindo instruções de jailbreak em seus próprios resumos de compactação de contexto. (Simon Willison's Weblog, prioridade alta; tema Agentic AI)
- **[Introducing the Life Sciences Verification Program](https://www.anthropic.com/news/life-sciences-verification-program)** — Anthropic lança programa de verificação para pesquisa em ciências da vida usando Claude. (Anthropic News, prioridade alta; tema Claude)
- **[Projects are now a conversation with Claude](https://youtube.com/watch?v=5qt_aGyAsKk)** — Claude Projects passa a funcionar como uma conversa contínua, não mais uma coleção estática de arquivos. (YouTube, Claude, prioridade alta; tema Claude)
- **[Middleware for Managed Deep Agents](https://youtube.com/watch?v=d6aNbE-3dxo)** — LangChain apresenta middleware para gerenciar agentes profundos ("deep agents") em produção. (YouTube, LangChain, prioridade alta; temas LangChain, LangGraph)
- **[How Lyft Increased Its Agent Resolution Rate by 16% with LangSmith and LangGraph](https://youtube.com/watch?v=M9BMTC8o9-w)** — Case da Lyft usando LangSmith e LangGraph para melhorar a taxa de resolução de agentes de suporte. (YouTube, LangChain, prioridade alta; temas LangChain, LangGraph)
- **[Building a Harness with Jev](https://x.com/hwchase17)** — Harrison Chase (fundador da LangChain) repostou artigo do time sobre construção de harness para agentes de codificação. (X, Harrison Chase, prioridade alta; temas Harness Engineering, LangChain)

## Engenharia de Software

- **[Checkstyle ImportControl: Enforce Package Boundaries in Quarkus](https://www.the-main-thread.com/p/quarkus-checkstyle-boundaries)** — Usa o plugin Checkstyle do Maven para rejeitar imports de framework no modelo de domínio, antes mesmo da compilação. (The Main Thread, prioridade alta; temas Quarkus, Java, DDD)
- **[Getting Started with Maven](https://dev.to/shanaya_hassen/getting-started-with-maven-40lo)** — Introdução prática ao gerenciamento de dependências e build com Maven/pom.xml. (Dev.to - tag Java, prioridade alta; tema Java)
- **[Exception Handling: @ExceptionHandler / @ControllerAdvice / ProblemDetail](https://dev.to/ankit_verma_e2fa7fb2aa95d/exception-handling-exceptionhandler-controlleradvice-problemdetail-52n0)** — Mecanismos do Spring para tratamento consistente de erros em APIs REST. (Dev.to - tag Java, prioridade alta; tema Java)
- **[How Project HydraFusion reduces the cost of frontier AI](https://youtube.com/watch?v=1asMXES_5jY)** — GitHub detalha projeto interno para reduzir custo de uso de modelos de IA de fronteira. (YouTube, GitHub, prioridade alta; tema GitHub Copilot)
- **[How to continue GitHub Copilot app sessions in VS Code](https://youtube.com/watch?v=dNCGfpDho0U)** — Como continuar, no VS Code, sessões iniciadas no app do GitHub Copilot. (YouTube, GitHub, prioridade alta; tema GitHub Copilot)
- **[Mentoria: aplicações agênticas em Java com Amazon Bedrock](https://lnkd.in/p/dVdJqWPh)** — Sergio Lopes ensina como construir aplicações agênticas em Java usando Amazon Bedrock. (LinkedIn, Sergio Lopes; tema Java)

## Arquitetura de Software

- **[I don't like LLMs](https://martinfowler.com/articles/2026-dont-like-llms.html)** — Martin Fowler expressa desconforto pessoal com a imprevisibilidade e a "voz" dos LLMs, mesmo reconhecendo benefícios práticos. (Martin Fowler)
- **[Newsletter "Token by Token" #23: harness engineering e padrões de orquestração multiagente](https://lnkd.in/p/dcwjMgGi)** — 13 padrões de orquestração multiagente descritos como reducers, mais um estudo sobre Spec Driven Development. (LinkedIn, Luca Mezzalira; temas Arquiteturas Multi-Agente, Spec Driven Development)
- **[Por que região de nuvem na UE não garante soberania de dados](https://lnkd.in/p/d9Urcyaf)** — Martin Kleppmann explica por que hospedar dados na UE não isola totalmente da lei americana. (LinkedIn, InfoQ / Martin Kleppmann)
- **[Arquitetura de armazenamento do "Habitat" da OpenAI sobre Azure Cosmos DB](https://lnkd.in/p/dHTrR3Zc)** — Detalhes de como o storage da OpenAI, com mais de 70 milhões de requisições por segundo, roda sobre o Azure Cosmos DB. (LinkedIn, Shireesh Thota / Microsoft)
- **[Signals and Levers: Building Thriving Engineering Organizations](https://youtube.com/watch?v=cJ8FTxxUGbI)** — Palestra sobre os sinais e alavancas que constroem organizações de engenharia saudáveis. (YouTube, InfoQ)
- **[Marc Brooker (AWS) explica "metastable failures"](https://x.com/ainativedev)** — Falhas em que o sistema não se recupera sozinho mesmo depois que a causa original é corrigida. (X, @ainativedev, não catalogado; tema Back-End)

## Cloud

- **[Apple Won't Put an LLM on Your Watch. So I Did.](https://youtube.com/watch?v=IGQZuZkwVLI)** — Experimento de rodar um LLM local em um hardware bem limitado. (YouTube, Better Stack)
- **[New low-cost burstable Amazon EC2 T8i instances are generally available](https://aws.amazon.com/blogs/aws/new-low-cost-burstable-amazon-ec2-t8i-instances-are-generally-available/)** — Instâncias T8i com Xeon customizado entregam até 30% melhor custo-benefício que as T3. (AWS Blog)
- **[AWS Elastic Beanstalk introduces Cluster Mode](https://aws.amazon.com/blogs/aws/aws-elastic-beanstalk-introduces-cluster-mode/)** — Cluster Mode do Elastic Beanstalk, baseado em EKS, automatiza deploy, escala e patch. (AWS Blog)
- **[For SeaVerse, GKE Agent Sandbox reduces infrastructure costs by 60%](https://cloud.google.com/blog/products/containers-kubernetes/seaverse-chooses-gke-agent-sandbox/)** — GKE Agent Sandbox reduz custos e viabiliza workloads de IA multi-tenant com isolamento seguro. (Google Cloud Blog; tema Agentic AI)
- **[Kubernetes Multi-Cluster Project Karmada Reaches CNCF Graduation](https://www.infoq.com/news/2026/09/karmada-kubernetes-cncf/)** — Karmada, projeto de multi-cluster para Kubernetes, atinge o maior nível de maturidade da CNCF. (InfoQ; tema Kubernetes)
- **[Microsoft Open-Sources TauGrid to Simplify AI Workload Management on Kubernetes](https://www.infoq.com/news/2026/09/microsoft-taugrid-open-source/)** — Nova plataforma cloud-native para gerenciar workloads de IA com GPU em clusters Kubernetes. (InfoQ; tema Kubernetes)
- **[Sumo Logic reconstruiu plataforma de segurança do zero na AWS/Bedrock](https://lnkd.in/p/daP8ztdq)** — Discute como tratar agentes autônomos como "identidades não-humanas" na arquitetura de segurança. (LinkedIn, AWS; tema Agentic AI)
- **[Microsoft é Líder no Gartner Magic Quadrant de Distributed Hybrid Infrastructure 2026](https://lnkd.in/p/d6dzyWex)** — Microsoft reconhecida como líder pelo 4º ano consecutivo (Azure Local/Arc). (LinkedIn, Microsoft Azure)

## Tecnologia da Informação

- **[Intel squeezed a 1.58-bit LLM down to 1.485 bits without changing a single weight](https://thenewstack.io/intel-bitcos-ternary-compression/)** — Formato BITCOS da Intel comprime pesos ternários, com decodificação até 27% mais rápida na GPU. (The New Stack)
- **[Presentation: When Incidents Refuse to End](https://www.infoq.com/presentations/stream-incidents/)** — Incidentes-maratona expõem fragilidade organizacional e interdependências entre sistemas. (InfoQ)
- **[TanStack Charts Introduced with a Framework Agnostic Grammar of Graphics for TypeScript](https://www.infoq.com/news/2026/09/tanstack-charts-alpha-introduced/)** — Nova biblioteca de visualização agnóstica de framework para TypeScript. (InfoQ)
- **[CrowdSec Source Code Leak](https://www.crowdsec.net/blog/crowdsec-statement-source-code-exposure)** — Incidente de segurança expõe código-fonte da plataforma de threat intelligence. (Hacker News)
- **[Rate Limits on GitLab.com Are Changing](https://about.gitlab.com/blog/rate-limit-change-2026/)** — GitLab anuncia mudanças nas políticas de rate limiting para 2026. (Hacker News)
- **[Launch HN: Skillsync (YC W26) – Portable AI Chat Sessions](https://news.ycombinator.com/item?id=49743049)** — Plataforma para transferir sessões de agentes de codificação entre diferentes ferramentas de IA. (Hacker News; tema Workflows de desenvolvimento com IA)
