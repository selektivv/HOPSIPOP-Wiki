# Fishing Table

The Fishing Table is a placeable angler's workbench used to research and craft all 100 [bait](bait.md) recipes. It has its own block and item textures, remembers each player's unlocked recipes, and can be placed anywhere you can build.

![Fishing Table block and item texture preview](../assets/fishing-table/fishing-table-preview.png)

## Craft the Table

The recipe is automatically added to your recipe book when you join.

|   |   |   |
| --- | --- | --- |
| Prismarine Crystals | Fishing Rod | Prismarine Crystals |
| Copper Ingot | Barrel | Copper Ingot |
| Copper Ingot | Copper Ingot | Copper Ingot |

You need two Prismarine Crystals, one Fishing Rod, one Barrel, and five Copper Ingots. Place the finished table and right-click it to open the menu. Breaking it normally drops the custom Fishing Table item again.

## Table Menu

The hub displays how many recipes you know out of 100 and provides two actions:

- **Research Bait Recipes** shows recipes that you have unlocked and the next locked recipes you have started collecting ingredients for.
- **Craft Bait** opens a shapeless 3×3 ingredient grid for recipes you have already researched.

## Find Bait Ingredients

There are 50 custom ingredients: ten from each of five sources and two of every ingredient tier per source. Every ingredient has its own resource-pack texture.

<img src="../assets/fishing-table/ingredient-textures.png" width="800" alt="All 50 Fishing Table ingredient textures">

| Source | Where ingredients appear |
| --- | --- |
| Trial Chambers | Reward, corridor, intersection, barrel, and supply loot |
| Villages | Profession and village-house chests |
| Ancient Cities | Ancient City and Ancient City ice-box chests |
| End Cities | End City treasure chests |
| Fishing | Independent bonus drops after a successful MasterFish catch |

Structure ingredients are added when an eligible vanilla loot container generates its contents for the first time. Each matching ingredient rolls independently, so one container can contain more than one. Fishing ingredients also roll independently; a Surge bonus fish performs another set of rolls.

| Ingredient tier | Used by bait tiers | Chance per eligible structure ingredient | Chance per fishing ingredient |
| ---: | ---: | ---: | ---: |
| 1 | 1–2 | 35% | 5% |
| 2 | 3–4 | 25% | 3.5% |
| 3 | 5–6 | 18% | 2.2% |
| 4 | 7–8 | 12% | 1.4% |
| 5 | 9–10 | 7% | 0.8% |

The structure chance only applies to ingredients assigned to that structure category; the fishing chance only applies to the ten fishing-source ingredients.

## Research a Recipe

1. Collect at least one ingredient used by a locked recipe. This makes up to the next two started recipes appear in the research catalog.
2. Catch the fish species listed on the recipe at least once. The requirement uses your permanent Fishing Glossary history, so you do not need to keep the fish item.
3. Carry every displayed ingredient in your normal inventory.
4. Click the recipe when every fish and ingredient requirement has a green check mark.

Research consumes the full ingredient recipe, permanently unlocks that bait for your account at every Fishing Table, and gives you one bait immediately. Already researched recipes remain visible for reference.

## Craft an Unlocked Bait

1. Open **Craft Bait**.
2. Move the exact custom ingredients and amounts into the 3×3 grid. Their positions do not matter.
3. When the output changes from **No matching recipe** to the bait, click it to craft.

The grid only accepts Fishing Table ingredients. A recipe matches only when the ingredient types and total amounts are exact, with no extras. Crafting consumes the grid and produces one bait. The grid is not storage, so remove unused ingredients before leaving the screen.

## Progression Tips

- Search several source types instead of staying in one structure: recipes deliberately combine ingredients from different categories.
- Lower bait tiers use lower-tier ingredients, while the two highest bait families require tier-5 materials.
- Keep fishing while gathering structure loot. Fishing-source ingredients are required throughout the progression.
- Check the research catalog after finding a new ingredient; it intentionally reveals only the next relevant locked recipes instead of showing 100 lock icons at once.
- Research unlocks belong to the player, not the placed table. You can use any Fishing Table afterward.

## Related Articles

- [Bait](bait.md)
- [Fishing Guide](../fishing.md)
- [Fishing Rods](rods.md)
- [All Fish Species](../fish-species.md)
