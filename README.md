# ELDERGLEAM NEXT-GEN 3.0
Welcome to the Official Readme of Eldergleam NG

![alt text](https://i.imgur.com/f5L5Yrj.png "Eldergleam Image")
[By Capt. Panda](https://www.youtube.com/@captpanda)

# IMPORTANT LINKS

[Community Discord](https://discord.gg/5RRtjr9c) 
[Nexus Modspage](https://www.nexusmods.com/skyrimspecialedition/mods/105778)

After reading the whole README and you're still having issues, feel free to join Discord and ask help.

# PRE-INSTALLATION STEPS
Before you install the modlist, there are some very important steps you need to take in order for a smooth installation process as well as a more seamless experience in-game.
Before diving into the modlist, it's essential to prepare your game environment. These pre-installation steps will help ensure a smooth installation process and a more seamless experience in-game. Follow **all** guidelines carefully:

## REQUIREMENTS
Verify that your system meets the recommended requirement for running the modlist. Take note, these are specs given to me by some of the community members that played Eldergleam.

![alt text](https://i.imgur.com/aGZlvGy.png)

#### PAGE FILE AND MEMORY CRASHES

Bigger Skyrim modlists need a lot of memory, and when there is not enough available it may fail allocating more. To fix this, you'll want to have a bigger pagefile.

A pagefile is a file on your disk Windows will use when there is not enough RAM available.

Never disable the pagefile - this may lead to various issues on your system, such as this Skyrim crash.

If you've never touched the pagefile, try performing the following steps:
1. Press Windows + R on your keyboard
2. Type sysdm.cpl ,3
3. Press Enter
4. Under the Performance section, press 'Settings'
Click the Advanced tab at the top
5. At the Virtual memory section press 'Change...'
6. Disable 'Automatically manage paging file size for all drives'
7. Click "Custom size:"
8. Set a custom size for the drive Skyrim is installed on with a minimum of at least 20480MB (40960MB if higher (BETTER))
9. Click Set
10. Click apply & OK
11. Press Yes to restart
12. 12. Restart your computer.

THIS IS NOT OPTIONAL, YOU CANNOT SKIP THIS STEP EVEN IF YOU HAVE 256 GB OF RAM.

## MICROSOFT
Download the latest x64 version beneath "Visual Studio 2015, 2017, 2019, and 2022" for [Microsoft Visual C++ Redistributable Packages](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).

You are also going to need to download and install [.NET runtime](https://dotnet.microsoft.com/en-us/download).

Make Onedrive exclude folders from syncing:
https://support.microsoft.com/en-us/office/choose-which-onedrive-folders-to-sync-to-your-computer-98b8b011-8b94-419b-aa95-a14ff2415e85

or Disabling Onedrive (Recommended):
https://support.microsoft.com/en-us/office/turn-off-disable-or-uninstall-onedrive-f32a17ce-3336-40fe-9c38-6efb09f944b0

## ACCOUNTS
You need an account on [Nexus](https://www.nexusmods.com). Premium is recommended to avoid having to manually click the download button for an entire day or.. WEEKS.

![alt text](https://i.imgur.com/MVvCyzb.png)

# PREPPING FOR INSTALLATION
In order to avoid issues when installing through Wabbajack, you will need to follow these **VERY IMPORTANT** steps.

## SETTING UP FOLDERS
Press Windows+E and locate the Driver you would like to play Skyrim from, for example "C:\" or "D:\". Ensure that you have enough space for the list (750+ GB). You want to create 4 folders on the *root* of the drive (Here C:\). Be sure to EXCLUDE these folders in your Anti-Virus or there will be instance to some that Anti-Virus will be deleting one of the programs we need.

C:\Eldergleam

Note: Recommended to put it in your fastest drive.

C:\wabbajack

Note: Any drive will do.

C:\ResourceDownloads

Note: Recommended to put in your HDD or any storage with a ton of space

NOTE: If you have one drive, make sure all 4 including Steam's folder are all OUTSIDE of Programs Files. Resource Downloads can also be used globally with other Modlists. If you have previously downloaded a Modlist and kept its Downloads/Resource folder, you can designate your "Resource Location" to it.

## STEAM SETTINGS
*Disable Steam Overlay*. Right-click on Skyrim Special Edition in your Steam > "Properties" > "General" > untick "Enable Steam Overlay while in-game". 

*Set Game Language to English*. Right-click on Skyrim Special Edition in your Steam > "Properties" > "Language" > select English.

*Change Updating Behavior*. Right-click Skyrim Special Edition in your Steam > "Properties" > "Updates" > change "Automatic Updates" to "Only update this game when I launch it". Disable Steam Cloud as well.

After you have completed these steps, you will need to add a new library on the root of your drive so that Skyrim is **not** installed to Program Files (x86). We already made a folder for this earlier here: "C:\SkyrimGAME". To make this a Steam library, you need to click on Steam (top left of your Steam) > Settings > Storage > click the tab at the top > "Add Drive". From here, locate C:\SkyrimGAME *(or whatever you named it)* and select this as the folder. 

It seems that Steam has issues when it comes to adding more libraries to the same drive, so in the case that it does not create a new library for you, you can try to follow the steps listed here: [Changing the default install folder](https://steamcommunity.com/discussions/forum/1/3395163747110198261/#c3395163747110912094).

## FRESH SKYRIM INSTALL
If you already have Skyrim Special Edition (with AE) installed, right-click on Skyrim Special Edition in your Steam library, click Properties > Local Files > Browse. Keep this explorer tab open and *uninstall* your Skyrim through Steam. If any files remain in the explorer, make sure to delete them. Following this, locate %localappdata% and delete the Skyrim folder. You must also delete the Skyrim folder in Documents\My Games.


Reinstall Skyrim Special Edition in a dedicated folder on the root of a drive, e.g., C:\SteamGames\SkyrimSpecialEdition.


Start the game to create registry entries and default config files. Make sure you do not alt-tab while the Creation Club content is installing. To avoid issues down the lines, also go into Creations menu and install all owned Creation Club content. Then close the game.


After you have done this, you need to make sure to download Creation Kit for SE. This must be installed to the same Steam Library as your Skyrim *(for example "C:\SteamGames")*.

## INSTALLATION THROUGH WABBAJACK
If you have completed **all** steps above, you can now begin to download Eldergleam Next-Gen through Wabbajack! For this, you naturally need to have [Wabbajack](https://www.wabbajack.org) installed *(into C:\wabbajack which should be excluded by antivirus)*.


You need to log into Nexus within Wabbajack by clicking the Gear at the top before you begin your installation. Set the install location to an empty folder on the root of a drive, such as C:\Eldergleam, and downloads to something like C:\ModDownloads. Note that you should usually tick the "Overwrite" if it is available.


If you encounter any issues during the installation process, consider going through the steps of the ReadMe once more. If you still cannot figure out what the problem is, please ask help in [Eldergleam's Official Discord](https://discord.gg/5RRtjr9c).

# POST-INSTALLATION

Just have fun and DO NOT use the Vanilla Start :) 
