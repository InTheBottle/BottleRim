# BottleRim
A total survival SimonRim focused gameplay overhaul using Community Shaders.
![BottleRim](Resources/Skyrim.webp)


**Links**: [Nexus Page](https://www.nexusmods.com/skyrimspecialedition/mods/154268) | [Changelog](https://github.com/InTheBottle/BottleRim/blob/main/changelog.md) | [Load Order](https://loadorderlibrary.com/lists/bottlerim-2) | [Discord](https://discord.gg/bungalo)

---

**Support**: Join the [BottleRim Discord](https://discord.gg/bungalo)

**Requirements**:
- Skyrim version 1.6.1170 (latest Steam update).
- Skyrim AE with all anniversary edition content (Paid Creation Content).

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
**BottleRim** is a total gameplay overhaul modlist for Skyrim AE (1.6.1170), built around [Community Shaders](https://www.nexusmods.com/skyrimspecialedition/mods/86492). Based on [Althros Dev Tools](https://github.com/Styyx1/ADT).

This list uses a heavily modified SimonRim base, MCO for third person and Sig animations for first person. The result is a super satisfying and immersive combat experience. Leveling has been modified to generally be a bit tougher as well and survival is a key part
of the list.

View the full mod list [here](https://loadorderlibrary.com/lists/bottlerim-2).

Licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## System Requirements
- **OS**: Windows 10 or 11 (no LTSC or modified versions; Linux not supported).
- **Storage**: SSD required.
- **Download Size**: ~127 GB.
- **Install Size**: ~212 GB.

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
   - Disable [auto-updates for Skyrim AE](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
   - Run Skyrim AE once for graphics check.
   - Run Skyrim through steam, install ALL creation club addons. Do not ALT tab during this process.
   - If you have issues with the creation club plugins missing, I highly recommend a CLEAN install of Skyrim, including completely deleting the skyrim steam folder and uninstalling.
  
3. **PageFile**:
   Larger modlists require a lot more of your memory, running out of memory will result in crashes and other potential issues. Highly recommended to do this step.

To set up a Pagefile:

   - Press Win Key + R
   - Type sysdm.cpl ,3 and hit ENTER
   - Navigate to Performance and click the box Settings
   - Click the Advanced tab at the top
   - Under Virtual Memory click the box Change
   - Uncheck Automatically Manage if it is checked
   - Select your disk drive, ideally your fastest solid state drive
   - Click Custom Size:
   - In the box next to Initial Size (MB), type 40960
   - In the box next to Maximum Size (MB), type 40960
   - Click Set.
   - Click OK.
   - Click Apply.
   - Click OK.
   - Restart your PC.


### Wabbajack Installation
1. **Install Wabbajack**:
   - Create a folder (e.g., `C:\Wabbajack`) on your drive’s root (not in Program Files, Desktop, etc.).
   - Download [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) and place it in the folder.
   - Run `Wabbajack.exe` (requires version 4.0.0.0 or later).

2. **Install BottleRim**:
   - Open Wabbajack, select Skyrim AE, find BottleRim, and click “Download and Install.”
   - Set Installation Location (e.g., `C:\BottleRim`) and Downloads Location (avoid Program Files, Desktop, etc.).
   - Click Install.
   - Nexus Premium automates downloads; without it, manually click “Slow Download” for each mod.
   - If successful, proceed to [Post-Installation](#post-installation). If not, check [Troubleshooting](#troubleshooting).

---

## Post-Installation

There are a few things you can and should do. 

1. This is optional as the list comes with preconfigured INIs, run Bethini through the MO2 dropdown and select a preset + recommended tweaks ONLY. (Do not turn off TAA, required if you use CS' DLAA or AMDs.)

2. Check the "Optionals" separator in Mo2, I have them enabled by default but all are safe to disable at any time. The reason for leaving them enabled is just to help those that use them not have to worry about where the plugins should go since it will already be set.
   
### Antivirus Exceptions
- Add exceptions in Windows Defender for the BottleRim folder and `ModOrganizer.exe` to avoid crashes.
- Steps: Windows Security > Virus & Threat Protection > Manage Settings > Exclusions > Add Folder > Select BottleRim folder.

### Keyboard Keybinds
- Controller support uses this layout; it is possible to reinstall the Complete Controller Setup mod to use a different layout.
<img src="Resources/Screenshot 2025-10-25 091049.png" alt="Screenshot" width="800">

---

## Playing the Game
- Launch Skyrim SE through Mod Organizer 2 (MO2) in the BottleRim folder.
- Enjoy surviving in BottleRim, or don't, it is pretty hard.

---

## Updating
1. Open Wabbajack, find BottleRim, and click “Download and Install.”
2. Use the same Installation and Downloads folders.
3. Backup custom mods or settings (prefix added mods with **[NoDelete]** in MO2).
4. Check [Changelog](https://github.com/InTheBottle/BottleRim/blob/main/Changelog.md) for save-safe updates.

---

## Modifying the list
There are a couple of mods you should check out in the MCM to customize your play style as you prefer.

- Helmet Toggle 2 
   
   Helmet Toggle 2 is awesome, and you can set the hotkey and conditions in the MCM to whatever you'd like.

  - Leveling Freedom

  If at any point you want to adjust the amount of experience it takes to get to the next level, find this mod in the MCM. Simple to adjust the curve or simply choose an easy or more difficult preset.
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
  - Crashing on startup? Reinstall or seek help on [Discord](https://discord.gg/bungalo) with crash logs.

- Join [BottleRim Discord](https://discord.gg/bungalo) for support.

---

## Credits
- [ElminsterAU](https://www.patreon.com/ElminsterAU) & xEdit team for SSEEdit.
- [Noggog](https://www.nexusmods.com/skyrim/users/862590) for Mutagen and Synthesis.
- [Halgari](https://www.nexusmods.com/skyrimspecialedition/users/17252164) & Wabbajack team.
- [Althro](https://github.com/Althro) and [Styyx](https://github.com/Styyx1) For ADT which is the best base to build off of.
- [Bingus](https://github.com/bingusthecatto) for Anvils epic readme that I used as a base for my own.
- [Sheson](https://ko-fi.com/sheson) for DynDOLOD.
- All mod authors and the Skyrim modding community.
