# Creeper Attraction Block

The Creeper Attraction Block guides nearby Creepers toward one fixed point. It is currently the only Attraction Block that can be crafted at the [Tinkerer Table](../tinkerer-table.md).

## Requirements

You need the **Nova [rank](../../ranks.md) or higher** to collect the crafted result from the Tinkerer Table.

## Tinkerer Table Recipe

Place the following items in the table's 3-by-3 ingredient grid:

| | | |
|---|---|---|
| Obsidian | Gunpowder | Obsidian |
| Gunpowder | Eye of Ender | Gunpowder |
| Obsidian | Lightning Rod | Obsidian |

When the pattern is correct, the Creeper Attraction Block appears in the result slot. Click it to consume all nine ingredients and receive the block.

## Effect

Once every second, Creepers within **20 blocks** are told to pathfind toward the placed block. The effect runs only while its chunk is loaded.

The block does not make Creepers harmless: it does not stop explosions, change their targeting, or teleport them through obstacles. Build the surrounding route and containment area accordingly.

## Placement Rules

- Only an operator can currently place or break the block.
- Only one Creeper Attraction Block can be placed on the server at a time.
- It cannot be placed in the [Capacity World](../../capacity-world/README.md).
- Breaking it returns the special Creeper Attraction Block item.

## Continue Learning

- [Attraction Blocks](../attraction-blocks.md)
- [Tinkerer Table](../tinkerer-table.md)
- [Ranks](../../ranks.md)
