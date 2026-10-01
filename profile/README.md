<div align="center">

# Mosaikit

**An open, modular platform for building web applications out of plugins.**

The core gives you the foundations every application needs.
Plugins add the rest: screens, services and data, piece by piece, like the tiles of a mosaic.

[![License: MPL-2.0](https://img.shields.io/badge/License-MPL--2.0-brightgreen.svg)](https://www.mozilla.org/MPL/2.0/)

</div>

---

## Why Mosaikit

Most applications rebuild the same foundations before they get to what makes them different:
sign-in, users, organizations, languages, themes. Mosaikit ships those once, in a small and
well-tested core, and lets everything else arrive as plugins that extend the frontend, the
backend services and the database.

- **Plugins all the way down.** A plugin can extend the core and other plugins, so a feature can be
  extended without being forked.
- **Bring your own frontend framework.** Plugin user interfaces are Web Components: each team picks
  the framework it prefers.
- **Multi-tenant from day one.** Organizations, users, local sign-in and federation with external
  identity providers are part of the core.
- **Runs where you need it.** A container image and a Helm chart for Kubernetes, and a portable
  distribution for a single machine.
- **Open, and open to business.** The core is licensed under MPL-2.0: you can build open-source or
  commercial plugins on top of it.
- **Verifiable releases.** Every release comes with a software bill of materials (CycloneDX) and
  checksums signed with Sigstore.

## Repositories

| Repository | What it is |
| --- | --- |
| [**mosaikit**](https://github.com/mosaikit/mosaikit) | The core: kernel, plugin API (Java and TypeScript SDKs), container image, Helm chart, portable distribution and documentation |
| [**.github**](https://github.com/mosaikit/.github) | This profile and the community files shared by every repository of the organization |
| [**mosaikit.github.io**](https://github.com/mosaikit/mosaikit.github.io) | The [site](https://mosaikit.github.io/) of the project and its marketplace of plugins |
| [**catalog**](https://github.com/mosaikit/catalog) | The signed catalog of the plugins published by the project, ready to add to an installation |

Coming next: the first **official plugins**, published in the catalog and listed in the
[marketplace](https://mosaikit.github.io/marketplace/).

## Get started

- **Try it:** download the latest version from the
  [releases](https://github.com/mosaikit/mosaikit/releases) — container image, Helm chart and
  portable archives for Windows, macOS and Linux.
- **Read the docs:** the [documentation](https://mosaikit.github.io/mosaikit/)
  covers installation, configuration and plugin development.
- **Build a plugin:** depend on the plugin API from Maven Central and npm, and follow the plugin
  development guide in the documentation.

## Get involved

Mosaikit is young, and this is the best moment to shape it.

- 💬 Ask questions and share ideas in [Discussions](https://github.com/mosaikit/mosaikit/discussions)
- 🐞 Report a bug or propose a feature in the [issues](https://github.com/mosaikit/mosaikit/issues)
- 🛠️ Contribute code or documentation: start from the
  [contributing guide](https://github.com/mosaikit/.github/blob/main/CONTRIBUTING.md)
- 🔒 Report a vulnerability privately, as described in the
  [security policy](https://github.com/mosaikit/.github/blob/main/SECURITY.md)
- ⭐ Star the [core repository](https://github.com/mosaikit/mosaikit) if Mosaikit is useful to you:
  it helps others find it

Everyone taking part in the project follows our
[code of conduct](https://github.com/mosaikit/.github/blob/main/CODE_OF_CONDUCT.md).
