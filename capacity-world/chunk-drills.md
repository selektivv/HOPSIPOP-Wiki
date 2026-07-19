# Chunk Drills

A Chunk Drill automatically excavates one 16-by-16 chunk in the Capacity World. It scans from the highest build layer downward, adds every block it actually mines to the owner's [counter](counters.md), and sends the resulting drops to the owner's Master Chest network. It keeps working while the owner is offline.

## Unlocking and Crafting

Buy the one-time Chunk Drill upgrade through `/cw` for **50,000 spendable [Capacity](../capacity.md)**. The purchase reduces your spendable Capacity, unlocks the item, and discovers its recipe.

The shaped recipe is:

- Top row: three Scaffolding.
- Middle row: Observer, Diamond Block, Observer.
- Bottom row: Piston, Conduit, Piston.

Only players with the upgrade can craft or place a Chunk Drill. The recipient also needs the upgrade to receive one through player trading or the Marketplace, and players without it cannot pick up a dropped drill.

<img width="1700" height="402" alt="Chunk Drill crafting recipe" src="https://github.com/user-attachments/assets/1c533efb-cc53-449c-97b3-67aba7224731" />

## Placing a Drill

- A drill can only be placed in the [Capacity](../capacity.md) World.
- Each player may have up to four active drills.
- You cannot place two of your own drills in the same chunk.
- Only the owner or an operator can break a placed drill.

The drill starts immediately after placement. Active drills are saved and resume after a server restart. Mining does not depend on the owner being online or on any player being nearby.

## What Gets Mined

The drill sweeps across each layer before descending to the next one. Mining upgrades let it select multiple blocks from the same sweep during one interval, keeping the excavation roughly level.

- Air, Bedrock, barriers, cave air, and void air are skipped and do not count.
- Water, lava, and non-solid blocks such as plants are cleared without drops, counter progress, or fuel progress. The Fluid Collector can preserve source fluids instead.
- Every other selected block is removed, its server-defined drops are sent to the owner's network, and one block is added to both the Capacity counter and the drill's fuel counter.
- [Lucky Break](lucky-break.md) is not applied to drill progress or drops.
- Container contents are transferred separately only while **Collect Chest Contents** is enabled. The container block's own drop is handled normally.

## Fuel Consumption

Each drill consumes **one fuel item after every 64 blocks it actually mines**. The owner cycles through four global fuel modes in `/chunkdrill`:

- **Coal** is the default.
- **Charcoal** uses only Charcoal.
- **Both (Coal first)** consumes Coal when available and falls back to Charcoal.
- **Both (Charcoal first)** consumes Charcoal when available and falls back to Coal.

Coal Blocks are never accepted. Skipped or cleared blocks do not advance the fuel counter. All blocks in an upgraded multi-block batch count individually; any amount beyond 64 remains toward the next fuel item.

The first fuel item is requested after the first 64 blocks have been mined. If the selected fuel is unavailable at that point, the drill pauses before selecting more blocks and resumes automatically when fuel becomes available. The menu shows each drill's current Mining or Paused status and the available stock for the selected fuel mode.

After a plugin or server restart, the scan begins at the top again and skips the space already cleared. The partial 64-block fuel counter is not persisted.

## Managing Drills

Open the management menu with `/chunkdrill`, by clicking the unlocked Chunk Drill entry in `/cw`, by left-clicking while holding a drill, or by interacting with your placed drill model.

The menu provides these actions:

- **Left-click a drill:** Teleport to it.
- **Right-click a drill:** Pick it up and return it to the Master Chest.
- **Collect All Drills:** Pick up all of your active drills and return them to the Master Chest.
- **Drill Fuel:** Cycle through Coal, Charcoal, Both with Coal first, and Both with Charcoal first.
- **Mining Speed, Fluid Collector, and Collect Chest Contents:** Manage the global upgrades and settings described below.

When excavation finishes, the drill removes itself and returns to the owner's network. Active drills are also returned before a [World Reset](resets.md). Breaking a drill manually is different: its item drops at the drill's location.

## Upgrades and Global Settings

Mining Speed upgrades must be purchased in order. Their Netherite and Diamond Blocks are removed from the Master Chest network, and each setting applies to all of the player's drills.

| Setting | Cost | Effect |
| --- | ---: | --- |
| Double Mining | 1 Netherite Block + 2 Diamond Blocks | Mines up to 2 blocks per interval. |
| Triple Mining | 2 Netherite Blocks + 4 Diamond Blocks | Mines up to 3 blocks per interval. |
| Quadruple Mining | 3 Netherite Blocks + 6 Diamond Blocks | Mines up to 4 blocks per interval. |
| Quintuple Mining | 4 Netherite Blocks + 8 Diamond Blocks | Mines up to 5 blocks per interval. |
| Fluid Collector | 100,000 Capacity | Unlocks a global on/off toggle for collecting water and lava source blocks. |
| Collect Chest Contents | Free | Globally toggles transfer of chest and other container contents into the Master Chest. It is disabled by default and does not require Quasar rank. |

Fluid Collector is enabled when purchased. For each water or lava source block, it removes one empty Bucket from the network and stores the matching filled Bucket. Flowing fluid is always cleared. If no empty Bucket is available, the source block is cleared without being collected.

The player's current [rank](../ranks.md) controls the delay between mining intervals. The interval is 10 server ticks at Atom and decreases by one tick per rank until it reaches the minimum of 1 tick at Multiversal; Omniversal and Apex remain at that minimum. Mining Speed upgrades change the number of blocks handled during each interval, not the interval itself.

## Storage and Safety

Keep enough free Master Chest space for mined drops, collected container contents, filled Buckets, and the drill item itself. Anything that does not fit has no player-inventory or ground fallback during automated storage. This also applies when a completed, collected, or reset-caught drill returns to the network.

With **Collect Chest Contents** disabled, the drill does not preserve a container's inventory separately before removing the block. Enable it before excavating chunks that may contain valuable containers.

The excavation leaves a full-height hole except for skipped blocks such as Bedrock and barriers. Do not stand beneath the drill or rely on nearby terrain remaining intact.

## Continue Learning

- [World Resets](resets.md)
- [Mining Troubleshooting](troubleshooting.md)
