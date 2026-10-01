# Contributing to Mosaikit

Thank you for considering a contribution! This guide applies to every repository of the
[Mosaikit organization](https://github.com/mosaikit) that does not have its own
`CONTRIBUTING.md`. Where a repository has one, read it as well: it covers the build and the
conventions specific to that repository.

## Ways to contribute

You do not need to write code to help:

- **Ask and answer questions** in [Discussions](https://github.com/mosaikit/mosaikit/discussions).
- **Report bugs** with the bug report form of the repository concerned. A good report says what you
  did, what you expected and what happened instead, with the version and the logs.
- **Propose features** with the feature request form. Explain the problem first: the best solution
  often comes out of the discussion.
- **Improve the documentation**: fixing an unclear sentence is a valuable contribution.
- **Write a plugin**: plugins are the heart of Mosaikit, and they do not need to live in this
  organization.

For security issues, do **not** open a public issue: follow the [security policy](SECURITY.md).

## Before you start coding

For anything bigger than a small fix, open an issue or a discussion first and describe what you
want to do. It saves you from working on something that clashes with ongoing work or with the
direction of the project. Issues labelled `good first issue` are a good place to start.

## Making a change

1. Fork the repository and create a branch from `main`.
2. Make your change, with tests. The build must pass locally: each repository's README explains how
   to run it (for the core, `./mvnw verify` runs both the backend and the frontend checks).
3. Update the documentation when the behaviour changes, and add an entry to `CHANGELOG.md` when the
   change is visible to users. Pure refactoring, tests and CI changes do not need one.
4. Open a pull request using the template, and link the issue it resolves.

Continuous integration runs the tests, the quality analysis and the security scans on every pull
request. A maintainer reviews it once the checks are green.

## Conventions

- **Language:** code, comments, commit messages and documentation are written in English.
- **Commits:** small and focused, with a message that says what changes and why. The first line is
  a short summary in the imperative mood (`Add tenant filter to the user list`).
- **Licence headers:** source files carry an SPDX header with the copyright and the licence
  (`SPDX-License-Identifier: MPL-2.0`).
- **Compatibility:** the plugin API follows semantic versioning. A change that breaks plugins needs
  a new major version and must be discussed in an issue first.

## Sign-off (Developer Certificate of Origin)

Every commit must be signed off, to certify that you wrote the change or have the right to submit it
under the licence of the project, as described in the
[Developer Certificate of Origin](https://developercertificate.org/). Add the sign-off with:

```bash
git commit -s -m "Your message"
```

This adds a `Signed-off-by: Your Name <your@email>` line that matches your Git identity. Pull
requests with commits that are not signed off cannot be merged.

## Licence

By contributing, you agree that your contributions are licensed under the licence of the repository
you contribute to — the [Mozilla Public License 2.0](https://www.mozilla.org/MPL/2.0/) for the core.
