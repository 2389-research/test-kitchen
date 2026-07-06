# Phase 5 result.md Template

Save to: `docs/plans/<feature>/cookoff/result.md`

```markdown
# Cookoff Results: <feature>

## Design
docs/plans/<feature>/design.md

## Implementations
| Impl | Plan Approach | Tests | Fresh-Eyes | Lines | Result |
|------|---------------|-------|------------|-------|--------|
| impl-1 | Component-first | 24/24 | 1 minor | 680 | eliminated |
| impl-2 | Data-layer-first | 22/22 | 0 issues | 720 | WINNER |
| impl-3 | TDD-strict | 26/26 | 2 minor | 590 | eliminated |

## Plans Generated
- impl-1: docs/plans/<feature>/cookoff/impl-1/plan.md
- impl-2: docs/plans/<feature>/cookoff/impl-2/plan.md
- impl-3: docs/plans/<feature>/cookoff/impl-3/plan.md

## Winner Selection
Reason: Clean fresh-eyes review, solid data-layer-first architecture

## Cleanup
Worktrees removed: 2
Branches deleted: <feature>/cookoff/impl-1, <feature>/cookoff/impl-3
Winner branch: <feature>/cookoff/impl-2
```
