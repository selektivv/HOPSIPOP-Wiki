# Coalworks

Coalworks is an automatic machine that turns Bamboo in your [MasterChest storage network](../master-chest/README.md) into Coal. It links to its owner when placed, so it does not need a MasterChest or another container beside it.

## Requirements

- Reach the **Quasar** [rank](../ranks.md) to discover the recipe and to craft or place Coalworks.
- Place it inside your own [claim](../claims.md).
- You can have up to **two Coalworks** placed at the same time.

## Crafting

Use this shaped recipe:

|  |  |  |
|---|---|---|
| Coal Block | Crafter | Coal Block |
| Iron Block | Heavy Core | Iron Block |
| Coal Block | Redstone Block | Coal Block |

## Processing Bamboo

Once placed, Coalworks automatically uses Bamboo from your own MasterChest network and sends the produced Coal back into the same network.

At its base level, each Coalworks converts **10 Bamboo into 1 Coal every 10 seconds**. It becomes active whenever the network contains enough Bamboo for a complete batch; otherwise, it remains passive and waits. There is no manual on/off switch.

Coalworks only processes while its chunk is loaded. Both placed machines work independently, but your upgrades apply to both of them.

> **Tip:** Store Bamboo anywhere in your network. You do not need to route it into the physical hopper or place a MasterChest above the Coalworks.

## The `/coalworks` Menu

Run `/coalworks`, use the Coalworks entry in `/shortcuts`, or right-click one of your placed machines to open the overview.

The menu shows:

- whether each Coalworks is active or passive;
- its coordinates;
- the total Bamboo converted and Coal produced;
- upgrades for processing speed and Bamboo efficiency;
- the design selector.

Click a placed Coalworks in the overview to retrieve it remotely. The block and its display are removed, and the Coalworks item is stored in your MasterChest network. If it cannot be stored there, it is returned to your inventory or dropped at your position.

Breaking a Coalworks also returns the special Coalworks item.

## Upgrades

Upgrade costs are paid with [Capacity](../capacity.md). Processing Speed and Bamboo Efficiency are separate upgrade paths, each with nine levels. Purchased levels belong to you and affect both of your Coalworks.

### Processing Speed

Each level reduces the time per batch by one second.

| Level | Time per Coal | Cost for this level |
|---:|---:|---:|
| 0 | 10 seconds | Base |
| 1 | 9 seconds | 10,000 Capacity |
| 2 | 8 seconds | 20,000 Capacity |
| 3 | 7 seconds | 30,000 Capacity |
| 4 | 6 seconds | 40,000 Capacity |
| 5 | 5 seconds | 50,000 Capacity |
| 6 | 4 seconds | 60,000 Capacity |
| 7 | 3 seconds | 70,000 Capacity |
| 8 | 2 seconds | 80,000 Capacity |
| 9 | 1 second | 90,000 Capacity |

### Bamboo Efficiency

Each level reduces the Bamboo required for one Coal by one. The upgrade price doubles with every level.

| Level | Bamboo per Coal | Cost for this level |
|---:|---:|---:|
| 0 | 10 | Base |
| 1 | 9 | 100,000 Capacity |
| 2 | 8 | 200,000 Capacity |
| 3 | 7 | 400,000 Capacity |
| 4 | 6 | 800,000 Capacity |
| 5 | 5 | 1,600,000 Capacity |
| 6 | 4 | 3,200,000 Capacity |
| 7 | 3 | 6,400,000 Capacity |
| 8 | 2 | 12,800,000 Capacity |
| 9 | 1 | 25,600,000 Capacity |

At maximum level in both paths, each Coalworks converts **1 Bamboo into 1 Coal every second** while its chunk is loaded.

## Designs

Open the design selector from `/coalworks` or through `/appearance`. Changing the design updates all of your placed Coalworks.

Available styles are Default, Cherry, Copper, Mangrove, Lapis Lazuli, Lush Cave, Medieval, Quartz, Cyberpunk, and Crying Obsidian. Locked designs can be previewed for two minutes; each design then has its own one-hour trial cooldown unless it is permanently unlocked by an operator.

## Continue Learning

- [MasterChest Storage Network](../master-chest/README.md)
- [Capacity](../capacity.md)
- [Ranks](../ranks.md)
- [Claims](../claims.md)
- [Shortcuts](../master-chest/shortcuts.md)
