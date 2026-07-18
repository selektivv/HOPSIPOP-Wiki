# Stone Cut Jobs

A Stone Cut Job converts a stored input into one selected stonecutter output. It unlocks after completing **Stonemason** and costs **10 Stonecutters** from the job owner's network.

## Before You Start

- Complete the Stonemason milestone. Check current progression with `/roadmap`.
- Store at least 10 Stonecutters in the network.
- Carry one sample of the intended input block.

## Create a Stone Cut Job

1. Open `/mc jobs`.
2. Select the **Stone Cut Jobs** tab.
3. Click **Add Stone Cut Job** in the top-right corner.
4. Place the input sample in the slot on the left.
5. Click the desired output shown on the right.
6. Press **Save**.

The menu searches the server's registered stonecutting recipes for that input and displays up to the first nine results. Saving verifies that the selected output material still has a valid stonecutting recipe for the input.

The job is created only if the network still contains 10 Stonecutters. They are then removed. The input sample returns to the player's inventory; overflow is dropped at the player's location.

## How It Works

On each automation check, an enabled Stone Cut Job:

1. Stops if its configured minimum result stock has already been reached.
2. Checks for at least one matching input in the network.
3. Removes one input.
4. Stores one selected output item.

Each job performs at most one conversion per check. The runner normally checks every 5 server ticks, allowing up to four conversions per second under normal server timing.

The implementation stores one output item per input, even if a custom registered stonecutting recipe advertises a larger result stack.

## Minimum Stock

At the default value `0`, the job keeps converting as long as input is available. Shift-click selects a minimum result stock; the job pauses once the network is at or above it.

Changing the minimum also updates every other Craft, Stone Cut, or Smelt job whose output has the same material.

## Manage the Job

| Control | Effect |
| --- | --- |
| Click | Enable or disable the job. |
| Shift-click | Cycle the minimum stock. |
| Right-click | Permanently delete the job and apply the rank-based refund. |

Deleting the job refunds between 0 and 10 Stonecutters according to the owner's current Capacity rank. See the [refund table](automation.md#capacity-and-removing-paid-jobs).

## Item Matching and Capacity

Normal inputs and results are counted by material. Firework Rockets and the plugin's Master Chest, OmniSync, Lava Sponge, and Cell Tower items use exact stored item data instead.

The input is removed before the output is stored. If the network is full, an output that does not fit has no player-inventory fallback.

## Continue Learning

- [All Automation Jobs](automation.md)
- [Craft Jobs](automation-craft.md)
- [Smelt Jobs](automation-smelt.md)
