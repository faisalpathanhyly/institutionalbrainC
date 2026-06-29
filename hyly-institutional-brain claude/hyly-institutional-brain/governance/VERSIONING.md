# Versioning

This repository uses semantic versioning for all knowledge assets.

## Format

`MAJOR.MINOR.PATCH`

## Rules

| Increment | When |
|-----------|------|
| `PATCH` | Typos, corrections, formatting fixes — no content meaning changes |
| `MINOR` | New content added, examples added, sections expanded — no structural breaks |
| `MAJOR` | Structural reorganization, removal of sections, breaking changes to schema |

## Repository-Level Versioning

The repository itself is versioned in `README.md` header and tracked via Git tags.

Tag format: `v1.0.0`, `v1.1.0`, etc.

## Asset-Level Versioning

Each knowledge asset tracks its own version in `meta.json`:

```json
{
  "version": "1.0.0",
  "updated": "2025-01-01"
}
```

Always bump version and update the `updated` date when submitting changes.
