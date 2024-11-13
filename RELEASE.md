# Release to NPM

Releases are managed through GitHub Actions.

The steps to create a new release are:
 1. Create a PR that bumps the version using the "Create bump version PR" workflow manually through GitHub Actions.
 2. Merge the PR generated by (1).
 3. The "release" workflow will detect a new release, package it, and publish it.

See the `release` and `create-bump-version-pr` workflows for more information.
