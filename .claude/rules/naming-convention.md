# Naming Conventions

## Files
| Type | Convention | Example |
|------|------------|---------|
| Components | PascalCase | UserCard.tsx |
| Utils | camelCase | formatDate.ts |
| Hooks | use + camelCase | useAuth.ts |
| Services | camelCase.service | user.service.ts |
| Types | PascalCase.types | User.types.ts |
| Python | snake_case | user_service.py |
| Tests | [name].test.ts | auth.test.ts |
| Plans | plan-YYMMDD-HHMM-short-title | plan-260128-1430-auth-refactor.md |

## Folders
- Always kebab-case → `user-profile/`
- Max 3 levels deep
- Feature-based grouping

## Variables
| Language | Convention | Example |
|----------|------------|---------|
| JS/TS | camelCase | userName |
| Python | snake_case | user_name |
| Constants | SCREAMING_SNAKE | API_URL |
| Classes | PascalCase | UserModel |

## Timestamps
When user requests timestamped files/folders:
- Format: `YYMMDD-HHMM`
- Append to name: `feature-name-250111-1430.md`
- Folders: `backup-250111-1430/`

## Before Creating
1. Check existing similar files for patterns
2. State full path
3. Confirm convention matches above