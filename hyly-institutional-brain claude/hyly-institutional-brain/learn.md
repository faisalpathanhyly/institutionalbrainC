# learn.md — AI Architectural Guide

> This document is written for AI systems. Human contributors should read `README.md` first.

## What This Repository Is

The Hyly Institutional Brain is a structured knowledge repository. It is not a document storage system. It is the organization's institutional memory, organized for consumption by humans, AI models, and future applications.

## Core Philosophy

### Knowledge is the Source of Truth
Knowledge exists independently of how it is consumed. Courses, AI tutors, and assessments are consumers — not owners — of knowledge.

### Learning Assets are Outputs
Courses are one delivery method. New delivery mechanisms should consume existing knowledge rather than recreate it.

### Every File Has One Responsibility
- `README.md` → explains what something **is**
- `learn.md` → explains how **AI should understand** it
- `meta.json` → describes **metadata**
- Governance files → define **repository rules**

Never overlap these responsibilities across files.

## Repository Conventions

### Folder roles
| Folder | Role |
|--------|------|
| `governance/` | Rules for managing the repository. Does NOT contain knowledge. |
| `shared/` | Reusable assets (schemas, templates, prompts, rubrics) used across domains. |
| `s-academy/` | Knowledge domains consumed by the S.Academy learning platform. |

### Domain folders (inside `s-academy/`)
Each domain is independent. Each domain contains:
- `README.md` — what this domain covers
- `meta.json` — domain metadata (status, owner, maturity)
- Knowledge asset subfolders as the domain grows

### MVP vs Scaffolded Domains
Active in MVP:
- `multifamily-industry/`
- `client-intelligence/`
- `ai-intelligence/`

Scaffolded (future):
- `partner-integrations/`
- `competitor-intelligence/`

Scaffolded domains have structure but minimal content. Do not populate them without explicit direction.

## Rules for AI Agents

1. Read `learn.md` before creating or modifying any file in this repository.
2. Follow the single-responsibility principle. Do not add content to a file that serves a different purpose.
3. Do not duplicate knowledge. If it exists in `shared/`, reference it — do not copy it.
4. Do not populate scaffolded domains unless explicitly instructed.
5. All metadata belongs in `meta.json`, not in `README.md`.
6. Respect governance files. They define what is allowed, not what is suggested.

## Architecture Stability

This architecture is intentionally stable. Changes to structure or naming conventions require governance approval. When in doubt, propose rather than act.
