<!-- omit from toc -->
# Al/Styyx Setup of Skyrim - ASSOS

![image](https://github.com/The-Animonculory/ASSOS/blob/master/Docs/Images/ASSOSLogo.png?raw=true)

Wabbajack Modlist Installer by *Althro and Styyx*

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/ASSOS/refs/heads/master/Docs/Images/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://raw.githubusercontent.com/The-Animonculory/ASSOS/refs/heads/master/Docs/Images/DiscordIcon.png" width="72px" /></td>
<td><a href="https://discord.gg/zscJV6nJKZ"><img alt="Discord" src="https://img.shields.io/discord/1437168312722391192?style=for-the-badge&label=Animonculory%20Creative%20Corner"></a></td>
</tr>
</table>



[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg


<!-- omit from toc -->
## Contents 
- [Preamble](#preamble)
- [System Requirements](#system-requirements)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
  - [Wabbajack Installation](#wabbajack-installation)
    - [Installing Wabbajack](#installing-wabbajack)
    - [Downloading and Installing ASSOS](#downloading-and-installing-assos)
      - [Problems with installation](#problems-with-installation)
- [Post-Installation](#post-installation)
  - [BethINI Pie](#bethini-pie)
- [Playing the List](#playing-the-list)
  - [Starting up the list](#starting-up-the-list)
- [Adding mods to ASSOS](#adding-mods-to-assos)
  - [Anniversary Edition](#anniversary-edition)
- [Updating the modlist](#updating-the-modlist)
- [FAQ](#faq)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Support](#support)
- [The Animonculory Team](#the-animonculory-team)

## Preamble
> *Get Started with your modlist without setting up the basic bug fixes and frameworks yourself.*

**Al and Styyx's Setup of Skyrim (ASSOS)** is designed to serve as a base to build off. You'll find all the required bug-fixes and frameworks present, with a few other items to help facilitate your list building. 

Where possible, the mods used are open source. We're big fans of Open Source and Creative commons licences 🙂

Whilst it is not designed for you to play the game with, it'll be stable enough to do so with. There's other lists probably more suited to that though.

> [!TIP]
> You need to have [**Java Runtime Environment**](https://www.java.com/en/download/windows_manual.jsp) installed to make the full use of this list.

A full list of mods used can be found [here](https://loadorderlibrary.com/lists/al-styyx-setup-of-skyrim-assos).

>[!NOTE]
>This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

> [!WARNING]
> Only Windows 10 and 11 are fully supported with Wabbajack (WJ). We do not support any other operating systems.

Whilst this list ***Definitely does*** work with Linux (since it is developed on linux) or ***may*** work with other variants of Windows, no support is offered for them officially as Wabbajack officially does not support linux or any non-standard windows 10/11 installs. Check out [jackify](https://github.com/Omni-guides/Jackify) for installing with linux. Do keep in mind, not everything may work as expected on any OS but default windows 10 or 11.

***

| | Requirements | Info |
| :---: | :---: | :---: |
| **Game** | Clean **Steam English version** | GOG and Epic Games **not supported.**|
| **Operating System** | Windows 11 (64bit) | Only Windows 11 is currently supported by Microsoft. |
| **CPU** | 4 Core/ 4 Threads | Anything newer than a 3rd gen i5 or 1st gen Ryzen. ARM & 32bit not supported. |
| **RAM** | 16GB | 32GB preferrable, but 16GB is fine. |
| **GPU** | 4GB Vram | Any modern card will be fine. |
| **Space** | 19GB | SSD strongly recommended. |

## Installation

Installing ASSOS is relatively easy and even without nexus premum, it will be quick. I don't recommend getting premium for a list this size. If you are updating the modlist, you can safely skip to the [updating section](#updating-the-modlist).

### Pre-Installation

> [!CAUTION]
> [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net 9 Desktop runtime](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.11-windows-x64-installer) are required. Download them by clicking on the links.

***

Prior to installing ASSOS, please complete the following steps.

1. Make sure your skyrim install is cleaned and its files are not modded. Otherwise fully uninstall it and reinstall it.
2. Change the language of the game to English, other languages are simply not supported.
3. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
4. Launch the game to the main menu and allow it to download the paid addon files.
5. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will most likely** mess with the installation and, in the case of the latter, causes more problems than it solves.

> [!TIP]
> If your game is not a fresh install, it is still worth making sure you have the paid addon files all downloaded.

>[!CAUTION]
>**Make sure your version of Rare Curios is from within the Game and not from verifying with Steam.**

****

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. We recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing ASSOS

Downloading and installing *ASSOS* can take a while depending on your internet connection and computer. To install *ASSOS*, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on ASSOS and wait for it to download.
3. Set the installation folder to be somewhere like `C:\Games\ASSOS`. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and read through this readme again.
7. If the installation is successful, move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation
It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
    - Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- Unable to download Data_ccbgssse037-curios
    - You missed the big warning sign in [Pre-Installation](#pre-installation). Go back there and read it.
        - If you think this is daft for a list without AE DLC support, we do so as well. You are welcome to complain to Wabbajack about this along with any other issues you have with the application. We do not support any issues with the application.

- x is not a whitelisted download:

     - This will happen when we update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

    - Either buy the game on steam or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
    - You did not follow the steps in [Pre-Installation](#pre-installation). Go back and follow it.
    - If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### BethINI Pie

This replaces the old BethINI and can be started from within mod organizer. Just select it in the executable dropdown.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `Play` and press the `Run` button.
    
## Adding mods to ASSOS

If you want some general tips on how to safely mod, visit our [Modding Tutorials](https://github.com/The-Animonculory/Modding-Resources) repository. Adding mods is your own responsibility and we will not provide any type of support for that whatsoever.

### Anniversary Edition

>[!WARNING]
> ASSOS **does not require** the paid Anniversary Edition DLC and **does not support** it.   

Do not confuse Anniversary Edition with the game's version, which is a number! The list uses SkyrimSE executable version **1.6.1170**.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. 

>[!CAUTION]
> Any mods you have added will be **deleted** when updating.

## FAQ

**Q: What's the difference to Skyrim Modding Essential?** \
A: It's more up to date.

**Q: What's the difference to ADT/STD?** \
A: It's meant to be used for new modlist setups or wabbajack modlists where STD(formerly ADT) is meant to be used for mod authors to make mods with.

**Q: What's the difference to any other modlist base?** \
A: We have no idea, we don't use/make the other ones.

**Q: Why doesn't it have *insert name of mod/tool here*?** \
A: The philosophy behind ASSOS is that, where possible, every mod used is open source, which includes the DLL mods. Certain mods are not open source, so they are not included or alternatives are used.

## Removing the Modlist
Simply delete the folder the modlist is in and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- The Animonculory Team.
- It's Always 710 for test installing the list
- Astro for test installing the list
- Halgari and everyone at the WJ Team.
- Kannon555 and KenShikunai on discord for testing and confirming my compile works on windows

## Support 

Only the latest version of the modlist is supported. No exceptions.

If you encounter bugs with the list as is open a new issue on the list's github page, but check if it's not already mentioned cause duplicate bug reports do not mean it will be magically fixed faster.

Support for the list is only for the base list as is, no support provided for adding stuff, removing stuff or anything in between.

## The Animonculory Team
 - Althro - Founder, Architect, Centurion and Developer. (Co-Author of ASSOS. Former author of ADT)
 - Styyx - Architect and Developer. (Co-Author of ASSOS. Maintainer/Author of STD/ADT)
 - Chef - Architect and Developer.
 - Destiny - Architect, Centurion and Developer.
 - KFC - Architect and Administrator.
