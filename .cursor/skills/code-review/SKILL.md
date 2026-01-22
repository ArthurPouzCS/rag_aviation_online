---
name: Code Review Assistant
description: Guidance for performing a thorough code review
---

## What this Skill does
When performing a code review:
- Check for edge cases & error handling
- Validate TypeScript types are used properly
- Verify unit/e2e tests exist for new features
- Ensure API handlers validate inputs with Zod

## When to load
This skill should be loaded when the user is reviewing a branch or staged changes.
