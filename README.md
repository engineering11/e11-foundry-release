# Foundry Desktop releases

Release builds of Foundry Desktop and its update channel. This repository holds no source code.

- Each release carries the macOS app, the Windows installer, the Linux AppImage, deb and rpm, their update signatures (`.sig`), and `latest.json`.
- Foundry checks `https://github.com/mikiyas11/e11-foundry-release/releases/latest/download/latest.json` for updates, and verifies each download against the public key built into the app.
