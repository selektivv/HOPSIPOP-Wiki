# Smelt Jobs

A Smelt Job runs one regular furnace recipe with a selected fuel stored in the job owner's network. It unlocks after completing **Furnacity** and costs **10 Blast Furnaces** from that network.

## Before You Start

- Complete Furnacity. Check current progression with `/roadmap`.
- Store at least 10 Blast Furnaces in the network.
- Carry one sample of the input and one sample of the fuel to configure the job.

## Create a Smelt Job

1. Open `/mc jobs`.
2. Select the **Smelt Jobs** tab.

   <img width="652" height="377" alt="image" src="https://github.com/user-attachments/assets/3d914ce7-6c77-4801-aa78-4afa91239294" />

3. Click **Add Smelt Job** in the top-right corner.
   <img width="1381" height="371" alt="image" src="https://github.com/user-attachments/assets/6fa3aae1-ce1e-43bf-bf99-45661229353e" />

   The setup screen opens only while the network contains at least 10 Blast Furnaces.

4. Place the item to process in the upper-left input slot.

   <img width="515" height="375" alt="image" src="https://github.com/user-attachments/assets/4ffd6287-bca0-445c-b840-bdea4715ecbc" />

5. Place the chosen fuel in the lower-left fuel slot.

   <img width="510" height="379" alt="image" src="https://github.com/user-attachments/assets/2a0dac6c-c45a-4a3c-86ad-f542abb22d51" />

6. Confirm the output preview and press **Save**.

   <img width="872" height="381" alt="image" src="https://github.com/user-attachments/assets/60948c90-bfb6-4960-925d-be03ec093c64" />


The menu accepts only a registered regular **furnace recipe**. Blasting, smoker, and campfire recipes are not used unless the server also registers a normal furnace recipe for the same input. If multiple furnace recipes match, the first registered match supplies the preview and saved output.

Saving also validates the selected fuel and checks for 10 Blast Furnaces in the network. Those furnaces are removed when the job is created. Both setup samples return to the player's inventory; overflow is dropped at the player's location.

## Accepted Fuels

The job uses its own fixed fuel list. Each output consumes 100 fuel units, and unused units remain assigned to that job while the server process is running.

| Fuel | Fuel units per item |
| --- | ---: |
| Lava Bucket | 10,000 |
| Coal Block | 8,000 |
| Dried Kelp Block | 2,000 |
| Bamboo Block | 1,250 |
| Blaze Rod | 1,200 |
| Coal or Charcoal | 800 |
| Blaze Powder | 600 |
| Supported logs, stripped logs, wood, stripped wood, and planks | 150 |
| Stick | 25 |
| Bamboo | 12 |

The supported wood families are Oak, Spruce, Birch, Jungle, Acacia, Dark Oak, Mangrove, and Cherry. Their logs, stripped logs, wood, stripped wood, and planks are accepted; Bamboo Planks are also accepted. Items not in this table are rejected even if vanilla Minecraft can burn them elsewhere.

## How It Works

On each automation check, an enabled Smelt Job:

1. Stops if its configured minimum result stock has already been reached.
2. Stops if no matching input is stored.
3. If its fuel balance is below 100, removes at most one selected fuel item and adds that item's fuel units.
4. Once at least 100 units are available, removes one input, spends 100 units, and stores one output.

The runner normally checks every 5 server ticks. A job can therefore process up to four inputs per second when enough input and fuel credit are available. Low-value fuels may first require several checks: for example, nine Bamboo items provide 108 units and allow one output, leaving 8 units for later.

Automation reads stored counts from a network snapshot refreshed roughly every 15 seconds. Input or fuel deposited outside automation may therefore take up to about 15 seconds to become visible to the job.

A Lava Bucket adds an empty Bucket back to the network when consumed. No furnace experience is produced. Other container items are not created.

Fuel credit is held separately for each job, but it is not saved with the job configuration. Unused credit is reset by a server/plugin restart.

## Minimum Stock

At the default value `0`, the job runs whenever input and fuel are available. Shift-left selects a higher minimum result stock and Shift-right selects a lower one; the job pauses once that stock is at or above the selected value.

Changing the minimum also updates every other Craft, Stone Cut, or Smelt job whose output has the same material.

## Manage the Job

| Control | Effect |
| --- | --- |
| Click | Enable or disable the job. |
| Shift-left-click | Select the next higher minimum-stock preset. |
| Shift-right-click | Select the previous preset. |
| Right-click | Permanently delete the job and apply the rank-based refund. |

Deleting the job refunds between 0 and 10 Blast Furnaces according to the owner's current Capacity rank. See the [refund table](automation.md#capacity-and-removing-paid-jobs).

## Capacity Warning

The input and fuel are consumed before the result is stored. If the network is full, an output or returned empty Bucket that does not fit has no player-inventory fallback.

Normal inputs and results are counted by material. Firework Rockets and the plugin's Master Chest, OmniSync, Lava Sponge, and Cell Tower items use exact stored item data instead.

## Continue Learning

- [All Automation Jobs](automation.md)
- [Craft Jobs](automation-craft.md)
- [Stone Cut Jobs](automation-stone-cut.md)
