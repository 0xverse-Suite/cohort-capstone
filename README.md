# 0xVerse Cohort Capstone

The 0xVerse Cohort Capstone is the shared, cohort-wide software workspace for 0xVerse Academy. The product specification is intentionally neutral until the current cohort approves a concrete scope.

## Architecture

- `apps/` — client applications and shared interfaces
- `backend/` — APIs, authentication, and server-side services
- `ai/` — approved AI, automation, and data workflows
- `database/` — schemas, migrations, and data documentation
- `docs/` — product, architecture, and operational decisions

## Contribution workflow

1. Select an assigned GitHub Issue and confirm its acceptance criteria.
2. Create a branch from the latest `main`: `feature/<student-or-team>/<task>` or `fix/<area>/<task>`.
3. Make focused commits and never commit secrets or local `.env` files.
4. Push the branch and open a pull request that links the Issue.
5. Address automated checks and mentor feedback.
6. A mentor approves and merges the pull request; direct pushes to `main` are prohibited.

Examples: `feature/frontend/student-dashboard`, `feature/ada/payment-api`, `fix/backend/auth-validation`.

## Local setup

```bash
gh repo clone 0xverse-suite/cohort-capstone
cd cohort-capstone
git switch main
git pull --ff-only
```

Runtime-specific setup will be added once the cohort selects its product and technology stack.

## Reviews

Pull requests should be small, explain how the change was tested, and include screenshots for visible UI changes. Reviewers check correctness, security, accessibility, maintainability, and alignment with the Issue. One approving review is required before merge.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the complete student workflow.
