# Dev Log Rules

## Location
`.claude/dev_log.md` in each project (created by init-project)

## Format
```
YYMMDD-HHMM | action | outcome
```
Max 200 chars per entry. Latest at TOP.

## Triggers (When to Log)
- After plan implementation complete
- Session end (summarize key actions)
- Major decision made
- Blocker hit or resolved

## Don't Log
- Routine file reads/exploration
- Every small edit
- Failed attempts (unless lesson learned)

## Reading
- Only read first 20 entries for context
- Full log for debugging patterns

## Archiving
- Monthly: rename to `dev_log-YYMM.md`
- Start fresh `dev_log.md`
