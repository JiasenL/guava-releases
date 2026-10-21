# Guava

A desktop video downloader for **Windows** and **Apple Silicon Macs**, with an integrated media browser.

Paste a video link, choose a quality, and download it—or browse a website inside Guava and select detected media. Guava also supports audio-only MP3 downloads, a download queue, pause/resume, and download history.

## Download

Get the installer from the **[latest release](https://github.com/JiasenL/guava-releases/releases/latest)**.

| Platform | Download | Requirements |
| --- | --- | --- |
| Windows | `Guava-Setup-<version>-x64.exe` | Windows x64 |
| macOS | `Guava-<version>-mac-arm64.dmg` | macOS 13 or later; Apple Silicon (M1 or later) |

Intel Macs are not supported. Download the `.exe` or `.dmg` installer; the other release assets are used by the updater.

## Installation

### Windows

Run the Setup executable and follow the installer. Windows installers are currently unsigned, so Windows may display an unknown-publisher or SmartScreen warning.

### Mac

Open the DMG, drag **Guava** into **Applications**, then open it from Applications.

The Mac app is signed with an Apple Development certificate and is **not notarized by Apple**. If macOS blocks it because the developer cannot be verified, and you trust this download:

1. Try opening Guava.
2. Open **System Settings → Privacy & Security**.
3. Find the message about Guava, choose **Open Anyway**, and confirm **Open**.

Managed Macs may restrict this option. Do not override warnings about malware, revoked certificates, or damaged software. See [Apple’s instructions](https://support.apple.com/en-ie/102445).

## Updates

**Windows:** updater-enabled versions check for newer releases and download updates in the background. Use **Check for updates**, then **Restart and update** when ready. Active downloads and source checks must finish or be paused before installation.

**Mac v0.1.0:** updates are manual. Download a newer DMG and replace Guava in Applications. Mac automatic updates are being introduced in the next release; v0.1.0 users will need to install that first updater-enabled DMG once. Afterward, newer updater-enabled versions can use **Check for updates** and **Restart and update** inside the app. Check the release notes for availability.

## About this repository

This repository contains public installers, update files, and release notes. Application development is maintained separately in a private source repository.
