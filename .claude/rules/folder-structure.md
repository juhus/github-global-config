# Folder Structure

## Main Layout
```
/src
  /components    → UI pieces (PascalCase)
  /services      → Business logic, API calls
  /utils         → Generic helpers
  /hooks         → Custom React hooks
  /types         → Shared TypeScript types
  /config        → App configuration ⚠️ restricted
/tests           → Test files
/docs            → Documentation
/sandbox         → Feature development (isolated)
/skills          → Production-ready modules
```

## Rules
- ❌ No new root folders without approval
- ❌ No files in /src root (must be in subfolder)
- ✅ Keep nesting max 3 levels
- ✅ Group by feature, not file type

## New Features Workflow
1. Create in `/sandbox/feature-name/`
2. Keep ALL files inside that folder
3. Include README.md
4. Don't import from /skills
5. Graduate when approved → move to /skills

## Before Creating Folders
State: "Creating folder: /path/folder-name — [reason]"