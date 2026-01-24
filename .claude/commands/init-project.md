Initialize project CLAUDE.md for: $ARGUMENTS

1. Scan current folder structure
2. Identify:
   - Main tech stack (Python, JS, etc.)
   - Key commands (package.json scripts, Makefile, etc.)
   - Required env vars (from .env.example or README)
3. Create CLAUDE.md using this template:

```markdown
# Project: [Detected or $ARGUMENTS]

> ✅ **WORK HERE** — Add project notes here. Keep under 30 lines.
> If adding detailed rules, create `.claude/rules/[topic].md` instead.

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
<!-- Triggers: plan complete, session end, major decision, blocker -->

YYMMDD-HHMM | init project | [project name] initialized
```

5. Keep CLAUDE.md under 30 lines
6. Show draft, wait for approval before saving
7. DO NOT duplicate rules from ~/Documents/GitHub/CLAUDE.md
