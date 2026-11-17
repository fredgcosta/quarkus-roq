---
title: "Radar Tech — 17 de novembro de 2026 (terça-feira)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-11-17
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-11-17
---

**Categorias de hoje:** Inteligência Artificial (7) · Engenharia de Software (7) · Arquitetura de Software (6) · Cloud (6) · Tecnologia da Informação (5) — 31 itens no total, coletados de blogs/RSS, YouTube, X e LinkedIn.

## Inteligência Artificial

- **[Components of Agent Memory ("Dreaming")](https://anthropic.com/research/components-of-agent-memory)** — Anthropic detalha como o processo de "dreaming" ajuda o Claude a organizar o que aprendeu e corrigir erros entre sessões. *(Anthropic, via LinkedIn)*
- **[Our first phase of embedded assessments](https://openai.com/index/our-first-phase-of-embedded-assessments)** — OpenAI inicia avaliações independentes de alinhamento e salvaguardas com Apollo Research, METR, Transluce e Goodfire. *(OpenAI News)*
- **[Anthropic Outlines its AI-Powered Code Review Process for Claude Code](https://www.infoq.com/news/2026/11/claude-code-review/)** — Como a equipe do Claude Code combina verificação automatizada, revisão por IA e aprovação humana por risco. *(InfoQ)*
- **[Claude Fable 5.2 vs. Opus 5.5: Same scores at almost 4x the cost](https://thenewstack.io/claude-fable-5-2-vs-opus-5-5/)** — Testes de programação/agentes mostram Fable 5.2 igualando o Opus 5.5 a um custo ~4x maior. *(The New Stack)*
- **[Padrão de "external sandbox" para agentes de coding](https://x.com/simonw)** — Simon Willison explora isolar agentes (Claude Code, Codex, Pi) em WebAssembly/QEMU/Apple Container, mantendo o agente fora da VM. *(X — Simon Willison)*
- **[QCon AI New York 2026: how LinkedIn, Netflix and DoorDash run agents in production](https://www.infoq.com/news/2026/11/qcon-ai-newyork-2026-program/)** — Panorama de como essas empresas operam agentes de IA em produção em larga escala. *(InfoQ, via LinkedIn)*
- **[Long-horizon agents and durable execution](https://martinfowler.com/articles/durable-execution-agents.html)** — Execução durável permite que agentes de longa duração retomem após falhas sem repetir trabalho. *(Martin Fowler)*

## Engenharia de Software

- **[HTTP/3 with Quarkus 4: One REST Endpoint, Two Transports](https://www.the-main-thread.com/p/quarkus-4-http3-quic-udp)** — Mesmo endpoint REST do Quarkus rodando em HTTP/1.1, HTTP/2 e HTTP/3. *(The Main Thread, Markus Eisele)*
- **[Java News Roundup: Lazy Constants, Spring for Apache Pulsar, GlassFish, Hibernate, TomEE, Seed4J](https://www.infoq.com/news/2026/11/java-news-roundup-nov09-2026/)** — Compilado semanal de novidades do ecossistema Java. *(InfoQ)*
- **[GitHub Rebuilds the Copilot App's Diff Surface to Open Million-Line Pull Requests Without Jank](https://www.infoq.com/news/2026/11/github-pull-requests-rebuild/)** — GitHub reconstrói a visualização de diffs do Copilot para lidar com PRs enormes. *(InfoQ)*
- **[Four days, zero lines: the AI force multiplier with GitHub Copilot](https://www.youtube.com/watch?v=ldhFlABY9Rs)** — Vídeo do GitHub sobre produtividade com Copilot. *(GitHub, YouTube)*
- **Quarkus Insights #269 — Ferramentas de migração assistidas por IA para Quarkus** — Skills open-source que analisam um projeto e guiam a migração passo a passo. Evento em 23/11. *(Quarkusio, via LinkedIn)*
- **Cuidado com lock timeout em migrations de schema** — Markus Eisele alerta que uma migração pode preservar cada nome de coluna e ainda travar o serviço esperando um lock. *(Markus Eisele, via LinkedIn)*
- **[Your Retry Logic Might Be the Reason Your System Won't Recover](https://hackernoon.com/your-retry-logic-might-be-the-reason-your-system-wont-recover)** — Retentativas sem controle geram tempestades de carga; propõe orçamentos de retry, backoff com jitter e circuit breakers. *(HackerNoon)*

## Arquitetura de Software

- **[Tests as data: ensuring AI-generated code does what we want](https://martinfowler.com/articles/tests-as-data.html)** — Testes de cliente como dados servem de contrato protegido entre humanos e agentes de código de IA. *(Martin Fowler)*
- **[Top Types of Hidden Coupling and How to Deal With Them](https://blog.bytebytego.com/p/top-types-of-hidden-coupling-and)** — Dependências ocultas entre componentes que não aparecem em diagramas de arquitetura. *(ByteByteGo, Alex Xu)*
- **Arquitetura na era da IA: você terceiriza trabalho, não responsabilidade** — Mesa-redonda no CodeCon Select com Rodrigo Branas, resumida por Elemar Júnior. *(via LinkedIn)*
- **Workshop "Implementing Domain-Driven Design"** — Vaughn Vernon abre turma de 4 dias cobrindo DDD estratégico/tático, EventStorming e Event-Driven Architecture. *(via LinkedIn)*
- **[Governed Autonomous Intelligence for Mission-Critical Utility](https://www.infoq.com/articles/utility-governed-autonomous-intelligence-ai/)** — Arquitetura agêntica com portão de políticas determinístico para sistemas críticos. *(InfoQ)*
- **[The Making of a Decision — Andrea Magnorsky, GOTO Copenhagen 2026](https://www.youtube.com/watch?v=E9dzhstNmCA)** — Palestra sobre o processo de tomada de decisão em arquitetura. *(GOTO Conferences, YouTube)*

## Cloud

- **[AWS Weekly Roundup: AWS Nitro Sandboxes, AWS Emulator, and more](https://aws.amazon.com/blogs/aws/aws-weekly-roundup-aws-nitro-sandboxes-aws-emulator-and-more-november-16-2026/)** — Destaques: emulador local de APIs, isolamento com Nitro Sandboxes, novidades em Cognito/ElastiCache/OpenSearch. *(AWS Blog)*
- **[AWS Nitro Sandboxes Put Each EKS Pod in Its Own MicroVM with One RuntimeClass Field](https://www.infoq.com/news/2026/11/aws-nitro-sandboxes-eks/)** — AWS isola cargas de EKS/ECS/EC2 em microVMs Firecracker via um único campo de configuração. *(InfoQ)*
- **[Cloudflare Introduces Private Origins for Application Services](https://www.infoq.com/news/2026/11/cloudflare-private-origins/)** — Acesso a apps em redes privadas sem expor IPs nem abrir portas de entrada (GA). *(InfoQ)*
- **[Beyond the compute bottleneck: Maximizing the ROI of AI accelerators with purpose-built storage](https://cloud.google.com/blog/products/storage-data-transfer/maximizing-ai-accelerator-roi-with-purpose-built-storage/)** — Defende storage de alto throughput para manter aceleradores de IA ocupados. *(Google Cloud Blog)*
- **[Your Kubernetes Cluster Is 92% Empty](https://medium.com/@noah_34952/your-kubernetes-cluster-is-92-empty-8f0783787b1a)** — Desperdício de capacidade em clusters K8s sob a ótica de FinOps. *(Medium — tag Kubernetes)*
- **Gemini Decisions API para roteamento de modelos** — Modelo de decisão avalia a dificuldade do prompt em centenas de ms para rotear para o modelo certo e economizar custo. *(Karl Weinmeister, Google Cloud, via LinkedIn)*

## Tecnologia da Informação

- **[Alpine Linux Users Urged to Patch OpenSSH Authentication Flaw](https://www.infoq.com/news/2026/11/alpine-linux-openssh-sshhole/)** — CVE-2026-123158 permite login não autenticado em sistemas musl sem PAM; já sendo explorada. *(InfoQ)*
- **[Universal XSS in uBlock Origin from website-driven element picker](https://iter.ca/post/ubo-uxss/)** — Vulnerabilidade XSS universal no uBlock Origin via seletor de elementos acionado por sites. *(Hacker News)*
- **[Tor Project Issues Rapid-Response DoS-Defense Fix Amid Sustained DDoS Attack](https://forum.torproject.org/t/security-release-0-4-9-17/22454)** — Correção emergencial de defesa contra DoS durante ataque DDoS prolongado. *(Hacker News)*
- **[Coles hit by a cybersecurity incident](https://www.colesgroup.com.au/updates/)** — Rede varejista australiana sofre incidente de cibersegurança. *(Hacker News)*
- **[Getting CRA Compliant Hardens the Code and Gets Your Company Closer to Digital Sovereignty](https://www.youtube.com/watch?v=C4ceqc6t0xw)** — Segurança da cadeia de suprimentos de software (Scorecard, Security Baseline, SLSA). *(InfoQ, YouTube)*

## Fontes com problema hoje

- **Microsoft Azure Blog** — falhou (bloqueado por `robots_disallowed`).
- **Assistir Mais Tarde**: não publicado hoje — só 4 vídeos novos desde a última publicação (limiar: 10).
- **Bookmarks**: não publicado hoje — 13 bookmarks novos desde a última publicação (limiar: 15).
