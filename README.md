# Mahmood Ahmed

AI/ML Engineer — 2+ years building production LLM systems, agent platforms, and scraping pipelines.

I work on the stuff that breaks in production, not just in a notebook: hallucination guardrails for LLM agents, scraping pipelines with LLM-based data enrichment, and reliability engineering around all of it.

## What I've built

**MyBioAI Agent Platform** — LLM agent platform (Claude/GPT-4, LangChain) with anti-hallucination guardrails. Built and shipped.The architecture centered on constraining agent output against a verified knowledge base and catching drift before it reached users.

**Company & Technology Intelligence Scrapers** — Production scraping pipelines with an LLM-based data enrichment layer (OpenAI API). Tested tree-of-thought, one-shot, and chain-of-thought-with-self-consistency prompting strategies for extraction accuracy; landed on self-consistency for the best reliability/cost tradeoff.

**[PrevYou](https://prevyou.app)** — Co-founded, live SaaS product. Virtual try-on powered by AI image generation. Stress-tested model robustness across pose, lighting, garment, and background edge cases before shipping.

**Automated reporting pipeline** — end-to-end pipeline turning scraped + enriched data into structured reports, no manual step in between.

Most of my recent production work sits behind client NDAs, which is why it isn't in the repos below — happy to walk through architecture and design decisions directly.


## Stack

`Python` `TypeScript` `FastAPI` `LangChain` `Claude / GPT-4` `AWS (EC2, ECR, ELB)` `Docker` `NGINX` `Pinecone` `tiktoken`

## Elsewhere

[Portfolio](https://mmahmood.vercel.app) · [LinkedIn](https://linkedin.com/in/m-mahmood-ahmad)
