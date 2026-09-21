# Repository agent instructions

## GitHub Actions / CI policy

- Do not add, restore, generate, or enable GitHub Actions workflows under `.github/workflows/*.yml` or `.github/workflows/*.yaml`.
- Do not add CI, CD, scheduled Actions, release Actions, deploy Actions, quality-gate Actions, or other GitHub-hosted workflow automation unless the repository owner explicitly requests it in the current task.
- Run lint, tests, builds, audits, packaging, and release validation locally instead of GitHub Actions.
- PRs should record the local validation commands and results when relevant.
- This restriction is intentional to avoid consuming the account's GitHub Actions minutes quota.
- Keep `.github/workflows/` free of executable YAML workflow files. Do not remove or weaken this policy without explicit owner approval.
