# Attraction Blocks

Attraction Blocks are special player heads that continually guide one mob type toward their position. Craftable variants are made at the [Tinkerer Table](tinkerer-table.md).

## How Attraction Works

Once every second, a placed Attraction Block looks for its matching mobs within **20 blocks** and asks them to pathfind toward the block at normal movement speed.

Attraction Blocks do not teleport mobs, spawn new mobs, freeze them, or disable their normal behavior. Terrain and pathfinding can therefore prevent a mob from reaching the block, and hostile mobs remain dangerous.

The attraction only runs while the block's chunk is loaded.

## Placement Rules

- Any player can place and break Attraction Blocks.
- Up to **four blocks of each attraction type** may be placed across the entire server at a time.
- Attraction Blocks cannot be placed in the [Capacity World](../capacity-world/README.md).
- Breaking one returns its special item instead of an ordinary player head.

If four blocks of the same type are already active, further placement is cancelled and the player is shown an error. The limit is counted separately for every attraction type.

## Available Types

| Attraction Block | Target | Tinkerer Table status |
|---|---|---|
| [Creeper Attraction Block](attraction-blocks/creeper-attraction-block.md) | Creepers | Craftable; no rank required |
| [Cow Attraction Block](attraction-blocks/cow-attraction-block.md) | Cows | Craftable; no rank required |
| [Chicken Attraction Block](attraction-blocks/chicken-attraction-block.md) | Chickens | Craftable; no rank required |
| Wither Skeleton Attraction Block | Wither Skeletons | Not currently craftable |
| [Blaze Attraction Block](attraction-blocks/blaze-attraction-block.md) | Blazes | Craftable; no rank required |

Operators can obtain any configured type through `/attraction admin`. The admin menu shows the current number of placed blocks and lists the world and coordinates of every placement for that type.

## Continue Learning

- [Tinkerer Table](tinkerer-table.md)
- [Creeper Attraction Block](attraction-blocks/creeper-attraction-block.md)
- [Cow Attraction Block](attraction-blocks/cow-attraction-block.md)
- [Chicken Attraction Block](attraction-blocks/chicken-attraction-block.md)
- [Blaze Attraction Block](attraction-blocks/blaze-attraction-block.md)
