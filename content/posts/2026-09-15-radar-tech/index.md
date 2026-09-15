---
title: "Radar Tech — 15 de setembro de 2026 (terça-feira)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-09-15
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-09-15
---

TI · Inteligência Artificial · Engenharia de Software · Arquitetura de Software · Cloud — curado de blogs, YouTube, X e LinkedIn por 4 agentes independentes (Agente Blogs em paralelo; Agentes YouTube, X e LinkedIn em sequência).

## Fontes com problema hoje

Nenhuma falha técnica — os 4 agentes (Blogs, YouTube, X, LinkedIn) retornaram normalmente, sem tela de login nem disputa de abas. Duas observações sem impacto na seleção: o feed Medium (tag Kubernetes) só trouxe itens de 04/08/2026, sem nada recente; e tanto o Agente X quanto o Agente LinkedIn não conseguiram capturar links diretos (permalinks) de posts individuais hoje — o X por causa da virtualização do feed (leitura feita por screenshot em vez de `get_page_text`) e o LinkedIn porque o feed não expõe URLs no texto puro. Nos dois casos, usamos o link de perfil do autor como alternativa (X) ou deixamos o item sem link (LinkedIn), conforme previsto no playbook. A checagem opcional de perfis específicos do LinkedIn (Gergely Orosz, Kelsey Hightower, Werner Vogels, páginas de empresas) não foi feita por tempo — não é falha, é etapa opcional.

## Inteligência Artificial (8 itens)

