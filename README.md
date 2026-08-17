# DDD STUDIO Beta Releases

Public, signed Beta distributions for DDD STUDIO.

## Repository boundary

- This repository contains release metadata only. The application source repository remains private.
- Application binaries are attached to GitHub prereleases. They are never committed to Git.
- A release may contain only the notarized DMG, updater ZIP, their blockmaps, and `beta-mac.yml`.
- Credentials, signing material, source maps, debug metadata, logs, databases, crash data, and user data are prohibited.
- `builder-debug.yml` and other build-system diagnostics are never release assets.

## Release policy

- Beta tags use `v<major>.<minor>.<patch>-beta.<sequence>`.
- Releases are assembled as drafts and published only after signature, notarization, staple, checksum, manifest, and package-content verification passes.
- Published assets are immutable. A correction requires a new Beta version.
- Keep the current Beta and the previous two Beta releases. Remove older releases only after rollback support is no longer required.
- Stable DDD STUDIO releases use a separate public distribution repository.

## Installation warning

Beta builds are prerelease software intended for developer evaluation. Back up important work before installation and report the exact Beta version when filing an issue.
