# Chunk Drills

A Chunk Drill automatically excavates one complete 16-by-16 chunk from top to bottom. Eligible blocks advance your mining [counter](counters.md), and the drops produced by mined blocks are sent to your [Master Chest](../master-chest/README.md).

## Unlocking and Crafting

Buy the one-time unlock from [Mining Upgrades](upgrades.md#chunk-drill-unlock) for 500,000 [Capacity](../capacity.md). The recipe is then added to your recipe book.

Arrange the ingredients in a crafting table as follows:

| Left | Middle | Right |
| --- | --- | --- |
| Scaffolding | Scaffolding | Scaffolding |
| Observer | Netherite Block | Observer |
| Piston | Conduit | Piston |

One drill therefore requires three Scaffolding, two Observers, one Netherite Block, two Pistons, and one Conduit.

## Placing a Drill

- A Chunk Drill can only be placed in the [Capacity](../capacity.md) World.
- You may have up to four active drills at once.
- You may place only one of your own active drills in the same chunk.
- Place it inside the chunk you want to excavate.
- Only the owner or an operator can break the placed drill.

Mining starts automatically after placement. The drill works from the world's highest layers downward and skips air, Bedrock, barriers, and similar unmineable space.

## Counter and Storage Behavior

Each eligible solid block processed by the drill adds exactly one [counter](counters.md) point. [Counter Reduction](counter-reduction.md), [co-op](coop.md), and [Counter Boost](boosts-and-notifications.md) rewards still apply when a goal completes. [Lucky Break](lucky-break.md) does not apply to drill-mined blocks.

Produced block drops are transferred directly to your MasterChest. Keep substantial free [Capacity](../capacity.md) available before starting a drill. If the network has no room, transferred drops or even a returning drill may not fit safely.

## Opening Drill Management

Use any of these methods after unlocking the drill:

- Run `/chunkdrill`.
- Open `/cw` and select the unlocked Chunk Drill option.
- Left-click while holding a Chunk Drill item.
- Interact with the visible structure of one of your placed drills.

The menu shows all four drill slots and the coordinates of active drills.

## Collecting Drills

- Click an active drill icon to stop that drill and return it to your MasterChest.
- Select Collect All Drills to stop and return every active drill.
- Breaking your placed drill stops it and drops the drill item at its location instead.
- A drill automatically returns to your MasterChest after finishing its chunk.
- Active drills are stopped and returned during a [Capacity World reset](world-rules-and-resets.md).

Always make room in the MasterChest before collection or a reset.

## Speed Upgrades

Drill speed improves automatically with your [rank](../ranks.md). Higher [ranks](../ranks.md) reduce the delay between mining intervals, up to the system's fastest interval.

The drill menu also offers permanent throughput upgrades:

- Double Mining costs 10 Netherite Blocks taken directly from your MasterChest.
- Triple Mining costs another 20 Netherite Blocks from your MasterChest and requires Double Mining first.

These upgrades make every active drill process two or three blocks per interval instead of one.

## Fluid Collector

Fluid Collector costs 100,000 [Capacity](../capacity.md) and is enabled when first unlocked. You can toggle it in the drill menu afterward.

When enabled, a drill can collect a water or lava source block by taking one empty bucket from your MasterChest and returning the appropriate filled bucket. Flowing fluids are removed without being collected. A source block is also removed without a filled bucket if no empty bucket is available.

## Chest Contents

At Quasar [rank](../ranks.md) or higher, the drill menu includes Global: Collect Chest Contents. Enable it before drilling chunks where generated containers may be present.

When enabled, contents found inside containers are transferred to your MasterChest before the container block is removed. When disabled, the drill handles only the drops produced by the container block itself, so its stored contents should not be considered protected.

## Staying Safe Around Drills

The excavated chunk becomes a full-height hole. Do not stand beneath the drill or rely on nearby terrain remaining intact. PvP is also enabled, and the whole world is temporary.

## Continue Learning

- See how drill blocks contribute to mining [counters](counters.md) and [rewards](mining-and-rewards.md).
- Compare drill unlocks and improvements under [mining upgrades](upgrades.md).
- Keep the receiving [storage network](../master-chest/README.md) below its [Capacity](../capacity.md) limit.
- Follow [world reset safety](world-rules-and-resets.md) before the timer expires.
