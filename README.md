# Hi there 👋

I'm **Valentin Gorpenko**, a **Senior Fullstack & AI Engineer** (Node.js / TypeScript / Vue · LLM agents) with **4+ years** building a production SaaS — the quiz builder **Marquiz** — where I grew from Middle to Senior. My core is **backend, data and reliability** on a product with hundreds of thousands of leads per account, plus an **applied-AI** track: I designed and built the company's agentic LLM service for generating and editing quizzes. Most of my work ships in a commercial product rather than public repos — happy to walk through it in a call.

### 💡 What I do

- **Applied AI / LLM agents** — designed and built an agentic quiz generation & editing service on **LangGraph** (TypeScript): persistent graph state in PostgreSQL, human-in-the-loop via interrupt/resume, thread recovery after dropped connections. The model emits **typed operations** instead of documents — validated with Zod and applied by a deterministic core (applied/rejected), with the JSON schema exported from the core itself. Model cascade by task complexity, prompt caching, classify-then-inject context (**~670 tokens instead of ~21K**), token accounting, and an eval set of 14 reference briefs with rubrics.
- **Backend, data & reliability** — archived **70M leads (200 GB)** in batches on production in ~6 hours with **zero downtime**, shrinking the main table from 215 GB to 15 GB; extracted quiz delivery into a separate read-side microservice (CQRS, own MongoDB) so the monolith stopped being a point of failure for client sites; sped up lead counters for accounts with **500k+ leads and 1,200 quizzes**.
- **Product features end-to-end** — led two "feature of the year" projects: a **CRM** with a custom-virtualized kanban board (DOM recycling, drag & drop, multi-device state sync) and an **e-commerce catalog** module (NestJS, PostgreSQL: categories, product cards, variants/options, multi-currency, JSON:API).
- **Integrations & enterprise** — Stripe, MailChimp, Huntflow, MAX messenger, Telegram bots; enterprise account work for Avito (private CRM delivery, spam filters, IP/fingerprint blocking, bulk re-delivery of leads to CRMs).
- **Team** — code review, incident response and technical support for a team of 8 engineers since 2024; deputizing for the tech lead; onboarding new developers.

### 🛠 Tech Stack

- **Backend:** Node.js, TypeScript, Express, NestJS, MongoDB (Mongoose), PostgreSQL, Redis, REST APIs, microservices, CQRS
- **AI / LLM / GenAI:** LLM agents & agentic workflows, LangGraph, LangChain, Vercel AI SDK, OpenRouter, OpenAI GPT, Anthropic Claude, prompt engineering, structured outputs, JSON Schema, Zod, guardrails, human-in-the-loop, stateful agents & checkpointing, context engineering, model routing, prompt caching, cost optimization, token accounting, evals / golden datasets, prompt versioning, RAG & vector search (side projects), Dify, AI-assisted development (Claude Code, Codex)
- **Frontend:** Vue 2/3 (Options & Composition API), Vuex / Pinia, Vite, Vitest / Jest, list virtualization, Drag & Drop, Core Web Vitals
- **DevOps:** Docker, Nginx, GitLab CI/CD, Heroku, Yandex Cloud

### 🧠 I'm interested in

- Putting LLM agents into real products — with guardrails, evals and a cost model, not demos
- Reliable backends on large, sensitive datasets
- Systems design and clean service boundaries
- Growing into a hands-on tech lead role

### 🎓 Background

B.A. in Foreign Languages (English, German) · System Design: High Scale Architecture (Karpov.courses, 2024) · Russian — native, English — B1–B2

### 📫 Contact

[Email](mailto:gorpenko2010@yandex.ru) • [Telegram](https://t.me/noctilumen)
