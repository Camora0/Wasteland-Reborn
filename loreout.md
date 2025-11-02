# LoreOut - Alpha
[![1.0 release trailer](https://github.com/Camora0/Wasteland-Reborn/blob/loreout/LoreOutLogo2.png?raw=true)]()
[![Install guide](https://github.com/Camora0/Wasteland-Reborn/blob/main/WastelandRebornImage3U.png)]

This modlist is hosted on The Modding Bungalo - https://discord.gg/nZQpydyQQg



### An Introduction

LoreOut is a modernized full redesign of Fallout 4, with over 800 mods to build the a highly refined and perfected experience of the game.

#### A Note About Difficulty

While LoreOut is built to retain the general aesthetic and gameplay feel of vanilla Fallout 4, many general overhauls have been added; most importantly those that touch on difficulty. As such, we implore you, as a new player, to read through what the mods mentioned do, read up on the perks and skills available in You are Exceptional, and most importantly, don't get discouraged. difficulty is highly adjustable but finely tuned for a more involved experience out of the box.

#### Hardware Requirements

An SSD is ***ABSOLUTELY REQUIRED***. Hard Disk Drives (HDDs) are, unfortunately, too slow for stable performance (and can cause install or other general issues) due to the nature of the HDD itself. 

**For ~90-120FPS @ 1080P**
1. CPU: AMD Ryzen 7 5700x3D / Intel Equivalent
2. GPU: AMD Radeon 6700XT / Nvidia RTX 3070
3. RAM: 32gb on Windows based systems/ 16gb on Linux distros
---

<details>
<summary><h2>Installation</h2></summary>

### Pre-Installation

Do note that you MUST use ***FULL (ALL DLC, except high-res textures) LATEST*** Steam version of Fallout 4 because we've said so. Not up for debates. In case you've got the AE (the latest DLC or whatever they call it), **DO NOT** manually downgrade. LoreOut will do it for you.

These steps are only needed if you are installing LoreOut for the first time.

#### Microsoft Visual C++ Redistributable Package

You most likely already have this installed. The package is required for MO2, and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if the other link doesn't work.

#### Turn off Steam updates

To turn off Steam automatically updating the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_.

**This game does use a Stock Game Folder, so it should be fine in the event of an update, but it is still best practice to turn it off.**

*It is also highly recommended to turn off Steam Overlay.*

#### Cleaning Fallout 4

It is highly recommended to uninstall the game through Steam, delete the game folder, and reinstall it. It is also recommended to delete the `Fallout4` folder in `Documents/My Games/`. Please also delete anything located in `%LocalAppData%/Fallout 4`. Note: Before doing so, make sure that you have backed up anything important as the Documents folder typically contains save game files and .ini files used prior to the installation.

#### Starting Fallout 4

After you have done everything above and have a clean Fallout 4 game folder, start the Launcher and let it do the initial graphics check. Do not worry about this part, as the installation will replace these graphics settings, then Start Fallout 4. 

Once the Main Menu has loaded you may exit. After doing this, do not play Fallout 4 again using the Launcher, as it will revert your .ini files and could mess up your settings.

#### Assigning pagefile

This step is important to those who have not modded before. This system has to do with how much RAM Windows can allocate to a process (the additional space comes from the disk the pagefile is in).

Set the initial size to the size of your RAM size. For example, I have 32 GB of RAM, so I set mine to 32. My max is set to 48 GB. Use the same proportions for your own RAM configuration.
[![Here's a video on how to change it.]()](https://youtu.be/beHDr6OFjlw?t=22)

#### Adding MS Defender exception

Sometimes antiviruses like to lock files before checking them or cause some unexpected and mostly un-needed behaviour. This occurs the most during extraction or building BSAs phases of the install. Keep in mind, if it is just a simple

All issue that come from this can be fixed by adding files `f4se.exe` and `ModOrganizer.exe` as exceptions.
[![Here's a video on how to change it.]()](https://youtu.be/zGiNGnX5dYg?t=34)


### Wabbajack

#### Preparations

Download the latest version of Wabbajack [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a folder. This folder **must not** be in your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder at the root level, like `C:/Wabbajack`.

#### Download and Installation

The total instance installation time depends entirely on your internet and CPU-Storage speeds To speed up this process it is advised to place the instance (installation) folder on an SSD.

1. Download the .wabbajack file from [here](https://drive.google.com/file/d/1Kr6jekSssBKhY3FVfZL6ePxbj7Mfb2CR/view?usp=sharing).
2. Open Wabbajack.
3. Click `Get Started` then click the button called `Install from disk` and select the .wabbajack file you downloaded.
4. Set your download and installation paths. The recommended Installation Path is a blank folder at the root of a drive (preferably not the C drive), such as D:\LoreOut. The download path will update automatically. There's an option to put the download folder on another drive, for example an HDD, but the instance **must** on an SSD.
5. Then click the Install button.
6. Wait for Wabbajack to finish. It may take a while depending on your internet speed and if you are using an SSD or HDD.

#### Problems with Wabbajack

If you run into download issues with Wabbajack, it is recommended to re-running Wabbajack before posting anything. Wabbajack will continue where it left off, so you will not have to start over.

### Modifying INIs

To ensure the proper settings are enabled, you need to run Bethini. 

#### Setting BethINI Pie up incase it is not set up automatically:
1. Set the Game Path to: "(Your install folder)\Stock Game and make sure to select ***Fallout4.exe***";
2. Set the INI Path to: "(Your install folder)\profiles\LoreOut";
3. Use the Restore Backup if you want to use your backed up INIs again. 

#### While Bethini is open, change the following settings, if they are not already set up:
+ Change the resolution of the game (I use a 1440p monitor, and the inis are set as such.) , display mode (default should be set and left at Borderless Windowed);
+ Set the presets to Bethini Presets, and press the High button.
+ Apply the recommended tweaks as well. Then save your settings.

### Saving on disk space ***(Highly OPTIONAL)***

After a successful download deleting the ***downloads*** folders content is safe. 
Note: If the user does end up cleaning the folder, any form of updating or redownloading ***WILL*** result in the mod archieves being redownloaded.

### How to start up LoreOut

Head over to the installation folder, locate the .exe file `ModOrganizer.exe` and launch it. Once it launches, there will be a drop-down box on the upper right and a big run button right next to it. Ensure that it is set to `LoreOut`, if not select it in the drop-down box, and then click the run button. You have to run the modlist through Mod Organizer 2 in order to load the mods correctly as Mod Organizer handles most mods via VFS (Virtual File System).

After making a new character in a new game, you will be prompted with Start Me Up Redux' Scenario Creator (save for Traits and Level Selection). this will allow you to fully customize how you start your experience, whether you'd rather a hunter simply surviving on the outskirts of the Commonwealth, a mad scientist hell-bent on unleashing energized death on your enemies, or even the vanilla start! (if you despise yourself...)

After this, you'll want to set up your MCM settings. 

### IT IS IMPERATIVE YOU SET THESE UP TO GET THE INTENDED PLAY EXPERIENCE

First, in the start menu, navigate to the MCM settings menu. Then click on the dropdown titled "MCM Settings", and then "MCM Settings Manager". Press Apply on the preset. Afterwards, you'll need to exit back into the game to select yes on a pop up regarding Legendary effects. Select yes on that pop up, then go back to the MCM settings manager and apply the rest of the settings. 

Once this is done, Save and load your game, and you're good to go!

</details>

<details>
<summary><h2>Updating the list</h2></summary>

If LoreOut receives an update, please check the Changelog before doing anything.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that if you added any of your own mods into the Modlist, they will be deleted. To prevent this, you can add [NoDelete] to the beginning of the name of the mod you added. We cannot and will not guarantee support or compatibility for mods added on top of the list (Rule 11!)

Updating is like installing the modlist. You only have to make sure that you select the same paths and tick the _overwrite existing Modlist_ button (typically Wabbajack already selects the folders but it is recommended to make sure they're correct before continuing).


</details>

<details>
<summary><h2>Important mods</h2></summary>

### Gameplay

1. [Classic Radiation Poisoning 2](https://www.nexusmods.com/fallout4/mods/48185)
2. [Immersive Animation Framework](https://www.nexusmods.com/fallout4/mods/50555)
3. [Silent Protagonist F4SE](https://www.nexusmods.com/fallout4/mods/61732)
4. [You Are Exceptional - Skills and Perk Overhaul v1.05h](https://www.nexusmods.com/fallout4/mods/76739)

### Quests
1. [CSEP Presents Brothers in Arms Return Of The Outcasts - Mini DLC Sized Quest Mod](https://www.nexusmods.com/fallout4/mods/73657)
2. [CSEP Presents Commonwealth Killer - Quest Mod](https://www.nexusmods.com/fallout4/mods/61305)
3. [CSEP Presents Loaded Bases - Quest Mod](https://www.nexusmods.com/fallout4/mods/70031)
4. [Fallout 4 - Point Lookout](https://www.nexusmods.com/fallout4/mods/60330)
5. [Fourville](https://www.nexusmods.com/fallout4/mods/43979)

### New things
1. [Capital Wasteland Raider Pack](https://www.nexusmods.com/fallout4/mods/50007)
2. [DC and West Coast Supermutants](https://www.nexusmods.com/fallout4/mods/49680)
3. [Mojave Cazadores](https://www.nexusmods.com/fallout4/mods/57161)
4. [Mutant Menagerie - Life Finds A Way](https://www.nexusmods.com/fallout4/mods/68187)
+ 100s of new armors and weapons


</details>

<details>
<summary><h2>Removing the Modlist</h2></summary>

Just remove the install folder. Simple as.

</details>

## Credits and Thanks

You, the reader, for taking your time to read this document and for playing our modlist.

Biggie for the amazing colab and decision making to curate the best possible Fallout 4 modlist.

Alexerator, RetroPaladin, Micalov, DegenerateDak, CSEPteam, ShimSham, Grilledturkey, VishVadeva, the entire F4NV, Project Mojave and F4CW teams for providing countless of high-quality mods this Modlist uses.

LivelyNightmare - Writing the majority of the guides I used to build this list, as well as personally helping me.

Ungeziefi - Creating the Midnight Ride, for which this list is based on.

A Raven of Many Hats - Former maintainer of Midnight Ride, who gave me permission to fork it into the list. 

The many, many users of DegenerateDak's Discord for providing feedback, positive and negative, to facilitate the development of this list.

Palurien1985 for writing the first revision of the readme in a moments notice, ElisPlayz for corrections and future upkeep.
