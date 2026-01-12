Sync global config files in ~/Documents/GitHub/:

1. Navigate to ~/Documents/GitHub/
2. Run `git status` to show what will be synced
3. Show the user the files that will be committed
4. Ask the user to confirm before committing
5. If confirmed:
   - Run `git add .`
   - Run `git commit -m "chore: sync global configs"`
   - Run `git push`
   - Confirm success
6. If not confirmed, cancel and inform user

Files being tracked (defined in .gitignore):
- CLAUDE.md
- github.code-workspace
- my-note-global.md
- .claude/ folder
