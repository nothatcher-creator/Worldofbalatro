<p align="center">
  <img src="docs/assets/logo.png" alt="World of Balatro" width="760">
</p>

<p align="center">
  <strong>A Warcraft-inspired RPG overhaul for Balatro by Nothatcher.</strong>
</p>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-0.17.0-c49b3c">
  <img alt="Balatro" src="https://img.shields.io/badge/Balatro-1.0.1o-8b1e1e">
  <img alt="Steamodded" src="https://img.shields.io/badge/Steamodded-BETA--1224a-315d3d">
  <img alt="Platform" src="https://img.shields.io/badge/Android-tested-4f7d40">
</p>

# World of Balatro

**World of Balatro** turns a Balatro run into a character-driven RPG adventure. Create persistent characters, choose from 13 classes, equip armor and weapons, build real RPG stats, learn class abilities, progress through campaigns and dungeons, trigger world events with Tags, and use a full Auction House system.

The visible mod name is **World of Balatro**. The internal folder and mod ID remain `AzerothBalatro` for save compatibility.

## Highlights

- **13 classes** — Warrior, Paladin, Hunter, Rogue, Priest, Death Knight, Shaman, Mage, Warlock, Monk, Druid, Demon Hunter, and Evoker.
- **Persistent characters** — up to six saved characters/runs with independent gear and progression.
- **Character paper doll** — 14 armor slots plus weapons, rings, trinkets, class art, stats, and Jokers.
- **28-slot Bag** — consumables and class abilities live in a dedicated inventory.
- **10-slot action bar** — drag shortcuts from Character or Bag without removing the original item.
- **RPG attributes** — Strength, Agility, Intellect, Stamina, Critical Strike, Haste, Mastery, and Versatility have real gameplay effects.
- **Specs and talents** — class specialization and multi-tier talent progression.
- **Class resources** — class-specific resources such as Rage, Holy Power, Combo Points, Soul Shards, Chi, Fury, Essence, and more.
- **Campaign progression** — Elwynn Forest → Westfall → The Deadmines, followed by larger dungeon progression.
- **World Event Tags** — Auction House, Treasure Chest, Wandering Merchant, Rare Patrol, Darkmoon, and Lost Adventurer.
- **Auction House** — search and sort the catalog, buy discovered items, see undiscovered items greyed out, and list your own items at custom prices.
- **Dungeons and boss loot** — named encounters, rare mobs, Heroic variants, affixes, raids, themed drops, and Mythic+ continuation.
- **Spell Book** — browse the mod's classes, Jokers, spells, equipment, items, Tags, enemies, campaign content, and stats.
- **Guided tutorial** — a first-character walkthrough that introduces the major systems and can be skipped at any time.

## Campaign

<p align="center">
  <img src="docs/assets/elwynn.png" alt="Elwynn Forest" width="31%">
  <img src="docs/assets/westfall.png" alt="Westfall" width="31%">
  <img src="docs/assets/deadmines.png" alt="The Deadmines" width="31%">
</p>

The opening adventure follows a three-chapter campaign:

**Elwynn Forest → Westfall → The Deadmines**

Each chapter changes the zone backdrop and encounter flavor. Elwynn ends with Hogger, Westfall has its own Defias chapter boss, and the Deadmines culminates in Edwin VanCleef. After the campaign, the wider dungeon and Mythic-style progression opens up.

## RPG Stats

| Stat | Gameplay effect |
|---|---|
| Strength | Adds Chips to scored hands |
| Agility | Adds scaling XMult |
| Intellect | Adds Mult |
| Stamina | Reduces Blind requirements |
| Critical Strike | Chance for a hand to critically score XMult |
| Haste | Shortens class-ability cooldown behavior |
| Mastery | Strengthens specialized scoring |
| Versatility | Adds steady XMult and defensive Blind reduction |

Gear can roll Primary Stat, Stamina, Crit, Haste, Mastery, and Versatility. Existing equipment is upgraded without throwing away its existing secondary-stat rolls.

## Auction House

The Auction House is triggered through an **Auction House Tag**.

- Browse supported items from the game and mod.
- Filter by category.
- Search by item name.
- Sort by name, rarity, or price.
- Discovered items can be purchased.
- Undiscovered items stay visible but are greyed out and unavailable.
- Market prices vary by rarity and item value.
- Sell your own gear, Jokers, weapons, or consumables at a custom asking price.
- Higher asking prices take longer to sell.
- Pending auctions are stored with the character's run.

## Character UI

<p align="center">
  <img src="docs/assets/character.png" alt="Character panel" width="42%">
  <img src="docs/assets/bag.png" alt="Bag panel" width="50%">
</p>

The RPG UI is separated from the normal Balatro playfield:

- Press **C** for Character.
- Press **B** for Bag.
- Use **1–9 and 0** for action-bar slots on keyboard.
- On mobile, tap the corresponding UI controls.

## Installation

1. Install a compatible Balatro + Steamodded setup.
2. Download the latest release.
3. Put the entire `AzerothBalatro` folder into your Steamodded `Mods` directory.
4. Keep `main.lua`, `src`, `assets`, and `azeroth_balatro.json` together.
5. Launch Balatro and confirm **World of Balatro** appears in the mod list.

Current development target:

- Balatro `1.0.1o-FULL [M]`
- Steamodded `1.0.0~BETA-1224a`
- LÖVE `11.5.0`
- Lovely `0.8.0-static`
- Android is actively tested

## GitHub Pages

A full project site is included under [`docs/`](docs/). Enable GitHub Pages for the repository and choose the `main` branch with `/docs` as the source.

## Credits

**Created by Nothatcher.**

World of Balatro is a fan-made project and is not affiliated with or endorsed by LocalThunk, Playstack, Blizzard Entertainment, or their affiliates. Balatro and Warcraft-related names and trademarks belong to their respective owners.
