# Austin Gailey

I build internal AI platforms: the gateway, the agents, the cost controls and the guardrails. Site Reliability Engineer by training, so it ships with access control, logging and an on-call story.

Denver Metro, CO · [LinkedIn](https://www.linkedin.com/in/AustinGailey)

## What I've built

| Project | What it is | Stack |
|---|---|---|
| [mcp-gateway](https://github.com/AustinGailey/mcp-gateway) | MCP proxy with single sign-on, role-based tool access, an audit log, a per-team cost ledger and OpenTelemetry traces | TypeScript, OIDC, Kubernetes |
| [tokenwise](https://github.com/AustinGailey/tokenwise) | LLM cost gateway: prompt and response caching, a per-request savings ledger, one trace span per request | TypeScript, Cloudflare Workers, Hono, Next.js |
| [claude-cost-engineering](https://github.com/AustinGailey/claude-cost-engineering) | Prompt caching as a team default: 58% lower per-call cost, 79% with batch | Skill, runbook, calculator |

More on the way: a planner that runs coding agents under a token budget, and a multi-agent pipeline with independent QA gates.

## How I work

- Agents do the work; gates decide if it ships. No agent passes its own output.
- Every model call has an owner, a log line and a cost.
- Reliability is a feature: SLOs, real-path checks and a release gate before anything goes live.
