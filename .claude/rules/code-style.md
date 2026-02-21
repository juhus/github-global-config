# Code Style

## General
- TypeScript for all new files
- Functional over class-based
- Functions < 30 lines
- Descriptive variable names

## Imports Order
1. External libs
2. Internal modules
3. Types
4. Styles

## Comments
- Only when WHY isn't obvious
- No commented-out code
- TODO format: `// TODO: description`

## Functions
```typescript
// ✅ Good
function getUserById(id: string): User {}

// ❌ Bad
function get(i) {}
```

## Error Handling
- Always handle errors
- Use try/catch for async
- Log meaningful messages

## Don't
- ❌ Any type (use proper types)
- ❌ Magic numbers (use constants)
- ❌ Deep nesting (> 3 levels)
- ❌ Long files (> 300 lines)

## Agent → User Instructions
When agent needs user to act:
- **⚠️REQUIRE USER ACTION** → bold, visible header
- Clear numbered steps
- Don't bury in paragraphs
- Clear instructions where and what to do, spoon feed me anything I might need.

## New Rules & Commands
When user suggests new rules or commands:
1. Ask: "Does this apply to all projects or just this one?"
2. If **global rule**:
   - Create/update `~/Documents/GitHub/.claude/rules/[topic].md`
   - Update `~/Documents/GitHub/CLAUDE.md` "Read When Needed" table
3. If **global command**:
   - Ask: "Needed at every session start, or on-demand?"
   - If every session → update `/start` command
   - If on-demand → create new command in `.claude/commands/`
4. If **project-specific** → create in project's `.claude/rules/` 