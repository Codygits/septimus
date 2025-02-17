<a href="https://www.youtube.com/watch?v=70DZ5UV1Bdo"><img src="images/banner.webp" target="_blank"></a>

---

<p align="center">
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/58229">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CONFIGURATION.md">Configuration</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="ADDONS.md">Addons</a> ·
  <a href="HELP.md">Help</a>
</p>

---

# Configuration

- [Mod Organizer 2 Profiles](#mod-organizer-2-profiles)
- [Creation Club Setup](#creation-club-setup)
- [Alternate Start](#alternate-start)
- [Optional Tweaks](#optional-tweaks)
- [Optional Content](#optional-content)
  - [Widescreen](#widescreen)
  - [Character Presets](#character-presets)
- [Mod Configuration](#mod-configuration)
  - [MCM Menus](#mcm-menus)
- [ENB and Reshade Presets](#ENB-and-Reshade-Presets)
- [Performance Guide](#performance-guide)

## Mod Organizer 2 Profiles

Two profiles are pre-configured in MO2 for you. Septimus - Anniversary Edition and Septimus. If you do not own anniversary edition and all creation club content, play the standard Septimus profile. It contains all mods that do not require creation club integration.

Select the profile you wish to use here:

![Profiles](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/profiles.png)

## Creation Club Setup

In order to use Creation Club content, Mod Organizer 2 will need a copy of the creation club mod files.

- Launch the game from steam and allow all creation club content to download
- Activate the Anniversary Edition profile in Mod Organizer 2 at the top of the window
- Right click `[NoDelete] Official Creation Club - Paid` at the top of the mod list and hit open in explorer
- Copy all files from Skyrim Special Edition/data beginning with "cc" (example: ccvsvsse004-beafarmer.bsa) into the opened folder
- Ensure that all creation club content is activated in the "Plugins" tab on the right of mod organizer 2 and moved to the top of the load order
- If it is not all activated and sent to the top, shift click to select all, right click and hit enable selected, and then right click and hit send to -> top

When you have setup Creation Club content correctly, your Septimus MO2 will look like this:

![CC Top](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/ccenabled_top.png)

## Optional Tweaks

When enabling any optional tweaks, make sure they are always loaded BEFORE realisticwatertwo.esp in your load order. See the alternate start section for an example of this.

## Optional Content
**As a warning. The optional content has not been tested nearly as heavily as the rest of the list as not everyone has it enabled. Support will be limited if you enable any of the optional content as its more difficult to account for them. If you are at all worried about stability, do NOT enable any.**

### Widescreen

I have included the necessary mods to enable widescreen UI support. If you play on a widescreen monitor, this can be enabled in the optional mods section.

![Widescreen](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/widescreen.png)

### Character Presets

Septimus includes mod that contains a few character presets, and you can also copy presets you download from the [Septimus Character Presets Discord thread](https://discord.com/channels/773659452392865792/952965520083275796) to load when creating new characters. 

The presets mod is here:

![septimus-character-presets](https://user-images.githubusercontent.com/508163/159598073-ee99e599-2f5a-4ce3-93d3-169233858689.png)

You can select this mod, right-click it, and then select "Open in Explorer" to see the presets directory, which will be at this location:

```
Septimus\mods[NoDelete] Character Presets\SKSE\Plugins\CharGen\Presets
```

### General Rules
When enabling this content, just like with alternate start mods, ensure all mod esp files are just above realisticwatertwo.esp in your load order and if there is a Septimus patch for them, load that after the mod's esp and above all other Septimus patches. This applies for any optional content not specifically mentioned here. For content with its own section, follow the appropriate readme section for it.

### Legacy of the Dragonborn
"I HATE Legacy of the Dragonborn, PLEASE remove it". 

Don't worry. I've thought of this already. Simply uncheck all mods in the `Optional LOTD` separator in MO2 before starting your game.

## Mod Configuration

### MCM Menus

All MCM menus have been automated so you are good to ignore them unless you want to change anything.

## ENB and Reshade Presets

> :ledger: You should only ever enable exactly one preset (regardless of whether it is an ENB or Reshade). You should never enable both an ENB and Reshade preset at the same time.

Septimus includes an awesome tool called ENB Organizer for trying out different ENB and Reshade presets.

To change ENB & Reshade presets, do the following:

- Run ENB Organizer from the exe list in the top right of MO2
- If the program warns about not being able to check for updates, simply click ok and ignore it

![Exe List](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/exe_menu.png)

- Go to presets on the left menu and enable the enb preset you wish to use. Be sure to only enable one preset at a time. The safest way is to disable them all and then simply activate one preset. Mixing presets (including mixing ENB and Reshade presets) will not work.

![Enb Organizer](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/enb_enable.png)

- Very low spec users may want to switch to Cathedral Reshade instead of ENB for extra performance

## Performance Guide

- Try turning off any ENB that might be enabled and switching to the ultra lite reshade preset
- Activate the performance grass and dyndolod mods under Septimus - Performance Mode
- Copy the files from one of the presets in Septimus/Performance Options to the profile you're using and overwrite (Septimus/profiles/Septimus [- Anniversary Edition])

![Perf Options](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/perf_options.png)
![Perf Options 2](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/perf_options2.png)
![Perf Options 3](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/perf_options3.png)
- Double click on `SSE Display Tweaks - Septimus Settings` under `Essentials` and set the resolution to match your monitor resolution and remove the # at the beginning of the line
