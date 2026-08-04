# Fishing Table

The Fishing Table is a placeable angler's workbench used to research and craft all 99 [Bait](bait.md) recipes from 110 collectible [Bait Ingredients](bait-ingredients.md). It remembers every player's unlocked recipes and renders as a detailed, themeable workbench in the world.

## Craft the Table

The recipe is automatically added to your recipe book when you join. Players who are already online also receive it when the plugin reloads.

|   |   |   |
| --- | --- | --- |
| Prismarine Crystals | Fishing Rod | Prismarine Crystals |
| Copper Ingot | Barrel | Copper Ingot |
| Copper Ingot | Copper Ingot | Copper Ingot |

You need two Prismarine Crystals, one Fishing Rod, one Barrel, and five Copper Ingots.

Place the item and right-click the finished table to open it. Left-clicking breaks the table immediately and drops its custom item again.

## Designs and Ownership

A placed Fishing Table belongs to the player who placed it and uses that player's selected design. Choose a style through the MasterChest **Appearance → Fishing Table** menu. Changing the selection immediately refreshes every loaded Fishing Table you own.

There are ten designs:

- Default
- Cherry
- Copper
- Mangrove
- Lapis Lazuli
- Lush Cave
- Medieval
- Quartz
- Cyberpunk
- Crying Obsidian

Default is always available. A locked design can be previewed for two minutes; afterward that design reverts to Default and enters a one-hour trial cooldown. The Appearance menu shows each design's unlock, active-trial, and cooldown state. A legacy table without stored ownership is assigned to the first player who opens it after the update.

## Table Menu

The hub displays how many recipes you know out of 99 and provides two actions:

- **Research Bait Recipes** opens the four-page progression catalog.
- **Craft Bait** opens a shapeless 3×3 ingredient grid for recipes you have already researched.

## Find Bait Ingredients

There are 110 custom ingredients split into 11 private pools, one for every bait track. Their original sources are Trial Chambers, villages, Ancient Cities, End Cities, and MasterFish catches.

After you discover a structure ingredient in its original structure, it also becomes eligible as a fishing bonus. Fishing rewards are deposited directly into MasterChest when possible. See [Bait Ingredients](bait-ingredients.md) for every item, texture, track, tier, chance, and source.

## Research a Recipe

The Research catalog presents three complete effect tracks per page; the fourth page contains the final two tracks. Each track occupies one horizontal row with ranks 1 through 9 from left to right:

- Already researched ranks show their bait normally.
- The next available rank shows its real bait, fish prerequisite, and ingredient costs.
- All later ranks appear as locked `???` placeholders until the earlier recipes are researched.

To research the next rank:

1. Catch the fish species displayed on the recipe at least once. The requirement uses your permanent Fishing Glossary history, so you do not need to keep the fish item.
2. Own every displayed research ingredient across your normal inventory and MasterChest.
3. Click the recipe when every fish and ingredient requirement has a green check mark.

Research consumes inventory copies first and automatically removes any remaining required amount from MasterChest. It permanently unlocks that bait for your account at every Fishing Table and gives you one bait immediately.

The 11 tracks progress independently, but ranks inside one track must be unlocked from 1 to 9 without skipping. Ingredient discovery no longer hides the next recipe: the next rank is always shown, even when you do not own any of its ingredients yet.

## Craft an Unlocked Bait

1. Open **Craft Bait**.
2. Put the exact repeat-crafting ingredient and amount into the 3×3 grid. Its position does not matter.
3. When the output changes from **No matching recipe** to the bait, click it to craft.

The repeat recipe is much cheaper than research and uses only that bait's primary ingredient: one item for ranks 1–3 and two for ranks 4–9. The recipe matches only when the ingredient and total amount are exact, with no extras.

The crafting grid does not pull directly from MasterChest. Retrieve the ingredient first, then place it in the grid. Crafting consumes the grid and produces one bait; remove unused ingredients before leaving because the grid is not storage.

## Progression Tips

- Work on several effect tracks at once so structure and fishing finds remain useful.
- Check the complete horizontal track before choosing which next rank supports your current goal.
- Research can spend ingredients from MasterChest automatically; repeat crafting requires the physical item in the grid.
- Every track has its own exclusive ingredient pool, so an ingredient from one track cannot substitute for another.
- Research unlocks belong to the player, not the placed table. You can use any Fishing Table afterward.

## Related Articles

- [Baits](bait.md)
- [Bait Ingredients](bait-ingredients.md)
- [Fishing Guide](../fishing.md)
- [Fishing Rods](rods.md)
- [All Fish Species](../fish-species.md)
