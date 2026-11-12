# Austin Gailey

I build internal AI platforms: the gateway, the agents, the cost controls and the guardrails. Site Reliability Engineer by training, so it ships with access control, logging and an on-call story.

Denver Metro, CO · [LinkedIn](https://www.linkedin.com/in/AustinGailey)

## What I've built

| Project | What it is | Stack |
|---|---|---|
| [mcp-gateway](https://github.com/AustinGailey/mcp-gateway) | MCP proxy with single sign-on, role-based tool access, an audit log, a per-team cost ledger and OpenTelemetry traces | TypeScript, OIDC, Kubernetes |
| [tokenwise](https://github.com/AustinGailey/tokenwise) | LLM cost gateway: prompt and response caching, a per-request savings ledger, one trace span per request | TypeScript, Cloudflare Workers, Hono, Next.js |
| [runway](https://github.com/AustinGailey/runway) | Planner that launches headless coding agents under a token budget and lands their work through a merge train | Python |
| [take-one-pipeline](https://github.com/AustinGailey/take-one-pipeline) | Multi-agent pipeline with supervised jobs, enforced write lanes and nine independent QA gates | Python |
| [lodestar](https://github.com/AustinGailey/lodestar) | Reliability layer for agent-built software: journey registry, real-path checks, a release gate, and a ranked backlog agents claim work from | TypeScript, Python |
| [claude-cost-engineering](https://github.com/AustinGailey/claude-cost-engineering) | Prompt caching as a team default: 58% lower per-call cost, 79% with batch | Skill, runbook, calculator |

![Runway planner board](https://raw.githubusercontent.com/AustinGailey/runway/main/docs/hero.png)

![Lodestar health dashboard](https://raw.githubusercontent.com/AustinGailey/lodestar/main/docs/hero.png)

## How I work

- Agents do the work; gates decide if it ships. No agent passes its own output.
- Every model call has an owner, a log line and a cost.
- Reliability is a feature: SLOs, real-path checks and a release gate before anything goes live.
