# Austin Gailey

I build internal AI platforms: the gateway, the agents, the cost controls and the guardrails. Site Reliability Engineer by training, so it ships with access control, logging and an on-call story.

Denver Metro, CO · [LinkedIn](https://www.linkedin.com/in/AustinGailey)

## What I've built

| Project | What it is | Stack |
|---|---|---|
| [claude-cost-engineering](https://github.com/AustinGailey/claude-cost-engineering) | Prompt caching as a team default: 58% lower per-call cost, 79% with batch | Skill, runbook, calculator |

More on the way: an LLM cost gateway, an MCP gateway with single sign-on and role-based tool access, and a planner that runs coding agents under a token budget.

## How I work

- Agents do the work; gates decide if it ships. No agent passes its own output.
- Every model call has an owner, a log line and a cost.
- Reliability is a feature: SLOs, real-path checks and a release gate before anything goes live.
