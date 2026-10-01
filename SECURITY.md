# Security policy

The security of Mosaikit and of the systems that run it matters to us. Thank you for helping keep
it safe.

## Reporting a vulnerability

**Do not report vulnerabilities in public issues, discussions or pull requests.**

Report them privately through GitHub: open the **Security** tab of the repository concerned and
choose **Report a vulnerability**. If that is not possible, write to **massimo.anto@gmail.com** with
"Security" in the subject.

Please include:

- the affected component and version;
- a description of the vulnerability and its impact;
- the steps to reproduce it, ideally with a minimal proof of concept;
- any suggestion for a fix.

## What happens next

- We acknowledge the report within **5 working days**.
- We confirm or dismiss the vulnerability and agree with you on a timeline for the fix.
- We publish the fix and a security advisory, crediting you unless you prefer otherwise.

Please give us reasonable time to release a fix before disclosing the vulnerability publicly.

## Supported versions

Security fixes are released for the latest minor version of the current major release. Upgrading
to the latest version is the best way to stay protected.

## Verifying a release

Every release of the core includes a software bill of materials (CycloneDX) and the checksums of its
files, signed with [Sigstore](https://www.sigstore.dev/). The release notes explain how to verify
them with `cosign`.

## Plugins

This policy covers the repositories of the Mosaikit organization. Vulnerabilities in third-party
plugins should be reported to their authors.
