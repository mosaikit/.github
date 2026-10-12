# mosaikit/.github

Shared configuration of the [Mosaikit organization](https://github.com/mosaikit).

- [`profile/README.md`](profile/README.md) is the page shown on the organization's profile.
- The community files at the root of this repository — [contributing guide](CONTRIBUTING.md),
  [code of conduct](CODE_OF_CONDUCT.md), [security policy](SECURITY.md) and [support](SUPPORT.md) —
  apply to every repository of the organization that does not define its own.
- [`.github/ISSUE_TEMPLATE`](.github/ISSUE_TEMPLATE) and the
  [pull request template](.github/pull_request_template.md) are the default forms of every
  repository.

A repository overrides any of these files by adding its own copy.

## Workflows for extensions

- [`.github/workflows/extension.yml`](.github/workflows/extension.yml) is the reusable workflow of a
  extension: build and test, installation into the kernel images listed in `kernel-images`, and on a
  tag `vX.Y.Z` the signed package `<id>-<version>.zip` in a GitHub release.
- [`actions/kernel-api`](actions/kernel-api/action.yml) puts the extension API in the local Maven
  repository, from Maven Central or built from the Mosaikit repository.
- [`workflow-templates/mosaikit-extension.yml`](workflow-templates/mosaikit-extension.yml) appears in
  **Actions → New workflow** of every repository of the organization; `@mosaikit/create-extension`
  writes the same file into new extensions.
