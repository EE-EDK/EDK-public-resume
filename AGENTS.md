# AGENTS.md — Public Resume Repository — Agent Startup Brief

> **All AI agents read this first.** Project-scoped startup brief for any agent \
> (Claude, Gemini, Grok, Cursor, etc.) entering this project.

## Session Startup

Read project docs in this order (load only what the task needs):

| Order | File | Purpose |
|-------|------|---------|
| 1 | `GROK.md` | Grok execution context and project mandates (**read first in Grok sessions**) |
| 2 | `AGENTS.md` | this startup brief |
| 3 | `CLAUDE.md` | build commands, directory structure, conventions |
| 4 | `GEMINI.md` | governance mandates (overrides CLAUDE within the same directory tier) |

Load only what is scoped to this project; do **not** import sibling project context.

**Doc precedence (same tier):** `GROK.md` → `AGENTS.md` → `CLAUDE.md` → `GEMINI.md`

## Project Identity

This repository is a publicly accessible, static personal resume site (Ethan Kunz — Embedded Systems/EE focus), served via GitHub Pages directly from `index.html` with no build step. Agent scope here is repo and tooling conduct — structure, deployment, and archival hygiene — never the resume or biographical content itself.

## Red Lines

- No destructive file operations without explicit user confirmation.
- **No commits or pushes without explicit user authorization.** This matters more here than in most projects: per `README.md`, a push to `main` is reflected on the live site immediately — GitHub Pages serves `index.html` directly, with no build step or staging gate between a commit and the public page.
- **Historical preservation:** superseded resume versions live in `archive/` and are read-only — never modify archived content.
- Surgical changes only — minimize blast radius; do not refactor surrounding code unless asked.
- **Never invent, alter, or embellish resume or biographical content.** This documentation set governs tooling and structure only; resume claims, credentials, and biographical facts belong to the user and are out of scope for any agent to originate, infer, or edit.

## Commit Rules

See workspace-level protocol at `ENGINEERING-PROJECTS/root `AGENTS.md`` §Git commits.
Summary: do **not** infer "commit and push everything" unless the user explicitly requests it or triggers END SESSION. Given the live-deploy behavior noted above, confirm scope explicitly before any push to `main`.

## Validation Before Completion

- Always verify with tests, linters, DRC/ERC, or build scripts before declaring done. For this static site, that means confirming HTML validity and print-layout fidelity (`@media print`) where relevant.
- Never claim success without running the relevant verification suite.

## Parent Context

Workspace-level agent rules: `ENGINEERING-PROJECTS/root `AGENTS.md``
Technical Editor Protocol v5.4: `ENGINEERING-PROJECTS/templates/technical_editor_protocol_v5.4.md`
