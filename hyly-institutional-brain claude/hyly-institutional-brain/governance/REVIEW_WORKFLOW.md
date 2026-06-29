# Review Workflow

## Overview

All changes to the Institutional Brain go through a review before merging into `main`.

## Workflow

```
Contributor → Branch → PR → Domain Steward Review → Repository Owner (if governance) → Merge
```

## Branch Naming

| Type | Format |
|------|--------|
| New knowledge asset | `add/<domain>/<asset-name>` |
| Update existing asset | `update/<domain>/<asset-name>` |
| Governance change | `governance/<description>` |
| Shared asset | `shared/<asset-name>` |

## PR Requirements

- Clear title describing what changed and why
- `meta.json` updated with new `updated` date and version bump
- No duplication of existing knowledge (confirm checked)
- Follows `STANDARDS.md`

## Review Assignments

| Change Type | Reviewer |
|-------------|----------|
| Domain knowledge | Domain Steward |
| Shared assets | Repository Owner |
| Governance files | Repository Owner |
| Scaffolded domains | Repository Owner |

## Merge Policy

- Minimum 1 approval required before merge
- Governance changes require Repository Owner approval
- Do not self-merge without review
