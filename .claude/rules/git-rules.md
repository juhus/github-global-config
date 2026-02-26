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
1. Check `.claude/dev_log.md` — if session had notable work, add entry. Skip if nothing meaningful.
2. Check if a plan was used this session — if unsaved, copy to `.claude/plans/`. Skip if no plan.
3. Stage dev_log + plan alongside code changes (if updated)
4. Show what will be committed
5. Use clear message

## Branches
- feature/name → new features
- fix/name → bug fixes
- Don't push to main directly

## Global Workspace Git
- `~/Documents/GitHub/` tracks global config only (`CLAUDE.md`, `.claude/`, `github.code-workspace`)
- Project folders are excluded via `.gitignore` — each is its own separate repo
- ❌ Never point this remote to a project repo
- Always verify `git remote -v` before pushing here