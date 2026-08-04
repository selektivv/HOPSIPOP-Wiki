# Bait Ingredients

Bait Ingredients are 110 collectible materials used to research and reproduce [Baits](bait.md) at the [Fishing Table](fishing-table.md). There are 11 private ingredient pools—one for each bait track—with ten ingredients in every pool. Every ingredient has its own resource-pack texture.

<img src="../assets/fishing-table/ingredient-textures.png" width="900" alt="All 110 Fishing Table ingredient textures">

## Sources and Base Chances

Ingredients have five tiers and five original source categories. Every ingredient rolls independently, so one chest or catch can award several different ingredients.

| Tier | Structure-loot chance | Fishing-source chance |
| ---: | ---: | ---: |
| 1 | 35% | 5% |
| 2 | 25% | 3.5% |
| 3 | 18% | 2.2% |
| 4 | 12% | 1.4% |
| 5 | 7% | 0.8% |

- **Trial Chambers:** normal and ominous reward chests of every rarity, corridor chests, intersection chests and barrels, and normal or ominous supply chests.
- **Villages:** fisher, fletcher, tannery, weaponsmith, toolsmith, armorer, butcher, cartographer, mason, shepherd, and temple chests, plus desert, plains, savanna, snowy, and taiga house chests.
- **Ancient Cities:** standard Ancient City and ice-box chests.
- **End Cities:** End City treasure chests.
- **Fishing:** an independent bonus roll after every successful MasterFish catch, including MasterFishing-rod lava catches.

## Fishing and Discovery Rules

Fishing-source ingredients are eligible from the start. A structure-source ingredient must first be found through its listed structure; after that permanent discovery, that same ingredient also becomes eligible as a fishing bonus using its structure-loot chance as the base rate.

Relic baits multiply the base rate. Salvage baits instead add flat percentage points. The final chance is `base chance × (1 + Relic bonus) + Salvage bonus`, capped at 100%; only the equipped bait contributes because one bait is consumed per cast.

A Surge or Shoal multicatch bonus fish triggers another complete set of ingredient rolls. Fishing rewards are deposited directly into MasterChest; if storage is unavailable or full, they fall back to your inventory and then drop beside you.

Structure ingredients are added only when an eligible vanilla loot container generates its contents for the first time. Opening the same generated chest again does not reroll its loot.

## Ingredient Catalog by Bait Track

Each ingredient below belongs only to the named track. Pools are sorted from lower to higher tiers for progression, and no ingredient is shared between two tracks.

### Fortune — Rarity Luck

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/fishing_waterlogged_twine.png" width="48" height="48" alt="Waterlogged Twine"><br>Waterlogged Twine | 1 | Successful MasterFish catch | 5% |
| <img src="../assets/fishing-table/ingredients/trial_vault_copper_shard.png" width="48" height="48" alt="Vault Copper Shard"><br>Vault Copper Shard | 1 | Eligible Trial Chamber loot | 35% |
| <img src="../assets/fishing-table/ingredients/village_fletchers_feather_bundle.png" width="48" height="48" alt="Fletcher's Feather Bundle"><br>Fletcher's Feather Bundle | 1 | Eligible village chest | 35% |
| <img src="../assets/fishing-table/ingredients/ancient_reverberating_bone.png" width="48" height="48" alt="Reverberating Bone"><br>Reverberating Bone | 2 | Ancient City or ice-box chest | 25% |
| <img src="../assets/fishing-table/ingredients/ancient_soul_fire_ember.png" width="48" height="48" alt="Soul Fire Ember"><br>Soul Fire Ember | 2 | Ancient City or ice-box chest | 25% |
| <img src="../assets/fishing-table/ingredients/end_elytra_thread.png" width="48" height="48" alt="Elytra Thread"><br>Elytra Thread | 2 | End City treasure chest | 25% |
| <img src="../assets/fishing-table/ingredients/end_shulker_shell_fragment.png" width="48" height="48" alt="Shulker Shell Fragment"><br>Shulker Shell Fragment | 2 | End City treasure chest | 25% |
| <img src="../assets/fishing-table/ingredients/trial_vault_latch_fragment.png" width="48" height="48" alt="Vault Latch Fragment"><br>Vault Latch Fragment | 2 | Eligible Trial Chamber loot | 25% |
| <img src="../assets/fishing-table/ingredients/village_leatherworkers_awl_tip.png" width="48" height="48" alt="Leatherworker's Awl Tip"><br>Leatherworker's Awl Tip | 2 | Eligible village chest | 25% |
| <img src="../assets/fishing-table/ingredients/fishing_tideworn_pearl.png" width="48" height="48" alt="Tideworn Pearl"><br>Tideworn Pearl | 3 | Successful MasterFish catch | 2.2% |

