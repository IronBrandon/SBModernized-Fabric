# <img src="logo.png" alt="SBM Logo" style="width:31px; height: auto;"/> SBModernized

![Featured Image in SBModernized][FEATURED_IMAGE]

- - -

# Description

A modpack designed specifically for Hypixel SkyBlock on modern versions.\
Goodbye, 1.8.9, you will be missed...

The **SBModernized** mod-pack will be developed over time to be optimized, pretty, and modifiable. I will include a list below of all mods and packs that are purely visual you may disable, from most potential performance impact to least (_not everyone has a good PC_).

<details><summary>Purely Cosmetic Mods</summary>

_Note: Iris Shaders is not included as the shaders are disabled by default in-game._\
_Brackets indicate dependents of an API that can be disabled if its dependents are._

CreativeCore: _AmbientSounds_\
Forge Config API Port _Particular Reforged_\
Konkrete: _FancyMenu_\
Melody: _FancyMenu_

**High Performance Impact**
1. Sound Physics Remastered
2. Particular Reforged
3. Particle Rain

**Partial Performance Impact**
1. Cool Rain
2. Visuality
3. Essential
4. SkyCubed

**Miniscular Performance Impact**
1. AmbientSounds
2. Better Clouds
3. Chat Heads
4. FancyMenu
5. Model Gap Fix
6. Mod Menu

**High Impact Resource-Packs**: Detailed Animations, FA: Spiders, Furfsky Reborn
</details>

- - -

# How to Use

This modpack is intended to be out-of-box play, but here I'll have helpful tips and potential issues you may run into.

## Requirements

- **Memory**:
  - _[Minimum]_ 6 GB RAM (3 GB Allocated)
  - _[Recommended]_ 12 GB RAM (6 GB Allocated)
- **Storage**: 1 GB available storage

## Setup

1. Open this page in the Modrinth App or Prism Launcher and install your desired version of the pack.
2. Set allocated memory to _at least_ 2.5 GB, or use the recommended settings. Be sure to not set it too high and that third-party applications aren't taking too much of your memory (_common culprits are browsers and Discord_).
   - _Modrinth App_: `Gear Icon > Java and Memory > Memory allocated`
   - _Prism Launcher_: `Edit > Settings > Java > Memory`
   - 2560 MB Minimum Allocated
   - **6-8 GB RAM**: 3 GB Allocated
   - **12-16 GB RAM**: 6 GB Allocated
   - **24-32 GB RAM**: 8 GB Allocated
3. You can also set a custom window size or set fullscreen if desired, then start the game.
4. Before joining Hypixel, you should go to `Options > Resource Packs`, optionally enabled/disable any you like or dislike, then click `Done` to be sure all the resource packs load properly.
5. You can change some settings before starting, but to change certain settings involving UI for mods like Skyblocker, SkyHanni, etc. you must join Hypixel SkyBlock.

Now you should be ready to just play! If you are playing in a resolution other than 1920x1080 you can change the UI as you go, referring to the below tips if needed.

## Resource Packs

It's recommended that you keep all the packs as-is, but here are the purposes of some of the packs.

1. **FurfSky Reborn**, **Sophie's Enchant Books**, and **Arkudii's Detailed Skyblock** are all _highly_ recommended (_if you have poor performance, please try disabling other visual mods or packs first_). FurfSky is one of the largest SkyBlock item resource packs with textures for almost every custom item in SkyBlock. Sophie's Enchant Books help distinguish enchantment books' textures, making organization much easier. Arkudii's Detailed Skyblock is smaller, but adds some additional improvements to the environments that I believe will be well appreciated.
2. **FreshAnimations** and its add-ons are for more lively mob animations. Pretty well optimized and should work fine in most situations. This is purely preference.
3. **Detailed Animations** has beautiful player animations, which also apply to NPCs and some enemies. Not as optimized as other packs, disable if needed.
4. **Crops & Foliage Variations** is for prettier crops. May have a performance hit on the garden or farm, but it seems to be well optimized.
5. **Serified Font** is another preference thing. Has no performance impact and functions perfectly in all the UIs, and to some may look a lot better than Vanilla.

Try to keep the resource packs in their default order.

## Visuals & Audio

**Resolution**\
Because SBModernized was made for 1920x1080 monitors and optimized for my mid-level PC, other resolutions and PCs may need many changes to the HUD and graphics settings.\
There will be screenshots of different areas of the game with notes on which parts of the HUD are from what mods.

**Shaders**\
They work with a good PC; not high-end level but better than most.\
If the shaders don't run well for you, I recommend primarily playing with them off, then toggling the shaders with K when you want some nicer scenery while Fishing, Foraging, or Hunting.

**Clouds**\
For optimization, clouds are disabled on all the default shaders and we instead use Better Clouds, which still look good without being taxing on performance.

**Sound Physics**\
One included mod, Sound Physics, will not be for everyone. Set Friendly Mob and Hostile Mob sounds to 40%, then disable Sound Physics if you don't like the audio (_you can do this in the config or in the modrinth content menu_).

## User-Interface

**SkyHanni**: Use key Backslash in-game to modify some of the hud. This will likely need lots of editing if you use a resolution other than 1920x1080. It's UI includes the Custom Scoreboard, Sacks value display, location pathing, and more.

**SkyBlocker**: Use command `/widget` to modify SkyBlocker's Tablist widgets and some of its hud. Also `/skyblocker` for several other options, including `/skyblocker bars` for customizing the bars above the hotbar.

**SkyCubed**: Use command `/skycubed` to access SkyCubed's settings. You can also drag its map and info display (_box with current time_) by opening chat.

## Controls

**Common Keybinds**: Go to `Options > Controls > Key Binds` then use the search bar to find specific binds or browse all.

**SkyBlocker Shortcuts**: Use command `/skyblocker shortcuts` then scroll down to change any keybinds you wish to, including adding or removing any (_note: press 'Esc' after setting any keybind_).

Below are some notable keybinds (_all command binds are in SkyBlocker).

- **M**: Open Map (_Skycubed_)
- **Left Alt** (hold): Show tab secondary view (_Skyblocker_)
- **C**: Equipment Menu `/equipment`
- **G**: Bags Menu `/bags`
- **H**: Hunting Box `/huntingbox`
- **B**: Booster Cookie Menu `/boostercookie`
- **U**: Wardrobe Menu `/wardrobe`
- **I**: Storage Menu `/storage`
- **P**: Pets Menu `/pets`
- **Backslash (\\)**: Modify Skyhanni HUD
- **Numpad 0**: Warp Menu `/warp`
- **Numpad Period**: Warp to Hub `/hub`

See all default keybinds in the [Default Options][KEYBINDINGS_SOURCE] config

- - -

## More Info

[Credits](credits.md)\
[License](LICENSE.md)

[KEYBINDINGS_SOURCE]: /config/defaultoptions/keybindings.txt
[FEATURED_IMAGE]: featured.png
