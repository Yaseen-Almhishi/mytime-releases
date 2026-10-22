# MyTime Downloads

Official Windows downloads and update releases for MyTime, a Discord Rich Presence companion.

## Download

Download **MyTime.exe** from [the latest release](https://github.com/Yaseen-Almhishi/mytime-releases/releases/latest) and double-click it. Requires Windows 10/11 x64 and the Discord desktop app. Node.js, Git, and a source checkout are not required.

On first launch, enter your Discord application ID. No Discord user token is needed. Your settings stay on your PC under `%LOCALAPPDATA%\MyTime`.

## Updates

MyTime 1.0.2 and newer check this repository on launch and every six hours. In the dashboard, open **Updates** and choose **Update and restart**. No GitHub login or token is required. Versions 1.0.0 and 1.0.1 need one manual download of 1.0.2 to gain the updater.

The app verifies release checksums before running an update and keeps the previous executable. The executable is unsigned; Windows SmartScreen may warn. Checksums detect corruption, not compromise of the release publisher.

## Lyrics

Enable **Show lyrics in music-only modes (LRCLIB)** in the dashboard for Spotify-only or Side A-only mode. Timed lyrics depend on availability and matching track metadata. The dashboard shows the lookup status. Lyrics requests send recording title, artist, and duration to LRCLIB.

This repository contains release downloads and this documentation only. The development repository and its history remain private. No personal configuration, credentials, or private image folders are published here.
