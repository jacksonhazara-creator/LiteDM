# LiteDM

A fast download manager for Windows, with a browser extension for Chrome, Edge, Opera, Brave and Firefox.

- Splits each download into up to 32 connections, with pause and resume
- Saves videos from YouTube, Instagram, Facebook, X, TikTok, Vimeo and more, in the quality you choose
- Catches downloads from your browser and sorts them into folders (Music, Videos, Documents…)
- Download lists with schedules, speed limits, and LAN and Wi-Fi together
- Light, Dark and Nova themes; English, Deutsch, Français, Español, Türkçe, العربية, فارسی
- Updates itself

## Install

1. Download **LiteDM-Setup-x.y.z.exe** from [Releases](../../releases/latest).
2. Run it. You don't need administrator rights. Windows may show "Windows protected your PC" because the
   installer has no paid publisher certificate: click **More info**, then **Run anyway**.
3. Start LiteDM. The welcome window shows how to add the browser extension in a few clicks.

To update, you don't need to do anything: LiteDM checks this page, installs new versions in the background and
keeps your downloads.

## Safety

- Every update is signed with the publisher's private key. LiteDM refuses any installer that has been changed
  or that someone else signed, even if it was uploaded here.
- LiteDM sends nothing to anyone. Your downloads, settings and history stay on your PC, and website logins that a
  download needs are encrypted with Windows' own protection and deleted when the download finishes.

## Requirements

Windows 10 or 11 (64-bit). Everything else is included: .NET, and the free yt-dlp, FFmpeg and deno tools for
video sites.
