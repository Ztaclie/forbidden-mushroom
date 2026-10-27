# Forbidden Mushroom

A RimWorld mod that adds the **Meat Shroom**, a fungus that grows meat. Farm it in any soil or in the dark and cook its flesh like any other raw meat, with no animals involved.

**Supports RimWorld 1.7.**

## Features

### Implemented (Phase 1)

- **Meat Shroom plant**: sow it in grow zones and in hydroponics basins.
- Grows without light, so it works in sealed, unlit rooms.
- **Meat shroom flesh**: a raw meat item in the vanilla `MeatRaw` category.
- Accepted by every recipe that takes meat, including simple, fine and lavish meals, kibble and pemmican.
- No research needed. It is available from the start of the game.
- Stack-size sprites: the flesh shows one chunk, a small pile or a big pile depending on stack size.
- Meals cooked with the flesh give a small mood boost (+2 for half a day).
- Animal feed: carnivores and omnivores eat it as raw meat (same preference as vanilla meat), and it can be made into kibble.
- Works with other mods that add soil or terrain, such as Tilled Soil.

### Planned

Ideas for later phases, not promised yet:

- Research unlock and a growing-station building
- Natural spawning in caves and other biomes
- New meals that use the flesh
- Real art for the plant and flesh

## Stats

| | Meat Shroom (plant) | Meat shroom flesh (item) |
| --- | --- | --- |
| Def name | `FM_Plant_ForbiddenMushroom` | `FM_ShroomMeat` |
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

Numbers are a first pass and will be rebalanced in later phases.

## Compatibility

- Adds new defs only (`FM_` prefix) and patches no vanilla defs, so it should be safe to add or remove mid-save. Remove it only after harvesting or deleting the plants and flesh.
- Load after Core. No other load-order requirements.
- Checked against the Tilled Soil source files, which have no overlap. Its fertility of 99 makes the Meat Shroom grow noticeably faster.
- Version folders are not used yet. If RimWorld 1.6 is supported later, defs that differ go in `1.6/` and `1.7/` with a `LoadFolders.xml`.

## Installation

Subscribe on the Steam Workshop (link coming), or copy this folder into `RimWorld/Mods/` and enable it in the Mods menu.

## Development

Layout:

```
About/        mod metadata (About.xml, Preview.png when added)
Defs/         plant, item and thought definitions
Textures/     plant, immature plant and flesh sprites (stack sprites in a folder)
```

Testing: copy the mod into `RimWorld/Mods/`, enable it, start a dev-mode game and sow the Meat Shroom. Def changes need a full game restart.

### Steam Workshop checklist

- [ ] Replace placeholder textures in `Textures/`
- [ ] Add `About/Preview.png` (640x360)
- [ ] Add a mod icon
- [ ] Upload from the in-game Mods menu
