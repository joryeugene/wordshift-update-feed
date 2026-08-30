# WordShift update feed

This repository publishes the signed manifests and cross-platform binaries used by WordShift's
live v1.0 to v1.1 update demonstration. GitHub Releases delivers the files; each client verifies
the manifest with its pinned Ed25519 public key and checks the binary's size and SHA-256 before
installation.

The updater source, one-command walkthrough, and architecture live in
[cross-platform-self-updater](https://github.com/joryeugene/cross-platform-self-updater). Demo
artifacts are available in the [v1.0.0](https://github.com/joryeugene/wordshift-update-feed/releases/tag/v1.0.0)
and [v1.1.0](https://github.com/joryeugene/wordshift-update-feed/releases/tag/v1.1.0) releases.

## Development

Optionally enable the repository's staged secret scan:

```text
mise install
git config core.hooksPath .githooks
```
