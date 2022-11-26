# Final Fantasy X Cheat Sheet

To view the cheat sheet [click here](https://drunktraveler.github.io/).

This checklist was created by adopting the source code from the [Dark Souls 2 Cheat Sheet](https://github.com/smcnabb/dark-souls-2-cheat-sheet/tree/gh-pages) created by [Stephen McNabb](https://github.com/smcnabb) and [Dark Souls 3 Cheat Sheet](https://https://github.com/ZKjellberg/dark-souls-3-cheat-sheet).

The walkthrough is thanks to [FFX FAQ/Walkthrough (PS3) by KeyBlade999](https://gamefaqs.gamespot.com/ps3/643146-final-fantasy-x-x-2-hd-remaster/faqs/69037) and [finalcraft](http://www.finalcraft.com/final-fantasy-x/komplettloesung/) as well as [Dansg08 video series](https://www.youtube.com/watch?v=03HaLMNJWWk&list=PL9wpzJw8GKy74rLqQv7OH9v94Hj8qQWps&index=1).

## Contribution Guide

If you are interested in contributing to this guide, I welcome Pull Requests.

For some background on how the guide code is written, here is a sample item on the checklist:

```
<li data-id="playthrough_13_20" class="f_gem f_misc">Continue left until you can enter a room with a Large Soul of a Nameless Soldier and a Raw Gem</li>
```

The **data-id** is a unique ID used to store the user's progress. For example, ***playthrough_13_20*** is the 20th task in zone 13. New data-ids must be used in ascending order, but you can place the new entries anywhere within a zone.

The **class="f_gem f_misc"** field is used for the filtering system. This task provides the user with a gem and a consumable, so we use **f_gem** and **f_misc**. The full list of filter classes is:

| Class   | Description |
|---      |--- |
| f_boss  | Boss fights |
| f_miss  | Content that can be permanently missed |
| f_npc   | NPC side quests |
| f_estus | Estus Shards |
| f_bone  | Undead Bone Shards |
| f_tome  | Sorcery Scrolls, Pyromancy Tomes, and Divine Tomes |
| f_coal  | Coals |
| f_ash   | Umbral Ashes |
| f_gest  | Gestures |
| f_sorc  | Sorceries |
| f_pyro  | Pyromancies |
| f_mirac | Miracles |
| f_ring  | Rings |
| f_weap  | Weapons, Spell Tools, and Shields |
| f_arm   | Armor Sets or individual pieces |
| f_tit   | Titanite |
| f_gem   | Gems |
| f_cov   | Covenants |
| f_misc  | *any other items* |

If none of these filter classes match, use **class="f_none"**.
