# Hyly Institutional Brain

> The centralized knowledge repository for the Hyly Knowledge Management Practice Team.

## Purpose

The Hyly Institutional Brain is the organization's structured source of truth for institutional knowledge. It is designed to be consumed by humans, AI models, and applications — not just stored as documents.

This is not a document library. It is the organization's institutional memory.

## Vision

- Every piece of knowledge exists **once**
- Every improvement **builds** upon existing knowledge rather than duplicating it
- Every knowledge asset remains **discoverable**, **reusable**, and **version-controlled**

## Repository Structure

```
hyly-institutional-brain/
├── README.md              ← You are here (human-facing overview)
├── learn.md               ← AI-facing architectural guide
├── governance/            ← Rules for managing this repository
├── shared/                ← Reusable assets across all domains
└── s-academy/             ← AI-backed learning platform knowledge
    ├── multifamily-industry/
    ├── client-intelligence/
    ├── ai-intelligence/
    ├── partner-integrations/
    └── competitor-intelligence/
```

## High-Level Architecture

```
Hyly Institutional Brain (Source of Truth)
│
├── Governance       → Rules, ownership, lifecycle
├── Shared           → Schemas, templates, prompts, rubrics
└── S.Academy        → Knowledge Domains → Knowledge Assets → AI Intelligence Layer → Learners
```

## Ownership

**Owner:** Debarchana  
**Status:** Draft v1.0  
**Practice Team:** Knowledge Management

## Contribution

Before contributing to this repository, read [`learn.md`](./learn.md) for architectural conventions and [`governance/CONTRIBUTING.md`](./governance/CONTRIBUTING.md) for the review workflow.

All contributions must follow the single-responsibility file principle: each file answers one question.
