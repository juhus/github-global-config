# Planning Rules

## Location
- Plans saved to: `project/.claude/plans/` (synced with GitHub)
- NOT user-level `~/.claude/plans/` (not synced)

## Naming Convention
`plan-three-word-title-YYMMDD-HHMM.md`
Example: `plan-auth-system-refactor-260128-1430.md`

## When Planning
1. **Always check existing plans first** in `.claude/plans/`
2. If work relates to existing plan → **update that plan**
3. If new feature/topic → **create new plan** with different title
4. Never create duplicate plans for same topic

## Plan Content
- Current understanding
- Implementation approach
- Files to modify
- Verification steps
- Status/progress

## Commands
- `/start` → Check latest plan, ask to continue or fresh
- `/gohome` → Save current session to plan + commit
