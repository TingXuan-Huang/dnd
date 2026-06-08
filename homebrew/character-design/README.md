---
type: module-index
since: "homebrew"
tags: [character-design, module, player-build]
updated: 2026-05-23
---

# Character Design Module

The home for everything a player picks **when building a character**. Backgrounds, species, subclasses, custom feats, alternative character-creation rules — all the choices that make a PC who they are.

This module sits parallel to (not inside) `homebrew/world/` (the world they live in) and `homebrew/00-dm-operating-manual.md` (how the DM runs them).

## Why this is its own module

Character build choices are a different layer from house rules. House rules tweak how the *game* works at the table. Character design defines what the *player* can build before the table starts. The two interact (Weave Strain affects how spellcasters experience the game), but they're authored differently and read by different people:

- **Players** open this folder during character creation. Once.
- **DMs** open this folder when a new player joins, when reviewing a build, or when designing new options.
- **House rules** open every session.

## Current contents

### Backgrounds

Custom Fallowton-flavored 2024-format backgrounds. Use these alongside (or instead of) the four BR-2024 backgrounds (Acolyte, Criminal, Sage, Soldier).

| Background | File | Theme | Origin feat |
|---|---|---|---|
| **Sinkhole Witness** | [`../../docs/campaign/background-sinkhole-witness.md`](../../docs/campaign/background-sinkhole-witness.md) (original location) | Lifelong villager present when the field collapsed | Alert |
| **Ruin Scholar** | [`backgrounds/ruin-scholar.md`](backgrounds/ruin-scholar.md) | Outsider who came *for* the seals | Skilled |
| **Failed Apprentice** | [`backgrounds/failed-apprentice.md`](backgrounds/failed-apprentice.md) | Was taught the price before paying it | Magic Initiate |
| **Mechanist** | [`backgrounds/mechanist.md`](backgrounds/mechanist.md) | Hands-on across mundane and Dawnweave devices | Skilled |
| **Village Doctor** | [`backgrounds/village-doctor.md`](backgrounds/village-doctor.md) | Healing without paying strain | Skilled |

Each links its Weave Strain hook back to [`../../docs/campaign/weave-strain-magic.md`](../../docs/campaign/weave-strain-magic.md).

> **Note on Sinkhole Witness location.** The original Fallowton background still lives at its original path in `docs/campaign/` rather than here, to avoid breaking inbound links from the player guide. Treated as part of this module by reference.

### Abilities & Lores

The Fallowton interpretation of the six abilities (what each score *means* socially in this village) plus the **sub-specialty Lore system** — narrow factual specialties (Dawnweave, Hedge, Crown Law, Voss-Family) that grant a free question per long rest and advantage on related checks.

| File | What it covers |
|---|---|
| [`abilities.md`](abilities.md) | Ability gloss · RAW generation method · 4 launch Lores |
| [`survival.md`](survival.md) | HP-in-Fallowton · 12-entry Wound table · Death Vision system · Hollow Star Long Look · healing rules |
| [`progression.md`](progression.md) | 18-skill Fallowton reading · Milestone leveling with 5 Story Beats · Tier crossing rituals · downtime preview |
| [`build-options.md`](build-options.md) | 5 Origin feats · 5 General feats incl. Fighting Style · 5 species lineage variants · background design template + 6 suggested future backgrounds |

### Species (planned)

Currently the 9 BR-2024 species are all permitted as-is (see [`wiki/species/`](../../wiki/species/)). Custom Fallowton-flavored species — sinkhole-touched humans, Dawnweave-blooded tieflings, etc. — are in the backlog (planned).

### Subclasses (planned)

Subclasses tied to Dawnweave lore (e.g. a Light cleric domain that doesn't trigger the Awakening Clock, or a wizard tradition trained in seal reading) will live here.

### Feats (planned)

Custom Origin feats and General feats that interact with Weave Strain, the Awakening Clock, or specific lore (e.g. "Dawnweave-Touched" — minor seal-reading proficiency; "Purified Channel" — first cast each day skips strain).

### Alternative character-creation rules (planned)

- House rules for ability score generation (point buy / standard array / 4d6-drop-lowest)
- Starting wealth variants
- Multiclassing tweaks for Weave Strain casters

## How players use this module

1. Read [`../../docs/player-guide/README.md`](../../docs/player-guide/README.md) for the canonical character creation walkthrough.
2. Pick a background from the table above (or the four BR-2024 backgrounds).
3. If your background has a Weave Strain hook, read [`../../docs/campaign/weave-strain-magic.md`](../../docs/campaign/weave-strain-magic.md).
4. Read [`../house-rules.md`](../house-rules.md) for table mechanics.

## How DMs add content here

Match the format of existing entities in this folder. Frontmatter convention follows [`../../wiki/_templates/`](../../wiki/_templates/).

## Cross-references

- World lore: [`../world/`](../world/)
- DM Operating Manual: [`../00-dm-operating-manual.md`](../00-dm-operating-manual.md)
- House rules: [`../house-rules.md`](../house-rules.md)
- Wiki of 5.5e rules: [`../../wiki/`](../../wiki/)
- Player guide: [`../../docs/player-guide/`](../../docs/player-guide/)
