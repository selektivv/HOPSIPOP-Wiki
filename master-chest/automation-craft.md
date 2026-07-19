# Craft Jobs

A Craft Job repeatedly runs one shaped or shapeless crafting recipe using ingredients stored in the job owner's network. It unlocks after completing **Crafterlands** and costs **10 Crafters** from that network.

## Before You Start

- Complete the Crafterlands milestone. Check current progression with `/roadmap`.
- Store at least 10 Crafters in the network. They are consumed only when a new job is created.
- Leave enough [Capacity](../capacity.md) for the recipe output.

## Create a Craft Job

1. Open `/mc jobs`.
2. Select the **Craft Jobs** tab.

   <img width="507" height="376" alt="image" src="https://github.com/user-attachments/assets/52cc089e-8fec-4936-9788-eec93a077b50" />
   
3. Click **Add Craft Job** in the top-right corner.
   <img width="1179" height="371" alt="image" src="https://github.com/user-attachments/assets/a50ab44a-b812-4012-9f2a-de5dd66238f9" />
   
4. Reproduce the recipe in the 3x3 grid. Each occupied slot uses one sample item from the cursor.
   <img width="572" height="582" alt="image" src="https://github.com/user-attachments/assets/a91678e6-afb0-42c1-be79-4f271bc25ef8" />
   
5. Check the result preview.
   <img width="826" height="382" alt="image" src="https://github.com/user-attachments/assets/68f91839-14ea-48a4-983c-48600c9e3cd5" />
   
6. Press **Save**.

   <img width="858" height="387" alt="image" src="https://github.com/user-attachments/assets/2cb10036-f650-4e6e-aa47-ba2a5e694295" />


The job is created only if the grid matches a registered shaped or shapeless crafting recipe and the network still contains 10 Crafters. The Crafters are then removed from the network. All grid samples return to the player's inventory; overflow is dropped at the player's location.

For a shaped recipe, the pattern may occupy any valid offset inside the 3x3 grid. For a shapeless recipe, the positions do not matter, but the number and allowed types of all ingredient slots must match.

## How It Works

On each automation check, an enabled Craft Job:

1. Resolves the saved grid to its current registered crafting recipe.
2. Stops if a configured minimum stock has already been reached.
3. Counts the complete ingredient requirement, including repeated materials.
4. Stops without consuming anything if an ingredient is missing.
5. Removes one recipe's ingredients from the network.
6. Stores the recipe's full result stack in the network.

One Craft Job performs at most one recipe operation per check. The runner normally checks every 5 server ticks, so a job can complete up to four operations per second when the server is running normally and all resources are available.

Only the recipe result is returned. Crafting remainders such as empty buckets or bottles are not added separately by the job.

## Minimum Stock

The default value `0` runs the recipe continuously whenever its ingredients are available. Shift-clicking the job selects a minimum result stock. Once the stored result count is at or above that value, the job pauses.

The stock is checked before a full recipe operation. A recipe with a multi-item result may therefore exceed the target by part of one batch. For example, a recipe producing four items can run at stock 63 with a target of 64 and finish at 67.

Changing the minimum also updates every other Craft, Stone Cut, or Smelt job whose output has the same material.

## Manage and Edit the Job

| Control | Effect |
| --- | --- |
| Click | Open the 3x3 recipe editor. |
| Drop key | Enable or disable the job. |
| Shift-click | Cycle the minimum stock. |
| Right-click | Permanently delete the job and apply the rank-based refund. |

Saving an edit keeps the job's enabled state and minimum stock. Editing does not charge another 10 Crafters.

Deleting the job refunds between 0 and 10 Crafters according to the owner's current Capacity rank. See the [refund table](automation.md#capacity-and-removing-paid-jobs).

## Item Matching and Capacity

Normal ingredients and results are counted by material, not by durability, enchantments, or names. Firework Rockets and the plugin's Master Chest, OmniSync, Lava Sponge, and Cell Tower items use exact stored item data.

Ingredients are removed before the result is stored. If the complete result does not fit, the part without Capacity has no inventory fallback. Keep enough free space for at least one full output batch.

## Continue Learning

- [All Automation Jobs](automation.md)
- [Stone Cut Jobs](automation-stone-cut.md)
- [Smelt Jobs](automation-smelt.md)
