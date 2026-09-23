# Alexandre Ollivier

**Senior Full-Stack Engineer / Tech Lead — Agentic & AI Engineering**
10+ years, former VP Engineering · Freelance, remote-first (Paris / Europe) · **Available from October 2026** · [atelier-agentic.com](https://atelier-agentic.com) · [LinkedIn](https://www.linkedin.com/in/alexandre-ollivier-64b925285)

I build production software with AI coding agents (Claude Code) **without giving up engineering discipline**:
restricted permissions, spec-driven development, TDD, E2E tests, and a human review on every line that ships.

- 🏗️ Complete EAI shipped to production in **20 weeks with a 2-person team**: 100% agent-generated code, 100% human-reviewed, SDD + TDD
- 🎓 Trained **11 engineers** (front, back, DevOps) on an agentic workflow that took a billing engine v2 to production
- 👥 VP Engineering over **7 teams** on a 3M-user health platform: weekly releases, 40 hires

## What's here

| Repo | What it shows |
|---|---|
| **agentic-sdd** · _coming soon_ | Claude Code plugin: spec → plans → one fresh sub-agent per task (TDD) → green CI. The orchestrator I use daily. |
| **claude-code-guardrails** · _coming soon_ | Hardened `settings.json`, permission allow/ask/deny lists, safety hooks, CLAUDE.md & steering templates |
| **agent-cassettes** · _coming soon_ | Record & replay Claude Code sessions for deterministic, token-free E2E tests of agentic apps |
| **parallel-agents-worktrees** · _coming soon_ | Run N agents in parallel: git worktrees + per-branch Postgres + isolated ports + tmux |
| **fullstack-agentic-template** · _coming soon_ | TanStack Start · Hono · Drizzle · Postgres · Bun, agent-ready, deploys to Railway / Cloudflare |
| [**interactive-cv**](https://github.com/aoll/interactive-cv) | My CV as a conversational interface |

## Stack

`TypeScript` `React` `Node.js` `Bun` `TanStack` `Hono` `Drizzle` `PostgreSQL` `Vitest` `Playwright` `Railway` `Cloudflare` · `Claude Code` `Cursor` `Subagents` `MCP` `SDD` `Evals`

## How I work with agents

1. **Spec first**: requirements → design → tasks, each approved by a human before any code is written
2. **One task, one fresh sub-agent**: small context, red → green → refactor, one commit per green state
3. **Guardrails, not vibes**: deny-by-default permissions, pre-commit / pre-push gates, no force-push, no secrets in context
4. **Humans own the merge**: every PR is reviewed line by line

📫 Open to freelance missions: Tech Lead · Senior Full-Stack · Agentic Engineering. Reach me via [LinkedIn](https://www.linkedin.com/in/alexandre-ollivier-64b925285).
