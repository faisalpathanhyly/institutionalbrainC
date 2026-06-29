# Repository Standards

## File Naming

- All folder and file names use **lowercase** and **hyphens** (no spaces, no underscores)
- Example: `multifamily-industry/`, `client-overview.md`

## Required Files Per Knowledge Asset

| File | Required | Purpose |
|------|----------|---------|
| `README.md` | Yes | What this asset is (human-facing) |
| `meta.json` | Yes | Metadata (owner, status, version, dates) |
| `learn.md` | Recommended | How AI should understand this asset |

## meta.json Schema

```json
{
  "title": "",
  "version": "0.1.0",
  "status": "draft | active | deprecated",
  "owner": "",
  "domain": "",
  "created": "YYYY-MM-DD",
  "updated": "YYYY-MM-DD",
  "tags": [],
  "consumers": []
}
```

## Versioning

Follow semantic versioning (`MAJOR.MINOR.PATCH`):
- `PATCH` — corrections, typos, small updates
- `MINOR` — new content added, no breaking structural changes
- `MAJOR` — structural reorganization, breaking changes

## Formatting

- Markdown for all documentation files
- JSON for all metadata files
- Avoid HTML inside Markdown
- Keep files focused — if a file exceeds ~200 lines, consider splitting
