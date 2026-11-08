# LDM

LDM (formerly LiteDM) is a download manager for Windows that splits each download into up to 32 connections. A
browser extension for Chrome, Edge, Opera, Brave and Firefox sends your browser's downloads to it.

- Pause and resume, also after a restart
- Saves video and audio from web pages in the quality you choose
- Sorts downloads into folders (Music, Videos, Documents…)
- Download lists with schedules and speed limits
- Downloads over LAN, Wi-Fi or USB tethering from your phone, or over several of them at once
- Checks every finished file for damaged parts and fetches only those parts again, automatically or when you click
  Repair
- History & cleanup: remove finished or failed downloads from the list, let them leave it after a few days, clear the
  cache
- Light, Dark and Nova themes (Nova with Lito the fox); English, Deutsch, Français, Español, Türkçe, العربية, فارسی
- Updates itself

## Install

1. Download **LiteDM-Setup-x.y.z.exe** from [Releases](../../releases/latest). The installer file keeps its old
   name so that copies already installed can still update.
2. Run it. You don't need administrator rights. Windows may show "Windows protected your PC" because the
   installer has no paid publisher certificate: click **More info**, then **Run anyway**.
3. Start LDM. The welcome window shows how to add the browser extension.

LDM checks this page for new versions and installs them in the background; your downloads and settings stay.

## Safety

- Every update is signed with the publisher's private key. LDM refuses an installer that has been changed or that
  someone else signed, even if it was uploaded here.
- LDM collects no usage data. Your downloads, settings and history stay on your PC. Website logins that a download
  needs are encrypted with Windows' own protection and deleted when the download finishes.

## Please download responsibly

Only download what you are allowed to: your own files, free or openly licensed content, or content whose owner
permits it. Respect copyright and the terms of the websites you use.

## Requirements

Windows 10 or 11 (64-bit). Everything else is included: .NET, and the free open-source tools yt-dlp, FFmpeg and
deno (their licenses are installed with LDM).
