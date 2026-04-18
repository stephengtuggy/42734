# 42734

Minimal reproduction for [Renovate discussion 42734](https://github.com/renovatebot/renovate/discussions/42734)

## Current behavior

Renovate tries to update the `angular-monorepo` npm dependencies from v21.2.7 to v21.2.9, and fails with a number of errors from npm about peer dependency versions not matching.

## Expected behavior

Renovate should successfully create a PR that updates the `angular-monorepo` npm dependencies from v21.2.7 to v21.2.9.
