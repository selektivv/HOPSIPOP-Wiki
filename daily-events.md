# Daily Events

Daily Events are automatic 24-hour Master Chest competitions. Store the current event item in a Master Chest network; when the timer reaches zero, the networks with the three highest distinct item totals receive [Capacity](capacity.md).

## Join an Event

There is no sign-up command. A network participates automatically when it contains at least one of the current event item at the end of the event.

- The sidebar shows the current item and remaining time. If the sidebar is hidden, enable it through the [Shortcuts](master-chest/shortcuts.md) menu.
- `/mc guides` provides the in-game Daily Event Guide.
- Only items stored in the virtual Master Chest network count. Items in player inventories, Ender Chests, or ordinary containers are not included.
- The score and reward belong to the network owner. Items added to a [shared network](master-chest/sharing-networks.md) therefore support that network's owner.
- Players do not need to be online when the event ends.

## How an Event Works

1. The server scans non-operator Master Chest networks and selects the least common eligible item currently stored across them.
2. If no eligible stored item is available, the server chooses from a shuffled fallback pool.
3. The item is announced in game and on Discord, and the 24-hour timer begins.
4. Item totals can rise or fall throughout the event. Only the amount still stored when the timer reaches zero determines the result.
5. Rewards and results are announced, then the next item is selected and a new event starts.

Equipment, weapons, tools, arrows, pottery sherds, and several special items are excluded from selection. Dynamically selected items can repeat; the shuffled no-repeat rotation applies only when the fallback pool is needed.

## Rewards

| Placement | Capacity reward |
| --- | ---: |
| 1st | 10,000–20,000 |
| 2nd | 5,000–10,000 |
| 3rd | 1,000–5,000 |

The exact reward is chosen randomly within the placement's range and credited immediately. Event items are not removed from storage.

Ties share a placement. Each tied network owner receives a separate reward from that placement's range, and the next different item total takes the following placement. This means more than three players can receive rewards when totals are tied. Operator and moderator accounts are excluded from the results.

## Tracking the Event

The sidebar is the live source for the event item and countdown. The server announces the start and results in game and on Discord; Discord also receives a reminder during the final 20 minutes.

There is no public live-standings command. Keep the items in the correct network until the countdown ends, especially when using OmniSync or another player's shared storage.

## Continue Learning

- [Storage Network](master-chest/README.md)
- [Capacity](capacity.md)
- [Shared Networks](master-chest/sharing-networks.md)
- [Shortcuts](master-chest/shortcuts.md)
