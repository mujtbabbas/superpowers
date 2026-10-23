# Reader's Guide — superpowers

## What this project is

**Superpowers** is a **complete software development methodology for your
coding agents**, built on a set of composable skills plus the initial
instructions that make sure the agent actually uses them. Instead of letting
an agent freestyle, Superpowers walks it through a disciplined flow —
brainstorm, plan, test-drive, execute with subagents, review, verify, finish
— so agent-built software comes out engineered rather than improvised.

## How the content is organised

- `skills/` — **the skills library, 15 skills**, one folder each:
  `using-superpowers` (the entry point that teaches the agent the system),
  `brainstorming`, `writing-plans`, `executing-plans`,
  `subagent-driven-development`, `dispatching-parallel-agents`,
  `test-driven-development`, `systematic-debugging`,
  `requesting-code-review`, `receiving-code-review`,
  `verification-before-completion`, `finishing-a-development-branch`,
  `using-git-worktrees`, `writing-skills`, `diagnosing-superpowers`.
- [`README.md`](README.md) — the manual: **How it works**, **Installation**
  (per host — Claude Code via the official or Superpowers marketplace,
  Antigravity, Codex app/CLI, Cursor, Devin CLI, Gemini CLI, GitHub Copilot
  CLI, Kimi Code, OpenCode, Pi, Hermes Agent, Muse and more), **The Basic
  Workflow**, **When Something Goes Wrong**, **What's Inside** and
  **Philosophy**.
- **Per-host plugin packaging** at the root — `.claude-plugin/`,
  `.codex-plugin/`, `.cursor-plugin/`, `.antigravity-plugin/`,
  `.devin-plugin/`, `.hermes-plugin/`, `.kimi-plugin/`, `.muse-plugin/`,
  `.opencode/`, `.pi/`, `.agents/`, `gemini-extension.json` — the same
  methodology packaged for each agent host.
- `hooks/` — session hooks; `scripts/` — tooling; `docs/` — documentation
  (including the visual-companion material the README references);
  `tests/` — the test suites; `RELEASE-NOTES.md` — the long release history.

## How to use it

1. Install for your host from the README's **Installation** section.
2. Start a task — `using-superpowers` routes the agent into the workflow:
   brainstorm → plan → TDD execution (often via subagents) → review →
   verification → branch finish.
3. Read **Philosophy** and **When Something Goes Wrong** when the flow feels
   heavy; they explain what each step protects against.

## About this standalone edition

This repository is a standalone edition of
[obra/superpowers](https://github.com/obra/superpowers), converted from a
fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to Jesse Vincent
(obra) and the upstream contributors; licence MIT (see `LICENSE`).
