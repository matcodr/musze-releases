# Musze — downloads

Musze is a music-library manager for DJs and collectors, on **macOS and Windows**: your library the
way you keep it, a player with a deck, BPM / key / loudness / energy worked out on your own machine,
genres and a picture of your taste, names and artwork from free catalogue sources, playlists and
playlist folders, and exports for Rekordbox, Traktor, Engine DJ and djay Pro — including a **USB
stick that plays straight in CDJs and Engine OS players**.

This repository holds the installers and the release notes. Nothing else.

**The current release is 1.0.22.** ([What changed](https://github.com/matcodr/musze-releases/releases/latest))

## Two downloads

**Musze Free** is the whole app with **no limits on anything**: a library of any size, the player
and the deck, analysis, the Camelot wheel, genres, Your taste, More like this, For you, Render
check, the Inbox and **a sidebar section for your watched folder**, Discover, **finding music by record label**, playlists **and
smart playlists**, Tidy, writing tags and artwork back into your files, clean copies and drag-out of
any size, and **every export including the USB stick**. No account, no sign-up, nothing sent about you.

**Musze Pro** adds five things: **Sound Check** (the spectrogram, the verdicts and the on-demand
scan), **Duplicates**, **musical key names** beside the Camelot code (`8A · Am` rather than `8A`),
the **FX strip**, and **Discogs / SoundCloud / YouTube** lookups with account connections. One
purchase, no subscription. Details and price at [musze.app](https://musze.app).

Both are the same app in the same place, so buying Pro is a drag-over upgrade: your library,
playlists, tags and settings are all kept. A licence key bought earlier still works — paste it into
the **free** build, Settings → Sources → Licence.

## Download

Go to **[Releases](https://github.com/matcodr/musze-releases/releases/latest)** and pick your file.
The version is not in the file name, so these links never change.

**macOS**

- `Musze-Free-Silicon.dmg` / `Musze-Pro-Silicon.dmg` — Apple Silicon (M1, M2, M3, M4)
- `Musze-Free-Intel.dmg` / `Musze-Pro-Intel.dmg` — Intel Macs

Not sure which? Apple menu → About This Mac: *"Chip: Apple …"* means Silicon, *"Processor: Intel …"*
means Intel.

**Windows**

- `Musze-Free-Windows.exe` / `Musze-Pro-Windows.exe` — 64-bit Windows 10 and 11

Two older names, `Musze-arm64.dmg` and `Musze-x64.dmg`, are still attached to every release as
copies of the free Mac builds, because that is what the download buttons on musze.app point at
today.

## Install

**macOS**

1. Open the DMG and drag **Musze** into **Applications**.
2. First launch only: **right-click the app → Open → Open**. Musze is not yet signed with an Apple
   Developer ID, so a plain double-click is refused by macOS the first time.
3. There is nothing else to install. Everything Musze needs to read, convert, analyse and identify
   audio ships inside the app.

**Windows**

1. Run the `.exe` and choose where to install it. It installs for **you only** — no administrator
   password.
2. First launch only: Windows may show *"Windows protected your PC"*. Click **More info → Run
   anyway**. Musze is not yet signed with a Windows certificate.
3. Uninstalling from Settings → Apps leaves your library and settings alone.

In Spanish, step by step, with what to do when something goes wrong: **[INSTALACION.md](INSTALACION.md)**.

## Updates

Musze checks this page for new versions when it starts (no account, nothing sent about you) and
shows a small notice when one is available. Since 1.0.12 the notice has an **Update** button: press
it, Musze downloads the right file for your system and edition, checks it, and offers **Restart
now** — the app closes, replaces itself and opens again with your library untouched. Nothing is
downloaded or restarted until you press those buttons, and **Later** keeps the file for when you
are done playing.

If you are on 1.0.11 or earlier, install the new version by hand one last time; that copy does not
know how to update itself yet.

## Your library is safe

Musze reads your music where it is. It never moves, renames or deletes audio files — removing a
track from the library is bookkeeping, and anything Musze does put out of the way goes to the
Trash, never a delete. Writing BPM, key or artwork into a file only happens when you turn that on
in Settings.

## Problems

Open an issue here with what you did, what you expected and what happened, or write to
hello@musze.app. Settings → General → Diagnostics → **Copy diagnostic report** gives a report with
no file paths or personal data — paste it into the issue.
