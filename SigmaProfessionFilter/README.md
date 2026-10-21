# Sigma Profession Filter (Vanilla+)

**Original addon by [Sigma88](https://github.com/Sigma88)**: https://github.com/Sigma88/Sigma-ProfessionFilter

All credit for the addon goes to Sigma88. This copy is based on v0.7.3 and has been adapted to run on the Vanilla+ (1.12) client. The original is released under an "All Rights Reserved" license; this copy is shared with credit, and will be removed if the author asks.

## What it does

Adds filters, sort options, text search, a "starred" (favourites) filter and an "unlearned recipes" view to the Trade Skill and Craft windows.

## Included folders

Copy all the folders you want into `Interface/AddOns/`. `SigmaProfessionFilter` is required; the rest are optional modules.

| Folder | Purpose |
|---|---|
| `SigmaProfessionFilter` | Core addon (required) |
| `SigmaProfessionFilter_RecipeInfo` | Extra recipe information for all professions |
| `SigmaProfessionFilterAlchemy` | Alchemy filters |
| `SigmaProfessionFilterBeastTraining` | Hunter Beast Training filters |
| `SigmaProfessionFilterCooking` | Cooking filters |
| `SigmaProfessionFilterEnchanting` | Enchanting filters, with auto-enchant and gear slot highlighting |
| `SigmaProfessionFilterFirstAid` | First Aid filters |
| `SigmaProfessionFilterPoisons` | Rogue Poisons filters |
| `SigmaProfessionFilterSmelting` | Smelting filters (called Mining in the original) |

## Changes from the original

I made a few small adjustments here and there for the Vanilla+ server. That was a long time ago and I didn't keep a record of exactly what changed. Compared with the original v0.7.3, this copy differs in these ways:

- Rewritten for the 1.12 API: no `...` addon table, a replacement for `hooksecurefunc`, and the frame hooks reworked to match.
- Mining module renamed to Smelting, with new Smelting and Beast Training recipe data. The Jewelcrafting and Mining data files were removed.
- Enchanting: new auto-enchant feature (it applies the enchant to the matching gear slot when the character panel is open) and gear slot highlighting.
- Bundled the reputation star icon, and added a local tooltip helper for craft descriptions.
- Removed the French and Russian translation files (English only).
