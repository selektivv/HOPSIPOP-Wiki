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

The table faces the player when placed. Its compact body is **3 blocks wide, 1 block deep, and 2 blocks high**. Placement is cancelled unless that complete 3-by-1-by-2 space is clear.

The finished workstation uses six invisible Barrier blocks as a clickable 3-by-2 front. A slim display-entity frame, open supports, a gently angled console, and three text-free screens are fitted inside that space. Each screen is assembled from subtly rotated segments to create a light curve without making the workstation bulky. Its position and orientation persist across server restarts.

## Designs

Open `/mc` → Shortcuts → Appearance → **Tinkerer Table** to select a design. Default is always available. Cherry and Copper must first be unlocked for the player by an operator with `/masterchest theme unlock <player> tinkerer <cherry|copper>`.

- **Default:** Black glass, dark machinery, cyan controls and grid lines, bright material chips, and restrained gold details.
- **Cherry:** Cherry wood and planks, curved pink glass screens, pink and magenta control lines, Amethyst controls, Pearl Froglight cores, white mechanisms, and gold details.
- **Copper:** Cut, exposed, weathered, and oxidized Copper, Tinted Glass screens, patina control lines, Copper Grates, Copper Bulbs, and Chiseled Copper mechanisms.

The selected design is saved per player and applies to all Tinkerer Tables owned by that player. Changing it replaces only the display entities; the six clickable Barrier blocks, table identity, orientation, and crafting interface remain unchanged. Newly placed tables remember their owner immediately. Tables created before ownership tracking was added are assigned once when a player first opens them.

## Opening the Interface

Left- or right-click any Barrier surface belonging to the table to open its interface.

The interface contains:

- a 3-by-3 ingredient grid;
- a result slot on the right;
- a Recipe Book showing the currently available recipe;
- a Back button that closes the interface.

Click an ingredient into a grid slot to place one item there. Clicking an occupied slot with an empty cursor returns that ingredient. When the complete pattern matches a known recipe, the result appears on the right. Click the result to craft it; all nine ingredients are consumed and the finished block is added to your inventory. If the inventory is full, the result drops at your location.

Some results have a [rank](../ranks.md) requirement. A matching recipe can still be viewed in the grid, but its result cannot be collected below the required rank.

## Removing or Storing the Table

Open the interface and Shift-click **Dismantle & Store** to remove the complete workstation and move its item directly into your Master Chest. If the storage network is full, the item is placed in your inventory; if that is also full, it drops at your location.

You can alternatively sneak while breaking one of the table's Barrier blocks. This removes all of its Barrier blocks and displays and drops the Tinkerer Table item at the table.

## Available Creations

At present, the Tinkerer Table can craft the [Creeper Attraction Block](attraction-blocks/creeper-attraction-block.md).

## Continue Learning

- [Attraction Blocks](attraction-blocks.md)
- [Creeper Attraction Block](attraction-blocks/creeper-attraction-block.md)
- [Ranks](../ranks.md)
