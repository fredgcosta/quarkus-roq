---
title: "Radar Tech — 20 de setembro de 2026 (domingo)"
description: "Resumo diário de notícias de TI, Inteligência Artificial, Engenharia e Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn."
slug: radar-tech-2026-09-20
image: tech-news-banner.svg
tags: tech-news
author: techbot
date: 2026-09-20
---

Resumo diário de notícias de Tecnologia da Informação, Inteligência Artificial, Engenharia de Software, Arquitetura de Software e Cloud, curado automaticamente a partir de blogs, YouTube, X e LinkedIn.

**Fontes com problema hoje:** nenhum agente falhou. Todos os 23 feeds de `blogs_rss` responderam sem erro (Anthropic News incluída, via WebFetch direto na página); AWS Blog, Microsoft Azure Blog, Dev.to - tag AI, Medium - tag Software Architecture e Hands On Kubernetes Course simplesmente não tinham conteúdo novo na janela (não é falha). O Agente YouTube cobriu os 28 canais normalmente, sem canal indisponível. O Agente X leu as duas timelines ("Para você" e "Seguindo") sem tela de login, mas ambas vieram dominadas por um meme viral de marketing ("Jev"/TypeSafe AI) que inflou boa parte dos posts do dia sem relevância técnica real — filtrado; a checagem pontual opcional de contas ausentes foi feita parcialmente. O Agente LinkedIn leu o feed principal normalmente, sem tela de login. **Dia com poucas notícias genuinamente novas**: a maior parte do que os 4 agentes trouxeram hoje já havia sido publicada nos últimos 1-2 dias (forte sobreposição com o resumo de ontem) e foi descartada pela deduplicação — por isso algumas categorias abaixo têm menos itens que o normal. Assistir Mais Tarde não publicado hoje (0/10 vídeos novos — a playlist não recebeu adição desde 16/09). Bookmarks não publicado hoje (0/15 novos — o snapshot semanal (`collected/bookmarks-latest.md`) ainda é o de 14/09/2026, já totalmente coberto; vale confirmar se a Tarefa Agendada de sincronia dos bookmarks ainda está rodando).

## Inteligência Artificial

