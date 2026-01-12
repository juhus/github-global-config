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

## Key Commands
```bash
[Top 3-5 most useful commands]
```

## Project-Specific Notes
- Stack: [detected]
- Env vars: [if any]
- Patterns: [any unique patterns found]
```

4. Keep under 30 lines
5. Show draft, wait for approval before saving
6. DO NOT duplicate rules from ~/Documents/GitHub/CLAUDE.md