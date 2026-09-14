# Musze — downloads

Musze is a music-library manager for DJs and collectors on macOS: local library, BPM / key / loudness analysis, Sound Check, metadata and artwork from free catalogue sources, and export to Rekordbox, Traktor, Engine DJ and djay Pro.

This repository holds the installers and release notes only.

**Musze 1.0.2 is out.** The free edition: a library of up to 100 tracks, the whole player, BPM / key / loudness analysis, Render check, the Inbox, Discover, playlists and M3U8 playlists, and artwork and name lookups on MusicBrainz, Apple Music, Deezer, Jamendo and the Internet Archive. Clean copies and drag-out go up to 20 tracks at a time.
**Musze Pro** adds a library with no track limit; Sound Check with the spectrogram; tag write-back; smart playlists; Duplicates; Tidy; playlists for Rekordbox, Traktor, Engine DJ and djay Pro; clean copies and drag-out with no track limit; Discogs and YouTube lookups; and account connections. One purchase, for your Macs, with no subscription. Details and price at [musze.app](https://musze.app).

## Download

Go to **[Releases](https://github.com/matcodr/musze-releases/releases/latest)** and pick the file for your Mac:

- `Musze-<version>-arm64.dmg` — Apple Silicon (M1, M2, M3, M4)
- `Musze-<version>-x64.dmg` — Intel Macs

The same two files are also attached as `Musze-arm64.dmg` and `Musze-x64.dmg`, which is what the
download buttons on musze.app point at: `…/releases/latest/download/Musze-arm64.dmg` always fetches
the newest release.

Not sure which? Apple menu → About This Mac: "Chip: Apple …" means arm64; "Processor: Intel …" means x64.

## Install

1. Open the DMG and drag **Musze** into **Applications**.
2. First launch only: **right-click the app → Open → Open**. Musze is not yet signed with an Apple Developer ID, so a plain double-click is refused by macOS the first time.
3. There is nothing else to install. Everything Musze needs to read, convert, analyse and identify audio ships inside the app.

## Updates

Musze checks this page for new versions when it starts (no account, nothing sent about you) and shows a small notice when one is available. Since 1.0.12 the notice has an **Update** button: press it, Musze downloads the right file for your system and edition, checks it, and offers **Restart now** — the app closes, replaces itself and opens again with your library untouched. Nothing is downloaded or restarted until you press those buttons. If you are on 1.0.11 or earlier, install the new version by hand one last time; that copy does not know how to update itself yet.

## Your library is safe

Musze reads your music where it is. It never moves, renames or deletes audio files. Writing BPM, key or artwork into a file only happens when you turn that on in Settings.

## Problems

Open an issue here with what you did, what you expected and what happened. Settings → General → Diagnostics → **Copy diagnostic report** gives a report with no file paths or personal data — paste it into the issue.
