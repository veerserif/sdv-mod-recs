# veer's recommended Stardew Valley mods

2019-04-29: finished guide.

# Table of Contents
1. [Getting Started](#getting-started)
2. [Utilities and frameworks](#utilities)
3. [User Interface](#userinterface)
4. [Quality of Life](#qol)
5. [Specific Fixes](#smallfixes)
6. [Quality of Life+](#qolplus)

# Getting Started {#getting-started}

Make sure you're on the latest version of Stardew Valley on Steam. I highly recommend starting a new game for this; I take no responsibility if this breaks a save halfway through.

Using mods will not void achievements if done correctly. As far as I know, these mods should all work on Linux, OSX and Windows.

**I have not tested this for multiplayer**. If you want to play modded multiplayer, read the mod descriptions carefully and follow recommended instructions.

## Installing Mods

Navigate to `your install location/Stardew Valley/Mods`; if that folder isn't there, make it. Unzip whatever mod you've downloaded and move the mod's folder there. That's it, you're done.

I've noted dependencies where applicable. Assume all visual mods require Content Patcher, and assume all mods require SMAPI, unless otherwise noted.

# Utilities and frameworks {#utilities}
Mods to make all your other mods work.

**SMAPI**
*[https://smapi.io](https://smapi.io)*
The Stardew Modding API is needed to make pretty much every other mod on this list run. As of time of writing, they're getting ready to move to SMAPI 3.0 in time for the SDV 1.4 update. Most of these mods are already compatible with the upcoming version, but check with the official [SMAPI mod compatibility list](https://mods.smapi.io/) to make sure.
After running the appropriate installer file for your OS, make sure to change the Steam launch argument so it launches using the SMAPI launcher instead of the default one.

**Content Patcher**
*[https://www.nexusmods.com/stardewvalley/mods/1915](https://www.nexusmods.com/stardewvalley/mods/1915)*
Content Patcher cleverly allows mods that would otherwise overwrite game files work together, meaning you can have multiple mods modifying the same tilesheets. Also, as a user, installing Content Patcher-compatible mods now works the same as installing every other mod.
Note that this means we will only be using Content Patcher-compatible versions of visual mods.

**Farm Type Manager**
*[https://www.nexusmods.com/stardewvalley/mods/3231](https://www.nexusmods.com/stardewvalley/mods/3231)*
Allows features from different farm maps to be combined, for example enabling forageable plant spawning AND ore rock spawning on a single custom farm map. Necessary for custom farm maps.

**Stardew Hack**
*[https://www.nexusmods.com/stardewvalley/mods/3213](https://www.nexusmods.com/stardewvalley/mods/3213)*
Needed for a few mods on this list.

(opt) **SpaceCore**
*https://www.nexusmods.com/stardewvalley/mods/1348/*
We need this for the [Seed Catalogue](https://www.nexusmods.com/stardewvalley/mods/1640) mod below. If you don't want to use it, don't install this.

(opt) **Custom Music**
*https://www.nexusmods.com/stardewvalley/mods/3043*
Only used for the *very* minor mod, [Bathhouse Running Water](https://www.nexusmods.com/stardewvalley/mods/3758), which is itself only needed if you get the [Bathhouse Hot Spring](https://www.nexusmods.com/stardewvalley/mods/3110) mod. Otherwise, ignore.

# User Interface {#userinterface}
Access more info.

**UI Info Suite**
*https://www.nexusmods.com/stardewvalley/mods/1150*
Adds a lot of useful tooltips to the UI, showing:

- Today's luck
- Finer gradiations for heart levels
- More informative item tooltips, including if it's still needed for a bundle
- XP point gains and dynamic XP bar (e.g. equipping the pickaxe shows your mining XP)
- Access to the calendar and daily quest billboard from inventory menu
- Icons to indicate if animals need petting or have milk/wool for harvest
- NPC locations on map
- if Queen of Sauce is airing a recipe you don't know
- Tool upgrade icon, showing which tool and time till the upgrade is done
- Sprinkler, scarecrow, beehive and junimo hut ranges

Rolls up several QoL and UI mods into one configurable package. Absolutely critical.

**Running Late**
*https://www.nexusmods.com/stardewvalley/mods/3518*
Makes the in-game clock update every minute, rather than in ten-minute incremenets.

**24-Hour Format**
*https://www.nexusmods.com/stardewvalley/mods/2908*
Changes all in-game UI and the game clock to use 24h format.

# Quality of Life {#qol}
Smoothing over annoyances.

**Auto Animal Doors**
*https://www.nexusmods.com/stardewvalley/mods/1019*
Automates opening and closing barn and coop doors at a specified time in the date, which you can set. Will not open doors in rainy or stormy weather, and will not close doors until all animals are inside. If you go to bed before all your animals head back indoors, it'll warp them inside the barn. Rest easy!

**Automatic Gates**
*https://www.nexusmods.com/stardewvalley/mods/3109*
Automatically opens gates as you walk towards them. It does have one quirk, though: it only works on gates placed directly on the ground, not gates built on top of fences. So, put the gate down first, then extend the fence around it.

**Combat Controls**
*https://www.nexusmods.com/stardewvalley/mods/2590*
Makes it so that clicking on a tile also turns your character in the general direction of that tile. Applies to both weapons and tools, though you can change that in its config file. Also allows for auto-swing as a toggleable option.

**Fast Animations**
*https://www.nexusmods.com/stardewvalley/mods/1089*
Speeds up several animations, like geode breaking and drinking and eating. Configurable.

# Specific Fixes {#smallfixes}

Hyper-specific game fixes addressing a single problem.

**Artifact System Fixed**
*https://www.nexusmods.com/stardewvalley/mods/2761*
Changes RNG generation for rare artifacts, making seven previously-unobtainable artifacts available, makes three available from artifact dig spots as well as mining and fishing treasure chests, and generally rebalances artifact and geode rarity.

**Festival End Time Tweak**
*https://www.nexusmods.com/stardewvalley/mods/2966*
Never choose between being an antisocial but productive loner, and a festive but unproductive farmer again! Shortens festival times so they don't take up a full day, and lets you do things other than party hard then collapse into bed with a full stamina bar.

**Bee House Flower Range Fix**
*https://www.nexusmods.com/stardewvalley/mods/3013*
Tweaks beehouse range to include two additional tiles, one on the top and one at the bottom.

**Big Silos**
*https://www.nexusmods.com/stardewvalley/mods/2429*
Lets silos hold much, much more hay.

**Bigger Backpack**
*https://www.nexusmods.com/stardewvalley/mods/1845*
Adds a 36-slot backpack to Pierre's for 50,000G.

**Fixed Animal Tool Animations** (req: Stardew Hack)
*https://www.nexusmods.com/stardewvalley/mods/3215*
Stops the game from freezing you in place to finish the milking/shearing information when your animal wanders off halfway.

**Fixed Secret Woods Debris**
*https://www.nexusmods.com/stardewvalley/mods/1941*
Small mod that allows the debris in the secret woods to change appearance with the seasons. Also adds a special triple-debris spawning event, which you can turn off.

**Help Wanted Quest Fixes**
*https://www.nexusmods.com/stardewvalley/mods/2644*
Adds more variety to the daily quest billboard, as well as restoring quest types hidden in the game's code.

**Leah Cabin Music Fix**
*https://www.nexusmods.com/stardewvalley/mods/2653*
Stops Leah's cabin music playing in the forest.

**No Seeds From Trees Fix**
*https://www.nexusmods.com/stardewvalley/mods/2947*
There's a bug where, if you level up in the middle of the day, you can no longer get seeds from trees or the ground. This fixes that.

**BJS Capsule Mod**
*https://www.nexusmods.com/stardewvalley/mods/2502*
Makes two super-ultra-mega-rare events *only* ultra-mega-rare. As in, "obtainable by more than just one person in the history of the game's release".

# Quality of Life+ {#qolplus}
Kind of a nebulous name, but these go above and beyond fixes and add new, helpful, but minor functions to the game.

**Automate**
*https://www.nexusmods.com/stardewvalley/mods/1063*
Tired of hand-feeding your twenty furnaces? Don't want to put crops into every single one of your hundred casks manually? Rejoice! For Automation is here. Pop a chest next to a crafting machine, or chain up several crafting machines with a chest, and it'll automatically pull raw materials out while depositing the finished products into the chest. You prime the machines with whatever you want, and Automation does the rest.

You can open an automation overlay with a key, default `U`. You can also configure the mod to use other objects, for example wooden paths, to act as connectors between machines and chests.

**Better Junimos**
*https://www.nexusmods.com/stardewvalley/mods/2221*
This adds all kinds of functions, like having junimos fertilize and plant your fields if you put fertilizer or seeds in their huts, and making their work radii larger or smaller. But the two most important features are:

* gives junimos little leaf umbrellas when it rains
* lets you actually pay junimos for their labour

Honestly I don't know why you *wouldn't* install this mod for those two things.

**Chests Anywhere**
*https://www.nexusmods.com/stardewvalley/mods/518*
Lets you access chests, the fridge, the shipping bin, and jumimo huts from a menu (default keybind `B`). Highly customizable, which you can do by editing `config.json` inside its folder. [PathosChild has written out what each variable does.](https://github.com/Pathoschild/StardewMods/tree/stable/ChestsAnywhere#configuration) I play with the "Balanced" version, which lets you access chests only in your general area, and does not allow chest access when you're in the mines.

**Remote Fridge Storage**
*https://www.nexusmods.com/stardewvalley/mods/2545*
Lets you use cooking ingredients from specially marked chests (click the fridge icon in the left side tabs) in addition to your fridge. Compatible with Chests Anywhere.

**Kisekae**
*https://www.nexusmods.com/stardewvalley/mods/2348* || [Unofficial update required.](https://community.playstarbound.com/threads/updating-mods-for-stardew-valley-1-3.142524/page-62#post-3330027)
Replaced the old Get Dressed mod. Lets you change your character's appearance at any time. You can also save up to six outfits and switch between them.
You can change appearance in three ways: by paying the wizard 500G after reaching 4 hearts with him, by using the dresser in your house, or by opening the Kisekae menu (default keybind `C`). You can change the keybind in `config.json`, as well as a variable that allows you to swap gender in the Kisekae menu.

**Better Hay**
*https://www.nexusmods.com/stardewvalley/mods/1430*
Lets you collect hay even if your silos are full, or if you have no silos. Also lets you pull hay from the hopper even if every animal feed bin is full. Useful, if you don't want to wait until your first silo to start clearing grass. You can also configure it to have a chance to drop grass starter instead of hay.

**Time Multiplier**
*https://www.nexusmods.com/stardewvalley/mods/2262*
Lets you adjust the flow of time. Want each ten-minute in-game increment (by default, 7 seconds) to be faster? Slower? Up to you. This is done via the SMAPI console, using the commands `time_multiplier_toggle` to enable/disable the time multiplier, and `time_multiplier_change <value>` to set the time multiplier to `<value>`. The author recommends a value between 0.5 and 1.5.

**Time Freeze**
*https://www.nexusmods.com/stardewvalley/mods/973*
Freezes time while indoors.

**Rented Tools**
*https://www.nexusmods.com/stardewvalley/mods/1307*
Lets you rent the basic version of the tool you're upgrading from Clint, for 200G. This way, you'll at least be able to water your crops when you inevitably forget it's still at the blacksmith's.

# Gameplay changes
# Visual/design changes
# New content
## Farm layouts
## New areas
# Cool Things I Haven't Tested
These mods look super cool but I haven't tried them... yet.

**Dynamic Night Time**
*https://www.nexusmods.com/stardewvalley/mods/2072*
Changes sunrise and sunset in-game to match your actual sunrise and sunset, depending on your latitude. These times will vary by season. It also lets you optionally configure nights to be darker.

**Campfire Cooking**
*https://www.nexusmods.com/stardewvalley/mods/2297* || [Unofficial update required.](https://community.playstarbound.com/threads/updating-mods-for-stardew-valley-1-3.142524/page-54#post-3324188)
As the mod says, "embarassed" by the fact that you apparently can't cook until you upgrade your house? No more. Lets you cook using the fireplace in your starter home, or on any campfire or brazier. Note that the key to open the cooking menu is `X` (controllers) or `RMB`, and cannot be rebound.
