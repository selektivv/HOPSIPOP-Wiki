# Claim Settings

Claim Settings are per-claim controls available at Quasar [rank](../ranks.md) and above. Only the claim owner can see and edit them; trusted players and Managers cannot change these settings.

Open the [Claim GUI](../claims.md), select one of your own claims, then choose Claim Settings. All switches, Weather, and Time are shown together in one menu. Changes apply immediately and are saved separately for that claim.

<img width="504" height="372" alt="Claim Settings menu showing all per-claim controls" src="https://github.com/user-attachments/assets/9ae5d81c-6ead-4e1d-ad75-593b12cbde9e" />

## Mob Spawning

| Setting | Default | When On | When Off |
| --- | --- | --- | --- |
| Hostile Mob Spawning | On | Monsters can spawn naturally. | Prevents natural monster spawns. |
| Phantom Spawning | On | Phantoms can spawn naturally. | Prevents natural Phantom spawns. |
| Snowman Trails | On | Snow Golems leave snow trails. | Stops Snow Golems from creating snow. |

The two spawning switches do not block spawners, trial spawners, spawn eggs, dispensed eggs, commands, custom spawns, breeding, curing, metamorphosis, or constructed mobs such as Golems and the Wither.

## Damage & Combat

| Setting | Default | When On | When Off |
| --- | --- | --- | --- |
| PvP | Off | Allows direct and projectile player damage when the victim is inside the claim. | Claim protection continues to block PvP. |
| Explosion Block Damage | On | Entity and block explosions can damage blocks. | Protects claimed blocks from explosion damage. Entity damage is unaffected. |
| Lightning | On | Lightning can strike normally. | Prevents lightning strikes inside the claim. |
| Lava Fire | On | Lava can ignite blocks. | Prevents lava from igniting blocks inside the claim. |

## Fluids, Snow & Ice

| Setting | Default | When On | When Off |
| --- | --- | --- | --- |
| Water Flow | On | Water can flow into blocks inside the claim. | Stops water from flowing into destination blocks inside the claim. |
| Lava Flow | On | Lava can flow into blocks inside the claim. | Stops lava from flowing into destination blocks inside the claim. |
| Snow Fall | On | Snow can accumulate from weather. | Prevents weather snow from accumulating. |
| Snow Melt | On | Snow melts naturally. | Prevents snow from melting naturally. |
| Ice Form | On | Water can freeze into Ice. | Prevents water from freezing into Ice. |
| Ice Melt | On | Ice and Frosted Ice melt naturally. | Prevents Ice and Frosted Ice from melting. |

## Growth & Decay

| Setting | Default | When On | When Off |
| --- | --- | --- | --- |
| Grass Growth | On | Grass spreads naturally. | Stops Grass Blocks from spreading. |
| Vine Growth | On | Vines spread naturally. | Stops Vines from spreading. |
| Mycelium Spread | On | Mycelium spreads naturally. | Stops Mycelium from spreading. |
| Sculk Growth | On | Sculk spreads naturally. | Stops Sculk and Sculk Veins from spreading. |
| Leaf Decay | On | Leaves decay naturally. | Prevents leaves from decaying. |

## Weather & Time

| Control | Default | Cycle |
| --- | --- | --- |
| Weather | Server Weather | Server Weather → Clear → Rain |
| Time | Server Time | Server Time → Day → Sunset → Night → Midnight → Dawn |

Server Weather and Server Time follow the world. The other choices give every player inside the claim a personal weather or fixed-time view. Day is fixed at noon; the remaining time choices use their named time of day.

These visual overrides are applied when a player enters the claim, update immediately for players already inside, and reset when they leave. They do not change the world's weather or time. In particular, the Weather choice does not control snow accumulation or melting; use Snow Fall and Snow Melt for that.

These controls affect regular player-owned claims. Admin claims are ignored by the spawning, block, fluid, combat, and environmental protection switches. Back returns to [claim management](managing-a-claim.md).

## Continue Learning

- [Manage a Claim](managing-a-claim.md)
- [Claim Trust](trust-levels.md)
- [Ranks](../ranks.md)
