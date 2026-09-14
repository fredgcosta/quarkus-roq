---
title: "Radar Tech — 12 de setembro de 2026 (sábado)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-09-12
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-09-12
---
Curado por 4 agentes paralelos independentes (Blogs, YouTube, X, LinkedIn). Bookmarks do Edge são um snapshot semanal separado (não coletado nesta execução).

## Fontes com problema hoje

- **Google Cloud Blog** — continua fora do ar (retornou a página HTML de erro em vez do feed), mesmo problema dos dias anteriores.
- **High Scalability** — 404 ao buscar o feed; parece definitivamente abandonado.
- **Anthropic News (RSS)** — `rss.xml` voltou a dar 404; contornado com fallback em anthropic.com/news. Vale corrigir a URL em `sources.json`.
- **Medium** (Software Architecture e Kubernetes) — feeds parados há mais de um mês, sem nada novo; a tag Artificial Intelligence trouxe itens, mas nenhum relevante aos temas do Fred após filtragem.
- **Martin Fowler** — nenhum post dentro da janela de 7 dias tinha relação direta com arquitetura/engenharia técnica.
- **Agente X** — boa parte das contas de prioridade alta em Java/Anthropic segue sem atividade recente ou parece abandonada: @aloubyansky, @janmartiska, @The_Java_Dev, @pbakker, @kamila_code, @markrichardssa e @janleike sem posts há semanas/meses; @DarioAmodei e @karpathy sem posts há quase um mês; @kelseyhightower com 0 posts (conta parece inativa/diferente).
- **Agente LinkedIn** — segundo dia seguido de disputa de abas do mesmo Chrome com os agentes X e YouTube rodando em paralelo; não conseguiu capturar nenhum link (nem de post, nem de perfil) dos ~14 posts lidos no feed principal, nem executar a checagem extra de perfis específicos. Por isso, nenhum item do LinkedIn entrou no resumo de hoje — vale considerar rodar esse agente de forma sequencial, não em paralelo com X/YouTube no mesmo Chrome.
- **Agente YouTube** — nenhuma falha de coleta; sofreu a mesma disputa de abas, mas sem impacto nos dados.

## Inteligência Artificial (8 itens)

