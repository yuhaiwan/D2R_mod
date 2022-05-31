# How To Mod Diablo 2 Resurrected

This repository contains tools and guides relevant to modding Diablo 2 Resurrected.

## Video Guides

There are accompanying YouTube videos about modding Diablo 2 Resurrected, which can be found here:

### General Diablo 2 Resurrected Modding

#### Relevant Guides
**How to Mod Diablo 2 Resurrected:**

[![How To Mod Diablo 2 Resurrected](https://img.youtube.com/vi/RMquP82QHGw/0.jpg)](https://www.youtube.com/watch?v=RMquP82QHGw)

The above video shows the basics of modding Diablo 2 Resurrected. It goes over tools like CascView (for extracting the Diablo 2 Resurrected data directories), using `-direct -txt` to read modified files, and showing this all in action by making a quill rat drop the Manald Heal unique.

**Fastest Way To Mod Diablo 2 Resurrected:**

[![Fastest Way To Mod Diablo 2 Resurrected](https://img.youtube.com/vi/lZTTq7MXZ5w/0.jpg)](https://www.youtube.com/watch?v=lZTTq7MXZ5w)

Above is the most relevant video on modding D2R. It shows how to use a mod folder to only load the modified Diablo 2 Resurrected files, instead of having to extract all 40GB of data. This uses the `-mod {modname} -txt` command to load modified files from the `mods/{modname}/{modname}.mpq` directory. It is the easiest and fastest way to use Diablo 2 Resurrected mods.

#### Specific Guides
**D2R Drop Rates Explained**

[![D2R Drop Rates Explained](https://img.youtube.com/vi/sGLcnrZLAJg/0.jpg)](https://www.youtube.com/watch?v=sGLcnrZLAJg)

This video looks at Diablo 2 Resurrected's drop rates, and what calculations are done when a monster drops an item. We use an excel spreadsheet to calculate the chance for Baal in Hell to drop Tyrael's Might, and examine how we can change the data files in order to make Tyrael's Might drop more frequently. We look at things like effective magic find, players X, drop ratios, item types, rarity, treasure classes, etc.

The excel spreadsheet can be found [here](TyraelsMight.xlsx).

**Creating New Items and Sets in Diablo 2 Resurrected:**

[![Creating New Items and Sets in Diablo 2 Resurrected](https://img.youtube.com/vi/Gtq-AuOMFBc/0.jpg)](https://www.youtube.com/watch?v=Gtq-AuOMFBc)

This video looks at how to add new weapons and armour to Diablo 2 Resurrected, and how to use these new items in a set. For this D2R mod, we'll add a Noble Sword and Noble Armour, and then create the King's Allies set from this new equipment.

The modded files shown in this video can be found in this repository, under [this folder](mods/newitems.mpq).

**Modding New Set and Unique Item Sprites**

[![Modding New Set and Unique Item Sprites](https://img.youtube.com/vi/y-yDdxPFsJY/0.jpg)](https://www.youtube.com/watch?v=y-yDdxPFsJY)

This video looks at how to add unique and set item graphics (sprites) to Diablo 2 Resurrected. It builds off the previous video on modding in new weapons and armour into Diablo 2 Resurrected, and adding those items to a new set. For this D2R mod, we'll modify the King's Sword set item inventory graphics (sprites), making it really stand out.

The modded files shown in this video can be found in this repository, under [this folder](mods/newitems2.mpq).

**New Runes and Runewords:**

[![New Runes and Runewords | D2R Modding](https://img.youtube.com/vi/brOSBpiwejA/0.jpg)](https://www.youtube.com/watch?v=brOSBpiwejA)

This video looks at how to add new runes and runewords to Diablo 2 Resurrected. This also includes looking at all the unimplemented runewords in Diablo 2 Resurrected, and how the game can be modded to add those runewords back in. For this D2R mod, we'll create the Fus Ro Dah runes, and from those new runes, create the Dragonborn runeword! It's time to bring Skyrim to Diablo 2 Resurrected!

The modded files shown in this video can be found in this repository, under [this folder](mods/runes.mpq).

**Changing Item Colors:**

[![Changing Colors in Diablo 2 Resurrected](https://img.youtube.com/vi/zryNy2wfoO4/0.jpg)](https://www.youtube.com/watch?v=zryNy2wfoO4)

This video looks at how to change the color of item names, classes of items, and more in Diablo 2 Resurrected. We look at the color codes (ÿc codes), as well as the various JSON files which control all the colors across Diablo 2 Resurrected. We create a new Rainbow Sword unique weapon, and set its colors to those of an actual rainbow. We also change the color of unique items to a better gold, change the color of socketed items to aqua, and change the color of health, mana and rejuvination potions.

The modded files shown in this video can be found in this repository, under [this folder](mods/colours.mpq).

#### Older/Outdated Guides
**How To Package Diablo 2 Resurrected Mods:**

[![How To Package Diablo 2 Resurrected Mods](https://img.youtube.com/vi/tLMppJOOO0o/0.jpg)](https://www.youtube.com/watch?v=tLMppJOOO0o)

This video is outdated, and you should instead use the video above about the fastest way to mod Diablo 2 Resurrected. This guide went over using MPQ files to package and load the D2R mod, but this still relied on generating .bin files, which meant that `-direct -txt` still needed to be used. As a result, you needed to have the full data directory (40GB) extracted.

### Non-Tutorial Videos
**Will I Get Banned For Modding Diablo 2 Resurrected:**

[![Will I Get Banned For Modding Diablo 2 Resurrected](https://img.youtube.com/vi/Evvkz2AiWWg/0.jpg)](https://www.youtube.com/watch?v=Evvkz2AiWWg)

This video explores whether modding Diablo 2 Resurrected is likely to get you banned by Blizzard. Unfortunately, Blizzard has not issued any comments on the matter, so it is safest to only play offline with your D2R mods.

## Text Guide

TODO

## Tools

1. [SpriteEdit](https://github.com/eezstreet/D2RModding-SpriteEdit/releases)

## Links

1. [How To Mod Diablo 2 Resurrected GitHub Repository](https://github.com/HighTechLowIQ/ModdingDiablo2Resurrected)
2. [How To Mod Diablo 2 Resurrected - YouTube Video](https://www.youtube.com/watch?v=RMquP82QHGw)
3. [Importing Old Characters into Diablo 2 Resurrected - YouTube Video](https://www.youtube.com/watch?v=VqSrUiq1eQo)
4. [How To Package Diablo 2 Resurrected Mods - YouTube Video](https://www.youtube.com/watch?v=tLMppJOOO0o)
5. [Will I Get Banned For Modding Diablo 2 Resurrected - YouTube Video](https://www.youtube.com/watch?v=Evvkz2AiWWg)
6. [Fastest Way To Mod Diablo 2 Resurrected - YouTube Video](https://www.youtube.com/watch?v=lZTTq7MXZ5w)
7. [Creating New Items and Sets in Diablo 2 Resurrected - YouTube Video](https://www.youtube.com/watch?v=Gtq-AuOMFBc)
8. [Modding New Set and Unique Item Sprites | Diablo 2 Resurrected - YouTube Video](https://www.youtube.com/watch?v=y-yDdxPFsJY)
9. [New Runes and Runewords | D2R Modding - YouTube Video](https://www.youtube.com/watch?v=brOSBpiwejA)
10. [Changing Colors in Diablo 2 Resurrected | D2R Modding - YouTube Video](https://www.youtube.com/watch?v=zryNy2wfoO4)
11. [D2R Drop Rates Explained - YouTube Video](https://www.youtube.com/watch?v=sGLcnrZLAJg)
