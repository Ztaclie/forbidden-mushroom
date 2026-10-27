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
- No research needed. Everything is available from the start of the game.

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

## Compatibility

- Adds new content only, with an `FM_` prefix on every name. The only change to existing content is adding the flesh to some trader stock lists.
- Safe to add mid-save. To remove it, first harvest or delete the plants, flesh and snares.
- Load after Core. No other load-order requirements.
- Works with mods that add soil or terrain, such as Tilled Soil. Very high fertility makes the Meat Shroom grow faster.

## Installation

Subscribe on the Steam Workshop, or copy this folder into `RimWorld/Mods/` and enable it in the Mods menu.
