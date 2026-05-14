# Life Intelligence — Releases

This repository is the public distribution channel for the Life Intelligence hub. The hub is a self-hosted personal-data system that captures physiological signals from a Galaxy Watch + Android phone, transcribes voice notes, and exposes the data via a local HTTP and MCP API.

The source code lives in a separate, private repository.

## Download

Grab the latest Windows installer:

**[life-intelligence-windows-x86_64-installer.exe](https://github.com/upload-j/li-releases/releases/latest/download/life-intelligence-windows-x86_64-installer.exe)** (~128 MB)

Or browse all releases on the [Releases](https://github.com/upload-j/li-releases/releases) page.

## Install (Windows)

1. Download the installer above.
2. Run it. Windows will show a UAC prompt — accept.
3. The installer copies the hub to `C:\Program Files\Life Intelligence\`, opens inbound TCP port `17777` in the firewall, and optionally adds a Startup-on-login shortcut.
4. The hub launches automatically when finished. A small data folder opens at `C:\Users\<you>\.life-intelligence\` — this is where your captured data lives, on your machine.

## Set up phone + watch

The phone and watch apps are in Google Play closed testing. Visit the landing page to be added to the tester list, then install the app from Play Store. Once installed, the phone app's setup flow walks you through pairing with the hub.

## Privacy

All captured data — heart rate, voice notes, GPS, motion — stays on your machine. The hub never phones home or syncs to a cloud.
