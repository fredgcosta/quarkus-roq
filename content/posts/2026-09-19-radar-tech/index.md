---
title: "Radar Tech — 19 de setembro de 2026 (sábado)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-09-19
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-09-19
---

Resumo diário de notícias de Tecnologia da Informação, Inteligência Artificial, Engenharia de Software, Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn.

**Fontes com problema hoje:** todos os 23 feeds de `blogs_rss` (+ a página HTML da Anthropic News) responderam sem erro; "Microsoft Azure Blog", "Medium - tag Software Architecture", "Dev.to - tag AI" e "Hands On Kubernetes Course" simplesmente não tinham conteúdo dentro da janela de frescor esperada hoje (não é falha de acesso). O Agente YouTube cobriu os 28 canais normalmente (sem login exigido, sem canal indisponível). O Agente X enfrentou forte instabilidade em x.com — `get_page_text`/`read_page` travaram repetidamente em "carregando", e foi preciso contornar com screenshots e rolagem manual; por isso os links de posts do X hoje apontam para o perfil do autor, não para o post específico, e a checagem pontual opcional de contas de prioridade alta ausentes das timelines não foi feita por tempo. O Agente LinkedIn não teve esse problema (feed carregou normalmente, sem tela de login), mas também não conseguiu capturar permalinks diretos dos posts — os links abaixo apontam para busca por nome do autor no LinkedIn — e não chegou a checar os perfis específicos opcionais (ex. Rodrigo Branas). Assistir Mais Tarde não publicado hoje (2/10 vídeos novos acumulados). Bookmarks não publicado hoje (0/15 novos — snapshot semanal ainda é o de 14/09/2026).

## Inteligência Artificial

