# SecretVideo

**A dedicated player for watching videos from many sites — and saving them when you need to.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/secretvideo?lang=en)

![SecretVideo screenshot](images/secretvideo-en.webp)

## Overview

SecretVideo is a browser-style player built for video sites. Pick a site from the home screen and it opens right away; when you switch a video to full screen, it turns into a small **PIP window** so you can keep watching while you do something else.

When the video you are watching can be saved, a **Download button** appears next to the address bar. One click saves it in the format and quality you chose — original, MP4 or MP3. Sites that need a login work too: sign in once inside SecretVideo and your session is kept.

Ad blocking is on by default, `Ctrl+P` saves the whole page you are looking at as an image, and `Ctrl+R` records what you are watching, with sound, as a video.

## Features

- **Site home screen** — YouTube, Twitch, TikTok, CHZZK, Netflix, TVING, Wavve, Watcha, Coupang Play and more in one place. Add or edit the list as you like.
- **Full screen → PIP automatically** — switching a video to full screen turns it into a small always-on-top window. Drag it anywhere, resize it from the edges.
- **Download button that appears only when it can work** — it slides in once a savable video is ready. It does not appear for ads or live streams.
- **Format and quality of your choice** — Original / MP4 / MP3, 720p / 1080p / Best quality.
- **Download list window** — thumbnails and progress at a glance, with a Windows notification when a download finishes.
- **Wide site support** — a widely used download engine (yt-dlp) is built in; for sites it does not know, SecretVideo finds the playing file itself and saves it.
- **Stay signed in** — log in to a site inside SecretVideo and member-only videos can be watched and saved as well.
- **Ad blocking** — uBlock Origin Lite is built in and can be turned on or off from the menu. It updates itself to the latest release.
- **Full-page capture** — `Ctrl+P` saves the entire page, including everything below the fold, as a PNG.
- **Screen recording** — the Record button or `Ctrl+R` records what you are watching as an MP4. Only SecretVideo's own sound is recorded.
- **Settings window** — save options, quality, PIP, hardware acceleration, extensions and shortcuts in one window. Shortcuts can be changed to any key you like.
- **Remembers your windows** — main window position/size/maximized state, PIP window position and size, download list position.

## Download / Installation

| Package | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/secretvideo?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/secretvideo?lang=en&nosetup) |

SecretVideo can be used as a portable app: unzip anywhere and run `SecretVideo.exe`.

**On first launch** it downloads the components needed for saving videos (download engine, converter, ad blocker). Wait for the progress window to finish. This happens once; afterwards it only downloads again when a component has changed.

## Usage

### Getting started

1. Start SecretVideo. The **site home screen** appears. Click the site you want.
2. Browse the site and play a video as you would in any browser.
3. If the video can be saved, a **Download button** (↓) appears on the right of the address bar. Click it and saving starts right away.
4. The **Download list** window opens automatically and shows progress. When it finishes, a Windows notification appears; click it to open the save folder.

The default save folder is your PC's **Downloads** folder. Change it in the menu (⋮) → **Folder Settings**, or open it with **Open Folder**.

### The window

| Control | What it does |
|---|---|
| ◀ ▶ | Back / Forward |
| ⟳ / ✕ | Reload (Stop while a page is loading) |
| Address bar | Type an address to go there, or type words to search |
| ● / ■ | Record / Stop recording |
| ↓ | Download button — appears only when a savable video is ready |
| ⋮ | Menu |

The window title follows the page title. If a site tries to open a new window, SecretVideo opens it in the current window instead.

### How to…

**Save a YouTube video as MP3**
Menu → **Format Settings → MP3**, then click the Download button on the video page. Only the audio is downloaded and converted to MP3. The quality setting has no effect on MP3.

**Get a file that plays on a TV or other devices**
Choose **Format Settings → MP4**. For the same resolution SecretVideo prefers the widely compatible H.264 format, so the file is less likely to refuse to play in a basic player or on a TV. **Original** saves what the site provides as is (merged into MP4 when needed).

**Save space, or get the best quality**
Under **Download Quality** choose **720p**, **1080p** (default) or **Best quality**. 720p and 1080p mean "up to that resolution": if it is not available, the next one down is used.

**Downloads keep failing or stalling**
Try **Download Speed → Stable**. It downloads one part at a time, which copes well with an unreliable connection. If your connection is fast, **Fast** (several parts at once) is much quicker. The default is **Normal**.

**Member-only videos that need a login**
Sign in to the site inside SecretVideo as you normally would. The login is kept, so from then on member videos play directly, and the Download button appears whenever a video can be saved.

**Download a whole playlist**
On a YouTube playlist page, click the Download button to download the whole list one after another. Auto-generated **Mix / Radio** lists are the exception: only the video you are watching is downloaded.

**Sites where you scroll from video to video (TikTok and similar)**
SecretVideo notices which video is playing even when the page address does not change, so just scroll to the one you like and click the Download button.

**Streaming sites such as CHZZK and Twitch**
VODs and clips can be saved. **Live streams cannot be saved**, and the Download button does not appear for them.

