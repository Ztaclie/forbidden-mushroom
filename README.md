# Forbidden Mushroom

A RimWorld mod that adds the **Meat Shroom**, a fungus that grows meat. Farm it in any soil or in the dark and cook its flesh like any other raw meat, with no animals involved.

**Supports RimWorld 1.7.**

## Features

- **Meat Shroom plant**: sow it in grow zones and in hydroponics basins. It grows without light, so it works in sealed, unlit rooms.
- **Meat shroom flesh**: a raw meat item in the vanilla `MeatRaw` category. Every recipe that takes meat accepts it, including simple, fine and lavish meals, kibble and pemmican.
- **Mood**: meals cooked with the flesh give a small mood boost (+2 for half a day).
- **Animal feed**: carnivores and omnivores eat it as raw meat, with the same preference as vanilla meat.
- **Trade**: outlander, tribal and orbital bulk goods traders and outlander base traders stock the flesh, and traders that deal in raw food buy it from you.
- **Mycelium snare**: a one-tile hidden trap (Security tab) built from 15 meat shroom flesh. Like the spike trap it can be placed next to other traps. When stepped on it roots the victim in mycelium, which downs them so they can be captured alive.
- Entangled victims get hungry much faster. Mycelium binds fade with time or are cut away by tending.
- **Caps for pawns**: eight sibling mushrooms that give a temporary effect when eaten, each with a downside (see below). They are unlocked through a Mycology research tab.
- **Refined caps**: research lets you steep a cap in shroom broth at a stove to make a refined cap with the same benefit and no downside.
- **Packages**: bundle each group's caps into one package that applies all of their effects in a single action, in a normal and a refined version.
- The Meat Shroom, its flesh and the mycelium snare need no research and are available from the start of the game.

## Stats

| | Meat Shroom (plant) | Meat shroom flesh (item) |
| --- | --- | --- |
| Sow on | Ground, hydroponics | |
| Light needed | None | |
| Grow time | 7 days | |
| Yield per harvest | 10 flesh | |
| Nutrition | | 0.05 each |
| Rots after | | 4 days |
| Market value | | 1.2 |
| Stack size | | 75 |
| Category | | Raw meat (`MeatRaw`) |
| Mood | | +2 for 0.5 days in meals |

### Mycelium snare

| Stat | Value |
| --- | --- |
| Cost | 15 meat shroom flesh |
| Area | 1 tile (can be placed adjacent to other traps) |
| Movement per bind | x0.1, which downs the victim (stacks multiplicatively) |
| Hunger per bind | +1.0 rate (stacks additively) |
| Uses | Single use |

## Caps

All caps grow in ground or hydroponics, in the dark, and yield 6 per harvest. Eat one for a temporary effect. Raw caps keep their downside; refined caps do not.

| Cap | Group | Effect | Downside (raw only) |
| --- | --- | --- | --- |
| Ragecap | Combat | Faster movement, pain dulled, stronger melee | Crash: lower consciousness and manipulation |
| Ironhide cap | Combat | +25% sharp and blunt armor | Slower movement |
| Ghostcap | Combat | Much better melee dodge, a little faster | Shaky hands (lower manipulation) |
| Mender's bonnet | Restorative | Faster wound healing and immunity | Much higher hunger |
| Nightcap | Restorative | Deeper sleep, slower tiredness | Groggy afterwards |
| Hollowcap | Restorative | Hunger nearly switched off | Dulled thinking, ravenous crash |
| Dreamcap | Cognitive | Pain dulled, mood boost | Mood dip afterwards |
| Sagecap | Cognitive | Faster research and learning | Tiredness and a headache |

### Research

All of it is in the Mycology tab.

| Project | Unlocks |
| --- | --- |
| Mycology | The three branches below |
| Combat fungi | Ragecap, ironhide cap, ghostcap, combat package |
| Restorative fungi | Mender's bonnet, nightcap, hollowcap, recovery package |
| Cognitive fungi | Dreamcap, sagecap, mind package |
| Refined combat, restorative and cognitive fungi | Refined caps of that group (1 cap + 5 shroom flesh each) and the refined package |

Refined caps and all packages are made at a stove. A package takes one of each cap in its group.

## Compatibility

- Adds new content only, with an `FM_` prefix on every name. The only change to existing content is adding the flesh to some trader stock lists.
- Safe to add mid-save. To remove it, first harvest or delete the plants, flesh and snares.
- Load after Core. No other load-order requirements.
- Works with mods that add soil or terrain, such as Tilled Soil. Very high fertility makes the Meat Shroom grow faster.

## Installation

Subscribe on the Steam Workshop, or copy this folder into `RimWorld/Mods/` and enable it in the Mods menu.