### Colossus — Size

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/trial_trial_ember_dust.png" width="48" height="48" alt="Trial Ember Dust"><br>Trial Ember Dust | 1 | Eligible Trial Chamber loot | 35% |
| <img src="../assets/fishing-table/ingredients/ancient_deep_dark_moss_clot.png" width="48" height="48" alt="Deep Dark Moss Clot"><br>Deep Dark Moss Clot | 2 | Ancient City or ice-box chest | 25% |
| <img src="../assets/fishing-table/ingredients/end_end_stone_grit.png" width="48" height="48" alt="End Stone Grit"><br>End Stone Grit | 2 | End City treasure chest | 25% |
| <img src="../assets/fishing-table/ingredients/fishing_coral_polyp_fragment.png" width="48" height="48" alt="Coral Polyp Fragment"><br>Coral Polyp Fragment | 2 | Successful MasterFish catch | 3.5% |
| <img src="../assets/fishing-table/ingredients/village_masons_chalk_dust.png" width="48" height="48" alt="Mason's Chalk Dust"><br>Mason's Chalk Dust | 2 | Eligible village chest | 25% |
| <img src="../assets/fishing-table/ingredients/village_nitwits_lucky_button.png" width="48" height="48" alt="Nitwit's Lucky Button"><br>Nitwit's Lucky Button | 2 | Eligible village chest | 25% |
| <img src="../assets/fishing-table/ingredients/ancient_warden_roar_fragment.png" width="48" height="48" alt="Warden Roar Fragment"><br>Warden Roar Fragment | 3 | Ancient City or ice-box chest | 18% |
| <img src="../assets/fishing-table/ingredients/end_void_touched_pearl_shard.png" width="48" height="48" alt="Void-Touched Pearl Shard"><br>Void-Touched Pearl Shard | 3 | End City treasure chest | 18% |
| <img src="../assets/fishing-table/ingredients/fishing_kelp_wrapped_hook.png" width="48" height="48" alt="Kelp-Wrapped Hook"><br>Kelp-Wrapped Hook | 3 | Successful MasterFish catch | 2.2% |
| <img src="../assets/fishing-table/ingredients/trial_trial_corridor_dust.png" width="48" height="48" alt="Trial Corridor Dust"><br>Trial Corridor Dust | 3 | Eligible Trial Chamber loot | 18% |

