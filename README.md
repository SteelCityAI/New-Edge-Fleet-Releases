# New Edge Fleet releases

Official signed desktop installers and update packages from Steel City AI.

[Latest release and downloads](https://github.com/SteelCityAI/New-Edge-Fleet-Releases/releases/latest)

This repository hosts distribution files and release notes. The application source is maintained separately in a private repository. Downloads do not require a GitHub account; using Fleet requires an authorised Fleet login.

## Platforms

- Windows x86_64: NSIS installer (`.exe`).
- macOS Apple Silicon: `.dmg` installer and signed updater archive.
- macOS Intel: `.dmg` installer and signed updater archive.

The desktop app reads `latest.json` from the latest published release and verifies updater signatures against its embedded public key before installing. `downloads.json` lists the version-specific manual installers. `SHA256SUMS.txt` lists file checksums.

Published release files are immutable. A correction is issued as a new version. Drafts are used for acceptance testing before a release becomes available to installed clients.