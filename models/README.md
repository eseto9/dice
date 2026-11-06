# 3D models

All models and textures in this folder, except `people/`, are by **Kenney** (https://kenney.nl) and released under **CC0 1.0** (public domain). No attribution is required, but credit is given in the game.

They were taken from these kits, via the mirror at https://github.com/series-ai/jam-ready-assets:

| Folder | Kenney kit | Used for |
|---|---|---|
| `town/` | Fantasy Town Kit | Wagons (carts), market stalls, lanterns, banners |
| `pirate/` | Pirate Kit | Palms, barrels, crates, chest, rocks, the bandits' sand-skiff |
| `survival/` | Survival Kit | Tents, campfire, signpost |
| `nature/` | Nature Kit | Cacti, ruined statue and standing stones |
| `castle/` | Castle Kit | City gate and towers, siege tower |
| `graveyard/` | Graveyard Kit | Tomb guards (skeletons), sand wraith (ghost), pillars |

Each kit folder keeps its own `Textures/colormap.png`, because the models reference it by that relative path.

## people/

The crew and the human enemies are built from **Quaternius** packs (https://quaternius.com), also **CC0 1.0**:

- **Modular Character Outfits – Fantasy**: knight, ranger, noble and peasant outfit parts.
- **Universal Base Characters**: heads and hair.
- **Universal Animation Library**: `animations.json` (idle, walk, sword attack, death, sitting and a few more).

They were taken from the mirror at https://github.com/dcramer/terra (outfits and bases) and https://github.com/series-ai/jam-ready-assets (animations), then made web-sized: geometry simplified and quantized with gltf-transform, textures reduced to 1024 px or smaller (colour maps only), the ranger cloth recoloured from green to desert browns, and the animation library trimmed to the clips the game uses. Each part is a glTF JSON file with its geometry embedded; textures are in `people/tex/`.
