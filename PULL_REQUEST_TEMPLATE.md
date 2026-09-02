## Summary
<!-- What changes and why, from the reader's perspective. One or two lines. -->

## Checklist
- [ ] The title carries `[BT-XXXX]` — the id of **this** change (`type(scope): description [BT-XXXX]`). Linear moves the card to In Review when the PR opens and reopens cards already in Done, so name only the card this PR is about.
- [ ] The repo's gates are green locally (README → Verify; typically `pnpm lint && pnpm typecheck && pnpm test`, plus `pnpm build` where it exists).
- [ ] `README.md` still true if setup, commands, branches, environments or deploy changed ([org README standard](https://github.com/batwiseai/batwise-app/blob/develop/docs/standards/readme-standard.md)).
- [ ] JSDoc header (1–2 lines, WHAT not HOW) on every new `.ts`/`.tsx` file.
- [ ] `[deploy]` in the title only if this repo deploys from the squash subject (README → Deployment); it goes last.

## Related issues
<!-- BT-XXXX — a bare mention in this body also moves the card in Linear (In Progress when the PR opens, In Review when it merges). Do not name cards this PR is not about. -->

## Test plan
<!-- What was run, against which environment. Screenshots for UI changes. -->
