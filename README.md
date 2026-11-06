# Hi, I'm Armandas 👋

AI engineer and full-stack developer based in Vilnius, Lithuania. I build complete products end-to-end — frontend, backend, infrastructure, and the LLM systems on top — from a **commercial deployment platform** and a **citation-grounded RAG assistant** to **autonomous trading agents and workflow automation**. Everything designed, shipped, and operated in production on infrastructure I run myself.

## 🔨 What I'm working on

| Project | What it is | Stack |
|---|---|---|
| [theaode-case-study](https://github.com/Dason222/theaode-case-study) | **AODE** ([theaode.com](https://theaode.com)) — commercial self-hosted deployment platform (Vercel/Netlify alternative): git push-to-deploy, auto-SSL, rollbacks, module marketplace. Built and operated solo, in production. [Live demo](https://demo.theaode.com) | Next.js, TypeScript, Docker, Traefik |
| [eu-ai-act-assistant](https://github.com/Dason222/eu-ai-act-assistant) | **EU AI Act Assistant** — natural-language Q&A over Regulation (EU) 2024/1689 with paragraph-level EUR-Lex citations. Hybrid RAG (reference resolver + BM25 + local embeddings, RRF), provider-agnostic LLM gateway, citation validation and red-team-tested guardrails; hit@8 0.98 on a 57-question golden set. [Live demo](https://ey.theaode.com) | Python, FastAPI, Streamlit, RAG |
| [polymarket-trader](https://github.com/Dason222/polymarket-trader) | Fleet of 14 trading bots for Polymarket prediction markets — BTC 5-min binaries, whale-copy, sports momentum — under one Docker supervisor | Python, Docker, web3 |
| [trading-dashboard](https://github.com/Dason222/trading-dashboard) | Self-hosted dashboard aggregating live P&L across the whole bot fleet, with on-chain wallet-truth balance reads | FastAPI, PostgreSQL, Alpine.js |
| [openclaw-trader](https://github.com/Dason222/openclaw-trader) | Self-evolving LLM-driven trading agent: reasons over markets, evolves its own strategies, reports via Telegram | Python, LLM agents |
| [polymarket-sim](https://github.com/Dason222/polymarket-sim) | Backtesting & market-microstructure toolkit (Kyle's lambda, Hawkes processes, VPIN, optimal execution) | Python, NumPy |
| [ergonix-audit-platform](https://github.com/Dason222/ergonix-audit-platform) | Website audit platform — crawler with 40+ technical/security checks and AI content analysis | Go, React |
| [n8n-portfolio](https://github.com/Dason222/n8n-portfolio) | Production n8n workflows: market-intelligence platform + RAG/AI agent suite | n8n, LLM APIs |

## 🧰 Tools I work with

`TypeScript` `Next.js` `React` `Tailwind` `Python` `FastAPI` `PostgreSQL` `Prisma` `Docker` `Go` `n8n` `Traefik` `LLM agents` `RAG` `web3.py` `Linux ops`

---
*Everything above runs 24/7 on a VPS I administer myself — reverse proxy, TLS, monitoring, databases, and CI included.*