- **[datasette-auth-github chega à versão 1.0](https://simonwillison.net/2026/Sep/19/datasette-auth-github/)** — Plugin de autenticação via GitHub para o Datasette corrige sessões que expiravam rápido demais. (Simon Willison's Weblog, prioridade alta; tema Python)
- **[Jerry Liu (LlamaIndex) destaca benchmark "JevBench"](https://x.com/jerryjliu0)** — Comparação de modelos/classificadores em intelligence, calibration, speed e cost. (X, @jerryjliu0, prioridade alta; tema Agentic AI)
- **[LangChain publica "Jev-as-a-Judge for Agent Evals"](https://x.com/LangChain)** — Artigo sobre usar LLM-as-judge para avaliação de agentes. (X, @LangChain, prioridade alta; temas LangChain, LangGraph, Eval Driven Development)
- **[Anthropic otimiza modelos open-source de biologia com Claude e lança competição de design de proteínas](https://www.linkedin.com/company/anthropicresearch/posts/)** — Mais de 30 modelos científicos ficaram 4x mais rápidos; parceria com Adaptyv Bio, Modal e Twist Bioscience oferece até US$ 1M em créditos Claude para validar +5.000 designs de proteínas. (LinkedIn, Anthropic, prioridade alta; temas Anthropic, Claude)
- **[Google lança Agent Development Kit 1.0 para Kotlin](https://www.infoq.com/news/2026/09/google-adk-1-0-released/)** — ADK 1.0 chega com paridade em relação ao Python, framework de produção para agentes com suporte a IA on-device no Android. (InfoQ)
- **[LangChain Deep Agents: agentes de IA prontos para produção além dos LLMs](https://hackernoon.com/beyond-llms-creating-real-world-ai-agents-with-lang-chain-deep-agents)** — Como o DeepAgents adiciona memória, habilidades e supervisão humana a agentes de produção. (HackerNoon; tema LangChain)
- **[Paper do Google: WikiSkill — agentes que evoluem suas próprias skills](https://www.linkedin.com/search/results/content/?keywords=Stanislav%20Beliaev)** — Um modelo Qwen de 9B com skills evoluídas via um "wiki" persistente entre traces superou um modelo de 27B sem elas (47,4% vs 39,4% em 5 benchmarks). (LinkedIn, Stanislav Beliaev; tema Agentic AI)
- **["Laws Instead of Diffs": a linguagem Bend 2 propõe bloquear erros de IA via prova formal](https://www.linkedin.com/posts/alindnbrg_agentharness-codingagents-formalverification-share-7507075561895370753-7Nhq)** — Em vez de revisar diffs manualmente, declarar invariantes e deixar o compilador rejeitar edições de agentes sem prova. (LinkedIn, André Lindenberg; tema Agentic AI)

## Engenharia de Software

- **[Habilidades de IA com Matt Pocock](https://newsletter.pragmaticengineer.com/p/ai-skills-with-matt-pocock)** — Pocock discute como usa "skills" de codificação com IA e agentes para planejar e construir software, reforçando que fundamentos de engenharia continuam essenciais. (The Pragmatic Engineer; tema Workflows de desenvolvimento com IA)
- **[Seu agente é só tão bom quanto sua infraestrutura](https://thenewstack.io/ai-agent-infrastructure-performance/)** — Cargas de trabalho de IA agêntica exigem infraestrutura própria, feita para padrões de uso em rajada e sequenciais, não a infraestrutura tradicional de aplicações. (The New Stack)

## Arquitetura de Software

- **[Palestra "AI-Assisted Java Development on Real Enterprise Codebases with IBM Bob and Quarkus"](https://www.linkedin.com/search/results/content/?keywords=Markus%20Eisele)** — Conferência IBM TechXchange (29/out) mostrará IBM Bob + Quarkus Dev MCP guiando assistentes de IA em um codebase real de 10-15 anos. (LinkedIn, Markus Eisele/XDEV/IBM, prioridade alta; temas Quarkus, Java)
- **[Checklist de arquitetura antes de um pico grande de tráfego](https://www.linkedin.com/search/results/content/?keywords=Java%20Developers%20Community)** — Load testing (JMeter/k6/Gatling), escalonamento horizontal com Kubernetes/HPA, cache (Redis/CDN) e otimização de banco para sistemas distribuídos. (LinkedIn, Java Developers Community; tema Kubernetes)

## Cloud

- **[Nosso cluster guardava todo job que já havia terminado](https://dev.to/sergey_shinder_ab2d943365/our-cluster-had-kept-every-job-it-ever-finished-pd1)** — Cluster Kubernetes sofreu timeouts generalizados por acumular 340 mil Jobs antigos sem política de limpeza, sobrecarregando o etcd. (Dev.to - tag Kubernetes, prioridade alta; tema Kubernetes)
- **[Assinatura keyless com Cosign no GitHub Actions: SBOMs e Kyverno](https://dev.to/devtocash/cosign-keyless-signing-in-github-actions-sign-images-attest-sboms-and-enforce-it-with-kyverno-2afk)** — Guia prático de assinatura de imagens sem chaves, atestação de SBOM e políticas de segurança de supply chain. (Dev.to - tag Kubernetes, prioridade alta; temas Kubernetes, Cloud Native)
- **[Cloudflare mede preferências de TLS na origem e reduz retentativas de handshake de 52% para 3,7%](https://www.infoq.com/news/2026/09/cloudflare-automatic-key-exchang/)** — Medição por origem permite reduzir drasticamente falhas de handshake TLS, melhorando latência. (InfoQ)
- **[Guillermo Rauch (Vercel): recorde de volume de tokens em modelos abertos no AI Gateway](https://x.com/rauchg/status/2101186741042663579)** — 78,4% do volume de tokens no Vercel AI Gateway já é de modelos abertos, contra 21,6% de modelos fechados. (X, @rauchg, não catalogado em sources.json)
- **[Neo4j lança MCP for Aura](https://www.linkedin.com/search/results/content/?keywords=Neo4j)** — Servidor MCP totalmente hospedado no Neo4j Aura, permitindo consultas em grafos por linguagem natural com OAuth nativo e controle de acesso granular. (LinkedIn, Neo4j)

## Tecnologia da Informação

- **[Open-weight já processa a maioria dos tokens no AI Gateway da Vercel, mas Anthropic ainda concentra 64% do gasto](https://thenewstack.io/open-weight-anthropic-spend/)** — Modelos de peso aberto ultrapassaram 56% do volume de tokens, mas os proprietários seguem dominando o gasto pela consistência. (The New Stack; tema Anthropic)
- **[FFmpeg 9.0.2 lançado](https://x.com/FFmpeg/status/2101315772286980253)** — Correções de decodificação WebP animado, ProRes RAW via VideoToolbox, filtros Vulkan/CUDA e suporte a GPU via ONNX Runtime. (X, @FFmpeg, não catalogado em sources.json)
