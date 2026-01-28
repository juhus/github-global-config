Initialize project CLAUDE.md for: $ARGUMENTS

1. Scan current folder structure
2. Identify:
   - Main tech stack (Python, JS, etc.)
   - Key commands (package.json scripts, Makefile, etc.)
   - Required env vars (from .env.example or README)

3. Create CLAUDE.md using this template:

```markdown
# Project: [Detected or $ARGUMENTS]

> **WORK HERE** — Project context only. Keep under 30 lines.

## On Session Start
Run `/start` command to load context from dev_log and plans.

## Overview
[One-line description inferred from README or package.json]

## Project-Specific Notes
- Stack: [detected]
- Env vars: [if any]
- Patterns: [any unique patterns found]
```

4. Create `.claude/dev_log.md`:
```markdown
# Dev Log
<!-- Format: YYMMDD-HHMM | action | outcome (max 200 chars) -->
YYMMDD-HHMM | init project | [project name] initialized
```

5. Create `.claude/plans/` folder (empty)

6. Keep CLAUDE.md under 30 lines
7. Show draft, wait for approval before saving
8. DO NOT duplicate session logic — it's all in /start
