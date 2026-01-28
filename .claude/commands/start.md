Re-read CLAUDE.md files:
1. ~/Documents/GitHub/CLAUDE.md (global rules)
2. ./CLAUDE.md (project context)

Then:
1. Check current folder structure
2. List what exists in /src (if present)
3. Confirm you understand:
   - Global rules (modular approach, naming conventions, restricted areas)
   - Project purpose and context
   - Available commands

## Session Context Recovery
4. Read `.claude/dev_log.md` — show last 10 entries
5. Check `.claude/plans/` for latest plan:
   - Location: `./.claude/plans/` (project-level, synced with GitHub)
   - NOT ~/.claude/plans/ (user-level, not synced)
   - Naming: `plan-three-word-title-YYMMDD-HHMM.md`
   - If folder missing, create it
   - If plans exist, summarize the latest one

6. Brief summary: recent work (from dev_log) + latest plan
7. Ask whether to:
   - Continue with latest plan
   - Start fresh
   - Review specific dev_log items

## Context Recovery
If context degrades mid-session, run /start again.
