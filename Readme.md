# Al/Styyx Setup of Skyrim - ASSOS

Wabbajack Modlist Installer by *Althro and Styyx*

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/Althro/ADT/main/Resources/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://raw.githubusercontent.com/Althro/ADT/main/Resources/AMLogo.webp" width="72px" /></td>
<td><a href="https://discord.gg/B2ZzzBRTB5"><img alt="Discord" src="https://img.shields.io/discord/1132691434420576337?style=for-the-badge&label=My%20Cool%20Discord"></a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

<!-- omit from toc -->

## Contents 
- [Al/Styyx Setup of Skyrim - ASSOS](#alstyyx-setup-of-skyrim---assos)
  - [Contents](#contents)
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
    - [Disclaimer](#disclaimer)
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
  - [Adding mods to *ASSOS*](#adding-mods-to-assos)
    - [Anniversary Edition](#anniversary-edition)
  - [Updating the modlist](#updating-the-modlist)
  - [FAQ](#faq)
  - [Removing the Modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Support](#support)

## Preamble
*Get Started with your modlist without setting up the basic bug fixes and frameworks yourself*

Full list of mods used can be found [here](https://loadorderlibrary.com/lists/al-styyx-setup-of-skyrim-assos)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

### Disclaimer

**GOG and other Languages aside from English are not supported due to how Wabbajack works.**.

Only, Windows 10 and 11 are fully supported with Wabbajack. LTSC, special variants, lightened editions or any other modified variant, this includes any variant of linux, **MAY OR MAY NOT WORK** and I definitely don't bother supporting any of that.

***

**NOTE**: You need to have **.NET V9** and **Java Runtime Environment** installed to make the full use of this list.

*Insert system requirements*

Space required: Approx 19GB (downloads included).

## Installation

Installing *ASSOS* is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing *ASSOS*, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net 9 Desktop runtime](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.11-windows-x64-installer).
2. Make sure your skyrim install is cleaned and its files are not modded. Otherwise fully uninstall it and reinstall it.
3. Change the language of the game to English, other languages are simply not supported.
4. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
5. Launch the game to the main menu and allow it to download the paid addon files.
6. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will most likely** mess with the installation and, in the case of the latter, causes more problems than it solves.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing ASSOS

Downloading and installing *ASSOS* can take a while depending on your internet connection and computer. To install *ASSOS*, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on *ASSOS* and wait for it to download.
3. Set the installation folder to be somewhere like `C:\Games\*ASSOS*`. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and read through this readme again.
7. If the installation is successful, move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation
It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
    - Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
    - **Make sure your version of Rare Curios is from within the Game and not from verifying with steam** if you think this is dumb for a list without AE DLC support, i do so as well, please join the wabbajack discord server an tell them cause I'm forced to require it. Same goes if you don't know how to install it, I do not support issues the app administration created.

- x is not a whitelisted download:

     - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

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
    
## Adding mods to *ASSOS*

If you want some general tips on how to safely mod, visit our [Modding Tutorials](https://github.com/The-Animonculory/Modding-Resources) repository. Adding mods is your own responsibility and I will not provide any type of support for that whatsoever.

### Anniversary Edition

ASSOS does not require the paid Anniversary Edition DLC and does not support it.   
Do not confuse Anniversary Edition with the game's version, which is a number! The list does run Skyrim 1.6.1170

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

Q: What's the difference to Skyrim Modding Essential?
A: It's more up to date

Q: What's the difference to ADT/STD?
A: It's meant to be used for new modlist setups or wabbajack modlists where STD(formerly ADT) is meant to be used for mod authors to make mods with

Q: What's the difference to any other modlist base?
A: i have no idea, i didn't use/make the other ones

Q: Why doesn't it have *insert tool here*?
A: Because i think the other tools are up to taste of the list author and i for example do not use any other tool for my list

## Removing the Modlist
Simply delete the folder the modlist is in and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- The Animonculory Team.
- Halgari and everyone the WJ Team.

## Support 

Only the latest version of the modlist is supported. No exceptions.

If you encounter bugs with the list as is open a new issue on the list's github page, but check if it's not already mentioned cause duplicate bug reports do not mean it will be magically fixed faster.

Support for the list is only for the base list as is, no support provided for adding stuff, removing stuff or anything in between.
