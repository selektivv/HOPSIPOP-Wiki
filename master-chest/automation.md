# Automation Jobs

Automation Jobs process items already stored in a Master Chest network. Open them from the Automation Jobs button in the main menu or with `/mc jobs`.

## Job Types and Unlocks

| Job type | Unlock | Creation cost |
| --- | --- | --- |
| Delete | Available with the Master Chest | No machine cost |
| Stone Cut | Complete Stonemason | 10 Stonecutters from the network |
| Craft | Complete Crafterlands | 10 Crafters from the network |
| Smelt | Complete Furnacity | 10 Blast Furnaces from the network |

Machine costs are taken from the network when a new processing job is created. Editing an existing Craft recipe does not create a second job or charge the creation cost again.

## Creating a Delete Job

1. Open Automation Jobs and select Delete Jobs.
2. Select Add Delete Job.
3. Place one sample of the unwanted item into the filter slot.
4. Save the job.

The sample item is returned to you. By default, the job deletes all matching items. Shift-click the job repeatedly to cycle through keep amounts if you want the network to retain a minimum stock.

Delete jobs are ideal for renewable junk, but use them carefully: deletion is automatic and cannot be undone.

## Creating a Craft Job

1. Store at least 10 Crafters in the target network.
2. Open the Craft Jobs tab and select Add Craft Job.
3. Place one sample item in each required position of the three-by-three recipe grid.
4. Confirm that the expected result appears.
5. Save the job.

The samples are returned to you. The job consumes recipe ingredients from the network and stores the crafted result back in the same network.

## Creating a Stone Cut Job

1. Store at least 10 Stonecutters in the target network.
2. Open the Stone Cut Jobs tab and select Add Stone Cut Job.
3. Place a sample input item on the left.
4. Select one of the valid outputs shown on the right.
5. Save the job.

## Creating a Smelt Job

1. Store at least 10 Blast Furnaces in the target network.
2. Open the Smelt Jobs tab and select Add Smelt Job.
3. Place a sample input item and a valid blast-furnace fuel in their slots.
4. Check the output preview.
5. Save the job.

The job consumes both input and fuel from the network and adds the blasted result back to it.

## Controlling Existing Jobs

- Normal-click a Stone Cut, Smelt, or Delete job to enable or disable it.
- Press the Drop key while pointing at a Craft job to enable or disable it.
- Normal-click a Craft job to edit its recipe.
- Shift-click a job to cycle its minimum-stock setting.
- Right-click a job to delete it.

A minimum-stock value changes how a job behaves:

- Processing jobs pause when the result has reached the selected amount.
- Delete jobs keep the selected amount and delete only the excess.
- A value of zero means continuous production for processing jobs and delete-all behavior for Delete jobs.

Deleting a paid processing job may refund some or all of its ten machine items. The refund percentage depends on the network owner's capacity rank.

## Avoiding Conflicts

- Do not create a Delete job for the output of a job you want to keep.
- Set a sensible minimum stock to prevent endless processing.
- Keep enough capacity free for job outputs.
- Keep required ingredients and fuel in the same network that owns the job.
- Remember that automation in a shared network belongs to that network's owner.

