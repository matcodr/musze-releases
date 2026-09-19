# Musze — downloads

Musze is a music-library manager for DJs and collectors, on **macOS and Windows**: your library the
way you keep it, a player with a deck, BPM / key / loudness / energy worked out on your own machine,
genres and a picture of your taste, names and artwork from free catalogue sources, playlists and
playlist folders, and exports for Rekordbox, Traktor, Engine DJ and djay Pro — including a **USB
stick that plays straight in CDJs and Engine OS players**.

This repository holds the installers and the release notes. Nothing else.

**The current release is 1.0.35.** ([What changed](https://github.com/matcodr/musze-releases/releases/latest))

## One download, and a key

**Musze Free** is the app, and there is nothing else to download. A library of any size, the player
and the deck, **BPM**, energy and the sound profile, genres, Your taste, For you, the Render check,
the Inbox and **a sidebar section for your watched folder**, Discover and web search, **finding
music by record label**, playlists **and smart playlists**, writing tags and artwork back into your
files, clean copies and drag-out of any size, and **every export including the USB stick**. No
account, no sign-up, nothing sent about you.

Since **1.0.33** it also reads the **record label and catalogue number** out of FLAC, WAV and AIFF
files properly — most shops write those into a tag Musze was not looking at, so a crate bought record
by record used to look as though it had no labels at all. Nothing is re-analysed: the labels fill in
as your files are read.

**Musze Pro is a licence key**, not a second installer. Buy one, open **Settings → Sources →
Licence** in the copy you already have, paste it in, and it unlocks:

- **Key and the Camelot wheel** — the musical key of every track, the Key column, key rules in
  smart playlists, and the key written into your files and exports
- **Loudness** — integrated loudness, loudness range and true peak
- **More like this** — what mixes with a record, and what sounds like it
- **Keep this folder tidy** — names, tags and artwork written into a folder, with a preview and an undo
- **Sound Check** — the spectrogram, the verdicts and the on-demand scan
- **Duplicates**
- **Correct gain** — a quiet file rewritten at the level of your crate, in its own format, the original kept beside it
- **The FX strip**, the deck's **master filter**, **Match Gain** and the **Daylight** theme
- **Discogs** and **SoundCloud** lookups, with account connections

One purchase, no subscription. Details and price at [musze.app](https://musze.app). Nothing is
re-downloaded and nothing moves: the key unlocks the copy on your machine, and every key ever
bought still works.

## Download

Go to **[Releases](https://github.com/matcodr/musze-releases/releases/latest)** and pick your file.
The version is not in the file name, so these links never change.

**macOS**

- `Musze-Free-Silicon.dmg` — Apple Silicon (M1, M2, M3, M4)
- `Musze-Free-Intel.dmg` — Intel Macs

Not sure which? Apple menu → About This Mac: *"Chip: Apple …"* means Silicon, *"Processor: Intel …"*
means Intel.

**Windows**

- `Musze-Free-Windows.exe` — 64-bit Windows 10 and 11

Two older names, `Musze-arm64.dmg` and `Musze-x64.dmg`, are still attached to every release as
copies of the free Mac builds, because that is what the download buttons on musze.app point at
today.

**Already have a Pro installer?** Earlier releases carried `Musze-Pro-…` files. That copy keeps
working and tells you once, in the strip at the top of the window, that updates now come through
Musze Free: download the free one above, drag it over, and paste your key.

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
