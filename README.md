# Sanguine Skins for Phantom Blade Zero

The Sanguine blades on other weapons: Jagged Steel gets the Sanguine sword, Outlaw Warblade the long Sanguine blade, the White Serpent and Crimson Viper the paired Sanguine blades, each with its scabbard. Blood trails on Jagged Steel and the serpent blades, crimson trails on the Outlaw Warblade.

Main page and comments: [Nexus Mods](https://www.nexusmods.com/phantombladezero/mods/399). This repo has the same files for anyone who can't download from Nexus, plus the recipes they are built from.

## Install

Every zip holds `ProjectPBZ/Content/Paks/~mods/...`. Unpack it into the game folder (the one with `ProjectPBZ` in it) and start the game. To remove a file, delete its `.pak`, `.ucas` and `.utoc` from `~mods`.

## Files

| File | What it does | Install |
|---|---|---|
| Sanguine Skins Full | Jagged Steel and Outlaw Warblade | main file |
| Jagged Steel only | Only Jagged Steel, with blood trails | instead of Full |
| Outlaw Warblade only | Only the Outlaw Warblade, with crimson trails | instead of Full |

"Instead of Full" files use the same pak name as Full, so they replace it. Addons can go on top of any of them.

## Build it yourself

The `recipes` folder has a [Bladesmith](https://github.com/ayokiru/pbz-bladesmith) recipe for each file. Bladesmith builds the pak from your own copy of the game, so after a game patch you can rebuild instead of waiting for an update: open the recipe in Bladesmith and press Build & install, or run `bladesmith build recipes/full.json --install`.

When two paks change the same weapon, the game uses the one whose name comes first (capital letters before small ones). That is why the addons are named the way they are.
