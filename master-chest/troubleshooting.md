# Troubleshooting and Safety

## The Master Chest Says It Is Locked

Equip a full iron armor set at least once, then complete the Verdant dungeon. Use `/roadmap` to confirm which step is incomplete.

## I Cannot Craft OmniSync

Complete the Mobmon dungeon first. Use one Eye of Ender and eight normal Chests; special plugin items cannot replace the normal ingredients.

## My Items Went Into Someone Else's Network

OmniSync linking changes the default network opened by `/mc`, a portable Master Chest, and your own placed access points. Right-click OmniSync, select My Own Network, and verify the owner before depositing again.

## A Deposit Only Moved Part of a Stack

The target network reached its item-[capacity](../capacity.md) limit. Open Shortcuts to check free space, remove items, or earn more [capacity](../capacity.md). The unstored remainder should stay in the source inventory, physical buffer, or on the cursor.

## Right-Click Only Gives Me One Item

That is the intended control. Left-click a stored entry to retrieve up to one full stack; right-click retrieves one item.

## OmniSync Does Not Restock

Check all of the following:

- OmniSync is somewhere in your carried inventory.
- You are not in Creative or Spectator mode.
- The selected network contains a matching item.
- The used item is a supported block, food, firework rocket, experience bottle, or bone meal.
- The shared-network owner still grants you access.

## An Automation Job Does Nothing

- Confirm that the job is enabled.
- Confirm that the network contains its ingredients, input, and fuel.
- Check whether the result has already reached the minimum-stock target.
- Make sure there is free Master Chest [capacity](../capacity.md) for the result.
- For Smelt jobs, use an input with a blast-furnace recipe and a valid fuel.

## A Shared Network Is Missing

The owner has not invited you or has removed your access. Ask the owner to run `/mc invite <player>` again.

## Hopper Output Is Wrong

A hopper directly below the Master Chest is unfiltered and can pull arbitrary items. For precise output, use the Nova filtered-output setup with an Item Frame attached to the target hopper, dispenser, or dropper.

## Before Moving or Breaking a Master Chest

Virtual contents remain in the network. Items still visible in the chest's physical buffer are separate and are dropped when the access point is broken. Pick them up before leaving the area.

## Return to the Relevant Guide

- [Storage setup and access](getting-started.md)
- [Depositing and retrieving items](storing-and-retrieving.md)
- [OmniSync](omnisync.md)
- [Automation jobs](automation.md)
- [Hoppers and physical access points](hoppers.md)
