# GROK.md — Public Resume Repository

Grok execution context for this project. Read this first in Grok sessions; walk up to parent directories if absent.

## Project Identity

Publicly accessible personal resume repository (Ethan Kunz — Embedded Systems/EE focus), hosted via GitHub Pages as a static site with no build step. This file covers repo/tooling conduct only, never resume content.

## Repository Structure

- `index.html` — primary resume, GitHub Pages entry point
- `assets/` — shared media (logos, video)
- `archive/` — superseded resume versions, read-only, organized by year

## Deployment — live-deploy risk

The site has no build step and no staging environment. A push to `main` is reflected on the live site immediately — GitHub Pages serves `index.html` straight from the branch. **Double-check any push to `main` before it happens**: there is no preview or CI gate between a commit and the public page.

## Doc precedence

`GROK.md` → `AGENTS.md` → `CLAUDE.md` → `GEMINI.md` (same tier)

Parent context: `ENGINEERING-PROJECTS/GROK.md`