1. **[OpenAI lança a Agents API](https://openai.com/index/introducing-the-agents-api)** — API dedicada para construção e orquestração de agentes de IA, já disponível para desenvolvedores. *(OpenAI News, YouTube OpenAI · tema OpenAI, Codex · prioridade alta)*
2. **[Anthropic publica relatório de inteligência de ameaças de setembro](https://www.anthropic.com/threat-intelligence-report-september-2026)** — Documenta tentativas reais de uso malicioso do Claude; Boris Cherny chamou de "leitura assustadora". *(Anthropic News, X @bcherny · tema Claude, Anthropic · prioridade alta)*
3. **[Agentes da OpenAI teriam atacado o RubyGems desde maio](https://simonwillison.net/2026/Sep/12/openai-agents-rubygems/)** — Um enxame de agentes explorou e fez spam no repositório antes dos ataques a wikis abandonadas descobertos depois. *(Simon Willison, X @simonw · prioridade alta)*
4. **[GPT-Rosalind chega à API e ao Codex para raciocínio biológico](https://x.com/OpenAIDevs)** — Novo modelo conecta papers e resultados experimentais em pesquisas biológicas. *(X @OpenAIDevs · tema OpenAI, Codex · prioridade alta)*
5. **[Cognition integra o GPT-6 Astra ao Devin para autoteste de código](https://openai.com/index/cognition-devin-testing-with-astra)** — O agente Devin passa a validar automaticamente seu próprio código. *(OpenAI News · tema OpenAI, Agentic AI, EDD · prioridade alta)*
6. **[LangChain lança o OpenWiki, documentação gerada automaticamente para agentes de código](https://x.com/hwchase17)** — Já usado pela Credit Genie para que agentes consultem como o repositório funciona. *(X @hwchase17 · tema LangChain, LangGraph · prioridade alta)*
7. **[Novo `claude plugin eval` no Claude Code ganha atenção da comunidade de evals](https://x.com/HamelHusain)** — Permite criar casos de teste e comparar o valor real de um plugin ou skill. *(X @HamelHusain · tema Claude Code, EDD · prioridade alta)*
8. **[Evals para Deep Agents: seu agente citou documentos reais?](https://www.youtube.com/watch?v=pjv-mp5J4hA)** — LangChain mostra como avaliar agentes profundos, com vídeo complementar sobre LLM Judge via LangSmith CLI. *(YouTube LangChain · tema LangChain, EDD · prioridade alta)*

## Engenharia de Software (8 itens)

1. **[Quarkus HTTP Problem: erros de API padronizados](https://www.the-main-thread.com/p/quarkus-http-problem-rfc9457-exception-mappers)** — Padronização de erros de API via RFC 9457. *(The Main Thread · tema Quarkus, Java · prioridade alta)*
2. **[Quarkus Banner: construindo seu primeiro banner FIGlet](https://www.the-main-thread.com/p/quarkus-banner-build-time)** — Banner de startup personalizado e o pipeline de build do Quarkus. *(The Main Thread · tema Quarkus, Java · prioridade alta)*
3. **[Backend for Frontend (BFF): o padrão que salvou meus microsserviços](https://dev.to/fabiothomazrocha/backend-for-frontend-bff-o-padrao-que-salvou-meus-microsservicos-e-minha-sanidade-555p)** — Guia prático do padrão BFF em Spring Boot. *(Dev.to · tema Java, Back-End · prioridade alta)*
4. **[Ciclo de vida de entidades JPA/Hibernate: 4 estados explicados](https://dev.to/noor170/jpahibernate-entity-lifecycle-4-states-explained-simply-46in)** — Explicação didática com exemplos de dirty checking. *(Dev.to · tema Java · prioridade alta)*
5. **[8 livros de engenharia de software que a IA tornou mais relevantes](https://generativeprogrammer.com/p/8-software-books-ai-has-made-more)** — Princípios clássicos ficaram mais críticos, não menos, na era da codificação assistida por IA. *(The Generative Programmer · tema Workflows de desenvolvimento com IA · prioridade alta)*
6. **[GitHub: do piloto à adoção ampla do Copilot](https://www.youtube.com/watch?v=lfsWnaM2vmg)** — Erros mais comuns ao escalar o uso de Copilot. *(YouTube GitHub · tema GitHub Copilot · prioridade alta)*
7. **[GitHub CLI ganha suporte para anexar imagens e vídeos em issues e PRs](https://www.youtube.com/watch?v=YHHjEet47_4)** — Novo recurso facilita reportar bugs e revisar mudanças visuais. *(YouTube GitHub · tema GitHub Copilot · prioridade alta)*
8. **[Construindo o Codex, com Tibo Sottiaux](https://newsletter.pragmaticengineer.com/p/building-codex-with-tibo-sottiaux)** — Líder de engenharia do Codex conta como o agente foi construído. *(The Pragmatic Engineer, YouTube The Pragmatic Engineer · tema Codex)*

## Arquitetura de Software (6 itens)

1. **[Netflix reformula o Conductor para 420 milhões de execuções/mês](https://www.infoq.com/news/2026/09/netflix-conductor-4-workflow/)** — Motor de orquestração refeito para workflows 10x maiores. *(InfoQ)*
2. **[Como rodar em três clouds ao mesmo tempo, e quando não fazer isso](https://www.infoq.com/presentations/form3-multicloud-architecture/)** — Trade-offs práticos de arquiteturas multi-cloud. *(InfoQ · Cloud)*
3. **[A receita da Meta para construir agentes como "segundos cérebros organizacionais"](https://www.infoq.com/news/2026/09/meta-organizational-agents/)** — Abordagem da Meta para agentes de IA organizacionais. *(InfoQ · tema Arquiteturas Multi-Agente)*
4. **[Guia sobre os fundamentos de application networking](https://blog.bytebytego.com/p/a-guide-to-application-networking)** — DNS, load balancing, TCP e a jornada de uma requisição web. *(ByteByteGo)*
5. **[Como o roteamento inteligente de modelos pode cortar custos de LLM em até 10x](https://blog.bytebytego.com/p/how-smart-model-routing-can-cut-llm)** — Estratégias de roteamento entre modelos para reduzir custo. *(ByteByteGo · tema Arquiteturas Multi-Agente)*
6. **[Entendendo o colapso progressivo: como evitar uma falha em cascata](https://www.youtube.com/watch?v=ECUd5FuK5q4)** — Como projetar sistemas resilientes a esse tipo de colapso. *(YouTube InfoQ)*

## Cloud (8 itens)

1. **[Microsoft é nomeada líder no Gartner MQ para Container Management](https://azure.microsoft.com/en-us/blog/microsoft-named-a-leader-in-the-2026-gartner-magic-quadrant-for-container-management/)** — Reconhecimento via AKS, Azure Arc e Azure Container Apps. *(Azure Blog · tema Kubernetes)*
2. **[AWS Weekly Roundup: Claude Fable 5.1 na AWS, preview do Amazon Linux 2027 e mais](https://aws.amazon.com/blogs/aws/aws-weekly-roundup-claude-fable-5-1-on-aws-amazon-linux-2027-preview-aws-certified-ai-business-strategist-and-more-september-7-2026/)** — Resumo semanal cobrindo Claude Fable 5.1. *(AWS Blog · tema Claude)*
3. **[Duas zonas ou três? Framework de design para workloads Azure resilientes](https://azure.microsoft.com/en-us/blog/two-zones-or-three-a-design-framework-for-zone-resilient-azure-workloads/)** — Framework em nível de componente para zonas de disponibilidade. *(Azure Blog)*
4. **[AWS Lambda passa a logar fluxos de rede com eBPF e Rust](https://thenewstack.io/aws-lambda-ebpf-rust/)** — Substitui sistema antigo de captura de pacotes. *(The New Stack)*
5. **[Copilot escreveu um manifesto Kubernetes que passou na validação com 21 problemas de segurança](https://dev.to/jjoyneriv/copilot-wrote-a-kubernetes-manifest-that-passed-schema-validation-with-21-security-findings-in-it-38ch)** — Alerta sobre confiar cegamente em manifestos gerados por IA. *(Dev.to · tema Kubernetes, GitHub Copilot · prioridade alta)*
6. **[Marcamos workers do EKS como app servers e o Prometheus raspou o Telegraf indevidamente](https://dev.to/mridul_it_is/we-tagged-eks-workers-like-app-servers-and-prometheus-started-scraping-telegraf-on-nodes-that-2n59)** — Tagueamento expôs nós do EKS a monitoramento indevido. *(Dev.to · tema Kubernetes · prioridade alta)*
7. **[Hands On Kubernetes — Semana 3: gestão de recursos e armazenamento](https://handsonk8s.substack.com/p/week-3-resource-and-storage-management)** — Governança de recursos e resiliência em um sistema multi-tier. *(Hands On Kubernetes · tema Kubernetes, Cloud Native · prioridade alta)*
8. **[Oracle Developers: redes OCI resilientes para alta disponibilidade e disaster recovery](https://www.youtube.com/watch?v=_n-LYMxV5oA)** — Como construir redes OCI preparadas para falhas. *(YouTube Oracle Developers · tema Cloud Native · prioridade alta)*

## Tecnologia da Informação (5 itens)

1. **[IETF publica RFC 10008, criando o método HTTP QUERY](https://www.infoq.com/news/2026/09/http-query-method/)** — Primeiro método HTTP novo desde 2010. *(InfoQ)*
2. **[CPython adiciona suporte oficial ao RISC-V](https://www.infoq.com/news/2026/09/riscv-cpython/)** — Tier 3, tema Python. *(InfoQ)*
3. **[Simon Willison sobre a depreciação suave de re.match() no Python](https://simonwillison.net/2026/Sep/11/soft-deprecating-re-match/)** — Como e por que aposentar aos poucos essa função. *(Simon Willison · tema Python · prioridade alta)*
4. **[PlanetScale atinge 118 milhões de queries por segundo com o Neki](https://planetscale.com/blog/118-million-queries-per-second-on-neki)** — Novo motor de escalabilidade da PlanetScale. *(Hacker News · tema Back-End)*
5. **[Shopify abandona React Native e volta para Swift/Kotlin nativo](https://x.com/GergelyOrosz)** — Gergely Orosz compara com o caso histórico do Airbnb em 2018. *(X @GergelyOrosz, X @ShopifyEng · prioridade alta)*

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

## Bookmarks (Favoritos do celular — Edge) — 15 de 154 salvos

Snapshot mantido pelo trigger semanal separado, atualizado em 12/09/2026.

1. [Java's age is its AI superpower](https://stackoverflow.blog/2026/09/09/java-s-age-is-its-ai-superpower/) — Stack Overflow · salvo em 11/09/2026
2. [AI agents are creating more work, not less](https://thenewstack.io/openai-agent-research-bottleneck/) — The New Stack · salvo em 08/09/2026
3. [gstack: setup de Claude Code do Garry Tan](https://github.com/garrytan/gstack) — GitHub · salvo em 03/09/2026
4. [anthropics/skills — repositório público de Agent Skills](https://github.com/anthropics/skills) — GitHub · salvo em 03/09/2026
5. [CLAUDE.md baseado nas observações de Andrej Karpathy](https://github.com/multica-ai/andrej-karpathy-skills) — GitHub · salvo em 03/09/2026
6. [Orca: ADE para frota de agentes paralelos](https://github.com/stablyai/orca) — GitHub · salvo em 03/09/2026
7. [Context, Semantics, and Ontology: A Primer for the Agentic Era](https://motherduck.com/blog/context-layer-vs-semantic-layer-ontology/) — MotherDuck · salvo em 03/09/2026
8. [prime-agent: agente RLM auto-aprimorável](https://github.com/PrimeIntellect-ai/prime-agent) — GitHub · salvo em 03/09/2026
9. [awesome-llm-apps: 100+ AI Agents](https://github.com/Shubhamsaboo/awesome-llm-apps) — GitHub · salvo em 03/09/2026
10. [codeburn: rastreador de custo de tokens de IA](https://github.com/getagentseal/codeburn) — GitHub · salvo em 03/09/2026
11. [Docs7 – Documentation that makes AI agents love your product](https://context7.com/docs7) — Context7 · salvo em 03/09/2026
12. [Build Your Own RAG Chatbot with JavaScript!](https://www.freecodecamp.org/news/build-your-own-rag-chatbot-with-javascript/) — freeCodeCamp · salvo em 04/09/2026
13. [AI can write code. Developers solve problems.](https://skillsbuild.org/learn-with-ibm-bob) — IBM SkillsBuild · salvo em 03/09/2026
14. [generative-ai-for-beginners: 21 lições](https://github.com/microsoft/generative-ai-for-beginners) — GitHub · salvo em 03/09/2026
15. [project-based-learning: tutoriais baseados em projetos](https://github.com/practical-tutorials/project-based-learning) — GitHub · salvo em 03/09/2026

---

**Total do dia:** 35 notícias (TI: 5 · IA: 8 · Eng. Software: 8 · Arquitetura: 6 · Cloud: 8) + 10 vídeos "Assistir Mais Tarde" + 15 bookmarks.
