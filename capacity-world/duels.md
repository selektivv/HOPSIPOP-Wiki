# PvP Duels

The `/duel` command starts a protected one-on-one PvP fight on natural terrain in the [Capacity World](README.md). Both players are returned afterward, and the items they brought into the duel are restored.

## Sending a Challenge

Run `/duel <player>` using the exact name of an online player. You cannot challenge yourself, and neither player can already be fighting another duel.

The invited player has **60 seconds** to respond:

- `/duel accept` accepts the pending challenge.
- `/duel deny` declines it.
- `/duel decline` is an alternative decline command.

If the invitation expires, the challenger goes offline, or either player enters another duel first, it can no longer be accepted.

## Starting the Fight

After acceptance, the server saves both players' locations and inventories. It then searches for safe surface terrain in the Capacity World and places the players three blocks apart, facing each other. If no suitable location can be found after several attempts, the duel does not start.

The server announces the beginning of the duel globally. The players then have **five minutes** to fight. The arena uses normal Capacity World terrain and has no enclosing boundary.

## Winning and Reward

The first player to die loses the duel. The opponent is announced as the winner and receives the defeated player's head.

The head records:

- the defeated player's name and skin;
- the date and time of the duel;
- the winner's name.

The head is added to the winner's inventory. If there is no room, it drops at the winner's location.

## Inventory Protection

When the duel begins, the server records both players' 36 main inventory slots, armor, off-hand item, item metadata, quantities, and current durability.

When the duel ends, missing pre-duel items are returned and damaged equipment is repaired only back to the durability it had before the fight. This restoration is saved persistently, so it can still be completed after a disconnect or server restart. A player who is offline receives the restoration on their next join.

Experience, health, hunger, potion effects, and Ender Chest contents are not part of the duel snapshot.

## Duels Without a Winner

A duel is cancelled without a winner in any of these situations:

- neither player dies within five minutes;
- either player disconnects;
- the Capacity World begins resetting;
- the server restarts while the duel is active.

On cancellation, neither player receives a head. Both inventories are restored and both players return to their saved pre-duel locations. A disconnected player is restored and returned when they next join.

## Commands

| Command | Action |
|---|---|
| `/duel <player>` | Challenge an online player |
| `/duel accept` | Accept your pending challenge |
| `/duel deny` | Decline your pending challenge |
| `/duel decline` | Alternative decline command |

## Continue Learning

- [Capacity World](README.md)
- [World Rules](world-rules.md)
- [World Resets](resets.md)
