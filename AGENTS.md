# AVIBE Docs Guidelines

This repository contains the public Mintlify documentation for AVIBE and Vibe Remote.

## Writing Principles

- Write for developers and AI coding agents.
- Prefer concise, task-shaped pages over long narrative pages.
- Keep Vibe Remote positioned as a local-first remote-control layer for existing coding agents.
- Do not dilute the product voice into generic SaaS copy.
- Do not publish secrets, internal tokens, private URLs, or unreleased operational details.

## Mintlify

- `docs.json` is the source of truth for navigation.
- Pages are MDX files with frontmatter.
- Run `npm run validate` before pushing structural docs changes.
- Run `npm run broken-links` when links are changed.

## Content Boundaries

- Public docs should explain what users can install, configure, and trust today.
- Internal deployment details for AVIBE backend belong in the backend repo unless they are intentionally public.
- Comparison pages should be factual, specific, and respectful.
