# Fishing

MasterFishing replaces many vanilla catches with collectible fish. There are 1,000 species with individual icons, sizes, values, rarities, biome pools, and flavor text.

Sell catches for [Capacity](capacity.md) and Entropy, improve your rod, and compete in automatic fishing tournaments.

## Start Fishing

1. Run `/fish` to open the Fishing menu.
2. Open the Rod Shop and claim the free Apprentice Rod or buy a stronger rod.
3. Fish normally in any body of water.
4. Hover over a catch to see its rarity, size, exact Capacity value, and species story.
5. Run `/fish sell` to sell selected catches or every fish in your inventory.

A normal fishing rod can also catch MasterFish. Special rods increase the replacement chance, improve rarity luck, and hold augments.

## Catching Fish

The base chance for a vanilla catch to become a MasterFish is 65%. If this roll fails, the original vanilla catch remains.

When it succeeds, the plugin:

1. rolls a rarity;
2. applies rod, bait, and Luck Crystal upgrades;
3. builds a species pool for the current biome;
4. chooses a weighted species;
5. rolls its size in centimeters;
6. calculates and stores its final Capacity value on the item.

Larger specimens of the same species are worth more. Some species only enter the pool in matching biomes, while unrestricted species can be caught anywhere.

## Rarities

These are the starting weights before luck upgrades.

| Rarity | Base chance | Species |
| --- | ---: | ---: |
| Common | 60% | 350 |
| Uncommon | 25% | 250 |
| Rare | 10% | 180 |
| Epic | 4% | 120 |
| Legendary | 0.9% | 70 |
| Mythic | 0.1% | 30 |

Luck does not replace this table with a flat bonus. After the initial rarity roll, each successful luck check upgrades the catch by one tier. The upgrade chance is halved after every successful step, which keeps Legendary and Mythic catches uncommon even with strong equipment.

## Rods

The listed fish chance is the 65% base chance after the rod multiplier, before Treasure Crystal bonuses.

| Rod | Slots | Fish chance | Rarity luck | Price |
| --- | ---: | ---: | ---: | ---: |
| Apprentice Rod | 1 | 65% | — | Free |
| Journeyman Rod | 2 | 74.75% | +5% | 300 Entropy |
| Expert Rod | 3 | 84.5% | +12% | 900 Entropy |
| Master Rod | 4 | 97.5% | +22% | 2,200 Entropy |

Buy rods through `/fish shop`.

## Bait

Hold bait in your offhand before casting. One bait is consumed when the line is cast, and its luck bonus applies to that catch.

| Bait | Rarity luck | Price |
| --- | ---: | ---: |
| Plain Bait | +5% | 15 Entropy |
| Glimmer Bait | +15% | 60 Entropy |
| Abyssal Bait | +30% | 180 Entropy |

## Augment Crystals

Open `/fish augment catalog` to compare crystals, or buy them through `/fish shop`.

| Crystal | Tier I | Tier II | Tier III |
| --- | --- | --- | --- |
| Luck | +6% rarity luck | +14% | +25% |
| Treasure | +5 percentage points fish chance | +12 points | +20 points |
| Swift | 10% shorter wait | 25% shorter | 45% shorter |
| Autosell | Common | Up to Uncommon | Up to Rare |
| Surge | 5% double catch | 12% | 20% |

Autosell immediately converts catches at or below its threshold into Capacity and Entropy. Surge places the additional fish directly in your inventory, or drops it beside you if the inventory is full.

> **Current Swift status:** Swift crystals are available and display their configured effect, but the current catch listener does not yet apply their wait-time multiplier.

### Apply a Crystal

1. Hold the MasterFishing rod in your main hand.
2. Hold the crystal in your offhand.
3. Run `/fish augment apply`.

Each augment type occupies one slot. Applying a higher tier of an augment already on the rod upgrades it without taking another slot. Equal or lower tiers are rejected.

Run `/fish augment remove <augment-id>` to free its slot. Removal destroys the installed crystal; it is not returned.

Augment IDs are `luck`, `treasure`, `swift`, `autosell`, and `surge`.

## Selling and Entropy

Every sold fish pays its stored value in [Capacity](capacity.md) and currently grants 1 Entropy.

| Command | Action |
| --- | --- |
| `/fish sell` | Open the sell menu |
| `/fish sell hand` | Sell the fish stack in your main hand |
| `/fish sell all` | Sell every MasterFish in your inventory |

The sell menu lets you click individual fish or use **Sell All**.

Entropy is the Fishing shop currency. Spend it on rods, bait, and augment crystals. `/fish stats` shows your Entropy balance, total catches, and lifetime catch value.

### Master Chest Auto Fish Sell

At Quasar [rank](ranks.md), the Automation Jobs menu gains **Auto Fish Sell**. When enabled, it checks your storage network every 60 seconds, removes every stored MasterFish, and pays one combined sale.

See [Automation Jobs](master-chest/automation.md) for access to the automation menu.

## Roadmap Progress

Selling fish advances four permanent roadmap milestones.

| Lifetime fish sold | Reward |
| ---: | --- |
| 100 | Mobile Grindstone |
| 500 | Mobile Smithing Table |
| 1,000 | Mobile Enchanting Table |
| 3,000 | Mobile Anvil |

The counter increases through manual selling, Autosell crystals, and Master Chest Auto Fish Sell.

## Fishing Tournaments

The server checks for an automatic tournament every 20 minutes. A random 10-minute tournament starts when at least two players are online and no tournament is already active.

| Mode | Winning score |
| --- | --- |
| Total Value | Highest combined Capacity value of tournament catches |
| Catch Count | Most fish caught |
| Biggest Fish | Largest single catch in centimeters |
| Biome Hunt | Most catches made in the announced target biome |
| Biome Variety | Most different biomes with at least one catch |

A boss bar shows the remaining time. Standings are broadcast every two minutes. Open `/fish top` to see the tournament status and the all-time top ten winners.

### Tournament Rewards

| Place | Capacity | Entropy |
| ---: | ---: | ---: |
| 1st | 1,500 | 250 |
| 2nd | 1,000 | 125 |
| 3rd | 500 | 50 |
| Participation | 100 | — |

You must record at least one scoring catch to receive a reward. Players with equal scores share a place and each receive the full reward for that place.

## Player Commands

| Command | Purpose |
| --- | --- |
| `/fish` | Open the main Fishing menu |
| `/fish shop` | Buy rods, bait, and crystals |
| `/fish sell [hand\|all]` | Sell catches |
| `/fish stats [player]` | View Fishing statistics |
| `/fish augment catalog` | Browse augment effects and prices |
| `/fish augment apply` | Apply the offhand crystal to the main-hand rod |
| `/fish augment remove <id>` | Remove and destroy an installed augment |
| `/fish top` | Open tournament status and Hall of Fame |
| `/fish tournament info` | Show the current tournament mode and time |

## Useful Tips

- Use the free Apprentice Rod before spending Entropy on upgrades.
- Bait is consumed on cast, so reserve Abyssal Bait for sessions where rarity matters.
- Treasure improves the chance of receiving any MasterFish; Luck improves its rarity afterward.
- Autosell is convenient, but catches above its rarity threshold still remain as collectible items.
- Check the active tournament mode before deciding between fast catches, high-value fish, large species, or biome travel.
- Keep inventory space free when using Surge so the bonus catch does not drop on the ground.
