This page addresses mod-specific keybinds, how to use your in-game PDA, and how to interpret G.A.M.M.A.'s HUD system.

# Keybinds

[<img src="https://cdn.discordapp.com/attachments/914216733810761798/936956601296883792/GAMMA_keymap.png" alt="An image showing keybinds for G.A.M.M.A. overlaid on a QWERTY keyboard." width="800"/>](https://cdn.discordapp.com/attachments/914216733810761798/936956601296883792/GAMMA_keymap.png)

*Click through for full size. Image from Discord, #keybinds-in-gamma channel. Image from Jan 29, 2022 and may be out of date.*

## Anomaly/S.T.A.L.K.E.R. default binds
All of these keybinds can be changed in `Settings > Controls > Keybinds`. Mouse scroll wheel cannot be bound.

| Key | Action |
|-----|--------|
| W/A/S/D | Movement |
| Q/E | Lean left/right |
| F | Interact |
| Space | Jump |
| Left Shift | Walk/low crouch; transfer items in inventory/trade screen |
| X | Sprint |
| Left Ctrl | Crouch |
| Tab | Open PDA |
| Caps Lock | Detector |
| Left mouse button | Shoot/Attack |
| Right mouse button | Aim |
| Middle mouse button | Quick melee |
| Mouse 4 | Free look |
| 1 | Weapon (melee slot) |
| 2 | Weapon (secondary slot) |
| 3 | Weapon (primary slot) |
| 4 | Weapon (vision slot) |
| 5 | Bolt |
| 6 | Switch scope |
| 7 | Switch silencer | 
| 8 | Geiger counter |
| F1-F4 | Item quick use (see inventory) |
| F5 | Quicksave |
| F9 | Quickload |
| R | Reload, unjam, close PDA |
| T | Clean gas mask |
| Y | Ammo selection |
| U | Unload all guns |
| G | Grenade quick-throw |
| L | Flashlight on/off |
| L (hold) | Weapon laser on/off |
| V | Underbarrel grenade launcher/secondary scope toggle |
| C | Companion wheel |
| J | Teleport companions
| I | Inventory |
| K | Skills menu |
| H | Cycle body health HUD |
| Home | Reshade menu | 
| Esc | Game menu |
| Numpad Enter| HUD toggle |
| Numpad 0 (debug mode on) | Noclip toggle
| ` | Open console |
| F12 | Take screenshot |

n.b. If the mod "G.A.M.M.A. Unjam Reload on the same key" is disabled, `R` is the default keybind for unjam while `F10` becomes the default reload key.

### Movement and control specifics

In the game, you are encourage to use cover by being able to crouch, low-crouch (similar to going prone in other games), and lean. Additionally, you can walk slowly by holding the Walk button while moving or crouching while moving - this allows players to engage in some level of stealth gameplay, avoiding detection or enabling stealthier kills. 

## Mod-specific keybinds
These can be changed in-game by going to the Mod Configuration Menu (MCM), and either selecting the MCM Keybinds tab, or finding the specific mod and changing it through that menu.

| Key | Mod | Action |
|---|---|---|
| Mouse 5 | Free Zoom | Zoom in |
| / | Mini Map Toggle | Minimap toggle |
| Z | Patches by Hotkey | Remove/add faction patch |
| , | Weapon Tilt | Raise/tilt weapon (disabled by default) |
| Shift + F | Ammo Check | Check ammo in current magazine |
| Shift + F5 | YACS | Use Daddy Token (quicksave away from campfire) |

Ammo Check requires both it and Mags Redux to be activated to work.

# Heads-Up Display

[<img src="https://github.com/cwylo/GAMMA-manual/blob/main/images/hud-1-annotated.jpg" alt="Heads-up display for G.A.M.M.A., annotated for commentary." width="800"/>](https://github.com/cwylo/GAMMA-manual/blob/main/images/hud-1-annotated.jpg)

The heads-up display consists of four main elements. 

## 1 Minimap

This is disabled by default, but can be toggled on or off through the Mini Map Toggle mod (default keybind: `/`). When on, it shows a minimap, which is always centered on the player and rotates depending on the direction the player is looking. There is a ring around the player showing compass directions, with N in green, E in yellow, S in red and W in blue. If available, a red arrow will point in the direction of the currently active task waypoint.

## 2 Message log

This can also be accessed through the "Messages" tab in the PDA. This is a scrolling feed of activities in the Zone, whether from other stalkers, or warnings and quest updates. Crucially, warnings to seek shelter or stay sheltered from psy-storms and emissions will be displayed here.

## 3 Body HUD
The Body HUD is part of the [health system](Health). It displays the player's psy-health, regular health (the paper-doll of the whole body), limb health, radiation and stamina. It can be cycled through three presets: labelled, unlabelled and off. 

## 4 Icons

G.A.M.M.A. uses Strogglet15's [Alternative Icons](https://www.moddb.com/mods/stalker-anomaly/addons/alticons). These icons inform players of current status effects. In order of low to high severity, icons will have a white, yellow or red border on them. Icons include:

[<img src="https://github.com/cwylo/GAMMA-manual/blob/main/images/alt-icons-2.jpg" alt="An image explaining Strogglet15's Alternative Icons pack, option 2.">](https://www.moddb.com/mods/stalker-anomaly/addons/alticons)

* **Status** icons are always in white with a bold shadow, with colored corners depending on severity. **If you can see any of them**, it is time to address that particular need - whether it is radiation, thirst, hunger, sleep or health.
* **Buff** icons mean some kind of positive effect is happening. Buff icons are outlined in white with no fill. From left to right in order, they indicate health regen, bleed halting, lowering radiation, carry weight boost and stamina boost.
* **Boosters** are temporary damage resistances. They are always displayed against a solid black shield. From left to right the pictured boosters are for radiation resistance, acid resistance, and psy-resistance. Other forms include bullet/rupture damage (torso icon), impact damage (brick wall), fire resistance (flame), and electricity resistance (lightning bolt). These correspond to the icons found in the [inventory screen](Inventory and PDA).
