# Final Fantasy X Cheat Sheet

To view the cheat sheet [click here](https://drunktraveler.github.io/).

This checklist was created by adopting the source code from the [Dark Souls 2 Cheat Sheet](https://github.com/smcnabb/dark-souls-2-cheat-sheet/tree/gh-pages) created by [Stephen McNabb](https://github.com/smcnabb) and [Dark Souls 3 Cheat Sheet](https://github.com/ZKjellberg/dark-souls-3-cheat-sheet).

The walkthrough is thanks to [FFX FAQ/Walkthrough (PS3) by KeyBlade999](https://gamefaqs.gamespot.com/ps3/643146-final-fantasy-x-x-2-hd-remaster/faqs/69037) and [jegged](https://jegged.com/Games/Final-Fantasy-X/) as well as [Dansg08 video series](https://www.youtube.com/watch?v=03HaLMNJWWk&list=PL9wpzJw8GKy74rLqQv7OH9v94Hj8qQWps&index=1).

## Contribution Guide

If you are interested in contributing to this guide, I welcome Pull Requests.

For some background on how the guide code is written, here is a sample item on the checklist:

```
<li data-id="playthrough_15_5" class="f_sphere">Pick up the Luck Sphere on the right side of the corrider</li>
```

The **data-id** is a unique ID used to store the user's progress. For example, ***playthrough_15_5*** is the 5th task in zone 15. New data-ids must be used in ascending order, but you can place the new entries anywhere within a zone.

The **class="f_sphere"** field is used for the filtering system. This task provides the user with a Luck Sphere, so we use **f_sphere**. It is possible to use multiple classes. The full list of filter classes is:

| Class   | Description |
|---      |--- |
| f_boss  | Boss fights |
| f_miss  | Content that can be permanently missed |
| f_cons  | Consumable Items |
| f_battle| Battle Items |
| f_sphere| Sphere Items |
| f_prime | Al Bhed Primers |
| f_weap  | Weapons |
| f_arm   | Armor |
| f_misc  | *any other items* |

If none of these filter classes match, use **class="f_none"**.
