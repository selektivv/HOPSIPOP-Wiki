# Hoppers and Physical Access Points

A placed Master Chest acts as a bridge between normal Minecraft containers and the virtual network.

## Automatic Input

Hoppers can feed items into a placed Master Chest. Items placed in the Master Chest's physical buffer are also absorbed into its owner's virtual network.

If the network is full, items that do not fit remain in the physical container or source inventory instead of being destroyed.

## Unfiltered Output

Place a hopper directly below the Master Chest to pull items out of the network. Without a filter, it pulls arbitrary stored items, so use this only when the exact output does not matter.

## Filtered Output

Filtered output is a Nova [rank](../ranks.md) perk.

1. Place a hopper, dispenser, or dropper within 12 blocks of your Master Chest.
2. Attach an Item Frame to that container.
3. Put one sample of the desired item in the frame.
4. Leave space in the container.

The Master Chest pulls matching items from the network into that container. The item in the frame is only the filter sample; it does not need to be consumed.

The network owner must be online for filtered output to run, and the owner must have the Nova hopper-filter perk.

## Placement Notes

- A Master Chest remains a single chest even beside a normal chest or another Master Chest.
- Pistons cannot move a placed Master Chest.
- Breaking it returns the special Master Chest item.
- Breaking an access point does not delete virtual network contents.
- Hopper input and output stop when the relevant chunks are not loaded.

## Recommended Setup

Use one placed Master Chest as a clearly labeled network terminal. Feed bulk farm output into it from above or the side. Put deliberate filtered-output containers nearby, and avoid an unfiltered hopper directly underneath unless random output is acceptable.

## Continue Learning

- Review how to [place and move Master Chest access points](getting-started.md).
- Use [automation jobs](automation.md) to process items after hopper input.
- Keep enough [Capacity](../capacity.md) available for incoming items.
- Check [storage troubleshooting](troubleshooting.md) when output is incorrect.
