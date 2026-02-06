# Global Rules (All Projects)

> ⚠️ **READ-ONLY** — Do not modify this file. Update project CLAUDE.md instead.

## Memory Rules
- Project CLAUDE.md = context only (under 50 lines)
- Shared rules in `~/Documents/GitHub/.claude/rules/`
- Never add detailed instructions to project CLAUDE.md

### If Project CLAUDE.md Gets Long
1. STOP — do not add more content
2. Ask: "Should I create a new rule file in .claude/rules/?"
3. Options:
   - Project-specific rule → create `/project/.claude/rules/[topic].md`
   - Applies to all projects → suggest updating `~/Documents/GitHub/.claude/rules/`
4. Keep project CLAUDE.md under 50 lines

## Quick Reference
| Type | Convention |
|------|------------|
| Components | PascalCase.tsx |
| Utils | camelCase.ts |
| Python | snake_case.py |
| Folders | kebab-case/ |

## Read When Needed
| Task | Read First |
|------|------------|
| Creating files/folders | ~/Documents/GitHub/.claude/rules/naming-conventions.md |
| New features | ~/Documents/GitHub/.claude/rules/folder-structure.md |
| Writing code | ~/Documents/GitHub/.claude/rules/code-style.md |
| Git operations | ~/Documents/GitHub/.claude/rules/git-rules.md |
| Logging progress | ~/Documents/GitHub/.claude/rules/dev-log.md |
| Unsure / no rule applies | ~/Documents/GitHub/.claude/rules/principles.md |

## Core Rules
- When rules are silent, consult principles: .claude/rules/principles.md
- Challenge my ideas. Use AskUserQuestion tool to clarify. Suggest alternatives.
- Log to .claude/dev_log.md on: major decision, blocker, session end, /gohome
- Plan first if 5+ files → wait for approval
- State full path before creating any file
- Don't touch /config or .env without approval
- Use /sandbox for new features → graduate when ready

## Restricted Areas ❌
- /config/
- /core/
- .env files
- package.json (ask first)

## File Structure Reminder
```
~/Documents/GitHub/
  CLAUDE.md              ← READ-ONLY (global rules)
  .claude/rules/         ← Shared detailed rules
  .claude/commands/      ← Shared commands
  
  /project/
    CLAUDE.md            ← WORK HERE (project context only)
    .claude/rules/       ← Project-specific rules (if needed)
```

---

> 🚨 **AFTER READING THIS:** Run `/start` to load dev_log and plans.