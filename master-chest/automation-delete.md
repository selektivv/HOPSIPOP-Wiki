# Delete Jobs

A Delete Job continuously removes one selected item material from the job owner's storage network. It is available as soon as the player has unlocked Master Chest storage and has no creation cost.

## Create a Delete Job

1. Open `/mc jobs`.
2. Select the **Delete Jobs** tab.

   <img width="613" height="378" alt="image" src="https://github.com/user-attachments/assets/a2cdf31e-4888-47c6-8016-f3371c187477" />

3. Click **Add Delete Job** in the top-right corner.
   <img width="1484" height="371" alt="image" src="https://github.com/user-attachments/assets/46f1c79f-9f27-4a01-bbfc-03e1ac7d3ca5" />

4. Place one sample of the item to delete in the center slot.
   <img width="600" height="273" alt="image" src="https://github.com/user-attachments/assets/fd2872fc-164a-43f8-ab36-0107cddfde98" />

5. Press **Save**.

   <img width="894" height="270" alt="image" src="https://github.com/user-attachments/assets/f2f37a8d-4aad-42d7-b307-b1111877955e" />


The sample item is returned after saving. Closing the setup menu without saving also returns it.

When Save is pressed, the job counts all matching items already stored in the network and uses that exact count as its initial **Keep** value. The job is created enabled, but the stock that existed during creation is therefore protected.

## How It Works

Every automation check, the enabled job counts all matching items in the network:

- The initial keep value is the matching network stock counted when the job was created. For example, creating the job while 91 matching items are stored starts it at **Keep: 91**. Later stock above 91 is deleted.
- If no matching item was stored during creation, the keep value starts at `0`, so every matching item added later is removed.
- At any manually selected value of `0`, it removes the entire matching stock.
- Above `0`, it removes `current stock - keep value`. For example, with 91 items and **Keep: 64**, it deletes 27 and leaves 64.
- If the current stock is already at or below the keep value, nothing is removed.

The excess is deleted in one check rather than one item at a time. Deleted items cannot be recovered.

## Which Items Match?

For normal items, the filter matches the material only. Different durability, enchantments, names, or other metadata do not protect an item from the filter. For example, a normal Bow filter can delete both damaged and enchanted bows.

Firework Rockets and the plugin's Master Chest, OmniSync, Lava Sponge, and Cell Tower items are exceptions: these use an exact item match, including their stored item data.

## Manage the Job

| Control | Effect |
| --- | --- |
| Click | Enable or disable the filter. |
| Shift-click | Cycle the amount to keep. |
| Right-click | Permanently delete the job. |

The initial keep value can be any current stock count. Shift-click moves from that value to the next higher preset: `16`, `32`, `64`, `128`, `256`, `512`, `1,024`, `2,048`, `4,096`, `8,192`, `16,384`, `20,000`, `32,768`, `50,000`, `75,000`, or `100,000`. From `100,000` or any higher value, the next shift-click selects `0`.

## Safety

- A new filter starts enabled but preserves the matching stock present at creation. Review the displayed **Keep** value before adding or removing large amounts.
- Creating the filter while none of the selected item is stored starts it at **Delete all**.
- Do not target an ingredient used by another [Automation Job](automation.md).
- Right-click removes only the job. It does not restore items that the job already deleted.

## Continue Learning

- [All Automation Jobs](automation.md)
- [Craft Jobs](automation-craft.md)
- [Storage Troubleshooting](troubleshooting.md)
