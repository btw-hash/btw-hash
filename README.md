# BTW Studio

**Production AI features, built to a spec and handed back tested.**
Agents, LLM integrations, internal tools and the infrastructure they run on.

I work as the build side for studios and product teams: you own the client and the scope, I return a working, tested, deployed piece. Written async communication, fixed scope per task.

[Site](https://btwstudio.dev) · [Live CRM demo](https://crm-pro.btwstudio.dev) · [Telegram channel](https://t.me/btw_aitech)

---

## Selected work

| Project | What it proves | Stack |
|---|---|---|
| **[crm-pro](https://github.com/btw-hash/crm-pro)** | A full B2B sales CRM with six role workspaces, an AI assistant, voice-to-document and an ERP integration layer. [Try the demo](https://crm-pro.btwstudio.dev) | Next.js 16, React 19, Prisma, PostgreSQL, clean architecture |
| **[citewise](https://github.com/btw-hash/citewise)** | Document Q&A where every sentence carries a citation that is checked against the source in code, with an eval suite that reports its own misses. Runs with no API key. [Try the demo](https://citewise.btwstudio.dev) | TypeScript, Express, BM25 |
| **[docfields](https://github.com/btw-hash/docfields)** | Invoice extraction where every number is validated in code (line items, subtotal, tax, total) and reviewed next to the text it came from. [Try the demo](https://docfields.btwstudio.dev) | TypeScript, Express, PDF parsing |
| **[vault-research-agent](https://github.com/btw-hash/vault-research-agent)** | A multi-agent research pipeline with an eval suite: planner, router, parallel MCP workers, synthesizer and an LLM judge that sends weak answers back. Runs from a clean clone with no API key. | TypeScript, Claude, MCP |
| **[benchmark-cc](https://github.com/btw-hash/benchmark-cc)** | Measurement instead of opinion: an A/B harness that isolates what each layer of a Claude Code setup contributes in tokens, wall time and judged quality. | Node.js, Claude Code |
| **[btw-agents-pack](https://github.com/btw-hash/btw-agents-pack)** | 37 subagents and 17 skills extracted from daily production use, each with an explicit tool allowlist. MIT. | Claude Code |
| **[agent-dashboard](https://github.com/btw-hash/agent-dashboard)** | Real-time observability for running agents, drawn as a pixel-art office. Live session tracking over WebSocket with a polling fallback. | Node.js, Canvas 2D, WebSocket |
| **[Nox](https://github.com/btw-hash/nox)** (showcase, code is private) | A personal AI assistant in daily use: Telegram bot, Android app with over-the-air updates, scheduled jobs, alerting, and a self-hosted server it monitors itself. | TypeScript, grammY, SQLite, Capacitor, Claude Agent SDK |

## How I work

- **Spec first.** Requirements and out-of-scope are written down before code.
- **Tests and a real run.** A change ships after the test suite passes and the path was exercised in a browser or against the live system.
- **AI behind a port.** Model providers and external systems sit behind interfaces, so swapping a provider or a stub for the real thing is a one-file change.
- **Self-hosted when it pays.** Docker, Cloudflare tunnels and a monitored home server run the demos linked here.

## Stack

**AI** Claude API and Agent SDK, MCP, tool use, evals with LLM judges, OpenRouter, Gemini
**Backend** TypeScript, Node.js, Prisma, PostgreSQL, SQLite, grammY
**Frontend** Next.js, React, Tailwind, Phaser, react-three-fiber
**Infra** Docker, Caddy, Cloudflare, GitHub Actions, Vercel

## Available for

Subcontract builds for studios and agencies, part-time contract work, AI feature integration into an existing product.
