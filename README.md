<div align="center">

# 🌌 Awesome Solo Founder AI

**The battle-tested stack for running a one-person AI company.**

*Curated by [Viral Patel](https://github.com/Viralpatelz) — solo founder of [TyöHunt](https://tyohunt.com), an AI job-matching SaaS running live in production (23,500+ jobs, LLM scoring, Stripe billing) built and operated by one person + AI agents.*

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-3dffb8.svg)
![License](https://img.shields.io/badge/license-MIT-7ee7ff.svg)

*Every tool here earns its place: it must let one person do the work of a team.*

</div>

---

## Contents

- [AI Coding Agents](#-ai-coding-agents)
- [LLM APIs & Models](#-llm-apis--models)
- [Agent Frameworks](#-agent-frameworks)
- [LLM Cost Control](#-llm-cost-control)
- [Backend & Data](#-backend--data)
- [Frontend & Shipping](#-frontend--shipping)
- [Payments](#-payments)
- [Monitoring & Quality](#-monitoring--quality)
- [Marketing on Autopilot](#-marketing-on-autopilot)
- [Email & Comms](#-email--comms)
- [Scraping & Data Ingestion](#-scraping--data-ingestion)
- [Solo Founder Playbook](#-solo-founder-playbook)

---

## 🤖 AI Coding Agents

*Your engineering team.*

- [Claude Code](https://claude.com/claude-code) — Terminal-native coding agent. Delegate whole features, refactors, and debugging sessions.
- [Cursor](https://cursor.com) — AI-first IDE. Fastest inner loop for day-to-day editing.
- [GitHub Copilot](https://github.com/features/copilot) — Autocomplete + coding agent that opens PRs from issues.
- [Windsurf](https://windsurf.com) — Agentic IDE with strong multi-file awareness.
- [v0](https://v0.dev) — Prompt-to-UI for React/Tailwind. Great for landing pages in minutes.

## 🧠 LLM APIs & Models

*Your product's brain.*

- [Anthropic Claude](https://www.anthropic.com/api) — Strong reasoning + long context; excellent for structured extraction (CV parsing, scoring).
- [OpenAI](https://platform.openai.com) — Broad model lineup; batch API cuts costs ~50% for offline scoring jobs.
- [Google Gemini](https://ai.google.dev) — Long-context multimodal; generous free tier for prototyping.
- [Ollama](https://ollama.com) — Run open models locally for dev/testing without burning API credits.
- [OpenRouter](https://openrouter.ai) — One API for every model; instant fallbacks when a provider is down.

## 🕸️ Agent Frameworks

*Orchestrate more than one brain.*

- [LangGraph](https://github.com/langchain-ai/langgraph) — Graph-based agent orchestration with state, retries, human-in-the-loop.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Role-based multi-agent teams; quick to stand up.
- [Microsoft AutoGen](https://github.com/microsoft/autogen) — Research-grade multi-agent conversations.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) — Type-safe agents in Python; pairs perfectly with FastAPI.
- [Model Context Protocol](https://modelcontextprotocol.io) — The standard for wiring tools into LLMs. Bet on it.

## 🔥 LLM Cost Control

*The line items that kill solo companies.*

- [TokenBurn](https://github.com/Viralpatelz/TokenBurn) — Watch token spend in real time, before your wallet does.
- [Repo2Prompt](https://github.com/Viralpatelz/Repo2Prompt) — Compress a whole repo into one LLM-ready prompt; stop pasting files.
- **Batch everything** — score 100 items per call, not 1. This single change cut TyöHunt's AI bill by an order of magnitude.
- **Cache aggressively** — identical inputs should never hit the API twice. Redis + a hash key is enough.

## ⚙️ Backend & Data

- [FastAPI](https://fastapi.tiangolo.com) — Async Python API framework; the default for AI backends.
- [PostgreSQL](https://www.postgresql.org) — One database for everything, including vectors via [pgvector](https://github.com/pgvector/pgvector).
- [Redis](https://redis.io) — Cache, queue broker, rate limiter — one binary, three jobs.
- [Celery](https://docs.celeryq.dev) — Battle-tested async task queues for scraping/scoring pipelines.
- [Supabase](https://supabase.com) / [Neon](https://neon.tech) — Managed Postgres when you don't want to run your own.
- [Docker Compose](https://docs.docker.com/compose/) — A whole production stack on one VPS. Boring beats fancy.

## 🎨 Frontend & Shipping

- [Next.js](https://nextjs.org) + [Tailwind CSS](https://tailwindcss.com) — Ship polished UI fast; AI agents know these frameworks best.
- [shadcn/ui](https://ui.shadcn.com) — Copy-paste components that look designed.
- [Vercel](https://vercel.com) / [Railway](https://railway.com) — Deploy on push; zero DevOps until you need it.
- [Hetzner](https://www.hetzner.com) — When you outgrow free tiers: serious VPS power for coffee money.

## 💳 Payments

- [Stripe](https://stripe.com) — The default. Subscriptions, coupons, trials, EU VAT — all handled.
- [Lemon Squeezy](https://www.lemonsqueezy.com) — Merchant of record; they deal with global sales tax for you.
- [Paddle](https://www.paddle.com) — MoR alternative, strong for B2B SaaS invoicing.

## 🚨 Monitoring & Quality

- [Sentry](https://sentry.io) — Know about bugs before users tweet about them.
- [Better Stack](https://betterstack.com) — Uptime checks + status page + log aggregation.
- [Lighthouse CI](https://github.com/GoogleChrome/lighthouse-ci) — Gate deploys on performance budgets.
- [Plausible](https://plausible.io) / [PostHog](https://posthog.com) — Analytics without the cookie-banner circus / product analytics with session replay.

## 📣 Marketing on Autopilot

*One founder can't post daily. Agents can.*

- **Content loops** — schedule AI agents to draft blog posts, social posts, and DM packs on a cron; you review and hit publish.
- [Buffer](https://buffer.com) — Queue a week of social posts in one sitting.
- [Canva API](https://www.canva.com/developers/) — Programmatic social graphics in your brand style.
- **SEO via programmatic pages** — generate landing pages from your data (per-city, per-category). TyöHunt's `/salaries` pages are pure database → SEO.

## ✉️ Email & Comms

- [Resend](https://resend.com) — Developer-first transactional email; React templates.
- [Loops](https://loops.so) — Drip campaigns and win-back flows without a marketing hire.
- [Postmark](https://postmarkapp.com) — When deliverability is non-negotiable.

## 🕷️ Scraping & Data Ingestion

- [Playwright](https://playwright.dev) — Headless browser automation that survives modern JS sites.
- [Firecrawl](https://firecrawl.dev) — URL → clean LLM-ready markdown.
- [Sitemap + JSON-LD parsing](https://developers.google.com/search/docs/appearance/structured-data/job-posting) — Most job/product sites expose structured data; parse it instead of scraping HTML. 10× more stable.
- **Respect robots.txt** — compliance risk is founder risk when the founder is also the legal department.

## 📜 Solo Founder Playbook

Principles that keep a one-person AI company alive:

1. **Ship daily.** A feature in staging helps no one.
2. **Verify first.** Never claim untested work works — run it, prove it.
3. **AI is leverage, not magic.** One founder + agents beats a slow team of ten — but only with tight review loops.
4. **Every LLM call is a line item.** Batch it, cache it, or delete it.
5. **Boring infra, exciting product.** One VPS, one Postgres, Docker Compose. Spend novelty tokens on the product.
6. **If one way fails, find another. Always ship.**

---

## Contributing

Found a tool that lets one person do the work of a team? [Open a PR](CONTRIBUTING.md) — one line, one link, one honest sentence on why it earns its place.

## License

[MIT](LICENSE) © Viral Patel
