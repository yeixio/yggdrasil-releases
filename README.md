# Yggdrasil releases

This repository publishes Yggdrasil builds and accepts bugs and feature requests. The application source stays private.

## Download

Installers are attached to [Releases](https://github.com/yeixio/yggdrasil-releases/releases). The project site lists the latest files at [yggdrasil.yeix.io/download](https://yggdrasil.yeix.io/download).

Do not commit zip or tar archives here. When a version tag is published, CI attaches the build files to a release.

## Bugs and feature requests

Open an [issue](https://github.com/yeixio/yggdrasil-releases/issues) for a bug or a feature request.

## Versioned documentation

The main app's release workflow publishes `docs/<version>.json` and updates
`docs/index.json` here after a successful app release. The website reads this
public index automatically and retains version-specific guides. Snapshots are
immutable and contain only the public user guide, the release tag, and source
commit provenance; the application source remains private.

Edit the current guide in the main app repository at `docs/user-guide/guide.json`
before tagging a release. Do not hand-edit published snapshots or the index.
The bootstrap alpha.23 snapshot preserves the existing public guide.
