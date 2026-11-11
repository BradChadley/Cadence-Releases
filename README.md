# Cadence

A Windows music player for your own collection, with MusicBee library import, Last.fm scrobbling, and Discord presence.

**[Download the latest Windows installer](https://github.com/BradChadley/Cadence-Releases/releases/latest/download/Cadence-win-Setup.exe)** · [Release notes](https://github.com/BradChadley/Cadence-Releases/releases)

## Install

Windows x64; .NET is included. Run the installer for your Windows account. This preview is unsigned, so Windows may show a reputation warning.

On first launch, bring an existing Cadence library over or choose **Find my MusicBee library**. Import preserves original added dates, listening history, and supported recent views. MusicBee and music files stay unchanged.

## Automatic updates

Cadence opens directly into your library. It checks this repository quietly after the library is ready and downloads verified updates in the background, without a startup popup or interrupting playback. Ready updates install automatically on the next launch. You can also use **Restart now** in Settings → Updates. Automatic checking can be turned off there.

Future versions still need to be built and published here. Cadence then installs them automatically; it does not build source code itself.

## Your library

Library data and settings are stored separately at `%LocalAppData%\CadencePlayer\Data`. Program updates and uninstalling leave that folder intact. Music files remain in their original locations. Last.fm and Discord are optional connections.

This repository contains the installer and update assets. Personal libraries, music, credentials, and development source archives are not included.
