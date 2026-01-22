---
name: Deployment Workflow
description: Steps and conventions for deploying to production
---

## Deployment Steps
1) Run local build: `npm run build`
2) Run typecheck: `npm run typecheck`
3) Run full test suite: `npm run test`
4) Ensure env variables are set
5) Push to configured remote

## Notes
- Feature branches must be up to date with main
- Use feature toggles for gradual rollout
