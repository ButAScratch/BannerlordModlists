# Where My Bannerlord Mod Lists Go

## **This mod list is for 1.5.9**

#### [Mod List]
[Mod list]: https://github.com/ButAScratch/BannerlordModlists/blob/Gohandhi-Modified/MODLIST.md

#### [Changelog]
[Changelog]:https://github.com/ButAScratch/BannerlordModlists/blob/Gohandhi-Modified/CHANGELOG.md


## Installation

### Quick foreword

[via this method]: https://redd.it/g0korl

While the Bannerlord Mod Launcher should do it for you, always make sure your mod's DLLs are unblocked [via this method] if you are crashing on startup.
To save any headaches, I recommend starting the game and loading into the character customization screen (Where you would select your character's culture) every 10 mods or so just to make sure things are being nice. (Doing this also makes setting up the load order easy because you'd be doing it gradually.)

Also, if you don't like a mod you can remove it as long as nothing else in the list is relying on it. To check this go to the mod that you want to remove's page, and click the `Requirements` dropdown if it exists. If it doesn't exist, you're safe to remove it. If it does, check if anything in the `Mods requiring this file` section is in the mod list. If no mods in the list require the mod to function, you're safe to remove it.

Generally speaking, other mods can also be added into the list seamlessly as long as they're not touching the same files, like having two mods that change the Sturgian troop tree, or several mods that change the world's layout for example.  

---

### Now on to the instructions!
**Method One** *(Recommended if you don't feel like overcomplicating things)*

[Bannerlord Mod Launcher]: https://www.nexusmods.com/mountandblade2bannerlord/mods/265


- Download the [Bannerlord Mod Launcher]. Extract it to your game's directory.
- Download the correct version of each mod manually.
- Extract mod contents to `...\steamapps\common\Mount & Blade II Bannerlord\Modules`. 

(This looks something like `...\steamapps\common\Mount & Blade II Bannerlord\Modules\Diplomacy\bin`. Not every mod will have a bin folder but you get the point.)

- Start BML and set the load order as the list the mods are in on the mod list page. 

- Once you're in the game, head to the Mod Options menu and change the settings to your preference.

- Profit.

--- 

### **Method Two** (*Recommended if you'd like to have several mod lists at once*)

[Bannerlord Mod Launcher]: https://www.nexusmods.com/mountandblade2bannerlord/mods/265
[Mod Organizer 2]: https://github.com/ModOrganizer2/modorganizer/releases/latest

**Mod Organizer 2 uses virtual file system, meaning unless you manually place them there, no mods will ever actually touch your game install, insuring you'll always have a clean and working version of Bannerlord you can fall back to. It also means you will be able to have multiple mod lists in a very clean way.** I vastly prefer it over Vortex because of stability.

- Download the [Bannerlord Mod Launcher]. Extract it to your game's directory.
- Download and install [Mod Organizer 2] portable. (The 7z version.)
- Create a folder called `Bannerlord Mod Lists`. Inside of that, create a subfolder named `MO2`. (For example, `E:\SSD Modding\Bannerlord Mod Lists\MO2` is where I would install it.)
- Start `ModOrganizer.exe`, and create  a new global instance. Select Bannerlord as the game to manage. Name the instance something you can use to identify that particular mod list.
- Select the location to be a new folder inside of the Bannerlord Mod Lists folder you created, and give that folder the same name you gave the instance in the last step. Using my previous example again, this location would be `E:\SSD Modding\Bannerlord Mod Lists\Personal`
- Skip or read the tutorial if it prompts you.
- To the left of the `Run` button located on the right, click the dropdown menu. Then click `<Edit...>`, then select the blue plus icon, and click `Add from file...`. Navigate to where you installed the Bannerlord Mod Launcher, and select it.
- Next, here go into the settings page (Wrench & screwdriver icon on the top icon bar), then navigate to the `Nexus` tab and log in. Then click `Associate with "Download with manager"` links. From now on when you're downloading a mod through the Nexus, navigate to the `Files` tab and click `Download with manager`.

**Every time you want to start the game from now on, start Mod Organizer 2. Then launch the Bannerlord Mod Launcher from there, and *then* start the game through that.**

**How to have multiple mod lists with Method 2**

- In the top left of MO2, click the icon with two arrows making a circle.
- From there, click `Create new instance`. Then click `Create a global instance`.
- After that, select Bannerlord, then name it something you can use to identify that particular mod list.
- Select the location to be a new folder inside of the Bannerlord Mod Lists folder you created, and give that folder the same name you gave the instance in the last step.
- From now on, click that same icon with the arrows making a circle to switch between your modlists.