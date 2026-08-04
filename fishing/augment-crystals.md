# Augment Crystals

Augment Crystals permanently add specialized effects to a MasterFishing rod. Open `/fish augment catalog` to compare them, or use `/fish shop` and select **Augment Shop** to buy one. The six crystal types are split across two shop pages.

Each crystal type has its own texture. All four tiers of one type share that texture but keep their tier-specific name, color, effect, and price.

## Crystals, Tiers, and Prices

| Icon | Crystal | Tier I | Tier II | Tier III | Tier IV |
| --- | --- | --- | --- | --- | --- |
| <img src="../assets/fishing-gear/crystal-luck.png" width="48" height="48" alt="Luck Crystal"> | Luck | +6% rarity luck; 1,000 Entropy | +14%; 2,500 | +25%; 6,000 | +35%; 15,000 |
| <img src="../assets/fishing-gear/crystal-treasure.png" width="48" height="48" alt="Treasure Crystal"> | Treasure | +5 percentage points fish chance; 1,000 Entropy | +12 points; 2,500 | +20 points; 6,000 | +28 points; 15,000 |
| <img src="../assets/fishing-gear/crystal-swift.png" width="48" height="48" alt="Swift Crystal"> | Swift | 10% shorter wait; 1,000 Entropy | 25%; 2,500 | 45%; 6,000 | 65%; 15,000 |
| <img src="../assets/fishing-gear/crystal-autosell.png" width="48" height="48" alt="Autosell Crystal"> | Autosell | Common; 1,500 Entropy | Up to Uncommon; 4,000 | Up to Rare; 9,000 | Up to Epic; 20,000 |
| <img src="../assets/fishing-gear/crystal-surge.png" width="48" height="48" alt="Surge Crystal"> | Surge | 5% double catch; 2,000 Entropy | 12%; 5,000 | 20%; 11,000 | 28%; 24,000 |
| <img src="../assets/fishing-gear/crystal-titan.png" width="48" height="48" alt="Titan Crystal"> | Titan | 15% size bias; 1,200 Entropy | 35%; 3,000 | 55%; 7,200 | 80%; 18,000 |

## What Each Crystal Does

### Luck

Luck adds rarity luck after a MasterFish is selected. Successful luck checks can upgrade the catch by one or more rarity tiers, with the chance halved after each successful step. Its bonus combines with rod and [bait](bait.md) luck.

### Treasure

Treasure adds percentage points to the chance that a vanilla catch becomes a MasterFish. It is applied after the [rod](rods.md) multiplier, and the final chance is capped at 100%.

### Swift

Swift shortens the actual time until a bite. It also works alongside the fishing rod's vanilla Lure enchantment.

### Autosell

Autosell immediately converts catches at or below its rarity threshold into Capacity and Entropy. Tier I sells Common fish, while Tier IV sells Common through Epic fish. Higher-rarity catches stay in your inventory.

### Surge

Surge can create a second fish from one successful catch. A bonus fish respects the rod's Autosell threshold and Titan effect. If it is not sold, it enters your inventory or drops beside you when your inventory is full.

### Titan

Titan biases the random size roll toward the upper end of the selected species' size range. It does not add a fixed number of centimeters and does not guarantee a maximum-size fish. The bias also applies to a Surge bonus fish.

Luck, Treasure, Swift, Autosell, and Surge each produce their own particle signature around the bobber while active. Titan changes the size roll but does not add a bobber particle signature.

## Apply or Upgrade a Crystal

1. Hold the MasterFishing rod in your main hand.
2. Hold the crystal in your offhand.
3. Run `/fish augment apply`.

Each augment type occupies one slot. Applying a higher tier of a type already installed upgrades it without consuming another slot. Equal or lower tiers are rejected. Available slots depend on the [Fishing Rod](rods.md), from one on the Apprentice Rod to five on the Grandmaster Rod.

## Remove a Crystal

Run `/fish augment remove <augment-id>` to free its slot. Removing an augment destroys the installed crystal; it is not returned.

Valid IDs are `luck`, `treasure`, `swift`, `autosell`, `surge`, and `titan`.

## Related Articles

- [Fishing Guide](../fishing.md)
- [Fishing Rods](rods.md)
- [Baits](bait.md)
- [Bait Ingredients](bait-ingredients.md)
- [Capacity](../capacity.md)
