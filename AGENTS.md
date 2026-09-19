# Agent rules

## GitHub Actions cost boundary

- Do not create, restore, enable, run, or rely on GitHub Actions in this repository. `.github/workflows/` must remain absent.
- CI, verification, release, and deployment must use local tooling or another mechanism whose effective cost is explicitly guaranteed to be A$0/US$0.
- Never trade convenience for metered GitHub-hosted runner usage. If a task appears to require Actions, redesign the path instead.
- This rule may be changed only by an explicit current owner instruction after confirming the replacement cannot incur GitHub Actions charges.

