# Git Rules

## Commits
- Don't commit without being asked
- Atomic commits (one change each)
- Use conventional format:

| Prefix | When |
|--------|------|
| feat: | New feature |
| fix: | Bug fix |
| refactor: | Code change (no new feature) |
| docs: | Documentation |
| test: | Tests |
| chore: | Maintenance |

## Examples
```
feat: add user login page
fix: resolve auth token expiry bug
docs: update README setup steps
```

## Before Committing
1. Show what will be committed
2. Wait for approval
3. Use clear message

## Branches
- feature/name → new features
- fix/name → bug fixes
- Don't push to main directly