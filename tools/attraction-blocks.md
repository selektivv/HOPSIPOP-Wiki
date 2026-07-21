# Attraction Blocks

Attraction Blocks are special player heads that continually guide one mob type toward their position. Craftable variants are made at the [Tinkerer Table](tinkerer-table.md).

## How Attraction Works

Once every second, a placed Attraction Block looks for its matching mobs within **20 blocks** and asks them to pathfind toward the block at normal movement speed.

Attraction Blocks do not teleport mobs, spawn new mobs, freeze them, or disable their normal behavior. Terrain and pathfinding can therefore prevent a mob from reaching the block, and hostile mobs remain dangerous.

The attraction only runs while the block's chunk is loaded.

## Placement Rules

- Only operators can currently place or break Attraction Blocks.
- Only one block of each attraction type may be placed across the entire server at a time.
- Attraction Blocks cannot be placed in the [Capacity World](../capacity-world/README.md).
- Breaking one returns its special item instead of an ordinary player head.

If another block of the same type is already active, placement is cancelled and the player is shown an error.

## Available Types

| Attraction Block | Target | Tinkerer Table status |
|---|---|---|
| [Creeper Attraction Block](attraction-blocks/creeper-attraction-block.md) | Creepers | Craftable; Nova rank required |
| Cow Attraction Block | Cows | Not currently craftable |
| Chicken Attraction Block | Chickens | Not currently craftable |
| Wither Skeleton Attraction Block | Wither Skeletons | Not currently craftable |

Operators can obtain the configured types through `/attraction admin`. The admin menu also shows the coordinates of a type that is already placed.

## Continue Learning

- [Tinkerer Table](tinkerer-table.md)
- [Creeper Attraction Block](attraction-blocks/creeper-attraction-block.md)
- [Ranks](../ranks.md)