### Prosperity — Catch Value

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/fishing_sunken_net_fiber.png" width="48" height="48" alt="Sunken Net Fiber"><br>Sunken Net Fiber | 2 | Successful MasterFish catch | 3.5% |
| <img src="../assets/fishing-table/ingredients/trial_breeze_charm_fragment.png" width="48" height="48" alt="Breeze Charm Fragment"><br>Breeze Charm Fragment | 2 | Eligible Trial Chamber loot | 25% |
| <img src="../assets/fishing-table/ingredients/village_shepherds_wool_twine.png" width="48" height="48" alt="Shepherd's Wool Twine"><br>Shepherd's Wool Twine | 2 | Eligible village chest | 25% |
| <img src="../assets/fishing-table/ingredients/ancient_sculk_shrieker_membrane.png" width="48" height="48" alt="Sculk Shrieker Membrane"><br>Sculk Shrieker Membrane | 3 | Ancient City or ice-box chest | 18% |
| <img src="../assets/fishing-table/ingredients/ancient_soul_lantern_wax.png" width="48" height="48" alt="Soul Lantern Wax"><br>Soul Lantern Wax | 3 | Ancient City or ice-box chest | 18% |
| <img src="../assets/fishing-table/ingredients/end_chorus_marrow.png" width="48" height="48" alt="Chorus Marrow"><br>Chorus Marrow | 3 | End City treasure chest | 18% |
| <img src="../assets/fishing-table/ingredients/end_end_ship_compass_needle.png" width="48" height="48" alt="End Ship Compass Needle"><br>End Ship Compass Needle | 3 | End City treasure chest | 18% |
| <img src="../assets/fishing-table/ingredients/trial_windcharge_residue.png" width="48" height="48" alt="Windcharge Residue"><br>Windcharge Residue | 3 | Eligible Trial Chamber loot | 18% |
| <img src="../assets/fishing-table/ingredients/village_cartographers_compass_needle.png" width="48" height="48" alt="Cartographer's Compass Needle"><br>Cartographer's Compass Needle | 3 | Eligible village chest | 18% |
| <img src="../assets/fishing-table/ingredients/fishing_riverbed_clay_nodule.png" width="48" height="48" alt="Riverbed Clay Nodule"><br>Riverbed Clay Nodule | 4 | Successful MasterFish catch | 1.4% |

### Clockwork — Bite Speed

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/trial_ominous_bolt_coil.png" width="48" height="48" alt="Ominous Bolt Coil"><br>Ominous Bolt Coil | 2 | Eligible Trial Chamber loot | 25% |
| <img src="../assets/fishing-table/ingredients/ancient_catalyst_bloom_spore.png" width="48" height="48" alt="Catalyst Bloom Spore"><br>Catalyst Bloom Spore | 3 | Ancient City or ice-box chest | 18% |
| <img src="../assets/fishing-table/ingredients/ancient_whispering_sculk_bud.png" width="48" height="48" alt="Whispering Sculk Bud"><br>Whispering Sculk Bud | 3 | Ancient City or ice-box chest | 18% |
| <img src="../assets/fishing-table/ingredients/end_elytra_membrane_scrap.png" width="48" height="48" alt="Elytra Membrane Scrap"><br>Elytra Membrane Scrap | 3 | End City treasure chest | 18% |
| <img src="../assets/fishing-table/ingredients/fishing_anglerfish_lure_node.png" width="48" height="48" alt="Anglerfish Lure Node"><br>Anglerfish Lure Node | 3 | Successful MasterFish catch | 2.2% |
| <img src="../assets/fishing-table/ingredients/village_cartographers_ink_vial.png" width="48" height="48" alt="Cartographer's Ink Vial"><br>Cartographer's Ink Vial | 3 | Eligible village chest | 18% |
| <img src="../assets/fishing-table/ingredients/village_masons_grindstone_dust.png" width="48" height="48" alt="Mason's Grindstone Dust"><br>Mason's Grindstone Dust | 3 | Eligible village chest | 18% |
| <img src="../assets/fishing-table/ingredients/end_end_crystal_splinter.png" width="48" height="48" alt="End Crystal Splinter"><br>End Crystal Splinter | 4 | End City treasure chest | 12% |
| <img src="../assets/fishing-table/ingredients/fishing_deep_current_residue.png" width="48" height="48" alt="Deep Current Residue"><br>Deep Current Residue | 4 | Successful MasterFish catch | 1.4% |
| <img src="../assets/fishing-table/ingredients/trial_vault_rune_tablet.png" width="48" height="48" alt="Vault Rune Tablet"><br>Vault Rune Tablet | 4 | Eligible Trial Chamber loot | 12% |

