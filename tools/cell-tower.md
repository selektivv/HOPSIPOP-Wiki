# Cell Tower

A Cell Tower locates free-for-all Death Chests and guides you to a selected chest with a GPS particle trail. Quasar and higher [ranks](../ranks.md) can also search for nearby biomes.

## Crafting

Reach the Atom [rank](../ranks.md) to discover the recipe. Place a Lodestone in the center, Ender Pearls on its four sides, and Iron Ingots in the four corners.

![Cell Tower crafting recipe](../assets/cell-tower-crafting.png)

## Using the Tower

Place the Cell Tower inside your own [claim](../claims.md). You may have only one placed tower.

Right-click the tower or open `/mc` → Shortcuts → Cell Tower. Select a destination to start GPS navigation. Break your tower to recover the special item.

## Designs

Open `/mc` → Shortcuts → Appearance → **Cell Tower** to select a design.

- **Default:** A dark industrial mast with ceramic receiver faces, green telemetry lights, exposed metal, deployable panels, and two tracking dishes.
- **Cherry:** A ceremonial signal shrine with light torii collars, detached petal arrays, shoji details, and a shallow lantern canopy.
- **Copper:** A dark mechanical mast with copper service cabinets, patina conduits, a ventilated receiver crown, and a double-helix power bus.
- **Mangrove:** A living signal tree carried by buttress roots, with climbing root spirals, branch-like antenna arrays, and warm spore lamps.
- **Lapis Lazuli:** An arcane observatory with faceted astrolabe rings, constellation nodes, crystalline optics, and an uneven crystal crown.
- **Lush Cave:** A vertical grotto with splayed cave roots, twin moss spirals, offset Azalea terraces, pale Calcite supports, and hanging glow pods.
- **Medieval:** A fortified watchtower with masonry buttresses, open timber cross-bracing, detached battlements, beacon lamps, a shallow belfry, and a crenellated crown.
- **Quartz:** A celestial marble beacon with slender columns, fine gilded ribbons, separated solar-ring facets, luminous nodes, an open colonnade, and a stepped obelisk crown.

Default is always available. The seven alternative designs are unlocked separately for each tool and player by an operator with `/masterchest theme unlock <player> tower <cherry|copper|mangrove|lapis|lush|medieval|quartz>`. A locked design can be tried for two minutes by clicking it. After the preview ends, the tower returns to Default and that design enters a one-hour preview cooldown.

Every design has a restrained ambient particle accent around the receiver: cyan motes and an occasional End Rod for Default, pink motes and Cherry Leaves for Cherry, patina motes and electrical sparks for Copper, rust-red motes and spores for Mangrove, blue motes with enchantment glyphs for Lapis Lazuli, green motes with falling Spore Blossoms for Lush Cave, earthy brown motes with drifting ash for Medieval, and ivory motes with occasional wax-glint sparks for Quartz. These effects appear only while players are nearby.

The selection is saved per player and applies to that player's placed Cell Tower. Changing it rebuilds the display and collision model immediately while preserving the tower itself, its owner, and any active GPS destination. Moving panels and tracking dishes return to their current GPS pose after the rebuild. Fine decorative details such as petals, roots, Azalea terraces, battlements, and astrolabe facets do not create additional collision.

## Continue Learning

- [Ranks](../ranks.md)
- [Claims](../claims.md)
- [Shortcuts](../master-chest/shortcuts.md)
