# BottleRim
A total light survival SimonRim focused gameplay overhaul using Community Shaders.
![BottleRim](https://github.com/InTheBottle/BottleRim/blob/main/Resources/BottleRim.png)


**Links**: [Nexus Page](https://www.nexusmods.com/skyrimspecialedition/mods/154268) | [Changelog](https://github.com/InTheBottle/BottleRim/blob/main/changelog.md) | [Load Order](https://loadorderlibrary.com/lists/bottlerim-2) | [Discord](https://discord.gg/avzs76EgnA)

---

**Support**: Join the [BottleRim Discord](https://discord.gg/avzs76EgnA)

**Requirements**:
- Skyrim SE version 1.6.1170 (latest Steam update).
- Requires ALL Creation Club content.

---

## Contents
- [Introduction](#introduction)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Post-Installation](#post-installation)
- [Playing the Game](#playing-the-game)
- [Updating](#updating)
- [Modifying the list](#Modifying-the-list)
- [Uninstalling](#uninstalling)
- [Troubleshooting](#troubleshooting)
- [Credits](#credits)

---

## Introduction
**BottleRim** is a total gameplay overhaul modlist for Skyrim SE (1.6.1170), built around [Community Shaders](https://www.nexusmods.com/skyrimspecialedition/mods/86492). Based on [Althros Dev Tools](https://github.com/Styyx1/ADT).

This is a list is a SimonRim focused light survival experience.

View the full mod list [here](https://loadorderlibrary.com/lists/bottlerim-2).

Licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## System Requirements
- **OS**: Windows 10 or 11 (no LTSC or modified versions; Linux not supported).
- **Storage**: SSD required.
- **Download Size**: ~93 GB.
- **Install Size**: ~141 GB.

| Component | Recommended (1080p) | My Specs (1440p) |
|-----------|---------------------|------------------|
| CPU       | i5 13600k or similar | i5 13600K       |
| GPU       | RTX 3060 or similar | RTX 4070        |
| RAM       | 16GB or more        | 32GB            |
| Storage   | SATA SSD            | NVMe SSD        |

---

## Installation

### Pre-Installation
1. **Install Dependencies**:
   - [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe).
   - [.NET Runtime 8.x.x Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.15-windows-x64-installer).
   - [.NET Runtime 6.0.0 Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.30-windows-x64-installer).
   - If Visual C++ is installed, use the `Repair` option.

2. **Steam Setup**:
   - Disable [auto-updates for Skyrim SE](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
   - Run Skyrim SE once for graphics check.
   - Install [Creation Kit](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/) on the same drive as Skyrim SE.
   - Run Creation Kit once, select `Yes` to unpack scripts.
   - Run Skyrim through steam, install ALL creation club addons. Do not ALT tab during this process.
   - If you have issues with the creation club plugins missing, you'll have to delete the skyrim folder thats in the steam folder and do a clean        install of skyrim, after its installed you can launch the game through steam and download all the creation club plugins that way.

### Wabbajack Installation
1. **Install Wabbajack**:
   - Create a folder (e.g., `C:\Wabbajack`) on your drive’s root (not in Program Files, Desktop, etc.).
   - Download [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) and place it in the folder.
   - Run `Wabbajack.exe` (requires version 4.0.0.0 or later).

2. **Install BottleRim**:
   - Open Wabbajack, select Skyrim SE, find BottleRim, and click “Download and Install.”
   - Set Installation Location (e.g., `C:\BottleRim`) and Downloads Location (avoid Program Files, Desktop, etc.).
   - Click Install.
   - Nexus Premium automates downloads; without it, manually click “Slow Download” for each mod.
   - If successful, proceed to [Post-Installation](#post-installation). If not, check [Troubleshooting](#troubleshooting).

---

## Post-Installation

There are a few things you can and should do. 

1. Run Bethini through the MO2 dropdown and select a preset + recommended tweaks. (Do not turn of TAA, required if you use CS' DLAA or AMDs.)

2. This list comes with a preconfigured Community Shaders setup, but feel free to press the "End" key and play around with things.

3. Check the "Optionals" separator in Mo2 to activate Framegen or camera headbob if you'd like.

4. Open the MCM, select Bathing in Skyrim and choose to either enable or leave it disabled.
   
### Antivirus Exceptions
- Add exceptions in Windows Defender for the BottleRim folder and `ModOrganizer.exe` to avoid crashes.
- Steps: Windows Security > Virus & Threat Protection > Manage Settings > Exclusions > Add Folder > Select BottleRim folder.

### Keyboard Keybinds
- **Community Shaders**: `End` key.
- Other controls use vanilla Skyrim keybinds.

---

## Playing the Game
- Launch Skyrim SE through Mod Organizer 2 (MO2) in the BottleRim folder.
- Enjoy the enhanced visuals!

---

## Updating
1. Open Wabbajack, find BottleRim, and click “Download and Install.”
2. Use the same Installation and Downloads folders.
3. Backup custom mods or settings (prefix added mods with **[NoDelete]** in MO2).
4. Check [Changelog](https://github.com/InTheBottle/BottleRim/blob/main/Changelog.md) for save-safe updates.

---

## Modifying the list
There are a couple mods you should check out in the MCM to customize how you would like to play.

- Helmet Toggle 2
- Bathing in Skyrim

  Helmet Toggle 2 is awesome and you can set the hotkey and conditions in the MCM to whatever you'd like.

  Bathing in Skyrim comes disabled by default, some people may not want this so if you do be sure to enable it before leaving the starting cell.
---

## Uninstalling
- Delete the BottleRim folder.

---

## Troubleshooting
- **Installation Issues**:
  - Missing files? Manually download and place them in the Downloads folder.
  - Game folder not found? Ensure Skyrim SE is installed and follow [Pre-Installation](#pre-installation).
  - Antivirus flagging? Add exceptions or uninstall aggressive third-party AV (e.g., Norton).

- **Post-Installation Issues**:
  - Form 43/DLL errors? Reinstall with “Overwrite Installation” checked in Wabbajack.
  - Crashing on startup? Reinstall or seek help on [Discord](https://discord.gg/avzs76EgnA) with crash logs.

- Join [BottleRim Discord](https://discord.gg/avzs76EgnA) for support.

---

## Credits
- [ElminsterAU](https://www.patreon.com/ElminsterAU) & xEdit team for SSEEdit.
- [Noggog](https://www.nexusmods.com/skyrim/users/862590) for Mutagen and Synthesis.
- [Halgari](https://www.nexusmods.com/skyrimspecialedition/users/17252164) & Wabbajack team.
- [Althro](https://github.com/Althro) and [Styyx](https://github.com/Styyx1) For ADT which is the best base to build off of.
- [Bingus](https://github.com/bingusthecatto) for Anvils epic readme that I used as a base for my own.
- [Sheson](https://ko-fi.com/sheson) for DynDOLOD.
- All mod authors and the Skyrim modding community.