### Shoal — Multicatch

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/ancient_ancient_bone_marrow_dust.png" width="48" height="48" alt="Ancient Bone Marrow Dust"><br>Ancient Bone Marrow Dust | 3 | Ancient City or ice-box chest | 18% |
| <img src="../assets/fishing-table/ingredients/fishing_abyssal_silt_clump.png" width="48" height="48" alt="Abyssal Silt Clump"><br>Abyssal Silt Clump | 3 | Successful MasterFish catch | 2.2% |
| <img src="../assets/fishing-table/ingredients/trial_chamber_static_node.png" width="48" height="48" alt="Chamber Static Node"><br>Chamber Static Node | 3 | Eligible Trial Chamber loot | 18% |
| <img src="../assets/fishing-table/ingredients/village_armorers_rivet.png" width="48" height="48" alt="Armorer's Rivet"><br>Armorer's Rivet | 3 | Eligible village chest | 18% |
| <img src="../assets/fishing-table/ingredients/ancient_silent_catalyst_dust.png" width="48" height="48" alt="Silent Catalyst Dust"><br>Silent Catalyst Dust | 4 | Ancient City or ice-box chest | 12% |
| <img src="../assets/fishing-table/ingredients/end_dragon_scale_fragment.png" width="48" height="48" alt="Dragon Scale Fragment"><br>Dragon Scale Fragment | 4 | End City treasure chest | 12% |
| <img src="../assets/fishing-table/ingredients/end_obsidian_star_fragment.png" width="48" height="48" alt="Obsidian Star Fragment"><br>Obsidian Star Fragment | 4 | End City treasure chest | 12% |
| <img src="../assets/fishing-table/ingredients/trial_mob_spawner_filament.png" width="48" height="48" alt="Mob Spawner Filament"><br>Mob Spawner Filament | 4 | Eligible Trial Chamber loot | 12% |
| <img src="../assets/fishing-table/ingredients/village_armorers_forge_slag.png" width="48" height="48" alt="Armorer's Forge Slag"><br>Armorer's Forge Slag | 4 | Eligible village chest | 12% |
| <img src="../assets/fishing-table/ingredients/fishing_bioluminescent_gland.png" width="48" height="48" alt="Bioluminescent Gland"><br>Bioluminescent Gland | 5 | Successful MasterFish catch | 0.8% |

### Wayfinder — Biome Focus

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/trial_resonant_trial_coil.png" width="48" height="48" alt="Resonant Trial Coil"><br>Resonant Trial Coil | 3 | Eligible Trial Chamber loot | 18% |
| <img src="../assets/fishing-table/ingredients/ancient_chiseled_dark_tablet.png" width="48" height="48" alt="Chiseled Dark Tablet"><br>Chiseled Dark Tablet | 4 | Ancient City or ice-box chest | 12% |
| <img src="../assets/fishing-table/ingredients/ancient_silent_vault_key.png" width="48" height="48" alt="Silent Vault Key"><br>Silent Vault Key | 4 | Ancient City or ice-box chest | 12% |
| <img src="../assets/fishing-table/ingredients/end_void_rift_shard.png" width="48" height="48" alt="Void Rift Shard"><br>Void Rift Shard | 4 | End City treasure chest | 12% |
| <img src="../assets/fishing-table/ingredients/fishing_pearlescent_shell_shard.png" width="48" height="48" alt="Pearlescent Shell Shard"><br>Pearlescent Shell Shard | 4 | Successful MasterFish catch | 1.4% |
| <img src="../assets/fishing-table/ingredients/village_weaponsmiths_anvil_chip.png" width="48" height="48" alt="Weaponsmith's Anvil Chip"><br>Weaponsmith's Anvil Chip | 4 | Eligible village chest | 12% |
| <img src="../assets/fishing-table/ingredients/village_weaponsmiths_whetstone.png" width="48" height="48" alt="Weaponsmith's Whetstone"><br>Weaponsmith's Whetstone | 4 | Eligible village chest | 12% |
| <img src="../assets/fishing-table/ingredients/end_dragon_breath_residue.png" width="48" height="48" alt="Dragon Breath Residue"><br>Dragon Breath Residue | 5 | End City treasure chest | 7.0% |
| <img src="../assets/fishing-table/ingredients/fishing_leviathan_whisker.png" width="48" height="48" alt="Leviathan Whisker"><br>Leviathan Whisker | 5 | Successful MasterFish catch | 0.8% |
| <img src="../assets/fishing-table/ingredients/trial_trial_chamber_sigil.png" width="48" height="48" alt="Trial Chamber Sigil"><br>Trial Chamber Sigil | 5 | Eligible Trial Chamber loot | 7.0% |

