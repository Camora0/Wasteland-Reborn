
[![1.0 release trailer](https://github.com/Camora0/Wasteland-Reborn/blob/loreout/LoreOutLogo2.png?raw=true)]()
[![Install guide](https://github.com/Camora0/Wasteland-Reborn/blob/main/WastelandRebornImage3U.png)](https://youtu.be/NccDkn4NZFU)

This modlist is hosted on [The Modding Bungalo](https://discord.gg/bungalo) Discord server.



### An Introduction

LoreOut is a modernized full re-design of Fallout 4 with over 800 mods to create a highly refined and perfected game experience!

#### A Note About Difficulty

Loreout is built around a custom tweaked Survival difficulty setting. This is the only staff and volunteer supported difficulty setting. While LoreOut is built to retain the general aesthetic and gameplay feel of vanilla Fallout 4, many general overhauls have been added; most importantly those that touch on difficulty. As such, we implore you as a new player to read through what the mods mentioned do. Read up on the perks and skills available in You are Exceptional, and most importantly, don't get discouraged! Difficulty is highly adjustable, but is finely tuned for a more involved experience right out of the box.

#### Hardware Requirements

An SSD is ***ABSOLUTELY REQUIRED***. Hard Disk Drives (HDDs) are unfortunately too slow for stable performance (and can cause install or other general issues) due to the nature of the HDD itself. 

**For ~90-120FPS @ 1080P**
1. CPU: AMD Ryzen 7 5700x3D / Intel Equivalent
2. GPU: AMD Radeon 6700XT / Nvidia RTX 3070
3. RAM: 32gb on Windows based systems/ 16gb on Linux (Linux is not officially supported by Loreout staff)
---

<details>
<summary><h2>Installation</h2></summary>

### Pre-Installation

Do note that you MUST use a ***FULL (ALL DLC, WITHOUT high-res textures) LATEST*** Steam version of Fallout 4 because we've said so. Not up for debates. In case you've got the AE (the latest DLC or whatever they call it), **DO NOT** manually downgrade. Wabbajack will do it for you.

Your Fallout 4 Steam install must be set to the English language or the Wabbajack install will fail. 

Make certain your Fallout 4 installation path is not set to install in a \ProgramFiles\ folder, as this can and will cause issues. 

Make certain you install Loreout to the same drive as Fallout 4. 

The following steps are only needed if you are installing LoreOut for the first time.

#### Adding Anti-virus / MS Defender exceptions

Sometimes antivirus likes to lock files before checking them or cause some unexpected and mostly un-needed behavior. This occurs the most during extraction or building BSAs phases of the install.

Issues that come from this can be fixed by adding files f4se.exe and ModOrganizer.exe as exceptions
[![Here's a video on how to change it.]()](https://youtu.be/zGiNGnX5dYg?t=34)

#### Microsoft Visual C++ Redistributable Package

You most likely already have this installed. The package is required for MO2, and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if the other link doesn't work.

#### Turn off Steam updates

To turn off Steam automatically updating the game for you, head over to the Properties window. Navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_.

**This game does use a Stock Game Folder, so it should be fine in the event of an update, but it is still best practice to turn it off.**

*It is also highly recommended to turn off Steam Overlay, Medal, or any other Overlay programs.*


### Frame-gen / Smooth Motion / Upscaling

Loreout provides Upscaling and Frame Generation as part of the installation. If your GPU has these options as well, please ensure they are disabled in the Nvidia settings to avoid issues. 


#### Cleaning Fallout 4

It is highly recommended to uninstall the game through Steam, delete the game folder, and reinstall it. It is also recommended to delete the `Fallout4` folder in `Documents/My Games/`. Please also delete anything located in `%LocalAppData%/Fallout 4`. Note: Before doing so make sure that you have backed up anything important, as the Documents folder typically contains save game files and .ini files used prior to the installation. There are youtube videos on this process should you need a visual aid.

#### Initial launching of Fallout 4

After you have done everything above and have a clean Fallout 4 game folder, run the Launcher and let it do the initial graphics check. The Loreout installation will replace these graphics settings afterwards. 

Once the Main Menu has loaded you may exit. After doing this DO NOT play Fallout 4 again using the Launcher as it will revert your .ini files and could mess up your settings.


### Wabbajack

#### Preparations

Download the latest version of Wabbajack [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a folder. This folder **must not** be in your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder at the root level, like `C:/Wabbajack`.

#### Download and Installation

The total instance installation time depends entirely on your internet and CPU-Storage speeds.

1. Open Wabbajack.
2. Click `Browse Lists` then make sure that `Non-featured` option is selected on the left of the UI, below the search bar. Find `LoreOut` and click on it.
3. Set your download and installation paths. The recommended Installation Path is a blank folder at the root of a drive (preferably not the C drive), such as D:\LoreOut. The download path will update automatically. There's an option to put the download folder on another drive, for example an HDD, but the instance **must** on an SSD.
4. Then click the Install button.
5. Wait for Wabbajack to finish. It may take a while depending on your internet speed and if you are a Free or Premium Nexus subscriber. Unfortunately, Nexus Premium is the only method of automatically installing each mod.

#### Problems with Wabbajack

If you run into download issues with Wabbajack, it is recommended to re-run Wabbajack before posting anything on Discord. Wabbajack will continue where it left off, so you will not have to start over. Another common fix is to use the gear icon in lower left of screen, sign out of Nexus. Close and restart Wabbajack. Sign in to Nexus.


### How to setup LoreOut

Head over to the installation folder, locate the .exe file `ModOrganizer.exe` and launch it. 

### Select your correct resolution

Scroll near to the bottom of left pane in Mod Organizer 2 and look for the category "INI SETTINGS - Choose only one!"
Select the appropriate file for your display, and ensure no other ini options are activated.
If you are running Ultrawide, or Super Ultrawide you will also need to activate the appropriate option in OPTIONAL PLUGINS just below.

### If you have a zoomed or mis-aligned display even with the correct ini settings
 
Some users also need to take this step:
In Windows Explorer open the LoreOut\Stock Game folder. Right-click Fallout4.exe > Properties > Compatibility tab > Change High DPI settings > Enable Override > High DPI Scaling Behavior > Set scaling to Application.

Finally, a small number of users have also needed to adjust the High DPI settings the same way with \LoreOut\mods\Fallout 4 Script Extender (F4SE)\Root > f4se_loader.exe

### Launching Game

There is a drop-down box on the upper right of MO2 and a big "Run" button right next to it. Ensure that it is set to `LoreOut`. If not, select it in the drop-down box and click the run button. You have to run the modlist through Mod Organizer 2 in order to load the mods correctly, as Mod Organizer handles most mods via VFS (Virtual File System).


### IT IS IMPERATIVE YOU SET THESE TO GET THE INTENDED GAMEPLAY EXPERIENCE

First, create your character. Once you have exited the vault press ESC. Select Mod Config and navigate to the MCM settings menu. Then click on the dropdown titled "MCM Settings", and then "MCM Settings Manager". Press Apply on the preset. Afterwards you will need to exit back into the game to select "Remove" on a pop up regarding Legendary effects. Confirm that pop up. 

Once this is done, save your game, then exit to desktop. Restart the game and you're good to go!

</details>

<details>
<summary><h2>Updating the list</h2></summary>

If LoreOut receives an update, please check the Changelog before doing anything. Changelog will notify you if the update is SAVE-SAFE or not. 

To apply an update, simply run the Wabbajack process again and it will overwrite your current install. 

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that if you added any of your own mods into the Modlist, they will be deleted. To prevent this, you can add [NoDelete] to the beginning of the name of the mod you added. We cannot and will not guarantee support or compatibility for mods added on top of the list (Rule 11!)


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

Biggie_Boss for the amazing colab and decision making to curate the best possible Fallout 4 modlist.

Alexerator, RetroPaladin, Micalov, DegenerateDak, CSEPteam, ShimSham, Grilledturkey, VishVadeva, the entire F4NV, Project Mojave and F4CW teams for providing countless of high-quality mods this Modlist uses.

Ungeziefi - Creating the Midnight Ride, for which this list is based on.

A Raven of Many Hats - Former maintainer of Midnight Ride, who gave me permission to fork it into the list. 

The many, many users of DegenerateDak's Discord for providing feedback, positive and negative, to facilitate the development of this list.
