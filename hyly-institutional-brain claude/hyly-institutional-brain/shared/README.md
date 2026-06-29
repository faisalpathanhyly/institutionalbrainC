# Shared

This folder contains reusable assets consumed by multiple knowledge domains.

If an asset is used by more than one domain, it belongs here — not inside any single domain.

## Contents

| Folder / File | Purpose |
|---------------|---------|
| `schemas/` | JSON schemas for metadata and knowledge assets |
| `templates/` | Reusable Markdown templates for common asset types |
| `prompts/` | Common AI prompts reused across domains |
| `rubrics/` | Shared assessment rubrics |

## Usage Rule

Do not copy shared assets into domain folders. Reference them from `shared/`. If you need a domain-specific variant, extend the shared asset and document the variation.
