# Chunk Drills

A Chunk Drill excavates one 16-by-16 chunk from top to bottom. Eligible blocks add [counter](counters.md) progress, and drops go to the owner's Master Chest.

## Unlocking and Crafting

Buy the one-time unlock through `/cw` for 50,000 spendable [Capacity](../capacity.md). Purchasing it reduces your spendable Capacity, unlocks the recipe, and adds that recipe to your recipe book.

The recipe uses three Scaffolding, two Observers, one Netherite Block, two Pistons, and one Conduit. Only players who have purchased the unlock can craft the drill.

<img width="1700" height="402" alt="Screenshot 2026-07-19 164806" src="https://github.com/user-attachments/assets/1c533efb-cc53-449c-97b3-67aba7224731" />


## Coal Consumption

Each placed drill tracks its own fuel usage and removes **1 Coal from its owner's Master Chest for every 64 blocks it actually mines**.

- Only regular Coal counts. Charcoal and Coal Blocks are not accepted.
- Empty space, Bedrock, barriers, fluids, and other skipped blocks do not increase the Coal counter.
- Every mined block counts separately, including all blocks mined in one upgraded multi-block interval.
- After a mining interval brings the counter to 64 or more, the drill attempts to remove one Coal. Blocks beyond 64 in an upgraded multi-block interval remain counted toward the next Coal.
- If no Coal is available, it pauses before selecting more blocks. It checks again automatically and resumes when Coal becomes available.
- `/chunkdrill` shows whether each drill is mining or paused and displays the owner's current Coal stock.

## Placing a Drill

- Place it only in the [Capacity](../capacity.md) World.
- You may run up to four drills.
- Only one of your drills may occupy a chunk.
- Only the owner or an operator can break it.

The drill skips air, Bedrock, barriers, and other unmineable space. [Lucky Break](lucky-break.md) does not affect drill progress.

## Managing Drills

Open `/chunkdrill`, select the drill in `/cw`, or left-click while holding a drill item. The menu can collect one drill or all active drills into storage.

A finished drill and drills caught by a [World Reset](resets.md) return to the Master Chest. A manually broken drill drops at its location. Always leave enough [Capacity](../capacity.md) for the return transfer.

## Upgrades

- Double Mining costs 10 Netherite Blocks.
- Triple Mining costs another 20 Netherite Blocks.
- Quadruple Mining costs another 30 Netherite Blocks.
- Quintuple Mining costs another 45 Netherite Blocks.
- Fluid Collector costs 100,000 [Capacity](../capacity.md) and consumes empty buckets for water or lava source blocks.
- Quasar [rank](../ranks.md) unlocks chest-content collection.

Higher [ranks](../ranks.md) reduce the delay between mining intervals.

## Safety

The excavated chunk becomes a full-height hole. Do not stand beneath the drill or rely on nearby terrain remaining intact.

## Continue Learning

- [World Resets](resets.md)
- [Mining Troubleshooting](troubleshooting.md)