**Old Naver TV links and Naver clips**
Naver TV videos have moved to Naver clips, but if you open an old Naver TV address or a link copied from Naver search, you can still save the video right from the clip viewer. When you scroll to the next video, the one you are currently watching is the one that gets saved.

**Keep watching while you work (PIP)**
Switch a video to **full screen** and SecretVideo automatically turns into a small always-on-top PIP window.
- **Drag** the window to move it.
- Grab an **edge** to resize it.
- **Right-click** menu: Back to normal window / Always on top on or off / Exit.
- When the site leaves full screen, the window returns to its previous size and position.
- The PIP window's position and size are remembered for next time.
- If you do not want this, turn off Menu → **Enable PIP when entering fullscreen**. Full screen then uses the whole monitor like a normal browser.

**Keep a whole page as an image**
Press `Ctrl+P`. The **entire page** — not just the visible part, but everything below the fold — is saved to the save folder as `SecretVideo-001.png` and a notification appears. Handy for keeping posts, comments or subtitle screens.

**Keeping what you are watching as a video**
Click the **Record** button (●) to the right of the address bar, or press `Ctrl+R`. Recording starts and the button turns into ■. Click it again to stop; the video is saved to the save folder with a name such as `SecretVideo-001.mp4` and a notification appears.
- Only **sound coming from SecretVideo** is recorded. Music from other programs and Windows notification sounds are left out.
- If you move the window while recording, the recording follows it. The recording size is the window size when you start, so set the size you want first.
- If you close the program while recording, the video recorded so far is finished and saved.

**Ads get in the way / a site misbehaves because of ad blocking**
Ad blocking (uBlock Origin Lite) is on by default. If a particular site does not work properly, turn it off for a while under Menu → **Extensions** (or **Settings → Extensions**). When a new release of the ad blocker comes out, it is replaced automatically the next time you start the program.

**Managing downloaded files (Download list window)**
Open it any time from Menu → **Download List**. Each row shows a thumbnail, title, source and status (Idle → Scan → Recv → Conv → Done), and the row background shows progress.
- **Double-click**: open the downloaded file
- **Delete key**: remove from the list
- **Right-click**: Go to Source / Open Folder / View Log / Delete
- Closing the window or pressing `ESC` only hides it; downloads continue.
- Clicking the Download button on a video that is already downloaded or downloading opens this window and shows its status.

**Downloading the same video twice**
If a file with the same name exists, it is not overwritten; a number such as `(1)`, `(2)` is added.

**Editing the site home screen**
Use **Edit** on the home screen to add or remove sites, and **Reset** to restore the default list. Keeping only the sites you actually use makes starting faster.

**Changing the shortcuts**
Under Menu → **Settings → Shortcuts**, change **Screen capture** (default `Ctrl+P`) and **Start/stop recording** (default `Ctrl+R`). Click a field and it shows "Press a key…"; press the key you want and it is set right away.
- `Backspace`: restore the default key for that action only
- `Esc` or clicking the same field again: stop without changing
- A key already used by another action is not taken; you see "Already used by '…'."

**Drawing the screen without the graphics card**
Set Menu → **Settings → General → Hardware acceleration** to **Off**, and the screen is drawn and videos are played by the CPU instead of the graphics card. The change takes effect after restarting the program.

### Copyright notice

SecretVideo is a tool for watching and keeping (saving and recording) videos you are entitled to use, for personal purposes. Please respect each site's terms of service and copyright.

## Configuration

Change everything in one window from Menu (⋮) → **Settings** (General, Extensions, Shortcuts). Frequently used items can also be changed directly from the menu. Changes apply immediately and are saved automatically.

| Item | What it sets | Default |
|---|---|---|
| Folder Settings / Open Folder | Where files are saved | Downloads folder |
| Format Settings | Original / MP4 / MP3 | Original |
| Download Speed | Stable / Normal / Fast | Normal |
| Download Quality | 720p / 1080p / Best quality | 1080p |
| Download List | Show or hide the list window | Opens automatically when a download starts |
| Enable PIP when entering fullscreen | Turn full screen into a PIP window | On |
| Extensions | Ad blocking on or off | On |
| Hardware acceleration | On / Off (applies after restart) | On |
| Shortcut — Screen capture | Save the whole page as an image | `Ctrl+P` |
| Shortcut — Start/stop recording | Screen recording | `Ctrl+R` |

The UI language follows the Windows display language (Korean → Korean, everything else → English).

## Requirements

- Windows 10 or Windows 11, **64-bit**
- Microsoft Edge WebView2 Runtime (already present on Windows 11 and recent Windows 10; the installer adds it if missing)
- An internet connection (first-launch component download, watching and saving videos)
- Windows 10 version 2004 or later to record sound along with the video

## Updates

SecretVideo does **not** update itself. New versions are released manually after internal verification and announced on the [SecretVideo page](https://kilho.net/secretvideo). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

The built-in ad blocker (uBlock Origin Lite) is the one exception: when a new release comes out, it is replaced with the latest release automatically the next time you start the program.

## License

SecretVideo is **Freeware**.

You may use it anywhere — at home, at the office, in schools and government offices — and redistribute it freely in its unmodified form.

## Links

- Website: <https://kilho.net/secretvideo>
- Forum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
