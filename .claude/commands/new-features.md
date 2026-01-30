Create new feature: $ARGUMENTS

## Pre-flight: Search Before Create (Principle #3)
0. Before creating, search for existing similar features:
   - Check /sandbox/ for similar names/purpose to $ARGUMENTS
   - Check /skills/ for graduated features that overlap
   - Search project src/ for related code
   - If overlap found → ask user: "Found [existing]. Extend or new?"
   - Only proceed to create if user confirms new

1. Read ~/Documents/GitHub/.claude/rules/folder-structure.md
2. Read ~/Documents/GitHub/.claude/rules/naming-conventions.md
3. Create in /sandbox/$ARGUMENTS/
4. Include:
   - README.md (what this feature does)
   - /src (feature code)
5. Show full folder structure before creating
6. Wait for approval