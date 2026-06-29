# Knowledge Lifecycle

## Stages

```
Draft → Active → Under Review → Updated | Deprecated
```

| Status | Meaning |
|--------|---------|
| `draft` | Being authored, not ready for consumption |
| `active` | Reviewed, approved, ready for use |
| `under-review` | Flagged for revision, still visible but pending update |
| `deprecated` | No longer current; retained for historical reference only |

## Lifecycle Rules

- New assets start at `draft`
- Assets move to `active` only after review approval
- Deprecated assets are **not deleted** — they are retained with `status: deprecated` in `meta.json`
- If knowledge is superseded, the new asset must reference the deprecated one

## Review Triggers

An asset should be queued for review when:
- 6+ months have passed since last update
- Industry or product changes make content potentially outdated
- A Domain Steward flags it
- An AI agent surfaces a conflict with newer knowledge

## Retirement

Retiring knowledge requires:
1. Domain Steward approval
2. `status` updated to `deprecated` in `meta.json`
3. A `deprecated_note` field added explaining why and what replaced it