### Entropy — Entropy Bonus

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/trial_trial_spawner_cog.png" width="48" height="48" alt="Trial Spawner Cog"><br>Trial Spawner Cog | 1 | Eligible Trial Chamber loot | 35% |
| <img src="../assets/fishing-table/ingredients/ancient_resonating_skull_fragment.png" width="48" height="48" alt="Resonating Skull Fragment"><br>Resonating Skull Fragment | 4 | Ancient City or ice-box chest | 12% |
| <img src="../assets/fishing-table/ingredients/end_end_crystal_beam_dust.png" width="48" height="48" alt="End Crystal Beam Dust"><br>End Crystal Beam Dust | 4 | End City treasure chest | 12% |
| <img src="../assets/fishing-table/ingredients/fishing_riptide_current_vial.png" width="48" height="48" alt="Riptide Current Vial"><br>Riptide Current Vial | 4 | Successful MasterFish catch | 1.4% |
| <img src="../assets/fishing-table/ingredients/trial_vault_alloy_splinter.png" width="48" height="48" alt="Vault Alloy Splinter"><br>Vault Alloy Splinter | 4 | Eligible Trial Chamber loot | 12% |
| <img src="../assets/fishing-table/ingredients/village_butchers_twine_hook.png" width="48" height="48" alt="Butcher's Twine Hook"><br>Butcher's Twine Hook | 4 | Eligible village chest | 12% |
| <img src="../assets/fishing-table/ingredients/ancient_hollow_resonance_bell.png" width="48" height="48" alt="Hollow Resonance Bell"><br>Hollow Resonance Bell | 5 | Ancient City or ice-box chest | 7.0% |
| <img src="../assets/fishing-table/ingredients/end_end_void_filament.png" width="48" height="48" alt="End Void Filament"><br>End Void Filament | 5 | End City treasure chest | 7.0% |
| <img src="../assets/fishing-table/ingredients/trial_deepslate_vault_core.png" width="48" height="48" alt="Deepslate Vault Core"><br>Deepslate Vault Core | 5 | Eligible Trial Chamber loot | 7.0% |
| <img src="../assets/fishing-table/ingredients/village_village_bell_chime_shard.png" width="48" height="48" alt="Village Bell Chime Shard"><br>Village Bell Chime Shard | 5 | Eligible village chest | 7.0% |

### Reserve — Capacity Bonus

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/fishing_silver_scale_flake.png" width="48" height="48" alt="Silver Scale Flake"><br>Silver Scale Flake | 1 | Successful MasterFish catch | 5% |
| <img src="../assets/fishing-table/ingredients/trial_copper_vent_filings.png" width="48" height="48" alt="Copper Vent Filings"><br>Copper Vent Filings | 1 | Eligible Trial Chamber loot | 35% |
| <img src="../assets/fishing-table/ingredients/village_farmers_seed_pouch.png" width="48" height="48" alt="Farmer's Seed Pouch"><br>Farmer's Seed Pouch | 1 | Eligible village chest | 35% |
| <img src="../assets/fishing-table/ingredients/end_obsidian_spike_splinter.png" width="48" height="48" alt="Obsidian Spike Splinter"><br>Obsidian Spike Splinter | 4 | End City treasure chest | 12% |
| <img src="../assets/fishing-table/ingredients/trial_vindicators_cinder.png" width="48" height="48" alt="Vindicator's Cinder"><br>Vindicator's Cinder | 4 | Eligible Trial Chamber loot | 12% |
| <img src="../assets/fishing-table/ingredients/ancient_warden_heartcinder.png" width="48" height="48" alt="Warden Heartcinder"><br>Warden Heartcinder | 5 | Ancient City or ice-box chest | 7.0% |
| <img src="../assets/fishing-table/ingredients/ancient_warden_sinew_thread.png" width="48" height="48" alt="Warden Sinew Thread"><br>Warden Sinew Thread | 5 | Ancient City or ice-box chest | 7.0% |
| <img src="../assets/fishing-table/ingredients/fishing_leviathan_scale_plate.png" width="48" height="48" alt="Leviathan Scale Plate"><br>Leviathan Scale Plate | 5 | Successful MasterFish catch | 0.8% |
| <img src="../assets/fishing-table/ingredients/village_elder_villagers_signet.png" width="48" height="48" alt="Elder Villager's Signet"><br>Elder Villager's Signet | 5 | Eligible village chest | 7.0% |
| <img src="../assets/fishing-table/ingredients/village_toolsmiths_filings.png" width="48" height="48" alt="Toolsmith's Filings"><br>Toolsmith's Filings | 5 | Eligible village chest | 7.0% |

