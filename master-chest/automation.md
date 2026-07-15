# Automation Jobs

Automation Jobs process items inside one storage network. Open them with `/mc jobs`.

## Job Types

| Job | Result |
| --- | --- |
| Delete | Removes stock above a chosen amount. |
| Craft | Repeatedly crafts a selected recipe. |
| Stone Cut | Processes a selected stonecutter recipe. |
| Smelt | Uses a blast-furnace recipe and stored fuel. |

Jobs unlock through [progression](capacity-and-progression.md). Some paid jobs also require ten matching machine items from storage.

## Creating a Job

1. Choose the job type.
2. Select the input or recipe.
3. Set the amount to keep or produce.
4. Confirm the job.

A processing target of zero runs continuously. A Delete target of zero deletes all matching items.

## Safe Setup

- Keep ingredients, fuel, and output space in the same network.
- Leave enough [Capacity](../capacity.md) for results.
- Do not delete an item another job needs or produces.
- In shared storage, jobs belong to the network owner.

## Continue Learning

- [Hoppers](hoppers.md)
- [OmniSync](omnisync.md)
- [Storage Troubleshooting](troubleshooting.md)
