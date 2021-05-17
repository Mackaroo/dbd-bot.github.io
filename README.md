# Mack's Dead by Daylight Discord Bot

## Table of Contents
* [Important Info](https://github.com/mackaroo/dbd-bot/blob/main/README.md#notes)
* [Commands](https://github.com/mackaroo/dbd-bot/blob/main/README.md#commands)
 * Characters
 * Add-ons
 * Emblems
 * Perks
 * Status Effects
 * Misc.


## Notes

* Do not use spaces in arguments. Replace a space with a hyphen (-) when using the bot.
* Use the Killer's game name. 
  * Michael Myers = The Shape
  * Pyramid Head = The Executioner


## Commands

### Characters

| Command  | Description                  | Example  |
|----------|------------------------------|----------|
| `.killers` | List of all playable **Killers** | `.killers` |
| `.survivors` | List of all playable **Survivors** | `.survivors` |
| `.killer {killer-name}` | Gives information about the **Killer** | `.killer trapper` |

### Add-ons

| Command  | Description                  | Example  |
|----------|------------------------------|----------|
| `.addons {item}` | Lists the Item's available **Add-ons** | `.addons toolbox` |
| `addons {killer}` | Lists the **Killer's Add-ons** | `.addons nurse` |

### Emblems

| Command | Description | Example |
|---------|-------------|---------|
| `.emblems` | Lists every **Survivor & Killer Emblem** | `.emblems` |
| `.emblem {emblem name}`| Gives the description and in-depth explanation on the specified **Emblem** | `.emblem lightbringer` |

### Perks

| Command | Description | Example |
|---------|-------------|---------|
| `.perks` | Lists every **Survivor & Killer Perk** | `.perks` |
| `.perk {perk name}` | Gives description of the specified **Perk** | `.perk iron-will` |
| `.perks {character name}` | Lists and describes the specified character's **base Perks** | `.perks dwight` `.perks legion` |
| `.hex` | Lists and describes each **Hex Perk** | `.hex` |
| `.random {s}/{k}` | Returns a random **4 Perk combo build** for Survivor (s) or Killer (k) | `.random s` `.random k` |

### Status Effects

| Command | Description | Example |
|---------|-------------|---------|
| `.status-effects` | Lists and explains all **Status Effects** seen on the in-game HUD | `.status-effects` |
| `.{status-effect}` | Describes the specified **Status Effect** in detail | `.exposed` |

### Misc.

| Command | Description | Example |
|---------|-------------|---------|
| `.hatch` | Explains when the **Hatch** will spawn during a Trial | `.hatch` |
| `.items` | Lists and describes all unlockable **Survivor Items** | `.items` |