### Twofold — Double Value

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/ancient_sculk_sensor_splinter.png" width="48" height="48" alt="Sculk Sensor Splinter"><br>Sculk Sensor Splinter | 1 | Ancient City or ice-box chest | 35% |
| <img src="../assets/fishing-table/ingredients/end_purpur_dust.png" width="48" height="48" alt="Purpur Dust"><br>Purpur Dust | 1 | End City treasure chest | 35% |
| <img src="../assets/fishing-table/ingredients/fishing_brackish_roe_cluster.png" width="48" height="48" alt="Brackish Roe Cluster"><br>Brackish Roe Cluster | 1 | Successful MasterFish catch | 5% |
| <img src="../assets/fishing-table/ingredients/trial_breeze_vane_sliver.png" width="48" height="48" alt="Breeze Vane Sliver"><br>Breeze Vane Sliver | 1 | Eligible Trial Chamber loot | 35% |
| <img src="../assets/fishing-table/ingredients/village_librarians_bookmark_ribbon.png" width="48" height="48" alt="Librarian's Bookmark Ribbon"><br>Librarian's Bookmark Ribbon | 1 | Eligible village chest | 35% |
| <img src="../assets/fishing-table/ingredients/ancient_deep_dark_core_shard.png" width="48" height="48" alt="Deep Dark Core Shard"><br>Deep Dark Core Shard | 5 | Ancient City or ice-box chest | 7.0% |
| <img src="../assets/fishing-table/ingredients/end_end_gateway_residue.png" width="48" height="48" alt="End Gateway Residue"><br>End Gateway Residue | 5 | End City treasure chest | 7.0% |
| <img src="../assets/fishing-table/ingredients/fishing_abyssal_core_pearl.png" width="48" height="48" alt="Abyssal Core Pearl"><br>Abyssal Core Pearl | 5 | Successful MasterFish catch | 0.8% |
| <img src="../assets/fishing-table/ingredients/trial_vault_prism_sliver.png" width="48" height="48" alt="Vault Prism Sliver"><br>Vault Prism Sliver | 5 | Eligible Trial Chamber loot | 7.0% |
| <img src="../assets/fishing-table/ingredients/village_temple_incense_ash.png" width="48" height="48" alt="Temple Incense Ash"><br>Temple Incense Ash | 5 | Eligible village chest | 7.0% |

### Relic — Ingredient Multiplier

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/ancient_deep_dark_charcoal_fleck.png" width="48" height="48" alt="Deep Dark Charcoal Fleck"><br>Deep Dark Charcoal Fleck | 1 | Ancient City or ice-box chest | 35% |
| <img src="../assets/fishing-table/ingredients/ancient_sculk_vein_residue.png" width="48" height="48" alt="Sculk Vein Residue"><br>Sculk Vein Residue | 1 | Ancient City or ice-box chest | 35% |
| <img src="../assets/fishing-table/ingredients/end_chorus_petal_dust.png" width="48" height="48" alt="Chorus Petal Dust"><br>Chorus Petal Dust | 1 | End City treasure chest | 35% |
| <img src="../assets/fishing-table/ingredients/end_shulker_membrane_scrap.png" width="48" height="48" alt="Shulker Membrane Scrap"><br>Shulker Membrane Scrap | 1 | End City treasure chest | 35% |
| <img src="../assets/fishing-table/ingredients/trial_ominous_trial_key.png" width="48" height="48" alt="Ominous Trial Key"><br>Ominous Trial Key | 1 | Eligible Trial Chamber loot | 35% |
| <img src="../assets/fishing-table/ingredients/fishing_barnacle_cluster.png" width="48" height="48" alt="Barnacle Cluster"><br>Barnacle Cluster | 2 | Successful MasterFish catch | 3.5% |
| <img src="../assets/fishing-table/ingredients/village_fishers_net_twine.png" width="48" height="48" alt="Fisher's Net Twine"><br>Fisher's Net Twine | 2 | Eligible village chest | 25% |
| <img src="../assets/fishing-table/ingredients/end_void_forged_pearl_core.png" width="48" height="48" alt="Void-Forged Pearl Core"><br>Void-Forged Pearl Core | 5 | End City treasure chest | 7.0% |
| <img src="../assets/fishing-table/ingredients/fishing_krakenbone_splinter.png" width="48" height="48" alt="Krakenbone Splinter"><br>Krakenbone Splinter | 5 | Successful MasterFish catch | 0.8% |
| <img src="../assets/fishing-table/ingredients/trial_sovereign_trial_core.png" width="48" height="48" alt="Sovereign Trial Core"><br>Sovereign Trial Core | 5 | Eligible Trial Chamber loot | 7.0% |

