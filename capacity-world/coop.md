# Co-op Mining

A Capacity World co-op lets a group contribute to one shared block counter. It is designed for actively mining together inside the world.

## Requirements

- The invited player must be online.
- Neither player can already belong to a different co-op.
- Both players must have enough Co-op Size levels for the resulting group size.
- A group can contain no more than four players.

## Inviting a Player

Use either method:

- Run `/coop <player>`.
- Right-click the player while both of you are in the Capacity World.

The invitation includes accept and decline controls and expires after 60 seconds. If both players invite each other, the invitations are accepted automatically.

To reject an invitation manually, use `/coop decline <player>`.

## Shared Counter Behavior

When the first two players form a group, the player with the better Counter Reduction becomes the initial group owner. The owner's block goal becomes the shared goal. Adding a later member does not automatically replace the current owner, even if that member has a better personal goal.

Shared progress activates while at least one other group member is online and inside the Capacity World. If nobody else in the group is actively in the world, your mining uses your own counter and personal goal.

When a shared goal is completed:

- Every group member receives one Capacity.
- If the player whose mining or drill completed the goal has an active Counter Boost, that player receives three Capacity instead.
- The boost does not triple the other members' rewards.
- The shared counter resets for the group.

Lucky Break can accelerate shared progress when a member mines manually. Chunk Drill blocks add one point each.

## Leaving a Co-op

Run `/coop leave` to leave manually. Leaving the Capacity World also removes you from the active group.

If the group owner leaves and several members remain, ownership moves to the remaining player with the best block goal. A group dissolves when too few members remain. All co-ops are also dissolved during a Capacity World reset.

## Practical Tips

- Compare Counter Reduction levels before creating the first pair.
- Make sure every intended member has purchased enough Co-op Size before sending invitations.
- Use Counter Boosts on the player doing most of the mining or operating the active drill.
- Re-form the group after a world reset.
