# Salvio Tonon

Engineer at [Epic](https://epic.new). I build the system that turns a product spec into shipped software: AI agents plan, build and verify each issue in its own sandbox, and a person reviews what comes out.

**What I work on**

- **The builder** — Next.js app that takes a PRD to issues to pull requests, on a four-layer architecture every generated project inherits.
- **Sandboxes** — one machine per issue across Daytona and Boat, behind a reverse proxy that gives every provider the same preview origin.
- **The agent pipeline** — durable build → verify → fix workflows where every failure is classified and every transcript is kept.
- **CLI & skills** — [`@epicnew/cli`](https://www.npmjs.com/package/@epicnew/cli) and [`@epicnew/skills`](https://www.npmjs.com/package/@epicnew/skills) run the same lifecycle locally, for Claude Code, Codex and Gemini.

**Stack** — TypeScript · Next.js · React · Drizzle/libSQL · Workflow DevKit · AI SDK · Vitest · Playwright

[epic.new](https://epic.new)
