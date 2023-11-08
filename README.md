<a href="https://www.nexusmods.com/skyrimspecialedition/mods/100704/"><img src="https://staticdelivery.nexusmods.com/mods/1704/images/100704/100704-1694827736-950063437.png" target="_blank"></a>

---

<p align="center">
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/100704/">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="https://discord.gg/VXvZWsxzEG">Discord</a>
</p>

---

# Read-Me

- [Introduction](#introduction)
  - [List Contents](#list-contents)
  - [Requirements](#requirements)
- [Installation](#installation)
    - [Clean Install](#clean-install)
    - [Starting the Game](#starting-skyrim)
    - [Downloading and Installing](#downloading-and-installing)
- [Startup](#startup)
  - [Optional Mods](#optional-mods)
  - [ReShade](#reshade)
  - [GOG Support](#gog-support)
  - [Configuration](#setup-and-configuration)

## Introduction

﻿Vanguard is an MCO-based modlist that, rather than trying to completely transform the game into a souls-like ARPG, takes advantage of the incredible new mechanics and gameplay offered by modern combat mods to strengthen the core aspects we have all come to know and love from the Elder Scrolls series - all while maintaining an incredibly lightweight footprint. Visuals are completely overhauled through a core of Skyland﻿, RAID Weathers, and Community Shaders﻿﻿ which manages to create a beautiful game while still staying EXTREMELY performance friendly. Although combat is a major focus of the modlist, Vanguard also features many other overhauls, enhancements, and high-quality new content that has been meticulously edited and balanced to fit in with Skyrim's world - such as Open Cities, Cities of the North, Northern Roads, jayserpa's quest expansions and other fantastic mods, Sirenroot, The Environs series, Unmarked Location Pack, and SO much more. Check out the full modlist for more info!﻿﻿﻿﻿﻿﻿﻿﻿


 You can also watch a great showcase of this list [here](https://youtu.be/4luXs9L0_4w?si=V0ZQIjn0QKGPvn0a)!


## List Contents

You can browse the full list contents [here](https://loadorderlibrary.com/lists/Vanguard) if you want to know exactly what you're getting.

You can find a summary of all changes on the [Gameplay Changes](GAMEPLAY.md) page.

## Requirements:

- An fresh installation of the **English** version from Steam or GOG
  * The paid Anniversary Upgrade is NOT required. If you have it, there will be extra installation instructions at the end to disable the content.
  * Only the English version is supported. I understand that this may be frustrating for non-English speaking users, but due to the core file differences between the different versions, only one version can be supported. 
  * The game MUST be installed outside of any default Windows folders, such as `Program Files`, your `Desktop`, or `Documents`. If you have your Steam library in any of these locations, please follow [these](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) instructions to move it.

- [Microsoft Visual C++ Redistributable Package](https://aka.ms/vs/16/release/vc_redist.x64.exe)

- The latest release of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) installed outside of any default Windows folders.

# Installation:

## Clean Install
Vanguard requires a completely clean installation of Skyrim Special Edition. This means completely deleting both the game folder and also the folder located in `Documents\My Games\Skyrim Special Edition` then reinstalling the game through Steam/GOG. The game MUST be installed outside of any default Windows folders, such as `Program Files`, your `Desktop`, or `Documents.` If you have your Steam library in any of these locations, please follow [these](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) instructions to move it.

## Starting Skyrim
1. Run the launcher from Steam/GOG
2. There should be two pop-ups about detecting your hardware and applying settings. You do not need to change settings here, as settings will be set automatically by the installer
 > If you do not see any pop-ups, you did not properly do a clean installation! Delete `Documents\My Games\Skyrim Special Edition` and try again

## Downloading and Installing

The download and installation process can take a little while (an hour or more) depending on your system specs. For optimal speed, it is advised to install Wabbajack and the modlist to an SSD.

1. Create a folder for the modist outside of any default Windows folders called **Vanguard** (I recommend `C:\Games\Vanguard`) 
2. Launch the Wabbajack app and select `Browse Modlists`
3. Make sure `Show Unofficial Lists` is checked and search for `Vanguard`
4. Select the **Download** icon in the bottom right, then select he **Play** icon once the download is finished
5. In the **Modlist Installation Location** box, select the `Vanguard` folder you created in the first step
  * The Resource Download Location box should automatically fill in `Vanguard\Downloads`, but you can move this folder to a different drive if are low on space
6. Click the Go/Begin button and wait for Wabbajack to finish

# Startup

Open the installation folder and double click on the program called `ModOrganizer.exe`.

## Disabling Creation Club Content

Users of the paid Anniversary Edition DLC will need to disable the content as it is not compatible with this list. 

1. Download the `Vanguard CC Manager` file from [here](https://cdn.discordapp.com/attachments/773375221792899074/1154401209403322440/NoDelete_Vanguard_CC_Manager.7z)
2. Select the <img src="https://vivanewvegas.moddinglinked.com/img/mo2%20archive.webp"> button at the top of MO2
3. From the pop-up window, navigate to where the file downloaded and double-click it
4. From the next pop-up, set the name of the file at the top of the window to `[NoDelete] Vanguard CC Manager`
5. Select `Ok` then `Ignore` to the error pop-up (it is a false-flag)
6. Enable the check-box next to the mod in the left pane of MO2
7. Right-click on the mod in the left pane of MO2 and select `Ignore missing data`

## Optional Mods

There are a few optional mods that can be found under the `Optional Mods` separator in the left pane of MO2. 

- **Custom Control Map**: These are just my personal controls I used when making the list. The specific binds can be found on the [Gameplay Changes](GAMEPLAY.md) page.
- **Screen Space Shadows** and **Grass Collision**: 5-8 FPS impact combined, so you can enable them if you are happy with your current FPS.
- **Shadow Boost**: Dynamically lowers shadow quality and view distance to achieve better performance, can be disabled if you are happy with your current FPS.
- **No Kill Moves**: Disables the frustrating/cheesey kill moves for both the player and NPCs. Can be disabled if you for some reason enjoy the feature, but I highly recommend keeping them off.
- **Simple Degredation**: Adds a lightweight weapon condition system that makes tempered weapons slowly degrade back to their untempered state. Can be disabled if you dislike the feature.

## ReShade
The list comes with an optional ReShade preset that makes the game a lot more vibrant. It is enabled by default, but it can make some of the brighter weathers look a little too washed out so you may want to disable it. I highly recommend trying it out for yourself. It should have little to no performance impact. [Here](https://imgsli.com/MjA2NzY0) is a comparison shot of the ReShade off and on during a neutral weather.

## GOG Support
If you use the GOG version of the game, activate all the mods under the **GOG Support** separator

## Setup and Configuration

Make sure the dropdown box on the right is set to `SKSE` and press the Run button.

You're all set! Everything is already configured by default so you can hope right into a new game!
