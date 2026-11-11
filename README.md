# Cadence

A Windows music player for your own collection, with MusicBee library import, Last.fm scrobbling, and Discord presence.

**[Download the latest Windows installer](https://github.com/BradChadley/Cadence-Releases/releases/latest/download/Cadence-win-Setup.exe)** · [Release notes](https://github.com/BradChadley/Cadence-Releases/releases)

## Install

Windows x64; .NET is included. Run the installer for your Windows account. This preview is unsigned, so Windows may show a reputation warning.

On first launch, bring an existing Cadence library over or choose **Find my MusicBee library**. Import preserves original added dates, listening history, and supported recent views. MusicBee and music files stay unchanged.

## Automatic updates

Cadence checks this repository when the installed app opens. New versions download, verify, and install before playback starts. Choose **Open current version** to start listening immediately; a failed or slow check also lets the player open normally. Updates downloaded while listening wait until the next launch or **Restart now** in Settings → Updates.

Future versions still need to be built and published here. Cadence then installs them automatically; it does not build source code itself.

## Your library

Library data and settings are stored separately at `%LocalAppData%\CadencePlayer\Data`. Program updates and uninstalling leave that folder intact. Music files remain in their original locations. Last.fm and Discord are optional connections.

This repository contains the installer and update assets. Personal libraries, music, credentials, and development source archives are not included.