### Salvage — Flat Ingredient Chance

| Ingredient | Tier | Original source | Base chance |
| --- | ---: | --- | ---: |
| <img src="../assets/fishing-table/ingredients/ancient_warden_echo_shard.png" width="48" height="48" alt="Warden Echo Shard"><br>Warden Echo Shard | 1 | Ancient City or ice-box chest | 35% |
| <img src="../assets/fishing-table/ingredients/end_purpur_tile_chip.png" width="48" height="48" alt="Purpur Tile Chip"><br>Purpur Tile Chip | 1 | End City treasure chest | 35% |
| <img src="../assets/fishing-table/ingredients/fishing_minnow_scale_dust.png" width="48" height="48" alt="Minnow Scale Dust"><br>Minnow Scale Dust | 1 | Successful MasterFish catch | 5% |
| <img src="../assets/fishing-table/ingredients/village_tanners_hide_scrap.png" width="48" height="48" alt="Tanner's Hide Scrap"><br>Tanner's Hide Scrap | 1 | Eligible village chest | 35% |
| <img src="../assets/fishing-table/ingredients/ancient_reinforced_deepslate_chip.png" width="48" height="48" alt="Reinforced Deepslate Chip"><br>Reinforced Deepslate Chip | 2 | Ancient City or ice-box chest | 25% |
| <img src="../assets/fishing-table/ingredients/end_end_ship_rivet.png" width="48" height="48" alt="End Ship Rivet"><br>End Ship Rivet | 2 | End City treasure chest | 25% |
| <img src="../assets/fishing-table/ingredients/fishing_driftwood_splinter.png" width="48" height="48" alt="Driftwood Splinter"><br>Driftwood Splinter | 2 | Successful MasterFish catch | 3.5% |
| <img src="../assets/fishing-table/ingredients/trial_ember_conduit_coil.png" width="48" height="48" alt="Ember Conduit Coil"><br>Ember Conduit Coil | 2 | Eligible Trial Chamber loot | 25% |
| <img src="../assets/fishing-table/ingredients/village_clerics_blessed_chalk.png" width="48" height="48" alt="Cleric's Blessed Chalk"><br>Cleric's Blessed Chalk | 2 | Eligible village chest | 25% |
| <img src="../assets/fishing-table/ingredients/fishing_maelstrom_whisker_coil.png" width="48" height="48" alt="Maelstrom Whisker Coil"><br>Maelstrom Whisker Coil | 5 | Successful MasterFish catch | 0.8% |

## Using Ingredients at the Fishing Table

Research checks your normal inventory and MasterChest together. When you unlock a recipe, ingredients are consumed from your inventory first and any remainder is removed from MasterChest automatically.

Repeat crafting uses the Fishing Table's 3×3 grid. For that screen, retrieve the required ingredient from MasterChest and place the exact item and amount in the grid.

## Related Articles

- [Baits](bait.md)
- [Fishing Table](fishing-table.md)
- [Fishing Guide](../fishing.md)
- [All Fish Species](../fish-species.md)
