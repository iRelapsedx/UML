# Universal Mod Loader (UML)

**A safe, all-in-one mod manager and modding toolkit for PC games.**

UML finds the games installed on your PC, identifies what each one is built with, and shows how it can be modded, with the evidence behind every result. It installs mods with verified backups and a complete undo, explains crashes from the games' own logs, and provides the tools to create and package your own mods.

![UML home screen](screenshots/01-home.png)

## Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Updates](#updates)
- [Safety and privacy](#safety-and-privacy)
- [Reporting problems](#reporting-problems)
- [System requirements](#system-requirements)

## Features

| Area | What UML does |
|---|---|
| **Game discovery** | Reads the local install records of Steam, Epic Games Store, GOG, Ubisoft Connect, EA app, Battle.net, Rockstar Games Launcher, the Xbox app, Amazon Games and itch.io, as well as folders you add yourself. |
| **Engine detection** | Identifies the engine, scripting backend, mod frameworks and anti-cheat of every game, including Unity, Unreal Engine, Godot, GameMaker, Source and many more. Each result lists the files it is based on and a confidence level. |
| **Mod management** | Installs mods from archives, folders or single files and suggests where their files belong. Supports profiles, load order and conflict detection. Original game files are backed up and verified before they are replaced, and every change can be undone. |
| **Finding mods** | Offers official mod-loader releases, checked against their published checksums, together with Thunderstore, mod.io and GitHub releases. Online features are off by default: turn on **Settings → Online → Allow UML to contact mod sites** to let Discover Mods search these sites. |
| **Troubleshooting** | Reads game logs and Windows crash records and explains each problem: what happened, why, and how to fix and prevent it. Confirmed causes are kept apart from possible ones, and reports can be shared with personal details removed. |
| **Guides and tutorials** | Modding guides describe each publisher's rules with dated sources. Step-by-step tutorials check every step automatically, and engine guides explain how each engine is modded. |
| **Mod creation** | Mod Studio creates projects from templates, builds them, validates the result and packages it for distribution. |
| **File inspection** | A read-only inspector for game files and archives, with previews of textures, sounds, text and 3D models. |
| **Browser games** | Keeps your browser games alongside the rest of your library, opens each one in the browser you choose, and shows the engine and extension options of every installed browser. |
| **Emulators** | Finds the emulators on your PC and installs emulator mods (Switch and 3DS game mods, texture packs, graphic packs and game patches) into each emulator's own folders, never replacing existing files. A ROM patcher applies IPS, BPS and UPS patches to a copy of your ROM. The emulator list covers 54 actively developed emulators with the games known for mods on each. UML never downloads games, BIOS files, firmware or keys. |
| **Plugins** | Extends UML with additional detection rules, guides, install rules and more. Plugins contain data only and require your approval for each kind of change. |
| **AI assistant** | Optional help with modding questions and crash reports, using your own Anthropic API key or a local model. You see exactly what is sent before anything leaves your PC. |
| **Interface** | Dark and light themes, accent colours, Windows notifications and optional interface sounds. |

## Screenshots

> The screenshots show a demonstration library of fictional games.

| | |
|---|---|
| ![Game library](screenshots/02-game-library.png) **Game library** | ![Game details](screenshots/03-game-page.png) **Game details** |
| ![Detection evidence](screenshots/04-detection-evidence.png) **Detection evidence** | ![Mod Manager](screenshots/05-mod-manager.png) **Mod Manager** |
| ![Discover Mods](screenshots/06-discover-mods.png) **Discover Mods** | ![Troubleshooter](screenshots/07-troubleshooter.png) **Troubleshooter** |
| ![Tutorials](screenshots/09-tutorials.png) **Tutorials** | ![Engine guides](screenshots/10-engine-guides.png) **Engine guides** |
| ![Mod Studio](screenshots/11-mod-studio.png) **Mod Studio** | ![File Inspector](screenshots/12-file-inspector.png) **File Inspector** |
| ![Browser games](screenshots/17-browser-games.png) **Browser games** | ![Emulators](screenshots/18-emulators.png) **Emulators** |
| ![Emulator list](screenshots/19-emulator-list.png) **Emulator list** | ![Plugin Center](screenshots/13-plugin-center.png) **Plugin Center** |
| ![AI assistant](screenshots/08-ai-assistant.png) **AI assistant** | ![Getting started](screenshots/14-getting-started.png) **Getting started** |
| ![Settings](screenshots/15-settings.png) **Settings** | ![Light theme](screenshots/16-home-light-theme.png) **Light theme** |

## Installation

1. Download `UML_<version>_x64-setup.exe` from the [latest release](https://github.com/iRelapsedx/UML/releases/latest).
2. Run the installer. UML is installed for your Windows account only and does not require administrator rights.

The installer is not code-signed yet, so Windows SmartScreen may report an unknown publisher. If you downloaded the installer from this repository's releases, choose **More info → Run anyway** to continue.

## Updates

UML checks this repository for new releases shortly after it starts and every six hours. When an update is available, you can review its notes and choose when to install it. Updates are installed only if they carry UML's signature, and your library, mods and settings are always kept. Automatic checks can be turned off in **Settings → Updates**.

## Safety and privacy

- UML does not bypass anti-cheat or DRM and contains no online cheating features. Applying mods to a game protected by anti-cheat requires your explicit confirmation, and games whose terms forbid mods are offered no mod loaders.
- Original game files are backed up and verified before a mod replaces them, and every change can be reversed.
- Downloads are verified against the checksums published by their sources before installation.
- UML sends no telemetry. Online features are off by default, and update checks transmit no personal information.

## Reporting problems

Choose **Report** at the bottom of UML's sidebar (or **Settings → Data & about → Report a problem**) to open a [bug report](https://github.com/iRelapsedx/UML/issues/new?template=bug_report.yml) with your UML and Windows versions already filled in, and optionally UML's recent error messages with personal details removed. Nothing is sent until you submit the form on GitHub. Reports are public, so please don't include passwords or other personal information.

## System requirements

- Windows 10 or Windows 11, 64-bit
- Microsoft Edge WebView2 Runtime (installed automatically if it is missing)