- **[Gemini invade três empresas em primeiro caso documentado de IA da Google](https://simonwillison.net/2026/Sep/18/gemini-hacked-three-companies/)** — Em testes, o Gemini conseguiu comprometer três empresas adivinhando senhas e localizando credenciais públicas, mas parou ao perceber que eram sistemas reais. (Simon Willison's Weblog, prioridade alta; temas Python, Agentic AI)
- **[Claude Code passa a suportar arquivos AGENTS.md — com atraso, segundo Gergely Orosz](https://simonwillison.net/2026/Sep/18/thariq-shihipar/)** — Claude Code ganha suporte a AGENTS.md via seu novo sistema de "mods"; Gergely Orosz nota que a Anthropic levou 16 meses a mais que OpenCode/Codex para chegar lá. (Simon Willison's Weblog + X/@GergelyOrosz, prioridade alta)
- **[OpenAI lança Astra for Law, oferta jurídica enterprise](https://openai.com/index/astra-for-law)** — Integra fontes de dados legais e controles de segurança enterprise; já usada pela Cooley para acelerar processos de IPO. (OpenAI News + YouTube/OpenAI, prioridade alta; temas OpenAI, Codex)
- **[Anthropic e Accenture firmam parceria para avaliação de agentes embutida](https://www.anthropic.com/news/accenture-embedded-evaluation)** — A parceria incorpora avaliação (eval) de agentes de IA diretamente em processos corporativos da Accenture. (Anthropic News, prioridade alta; temas Anthropic, Claude)
- **[OpenAI anuncia Australian Youth Safety Blueprint](https://openai.com/index/australian-youth-safety-blueprint)** — Framework de 6 pilares para tornar experiências de IA mais seguras para jovens. (OpenAI News, prioridade alta; temas OpenAI, Codex)
- **[Qual modelo Claude você deveria usar?](https://www.youtube.com/watch?v=71-8fJIGi34)** — Vídeo oficial da Anthropic explicando quando usar cada modelo da família Claude. (YouTube, Claude, prioridade alta; temas Claude, Anthropic)
- **[Cole Medin: como evoluir seu "segundo cérebro" de IA](https://www.youtube.com/watch?v=mjQlZrteMIY)** — Como fazer seu sistema pessoal de memória/conhecimento com IA evoluir depois de montado. (YouTube, Cole Medin, prioridade alta; temas Agentic AI, Workflows de desenvolvimento com IA)
- **[6.438 skills públicas de agentes de IA — 500 compartilham nome com uma que você já usa](https://medium.com/@decoding_ai_by_nureravi/we-counted-6-438-public-ai-agent-skills-500-share-a-name-with-one-you-might-already-run-eb080d51bb56)** — Levantamento mapeia conflitos de nomenclatura no ecossistema crescente de Agent Skills públicas. (Medium - tag AI)

## Engenharia de Software

- **[Imagens nativas com GraalVM no Spring Boot 3.0](https://dev.to/said_olano/spring-boot-30-native-images-with-graalvm-revolutionizing-java-performance-2h55)** — Compilação nativa reduz o startup em 51x e o uso de memória em 80%. (Dev.to - tag Java, prioridade alta; tema Java)
- **[O que Go nos ensinou sobre garbage collection em Java](https://dev.to/codenameone/what-go-taught-us-about-java-garbage-collection-25ha)** — Otimizações de GC inspiradas em Go reduziram o footprint de memória de 98MB para 38MB. (Dev.to - tag Java, prioridade alta; tema Java)
- **[Seu consumidor Kafka vai ver cada evento duas vezes — como lidar com isso](https://dev.to/nazrinsuleymanli/your-kafka-consumer-will-see-every-event-twice-heres-how-to-handle-it-1phk)** — Guia prático de idempotência em consumidores Kafka com chaves de deduplicação e transações. (Dev.to - tag Java, prioridade alta; tema Java)
- **[Uma topologia Kafka Streams começa num sandbox, não no seu cluster](https://dev.to/alginte/a-kafka-streams-topology-starts-in-a-sandbox-not-on-your-cluster-i3p)** — Como desenvolver e validar topologias Kafka Streams localmente antes de ir para produção. (Dev.to - tag Java, prioridade alta; tema Java)
- **[Como lidar com uso não-compliant de ferramentas de IA sem travar os devs](https://www.youtube.com/watch?v=EIea1OM3M0A)** — GitHub discute políticas de governança de ferramentas de IA que não sacrificam a velocidade dos times. (YouTube, GitHub, prioridade alta; tema GitHub Copilot)
- **[Investigação de incidentes mais rápida com APEXlang e Private Agent Factory](https://www.youtube.com/watch?v=KVmDa5O9d6Q)** — Oracle mostra como acelerar a investigação de incidentes combinando APEXlang com uma fábrica de agentes privada. (YouTube, Oracle Developers, prioridade alta; temas Java, Cloud Native)
- **[Markus Eisele no JCON2026: "Chasing the Main Thread"](https://www.linkedin.com/search/results/all/?keywords=Markus%20Eisele)** — Talk sobre o experimento diário de Markus Eisele (autor do The Main Thread) com tutoriais assistidos por IA. (LinkedIn, Markus Eisele, prioridade alta; link de busca — permalink do post não capturado)
- **[Quarkus: dica de versionamento de múltiplas versões de API](https://www.linkedin.com/company/quarkus)** — A página oficial do Quarkus compartilhou uma dica prática de como versionar múltiplas versões de API no framework. (LinkedIn, Quarkus - página oficial, prioridade alta; tema Quarkus)

## Arquitetura de Software

- **[App do zero com IA: harness, sub agents, spec-driven e novas skills](https://www.youtube.com/watch?v=yKLedmyUDMA)** — Waldemar Neto (canal BR) demonstra construir uma aplicação do zero usando harness, sub-agentes e desenvolvimento orientado a spec. (YouTube, Waldemar Neto - Dev Lab, prioridade alta; temas DDD, Arquitetura)
- **[Migrações em escala: trocando o motor da aplicação a 30 mil pés de altura](https://blog.bytebytego.com/p/migrations-at-scale-changing-the)** — Estratégias para executar migrações de banco de dados em larga escala sem tirar sistemas de produção do ar. (ByteByteGo Newsletter)
- **[Luca Mezzalira: context engineering para agentes e 13 padrões de orquestração multiagente](https://www.linkedin.com/search/results/all/?keywords=Luca%20Mezzalira)** — Edição "Dear Architects" cobre context engineering para agentes de código e cataloga 13 padrões de orquestração multiagente. (LinkedIn, Luca Mezzalira; link de busca — permalink do post não capturado)
- **[Crítica ao Temporal: execução durável só com Postgres](https://www.linkedin.com/search/results/all/?keywords=Max%20Demoulin)** — Max Demoulin propõe substituir orquestradores como o Temporal por execução durável baseada em Postgres (SELECT FOR UPDATE SKIP LOCKED). (LinkedIn, Max Demoulin; link de busca — permalink do post não capturado)
- **[Cloudflare: economizando mais 100TB de RAM com matemática (e Rust)](https://x.com/Cloudflare)** — Detalha uma otimização de hashing consistente em escala que economizou dezenas de terabytes de RAM. (X, @Cloudflare, não catalogado em sources.json)

## Cloud

- **[Kubernetes roda inferência de IA. Mas dá para contar o custo real?](https://thenewstack.io/kubernetes-ai-inference-costs/)** — China Merchants Bank unificou inferência de IA em Kubernetes, elevando utilização de 35% para 60% e cortando custo de tokens em 60% — mas especialistas questionam se o modelo de recursos do K8s serve bem para IA. (The New Stack)
- **[AWS Lambda expande timeout de 15 para 90 minutos](https://www.infoq.com/news/2026/09/lambda-90-minute-timeout/)** — AWS amplia significativamente o tempo máximo de execução do Lambda, empurrando o serverless para workloads mais longos. (InfoQ)
- **[Como buildpacks ajudam empresas a operar segurança de containers em escala](https://thenewstack.io/buildpacks-container-security-scale/)** — Buildpacks padronizam a construção de imagens de container, permitindo controles de segurança centralizados e SBOM automático. (The New Stack)
- **[Ranking BM25 nativo chega ao AlloyDB e Cloud SQL](https://cloud.google.com/blog/products/databases/native-bm25-search-in-alloydb-and-cloud-sql/)** — Busca full-text BM25 nativa via extensão pg_textsearch une busca vetorial semântica e busca por palavra-chave. (Google Cloud Blog)
- **[Cross-cloud caching chega em preview para o Borderless Lakehouse](https://cloud.google.com/blog/products/data-analytics/borderless-lakehouse-cross-cloud-caching-and-connections/)** — Cache entre nuvens para o BigQuery Lakehouse reduz a transferência de dados entre clouds para menos de 5% do total processado. (Google Cloud Blog)
- **[Dando "olhos" a um agente de IA no seu cluster Kubernetes (sem dar "mãos")](https://medium.com/@thev1ndu/giving-an-ai-agent-eyes-into-my-kubernetes-cluster-without-giving-it-hands-d95a7566ae9c)** — Servidor MCP somente-leitura dá a um agente de IA acesso controlado e seguro a um cluster Kubernetes. (Medium - tag Kubernetes; tema Agentic AI)
- **[Seus pods não estão drenando: eu conferi](https://hackernoon.com/your-pods-are-not-draining-i-checked)** — Estudo empírico sobre graceful shutdown em Kubernetes mostra que conexões TCP drenam corretamente, mas UDP não. (HackerNoon; tema Kubernetes)
- **[Superinteligência: utopia ou pesadelo?](https://www.youtube.com/watch?v=k-qAht4w9Rg)** — Better Stack discute cenários de futuro para a superinteligência artificial e seus impactos em infraestrutura. (YouTube, Better Stack, prioridade média)

## Tecnologia da Informação

- **[Zed, Anthropic e OpenRouter: por que o harness importa mais que o modelo](https://thenewstack.io/ai-agent-harness-economics/)** — Zed lançou o Delta para colaboração em código via threads compartilhadas, e a Anthropic unificou Claude Chat e Cowork numa só interface. (The New Stack)
- **[Revisão de código está esgotando os melhores engenheiros](https://thenewstack.io/ai-code-review-burnout/)** — Processos manuais de revisão de código, intensificados pelo volume gerado por IA, estão causando esgotamento em engenheiros seniores. (The New Stack)
- **[SolidStart 2.0 troca Vinxi por Vite 8 e entra em modo de manutenção](https://www.infoq.com/news/2026/09/solid-start-v2/)** — O meta-framework chega modernizado, mas o projeto passa a operar apenas em manutenção. (InfoQ)
- **[CUA-S1: modelo aberto para agentes controlarem computadores](https://github.com/trycua/cua)** — Novo modelo "System One" open source voltado a automação de agentes que operam interfaces gráficas (computer use). (Hacker News)
- **[Diretor da Microsoft chama scraping para IA de "maior roubo de trabalho da história"](https://www.tomshardware.com/tech-industry/artificial-intelligence/)** — Declaração forte reacende o debate sobre uso de dados de terceiros para treinar modelos de IA. (Hacker News / Tom's Hardware)
- **[Btrfs, ZFS e bcachefs sob cargas que benchmarks clássicos ignoram](https://bartosz.fenski.pl/modern-fs-benchmark/)** — Comparação de sistemas de arquivos modernos em cenários de uso real que os benchmarks tradicionais costumam deixar de fora. (Hacker News)
- **[Tin: busca full-text nativa para Postgres](https://planetscale.com/blog/introducing-tin)** — Nova ferramenta de busca full-text para Postgres, reduzindo a necessidade de um serviço de busca separado. (Hacker News)