1. **[Claude escreve 80% do código em produção interna da Anthropic; testes cresceram 10x e CI 25x em 6 meses](https://x.com/bcherny)** — Post de Addy Osmani (Anthropic), repostado por Boris Cherny; engenharia teve que reconstruir a análise de impacto de testes para acompanhar o volume. *(LinkedIn + X/Boris Cherny · Claude Code · alta)*
2. **["The contagion of fear"](https://simonwillison.net/2026/Sep/14/the-contagion-of-fear/)** — Simon Willison destaca crítica de Bryan Cantrill a alegações de que IA "pode matar a todos" sem respaldo suficiente de especialistas. *(Simon Willison's Weblog · Agentic AI · alta)*
3. **[commit-rewriter 0.1](https://simonwillison.net/2026/Sep/14/commit-rewriter/)** — Ferramenta web para editar mensagens de commit Git, pensada para limpar commits gerados por IA. *(Simon Willison's Weblog · Agentic AI · alta)*
4. **[How Fyxer built an AI executive assistant people trust](https://openai.com/index/fyxer)** — Fyxer combina modelos da OpenAI com fine-tuning e feedback do usuário para organizar caixas de entrada. *(OpenAI News + YouTube · OpenAI · alta)*
5. **[Perplexity trusts GPT-6 Astra with end-to-end systems](https://openai.com/index/perplexity-improving-accuracy-with-astra)** — Perplexity usa o Astra para comunicações de software e monitoramento de produção com supervisão reduzida. *(OpenAI News · OpenAI · alta)*
6. **[Share your Managed Deep Agent with your team using Slack](https://www.youtube.com/watch?v=a5Yie-Bgx7A)** — Como compartilhar um Deep Agent gerenciado com o time via Slack. *(YouTube, LangChain · LangChain, LangGraph, Agentic AI · alta)*
7. **LangChain otimiza como o `deepagents` lê arquivos, reduzindo erros de edição em 15% e uso de tokens em 10%** — Post de Sydney Runkle, repostado por Harrison Chase. *([X, @hwchase17](https://x.com/hwchase17) · LangChain, LangGraph · alta)*
8. **MAP.md: um grafo de contexto para organizar pastas do Claude Code e evitar documentação órfã** — Charlie Hills. *(LinkedIn · sem link direto disponível)*

## Engenharia de Software (8 itens)

1. **[Building Production-Ready AI Agents with Spring AI and LangChain](https://dev.to/said_olano/building-production-ready-ai-agents-with-spring-ai-and-langchain-a-practical-guide-5927)** — Guia prático de arquitetura de agentes de IA combinando Spring Boot e LangChain. *(Dev.to - tag Java · Java, LangChain · alta)*
2. **[I Ran One Draft Through Four Anti-Slop Skills](https://generativeprogrammer.com/p/i-ran-one-draft-through-four-anti)** — Comparação de quatro ferramentas de IA para edição de texto, cada uma atuando em "altitude" diferente. *(The Generative Programmer · Workflows de desenvolvimento com IA · alta)*
3. **[Java News Roundup: New OpenJDK JEPs, CDI 5.0, Spring, Open Liberty, RefactorFirst, ADK for Kotlin](https://www.infoq.com/news/2026/09/java-news-roundup-sep07-2026/)** — Novos JEPs para compilação AOT e concorrência estruturada, além de GA do Jakarta CDI 5.0. *(InfoQ · Java)*
4. **[AI's best coding agent fails 60% of the time](https://thenewstack.io/real-swe-coding-benchmark/)** — Claude venceu benchmark de codificação apesar de taxa de falha de 61,2% em codebases reais. *(The New Stack · Claude, Agentic AI)*
5. **[Your AI coding spend bought 25% more output. Duplication rose 81%.](https://thenewstack.io/ai-coding-duplication-rose/)** — Análise da GitClear de 623M de mudanças de código mostra alta duplicação apesar do ganho de velocidade com IA. *(The New Stack · Workflows de desenvolvimento com IA)*
6. **[3 ways to streamline AI code reviews across your team](https://www.youtube.com/watch?v=NiMpZ4gW2dQ)** — Três formas de otimizar revisões de código com IA no time. *(YouTube, GitHub · GitHub Copilot · alta)*
7. **Java 27 chegou, com 9 JEPs (cabeçalhos de objeto compactos por padrão, G1 como GC padrão, TLS 1.3 pós-quântico e mais)** — Achraf HASBI. *(LinkedIn · Java · sem link direto disponível)*
8. **[EP225: Why Does Git Revert Cause Conflicts?](https://blog.bytebytego.com/p/ep225-why-does-git-revert-cause-conflicts)** — Explica por que git revert gera conflitos quando commits posteriores alteram as mesmas linhas. *(ByteByteGo)*

## Arquitetura de Software (7 itens)

1. **[I Argued With an Interviewer About Global Rate Limiting](https://hackernoon.com/i-argued-with-an-interviewer-about-global-rate-limiting-neither-of-us-were-right)** — Discussão sobre rate limiting distribuído, leases e trade-offs multi-região. *(HackerNoon)*
2. **[Agoda Replaces 72-Shard SQL Server Price Cache with DragonflyDB](https://www.infoq.com/news/2026/09/agoda-price-cache-dragonflydb/)** — Agoda migrou cache de preços com DragonflyDB, reduzindo latência P99 em 8x. *(InfoQ)*
3. **[Do you even need a presentation?](https://martinfowler.com/articles/never-send-slides/need-presentation.html)** — Primeira parte de série questionando a necessidade de apresentações e convenções de reunião. *(Martin Fowler)*
4. **[Fragments: September 8](https://martinfowler.com/fragments/2026-09-08.html)** — Coletânea de comentários sobre economia de IA, detecção de conteúdo gerado por LLM e disputas de copyright. *(Martin Fowler)*
5. **Vlad Khononov (autor de "Learning Domain-Driven Design") participa de webinar gratuito em 16/09 sobre desacoplamento e complexidade em arquitetura** — Iasa Global. *(LinkedIn · DDD · sem link direto disponível)*
6. **Lançamento do livro "The One Minute Architect", sobre como arquitetos de software desenvolvem julgamento e lidam com incerteza** — Karol Wiszowaty. *(LinkedIn · sem link direto disponível)*
7. **How to Serve 100 Fine-Tuned Models on One GPU** — Arquitetura de multi-LoRA serving compartilhando pesos base entre 100 variantes fine-tuned. *(X · não catalogado · sem link direto disponível)*

## Cloud (7 itens)

1. **[AWS Weekly Roundup: OpenAI GPT-6 Astra on Amazon Bedrock, Amazon Quick desktop GA, Kiro for students](https://aws.amazon.com/blogs/aws/aws-weekly-roundup-openai-gpt-6-astra-on-amazon-bedrock-amazon-quick-desktop-ga-kiro-for-students-and-more-september-14-2026/)** — GPT-6 Astra da OpenAI chega ao Bedrock e Amazon Quick desktop sai em GA. *(AWS Blog)*
2. **[Introducing the Google Cloud Developer Plugin for AI Coding Agents](https://cloud.google.com/blog/topics/developers-practitioners/introducing-the-google-cloud-developer-plugin-for-ai-coding-agents/)** — Google lança plugin instalável que equipa agentes de codificação com ferramentas para o GCP. *(Google Cloud Blog · Agentic AI)*
3. **[The Kubernetes Audit Worksheet](https://dev.to/kestrion/the-kubernetes-audit-worksheet-1m30)** — Framework de auditoria de 4h cobrindo inventário de cluster, pipelines, controles de acesso e custos. *(Dev.to - tag Kubernetes · Kubernetes · alta)*
4. **[A Temporary File on One Pod Evicted Every Other Pod on the Node](https://dev.to/sergey_shinder_ab2d943365/a-temporary-file-on-one-pod-evicted-every-other-pod-on-the-node-5aa7)** — Postmortem de incidente causado por spike de armazenamento efêmero não monitorado. *(Dev.to - tag Kubernetes · Kubernetes · alta)*
5. **[Top Kubernetes Production Incident Scenarios & Diagnostic Runbooks (2026 Edition)](https://dev.to/naveedkumbhar/top-kubernetes-production-incident-scenarios-diagnostic-runbooks-2026-edition-1ipk)** — Cinco cenários de incidentes reais com runbooks de diagnóstico. *(Dev.to - tag Kubernetes · Kubernetes · alta)*
6. **Google Cloud Tech fecha parceria com a Inferact (equipe por trás do vLLM) para tornar TPUs cidadãs de primeira classe em inferência de IA open-source** — kernels TPU open-source e integração nativa PyTorch via TorchTPU. *([X, @GoogleCloudTech](https://x.com/GoogleCloudTech) · não catalogado)*
7. **Mete Atamel detalha a hierarquia de permissões do Google Cloud Antigravity (AGY): acesso a arquivos, rede, execução de terminal e ferramentas MCP** — *([X, @meteatamel](https://x.com/meteatamel) · não catalogado)*

## Tecnologia da Informação (7 itens)

1. **[How Will We Train Developers If AI Does the Routine Work: A Conversation with Scott Hanselman](https://www.infoq.com/podcasts/train-developers-ai-routine-work/)** — Discussão sobre como formar devs na era em que a IA faz o trabalho rotineiro, propondo um modelo de "preceptorship". *(InfoQ (podcast) + YouTube)*
2. **[Chip Huyen explains how to cut inference costs without new hardware](https://thenewstack.io/pg-99-conf-2026-inference-costs/)** — Framework de otimização de custo de inferência: goodput, quantização, batching contínuo. *(The New Stack)*
3. **[Why an old caching trick is your secret to lower LLM costs](https://thenewstack.io/llm-response-caching-costs/)** — Cache de respostas (exact-match + similaridade semântica) pode reduzir custo de inferência em mais de 50%. *(The New Stack)*
4. **Incidente de segurança na METR: atacante roubou chave de API por 3 semanas e consumiu ~US$ 600 mil em créditos, explorando falha de autenticação Google em dashboard público de agente** — Comentado por ThePrimeagen (repost de matéria do The Hacker News). *([X, @ThePrimeagen](https://x.com/ThePrimeagen) · não catalogado)*
5. **Feature "Copy agent prompt" no NestJS Devtools empacota erro, stack trace, logs e código-fonte num prompt pronto para colar num coding agent** — *(LinkedIn, NestJS · sem link direto disponível)*
6. **[Pion, an agent designed to run any company autonomously](https://andonlabs.com/blog/why-we-built-pion)** — Startup constrói agente autônomo para operar empresas inteiras. *(Hacker News · Agentic AI)*
7. **Kotlin completou 15 anos; JetBrains comemora com campanha publicitária em Barcelona** — *(LinkedIn, Daniil Shulgin · sem link direto disponível)*

## Assistir Mais Tarde (YouTube) — 10 de 197 vídeos salvos

1. [The Art of Loop Engineering: How to Build Agents That Improve Over Time](https://www.youtube.com/watch?v=jPPiZ22DY3g) — LangChain
2. [The Great Loops Debate — Dex Horthy, Geoff Huntley, Ian Livingstone, Greg Pstrucha](https://www.youtube.com/watch?v=c35YoMdnI78) — AI Engineer
3. [Predicting Free Pizza with Python & Machine Learning • Lorena Mesa • GOTO 2017](https://www.youtube.com/watch?v=K7qFZ5Y9dCs) — GOTO Conferences
4. [How I passed the NEW Claude Architect Certification Exam (CCA-F)](https://www.youtube.com/watch?v=kY9z4hiH4nk) — Chance Xie
5. [What to teach when AI writes the code | Rainer Stropek | TEDxLinz](https://www.youtube.com/watch?v=yhGzXULZkEw) — TEDx
6. [mattpocock/skills: A complete AI Coding workflow, end-to-end](https://www.youtube.com/watch?v=M6mYodf0dJM) — Matt Pocock
7. [Don't Ship Skills Without Evals — Philipp Schmid, Google DeepMind](https://www.youtube.com/watch?v=0vphxNt4wyk) — AI Engineer
8. [Beyond the basics with Claude Code](https://www.youtube.com/watch?v=tuY2ChJIx48) — Claude
9. [Beyond Prompting: Context Engineering with LangChain4J](https://www.youtube.com/watch?v=cqNUaA-YDwM) — Microsoft for Java Developers
10. [/handoff is my new favourite skill](https://www.youtube.com/watch?v=dtAJ2dOd3ko) — Matt Pocock

[Ver playlist completa no YouTube →](https://www.youtube.com/playlist?list=WL)

## Bookmarks (Favoritos do celular — Edge) — 15 de 155 salvos

*Snapshot semanal mantido pelo trigger separado (`collected/bookmarks-latest.md`), atualizado em 14/09/2026.*

1. [anthropics/skills: Public repository for Agent Skills](https://github.com/anthropics/skills) — GitHub · IA · salvo 03/09
2. [garrytan/gstack](https://github.com/garrytan/gstack) — GitHub · IA · salvo 03/09
3. [andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) — GitHub · IA · salvo 03/09
4. [codeburn](https://github.com/getagentseal/codeburn) — GitHub · IA · salvo 03/09
5. [Java's age is its AI superpower](https://stackoverflow.blog/2026/09/09/java-s-age-is-its-ai-superpower/) — Stack Overflow · Eng. Software · salvo 11/09
6. [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) — GitHub · IA · salvo 03/09
7. [AI agents are creating more work, not less](https://thenewstack.io/openai-agent-research-bottleneck/) — The New Stack · IA · salvo 08/09
8. [Context, Semantics, and Ontology](https://motherduck.com/blog/context-layer-vs-semantic-layer-ontology/) — MotherDuck · IA · salvo 03/09
9. [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) — GitHub · IA · salvo 03/09
10. [When Spec-Driven Development Pays Off](https://www.infoq.com/articles/when-spec-driven-development-pays-off/) — InfoQ · Eng. Software · salvo 13/09
11. [Docs7 — Context7](https://context7.com/docs7) — IA · salvo 03/09
12. [Build Your Own RAG Chatbot with JavaScript!](https://www.freecodecamp.org/news/build-your-own-rag-chatbot-with-javascript/) — freeCodeCamp · IA · salvo 04/09
13. [AI can write code. Developers solve problems.](https://skillsbuild.org/learn-with-ibm-bob) — IBM SkillsBuild · IA · salvo 03/09
14. [generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) — GitHub · IA · salvo 03/09
15. [project-based-learning](https://github.com/practical-tutorials/project-based-learning) — GitHub · Eng. Software · salvo 03/09

---

**Fontes:** The New Stack, InfoQ, The Pragmatic Engineer, Martin Fowler, Simon Willison, AWS Blog, Azure Blog, Google Cloud Blog, OpenAI News, Anthropic News, Hacker News, Dev.to, Substacks (The Main Thread, The Generative Programmer, Hands On Kubernetes, ByteByteGo, Exponential View), HackerNoon, X (timelines Para você/Seguindo), LinkedIn (feed principal), YouTube.
