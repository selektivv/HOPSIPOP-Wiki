# Tinkerer Table

The Tinkerer Table is a large interactive workstation used to craft [Attraction Blocks](attraction-blocks.md). Its recipe is automatically added to every player's recipe book when they join.

## Crafting

Arrange the ingredients in a Crafting Table as follows:

| | | |
|---|---|---|
| Potent Sulfur | Diamond Block | Potent Sulfur |
| Diamond Block | Diamond Block | Diamond Block |
| Crying Obsidian | Crying Obsidian | Crying Obsidian |

## Placing the Table

The table faces the player when placed. It needs an entirely clear area that is **7 blocks wide, 3 blocks deep, and 5 blocks high**. Placement is cancelled if any part of that space is occupied.

The finished workstation uses invisible Barrier blocks for its solid floor and monitor surfaces. The detailed console, screens, controls, and frame are display entities. Its position and orientation persist across server restarts.

## Opening the Interface

Left- or right-click any Barrier surface belonging to the table to open its interface.

The interface contains:

- a 3-by-3 ingredient grid;
- a result slot on the right;
- a Recipe Book showing the currently available recipe;
- a Back button that closes the interface.

Click an ingredient into a grid slot to place one item there. Clicking an occupied slot with an empty cursor returns that ingredient. When the complete pattern matches a known recipe, the result appears on the right. Click the result to craft it; all nine ingredients are consumed and the finished block is added to your inventory. If the inventory is full, the result drops at your location.

Some results have a [rank](../ranks.md) requirement. A matching recipe can still be viewed in the grid, but its result cannot be collected below the required rank.

## Removing the Table

Sneak while breaking one of the table's Barrier blocks to dismantle the entire workstation. All of its Barrier blocks and displays are removed, and the Tinkerer Table item drops at the table.

## Available Creations

At present, the Tinkerer Table can craft the [Creeper Attraction Block](attraction-blocks/creeper-attraction-block.md).

## Continue Learning

- [Attraction Blocks](attraction-blocks.md)
- [Creeper Attraction Block](attraction-blocks/creeper-attraction-block.md)
- [Ranks](../ranks.md)
