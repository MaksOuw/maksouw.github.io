# Super Mario Odyssey - Practice Mod

A simple guide to explain how to install the practice mod, how to uninstall it, and how to use it.

In this guide, I will assume that you know how to use a computer, how to use a FTP client, and all of the pre requisites other than SMO Practice Mod are already installed and ready to use.

## Installation
### Pre requisites
- A hacked switch
- Super Mario Odyssey v1.3.0 (the mod can work on SMO 1.0.0 but I did not tried it)
- A FTP client on your computer / phone
- [Simple Mod Manager](https://github.com/nadrino/SimpleModManager) by Nadrino
- [ftpd](https://github.com/mtheall/ftpd) by Mtheall
- [smo-practice](https://github.com/Tischel/smo-practice) by Fruityloops1, enhanced by MonsterDruide1 / Ontwikseltsaar / Tischel

### Installation
Before any installation, you have to remove the SMO mod folder if you already tried to install another version of the mod : 
- Delete `/atmosphere/contents/0100000000010000` folder
- Delete `/atmosphere/exefs_patch/practice-mod` folder

And then, install the mod : 
- Get the last release of [smo-practice](https://github.com/Tischel/smo-practice) [here](https://github.com/Tischel/smo-practice/releases) (1.0.1 at the moment of writing this guide). You should have a `atmosphere.zip` file
- Extract the content of `atmosphere.zip` file on your computer  
(!) macOS users, be careful : when extracting, macOS adds shitty hidden `.DS_Store` files. You need to remove them, otherwise the game will not launch after enabling the mod (!)  
- Launch [ftpd](https://github.com/mtheall/ftpd) on your Switch
- Connect to your switch with your FTP client
- Send the `atmosphere` folder content to `/mods/Super Mario Odyssey/Practice` (create every folders if they does not exists) on the SD card
- Disconnect the FTP from your client
- Stop ftpd on your switch

## Usage
### Pre requisites
- A save file where **Cascade Kingdom** is ended (the Odyssey was activated and you went to **Sand Kingdom**)
- Disabling the "Show map" with Up D-Pad control in Super Mario Odyssey's options

### Enabling / disabling the mod
- Launch [Simple Mod Manager](https://github.com/nadrino/SimpleModManager) on your switch
- Search for the "Super Mario Odyssey" entry, press A
- You should have a "Practice" mod listed. To **enable** it, **press A**. To **disable** it, **press X**

### Commands

|Control|Mod menu status|Description|
|-----|-----|-----|
|<img src="https://static-00.iconduck.com/assets.00/alpha-l-box-icon-512x512-1k4kb0sh.png" style="width: 32px; height:32px;"/> + <img src="https://static-00.iconduck.com/assets.00/dpad-left001-icon-512x512-8kmssg05.png" style="width: 32px; height: 32px;"/>|x|Show / hide mod menu|
|<img src="https://static-00.iconduck.com/assets.00/alpha-l-box-icon-512x512-1k4kb0sh.png" style="width: 32px; height:32px;"/> + <img src="https://static-00.iconduck.com/assets.00/dpad-right001-icon-512x512-xjm58nfu.png" style="width: 32px; height: 32px;"/>|x|Enable / disable the mod|
|<img src="img/dpad.png" style="width: 32px; height: 32px;"/>|Displayed|Navigate through the mod menus and options|
|<img src="https://static-00.iconduck.com/assets.00/dpad-right001-icon-512x512-xjm58nfu.png" style="width: 32px; height: 32px;"/>|Displayed|Validate / change the choice of an option|
|<img src="https://static-00.iconduck.com/assets.00/dpad-left001-icon-512x512-8kmssg05.png" style="width: 32px; height: 32px;"/>|Hidden|Save Mario's current position|
|<img src="https://static-00.iconduck.com/assets.00/dpad-right001-icon-512x512-xjm58nfu.png" style="width: 32px; height: 32px;"/>|Hidden|Teleport Mario to previously saved position|
|<img src="https://static-00.iconduck.com/assets.00/dpad-up001-icon-512x512-iwiq9qii.png" style="width: 32px; height: 32px;"/>|Hidden|Reload current scene / Kill Mario (depends on which options is enabled, by default it's "Reload current scene")|
|<img src="https://static-00.iconduck.com/assets.00/dpad-down001-icon-512x512-wclbenmb.png" style="width: 32px; height: 32px;"/>|Hidden|???|

### Options

|Name|Enabled by default|Description|
|-----|-----|-----|
|Should Render|Yes|???|
|Teleport|Yes|Allow save position / teleport to position for Mario|
|Moon Refresh|Yes|Allow to get an already taken moon which is not taken in the save|
|Gray Moon Refresh|Yes|Allow to get an already taken moon which is taken in the save|
|Always Enable Warps|Yes|???|
|Disable Autosaving|Yes|Disable the autosaving feature. The game will not erase automatically the save when taking a moon|
|Cloud Kingdom Bowser Skip|No|Skip the first Bowser fight in Cloud Kingdom|
|Disable Teleport Puppet|No|???|
|D-Pad Up: Kill Mario|No|Kill Mario when pressing D-Pad Up|
|D-Pad Up: Reload Scene|Yes|Reload the current scene (usually, the current kingdom)|

### Stages

|Name|Corresponding Kingdom|
|-----|-----|
|CapWorldHomeStage|Cap Kingdom|
|WaterfallWorldHomeStage|Cascade Kingdom|
|SandWorldHomeStage|Sand Kingdom|
|LakeWorldHomeStage|Lake Kingdom|
|ForestWorldHomeStage|Wooded Kingdom|
|CloudWorldHomeStage|Cloud Kingdom|
|ClashHomeStage|Lost Kingdom|
|CityWorldHomeStage|Metro Kingdom|
|SnowWorldHomeStage|Snow Kingdom|
|SeaWorldHomeStage|Seaside Kingdom|
|LavaWorldHomeStage|Luncheon Kingdom|
|BossRaidWorldHomeStage|Ruined Kingdom|
|SkyWorldHomeStage|Bowser's Kingdom|
|MoonWorldHomeStage|Moon Kingdom|
|PeachWorldHomeStage|Mushroom Kingdom|
|Special1WorldHomeStage|Dark Side of the Moon Kingdom|
|Special2WorldHomeStage|Darker Side of the Moon Kingdom|
|MoonWorldBasementStage|Escape (Bowser's control)|
|MoonWorldKoopa1Stage|Bowser Moon Fight|
|MoonWorldKoopa2Stage|Bowser Moon Fight (harder)|

Every other stages available are sub-stages of kingdoms, try them if you want

### Miscellaneous
I will not describe every miscellaneous possibilities, since they are quite obvious.

|Name|Description|
|-----|-----|
|Gravity|Change the world's gravity|
|Wiggler Pattern|Select a specific MechaWiggler pattern (or let it random)|

Be careful, when you want to select a specific MechaWiggler pattern, you have to use D-Pad Left, since the selector is on "Reload scene" and "Wiggler Pattern" at the same moment.

### Modes

|Name|Description|
|-----|-----|
|isModeDiverOrJungleGymRom|Hide HUD and mod menu|
|isModeDiverRom|???|
|isModeJungleGymRom|???|
|isModeE3LiveRom|???|
|isModeE3MovieRom|Hide HUD and mod menu|
|isModeEpdMovieRom|???|

## Known bugs

Generally, story moons provoke bugs, so be careful.  

- Bowser's Kingdom :
	- 1st story moon has no cinematic
	- If you die after the 1st story moon, even if you re-take this story moon, you won't be able to get past it : the bridge does not deploy and the gates does not open anymore. If you have a teleportation point after this moon, you'll be able to continue but you won't have to take the moon shards, the moon is already waiting for you.
