# Contributing

## Before You Contribute

1. Read [`/learn.md`](../learn.md) — architectural conventions for this repository
2. Read [`STANDARDS.md`](./STANDARDS.md) — file naming and formatting rules
3. Read [`REVIEW_WORKFLOW.md`](./REVIEW_WORKFLOW.md) — how changes are reviewed

## Core Rules

- **One file, one responsibility.** Do not mix purposes across files.
- **Do not duplicate knowledge.** Check `shared/` before creating reusable assets.
- **Do not modify scaffolded domains** (`partner-integrations/`, `competitor-intelligence/`) without explicit approval.
- **All metadata belongs in `meta.json`**, not in `README.md`.

## Adding a New Knowledge Asset

1. Identify the correct domain under `s-academy/`
2. Create a subfolder with a clear, lowercase, hyphenated name
3. Add `README.md`, `meta.json`, and content files following `STANDARDS.md`
4. Submit for review per `REVIEW_WORKFLOW.md`

## Adding to Shared

If an asset is reused by more than one domain, it belongs in `shared/`. Propose additions to `shared/` by opening a PR with a clear description of which domains will consume it.

## Modifying Governance

Governance changes require approval from the Repository Owner. Do not merge governance changes without explicit sign-off.
