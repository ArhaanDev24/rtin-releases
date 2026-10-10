# RTIN downloads

RTIN is Tab for your whole computer: a small capsule on your desktop that learns your routine, suggests the next step, and does it when you press Tab.

This repository only hosts the installers. Get RTIN from **https://rtin.vercel.app**.

## macOS 13 or later (Apple Silicon and Intel)

Paste this in Terminal:

```bash
curl -fsSL https://rtin.vercel.app/install.sh | bash
```

It downloads the latest release, checks its SHA-256 and RTIN's signing certificate, and installs RTIN to Applications.

Or download `RTIN-mac-universal.dmg` from the [latest release](https://github.com/ArhaanDev24/rtin-releases/releases/latest). RTIN isn't notarized by Apple yet, so on first launch go to **System Settings → Privacy & Security** and click **Open Anyway**.

## Windows 10 and 11

Download `RTIN-Setup-win-x64.exe` from the [latest release](https://github.com/ArhaanDev24/rtin-releases/releases/latest). If SmartScreen appears, click **More info**, then **Run anyway**.

## Checking a download

Each file has a `.sha256` next to it. RTIN for macOS is signed with RTIN's own certificate, SHA-256 `2c431a211d6d0c2f5a2917ca3f1526ce9b5bad74b03d00f565609c1d9563111d`.

[Privacy policy](https://rtin.vercel.app/privacy) · [Terms](https://rtin.vercel.app/terms)
