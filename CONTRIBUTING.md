# Contributing to Katalyst

Katalyst is the internal operations platform for distributed tutoring coordination.

## Setup

```bash
npm install
cp .env.example .env.local
npm run dev
```

## Standards

- TypeScript strict mode
- Component-driven, data flows top-down
- No business logic in UI components — keep it in hooks or server actions
- Run 
pm run lint && npm run typecheck before pushing

## Branching

eat/<area>/<short-desc>, ix/<area>/<short-desc>

## Commit format

```
feat(scheduling): add tutor availability calendar view
fix(auth): resolve session expiry on role-protected routes
```