# Muzzeek — downloads

Muzzeek is a music-library manager for DJs and collectors on macOS: local library, BPM / key / loudness analysis, Sound Check, metadata and artwork from free catalogue sources, and export to Rekordbox, Traktor, Engine DJ and djay Pro.

This repository holds the installers and release notes only. Muzzeek's core is free.

## Download

Go to **[Releases](https://github.com/matcodr/muzzeek-releases/releases/latest)** and pick the file for your Mac:

- `Muzzeek-<version>-arm64.dmg` — Apple Silicon (M1, M2, M3, M4)
- `Muzzeek-<version>-x64.dmg` — Intel Macs

Not sure which? Apple menu → About This Mac: "Chip: Apple …" means arm64; "Processor: Intel …" means x64.

## Install

1. Open the DMG and drag **Muzzeek** into **Applications**.
2. First launch only: **right-click the app → Open → Open**. Muzzeek is not yet signed with an Apple Developer ID, so a plain double-click is refused by macOS the first time.
3. Muzzeek needs **ffmpeg** for analysis and for playing some formats. If it isn't installed, the app shows a guide with the two files to download and where to put them.

## Updates

Muzzeek checks this page for new versions when it starts (no account, nothing sent about you) and shows a small notice with a Download button when one is available. Until the app is code-signed, you install updates the same way as the first time.

## Your library is safe

Muzzeek reads your music where it is. It never moves, renames or deletes audio files. Writing BPM, key or artwork into a file only happens when you turn that on in Settings.

## Problems

Open an issue here with what you did, what you expected and what happened. Settings → General → Diagnostics → **Copy diagnostic report** gives a report with no file paths or personal data — paste it into the issue.
