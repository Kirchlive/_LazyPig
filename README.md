# _LazyPig Fork Update
**by Tetto/Kirchlive**

Forked from the original **_LazyPig** by Ogrisch, mrmr, Lexie and TrumpetX.
Updated for [Turtle WoW](https://turtle-wow.org/) with new features and bug fixes.

> `## Interface: 11200` | Vanilla WoW 1.12

## New in v6.2.0-K40

- **Tower of Karazhan Roll Automation** — auto roll all items in Kara40 (Need/Greed/Pass) with Exclude Epics option
- **Green Items Roll [Ctrl+Alt]** — removed from "Special Key Combinations", now Enable/Disable directly via checkboxes
- **pfUI Bugfix** — Green Items Roll [Ctrl+Alt] now works with pfUI loot frames

![Cursive Raid Preview](https://i.imgur.com/AqddZgH.png)

## Features

### Passive Enhancements
| Feature | Description |
|---------|-------------|
| Auto Dismount | When casting spell or interacting with flightmaster (AQ40 mounts included) |
| Auto Roll Automation | ZG, MC, AQ, Black Morass, Emerald Sanctum, Naxxramas, **Tower of Karazhan** |
| Loot Window Auto Position | Under the cursor when looting |
| Gossip Auto Processing | When talking to NPC (taxi, battlemaster, innkeeper, vendors) |
| World Chat Mute | Mute /world channel in raid/dungeon/bg zone, filter repeated messages |
| Improved Right Click | Right click on container item to drag into trade/auction/mail window |

### Active Enhancements (require modifier key press)
| Feature | Key | Description |
|---------|-----|-------------|
| Green Items Roll | Ctrl+Alt | Roll on green items (works independently, no Special Key Combinations needed) |
| Stack Split/Merge | Shift+Right Click | Split stacked items |
| Grey Sell/Repair | Alt (at merchant) | Sell grey items and repair |
| Repeatable Quests | Alt (at NPC) | Auto-complete token quests (AD, ZG, BG marks) |

### Minor Enhancements
| Feature | Description |
|---------|-------------|
| Group Auto Accept | 3 modes: Guildmates, Friends, Everyone |
| Summon Auto Accept | Accept 2 seconds before confirm expires |
| Instance Resurrection | Auto accept OOC in raids/dungeons/BGs |
| Extended Camera Distance | Increase max camera distance up to 50y |
| Duel Auto Decline | Hold Shift to bypass |
| Auto Stance | Auto change warrior stance/druid form on spell cast |

### Special Key Combinations (enable separately in `/lp` > Miscellaneous)
| Keys | Action |
|------|--------|
| Alt+Ctrl+Shift | Logout |
| Ctrl+Shift | Follow target |
| Alt+Shift | Inspect player / Bid auction |
| Alt+Ctrl | Trade / Confirm popups / Mail / Auction buttons |

---

## Installation

1. Download or clone this repository
2. Copy the `_LazyPig` folder into `Interface/AddOns/`
3. Type `/lp` in-game to configure

---

## Configuration

Type `/lp` or `/lazypig` to open the options window. Most features can be toggled individually.

---

## Changelog

### v6.2.0-K40 (Kirchlive Fork)
- Added Tower of Karazhan Roll Automation (auto roll all items in Kara40)
- Fixed Green Items Roll [Ctrl+Alt] — removed from "Special Key Combinations", activates directly via checkbox
- Fixed Green Items Roll [Ctrl+Alt] — pfUI compatibility (detects pfLootRollFrame)
- Increased options window height for new menu entries

### v5.01
- Added auto mana buff remover (Intellect, Spirit, Wisdom)

### v5.00
- Block Battleground Quest Share feature
- Brand New GUI by mrmr

### v4.56
- Minor fixes, resurrection auto accept only in instances

### v4.52
- Added find WSG EFC binding
- Improved repeatable quests for WSG and Arathi

### v4.50
- Added drop WSG Flag binding

### v4.40
- Added keybindings, spam filter, salvation remover

### v4.00
- Added GUI (`/lp`)

### v3.50
- Improved split mechanism

### v3.0
- Added "Mute World" chat functionality

### v2.88
- Added Alt+Ctrl green roll key combinations

### v2.7
- New key combinations, improved right click, auto repair

### v2.5
- Fixed dismounting with 16+ buffs, BG quest fixes

### v2.3
- Grey sell, thorium shells automation, auto queue BG

### v1.9
- Auto roll for ZG bijous and coins

### v1.8
- Stack split feature

### v1.7
- Record/replay for repeatable quests

---

## Credits

Original authors: **Ogrisch**, **mrmr**, **Lexie**, **TrumpetX**
Fork maintainer: **Tetto/Kirchlive**
