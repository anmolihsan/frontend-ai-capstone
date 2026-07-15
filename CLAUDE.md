# Project Conventions

## Stack
- **Runtime**: Node.js LTS
- **Package Manager**: npm
- **Framework**: React with Next.js (App Router)
- **Styling**: Tailwind CSS
- **State Management**: Zustand or React Context
- **AI Assistant**: Claude Code / Cursor

## Coding Standards
- Use ESLint + Prettier (Airbnb style)
- File naming: kebab-case for components, camelCase for utilities
- Commit messages: Conventional Commits (see below)

## AI Collaboration Rules
- When generating code, always include JSDoc comments.
- Write unit tests for all new functionality.
- Suggest refactorings if you see duplication.

## Conventional Commits
We follow the [Conventional Commits 1.0.0](https://www.conventionalcommits.org/) format:
- `feat:` new feature
- `fix:` bug fix
- `docs:` documentation only
- `chore:` maintenance tasks
- `refactor:` code restructuring
