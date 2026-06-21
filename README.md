# Daniel Kitchen

I build AI agents and ship them — Anthropic SDK direct, real evals, production deploys. Not demos.

<a href="https://yonderrecipes.com"><img src="https://raw.githubusercontent.com/iamdanielkitchen/yonder/main/docs/yonder-home.png" alt="Yonder — a calibrated-novelty recipe app, live at yonderrecipes.com" width="420"></a>

Founder-operator for 20 years at The Diffusion Co. — I ran multi-vendor product engagements end to end: scoping with external PCB and firmware contributors, validating designs, and driving each one from discovery to a shipped product, with 15+ years of customer-facing work underneath it. Now I do the same with LLMs as first-class components.

## What I have shipped

- **[Fieldstone](https://ecomm-support-agent.vercel.app)** — a conversational support agent, Anthropic-SDK-direct with no framework. Five typed tools including an `escalate_to_human` with a `reason_code` enum, dual-signal confidence scoring, and a 98.1% RAG eval pass rate across an 18-case Opus-judged golden set. · [code](https://github.com/iamdanielkitchen/ecomm-support-agent)
- **[Yonder](https://yonderrecipes.com)** — a recipe app that breaks your food rut one dish at a time. A calibrated-novelty engine on Cloudflare Workers and Claude, grounded in a 2,476-recipe corpus: every pick is new to you but a plausible hit. · [showcase](https://github.com/iamdanielkitchen/yonder)
- **[Curie](https://iamdanielkitchen.github.io/diffuser/)** — a piezoelectric multi-oil diffuser I designed and shipped. Three oils, independently dosed, app-controlled. Self-taught CAD in Shapr3D; 23 validated prototypes to paying customers.
- **[Lever](https://breathingcyclic.netlify.app)** — two breathing protocols from Huberman's research in one offline-capable page. No accounts, no streaks, no upsell. Built in a single session with Claude.

## What I am building now

**AJO** — a message bus that runs a fleet of Claude agents as one system: 18 projects, 85 roles, one router. It is built in layers — campaign planning, per-role memory pushed at spawn, a quality judge that scores whether the work was *actually* done, and a quarantined boundary for untrusted outside input — each one inert by default and gated behind a human-approved pilot.

The bet: a system that takes an objective, splits it across roles, does the real work, hands off, and checks its own output — autonomous coordination with no human in the loop. The objective is swappable; the coordination is the product. When it runs, it turns one operator into a fleet.

## Where this is going

The arc is one line — ship a single agent to production with evals that hold (Fieldstone), then build the system that runs many of them reliably (AJO). I am most useful where an AI agent has to leave the demo and survive contact with real users: getting it deployed, measured, and trustworthy enough to run on its own.

## Stack

**AI / LLM** — Anthropic Claude (Opus / Sonnet / Haiku), Anthropic SDK direct, Claude Code. Prompt engineering, Skills with extended thinking, tool use, RAG, embeddings (Voyage), LLM-as-judge evals, MCP. Multi-model routing across Claude, Perplexity, and Grok, picked per task.

**Backend / infra** — Python, Node.js, TypeScript, Next.js. Cloudflare Workers (KV, D1, Durable Objects), Vercel, Netlify. SQLite, MongoDB Atlas, REST APIs, webhooks, PWAs and service workers.

**Tooling / discipline** — Git/GitHub, Make.com, scheduled jobs, Datasette, pytest, pre-commit. I measure whether the output is right, not whether the run finished.

**Hardware / product** — Shapr3D CAD, cross-functional leadership across PCB and firmware.

**Customer / support** — Zendesk, Salesforce Service Cloud, escalation and de-escalation.

---

Reach me at iamdanielkitchen@gmail.com.
