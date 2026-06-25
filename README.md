# Daniel Kitchen

I build AI agents and ship them — Anthropic SDK direct, real evals, production deploys. Not demos.

<a href="https://yonderrecipes.com"><img src="https://raw.githubusercontent.com/iamdanielkitchen/yonder/main/docs/yonder-home.png" alt="Yonder — list the dishes you eat on repeat, get one new recipe tuned to how far you'll stretch" width="420"></a>

Twenty years running The Diffusion Co. — scoping products with outside PCB and firmware shops, validating designs, shipping hardware to paying customers. Fifteen-plus years of customer-facing work before that. Same job now, with LLMs as first-class parts of the build.

## What I have shipped

- **[Fieldstone](https://ecomm-support-agent.vercel.app)** — a support agent that looks up orders, checks return eligibility, creates returns, and escalates to a human — each through a typed tool. Retrieval against a 50-article help center when the order tools can't answer. Dual-signal confidence scoring; 98.1% pass rate on an 18-case Opus-judged golden set. Anthropic SDK direct, no framework. · [code](https://github.com/iamdanielkitchen/ecomm-support-agent)
- **[Yonder](https://yonderrecipes.com)** — list the dishes you eat on repeat; get one new recipe from a 2,476-dish corpus, tuned to how far you're willing to stretch. Calibrated novelty on Cloudflare Workers + Claude — every pick is new to you but a plausible hit. · [showcase](https://github.com/iamdanielkitchen/yonder)
- **[Curie](https://iamdanielkitchen.github.io/diffuser/)** — a piezoelectric diffuser with three oils, independently dosed, app-controlled. Designed in Shapr3D (self-taught), 23 validated prototypes, shipped to paying customers.
- **[Lever](https://breathingcyclic.netlify.app)** — two Huberman breathing protocols in one offline-capable page. Calm down or charge up. No accounts, no streaks, no upsell.

## What I am building now

**AJO** — a message bus that runs Claude agents as one system: 18 projects, 85 roles, one router. You give it an objective; it splits the work across roles, hands off, and a quality judge scores whether the job was actually done. Per-role memory pushed at spawn. Untrusted outside input stays quarantined until a human approves the pilot. Each layer is inert by default.

## Where this is going

Fieldstone first: one agent in production with evals that hold. AJO next: the coordination layer that runs many of them without falling apart. I'm most useful where an agent has to leave the demo — deployed, measured, trustworthy enough to run on its own.

## Stack

**AI / LLM** — Anthropic Claude (Opus / Sonnet / Haiku), Anthropic SDK direct, Claude Code. Tool use, RAG, embeddings (Voyage), LLM-as-judge evals, MCP. Multi-model routing (Claude, Perplexity, Grok) picked per task.

**Backend / infra** — Python, Node.js, TypeScript, Next.js. Cloudflare Workers (KV, D1, Durable Objects), Vercel, Netlify. SQLite, MongoDB Atlas, REST, webhooks, PWAs.

**Tooling / discipline** — Git/GitHub, Make.com, scheduled jobs, Datasette, pytest, pre-commit. I measure whether the output is right, not whether the run finished.

**Hardware / product** — Shapr3D CAD, PCB and firmware coordination.

**Customer / support** — Zendesk, Salesforce Service Cloud, escalation and de-escalation.

---

Reach me at iamdanielkitchen@gmail.com.
