---
type: homebrew-rules
category: central-mechanic
since: "homebrew"
tags: [the-notice, hollow-star, corruption, awakening-clock, consolidated]
updated: 2026-05-23
status: needs-review
supersedes: ["awakening-clock", "hollow-star-corruption-tracker"]
---

# The Notice

The single central mechanical tracker of the Fallowton campaign. Replaces and consolidates **two previous systems**: the **Awakening Clock** (Module 1's hidden 0-6 timer) and the **Hollow Star Corruption Tracker** (the personal 0-6 sanity counter from `sanity-and-spirit.md`).

Eleven separate systems used to point at the Hollow Star theme; they all now resolve through this one number. Different thresholds produce different *expressions* of the same fundamental relationship: **how much the Hollow Star is aware of you.**

> **Why consolidate.** When everything is the Hollow Star, the Hollow Star becomes wallpaper. By unifying the trackers, the campaign's central horror keeps its weight. One number; one ledger; one terror.

---

## The two scales

The Notice has **two tracks**:

```
PERSONAL NOTICE:    0 ─ 1 ─ 2 ─ 3 ─ 4 ─ 5 ─ 6 ─ 7 ─ 8 ─ 9 ─ 10
                    clean      touched   marked   hollowing   bleeding   LOST

WORLD NOTICE:       0 ─ 1 ─ 2 ─ 3 ─ 4 ─ 5 ─ 6 ─ 7 ─ 8 ─ 9 ─ 10
                    dormant       stirring    aware        awake       presence
```

- **Personal Notice** — one number per PC. Tracks the Hollow Star's awareness of that character specifically. Public to the player; tracked on their character sheet.
- **World Notice** — one number for the region or specific site (the ruin under Fallowton; later, other Converter sites; even later, the world at large). Tracked behind the DM screen; surfaces through ambient effects.

### How they interact (the feedback loop)

The two scales **feed each other.** This is the engine of escalation.

- **When World Notice ticks up by N**, every PC within 60 ft of the source gains **+⌈N/2⌉ Personal Notice** (the world's attention spills onto you)
- **When a PC's Personal Notice reaches 7**, **World Notice gains +1** in the region they're in (your corruption is attracting attention to the world around you)
- **When a PC's Personal Notice reaches 10**, World Notice gains +1 *globally* — the Hollow Star has fully marked one person; the world feels it

This creates a vicious cycle. PCs who flirt with corruption make the world more aware; the more aware world corrupts them faster. Stopping requires intentional reduction (Sister Elra, cleansed spring, Long Hush, personal-sacrifice quest).

---

## Personal Notice thresholds

| Notice | Stage | Effects |
|---|---|---|
| **0** | **Clean** | Nothing. The body and the soul are aligned. |
| **1–2** | **Touched** | Bad dreams; rare insomnia (intersects with [`survival-realism.md`](survival-realism.md) §A2). Once per session, an ambient phenomenon notices you. No mechanical penalty. |
| **3–4** | **Marked** | NPCs sense it without being told (*"they see something behind your eyes"*). **Forbidden Choice unlocks**: once per long rest, consult the Hollow Star for one useful piece of campaign info, but **+1 Notice as the cost.** The first carrot. |
| **5–6** | **Hollowing** | Disadvantage on saves vs charm/fear from Dawnweave sources. Villagers shy away unprompted. Children stop talking when you enter. **Divine magic has 1-in-6 chance to falter.** Hollowed Wound healing time doubles for you. **Long Look effects fire** (per "Mechanical expressions" below). |
| **7–8** | **Bleeding** | Mind→Body bleed fires harder: lose **1 from a random physical stat** (per `sanity-and-spirit.md` §H6.1). Your **first leveled spell each day costs +1 Strain.** Revival from death = automatic Permanent Vision. **World Notice gains +1** in your region when you cross this threshold. |
| **9** | **Critical** | Hollow Star actively present in your dreams. Each session, **Personal Notice ticks +1 automatically** unless reduced. Lose another **1 physical stat**. Divine magic 2-in-6 chance to falter. NPCs you've known your whole life may refuse to meet your eyes. |
| **10** | **LOST** | **PC becomes NPC.** Player rolls a new character. The old PC may return later as antagonist, ally NPC with broken agency, or as a Marked-tier ghost (per `sanity-and-spirit.md` §H5). World Notice gains +1 globally. |

### Mechanical expressions of Personal Notice (the old systems, unified)

The following old systems are now **expressions of Personal Notice**, not separate trackers:

| Old system | New form |
|---|---|
| **Death Vision narration** (per `survival.md` §C) | Fires on every death save regardless of Notice. The *content* of the vision sharpens with Notice — at Notice 0 the player describes a random memory; at Notice 5+ they describe something the Hollow Star is *showing* them |
| **Death Vision nat-20 info-gift** | Available at any Notice. **Accepting it = +1 Notice.** This is now visible; players know the price |
| **Death Vision nat-1 memory loss** | Fires regardless of Notice. At Notice 5+, the loss becomes "stickier" — returns at dawn but feels off all day |
| **Hollow Star Long Look** (5+ death saves in a day) | This is a *Notice 5-6 trigger.* Without Notice 5+, the cumulative death saves do nothing extra. At Notice 5+, the Long Look fires |
| **Permanent Vision on revival** | Notice 7+ guarantees it. At Notice 4-6, revival triggers Permanent Vision on a failed Wis save DC 14. Below Notice 4, no Permanent Vision (the soul came back clean) |
| **Hollowed Wound** | A Wound caused by Dawnweave-touched damage. Adds **+1 Personal Notice** in addition to the existing wound effects |
| **Faith-Wound Trauma** (cleric/paladin spellcasting penalty) | Triggered at Notice 5+ when a cleric/paladin takes any Trauma. Mechanic unchanged |
| **The Awakening Clock** (M1's hidden timer) | Now World Notice for the Fallowton ruin |

---

## World Notice thresholds

World Notice is **regional**. Each major Converter site has its own. Fallowton's ruin is the campaign's first.

| World Notice | Stage | What players experience in the region |
|---|---|---|
| **0–2** | **Dormant** | Nothing supernatural. Normal world. |
| **3–4** | **Stirring** | Dust shifts on its own near the source. Torches flutter without wind. Animals avoid certain spots. The Awakening Clock effects 1-2 from old M1 = here. |
| **5–6** | **Aware** | Carvings flicker blue in the corner of someone's eye. One PC: **Wisdom save DC 11 or Frightened until end of next turn** (whispered name from the wall). M1's stage 3 fires here. |
| **7–8** | **Awake** | Floors creak before footsteps. Off-screen NPCs report bad dreams. A bell rings once without hands (Fallowton's surface bell — M1's stage 5). |
| **9–10** | **Presence** | The Hollow Star is locally manifest. The pool fills with black water (Pool Shudder); the village shrine candles all extinguish simultaneously; PCs cannot long-rest safely anywhere within 1 mile. M1's stage 6 — END SESSION. |

### What ticks World Notice UP

| Trigger | Tick |
|---|---|
| **Leveled spell cast in a Converter site** | +1 per cast |
| **A PC at Personal Notice 5+ enters a Converter chamber** | +1 |
| **A PC at Personal Notice 7+ exists in the region per session** | +1 |
| **Pool Shudder-type event fires** | +1 (consumed by the event itself; this is the World Notice eating the world Notice as it manifests) |
| **A Marked-tier ghost manifests in the region** | +1 |
| **The Office's Walk passes through the region** (Stillmonth 1) **WITHOUT a Concord acknowledgment** | +1 (the world feels the absence of the rite) |
| **Specific Module 1 actions** (per `module-1-integration.md`): mote-touch, shouted name, etc. | +1 each |

### What ticks World Notice DOWN

| Action | Reduction | Limit |
|---|---|---|
| **Sister Elra performs a Settling Rite** | −1 | 1×/year |
| **Destroying an active Dawnweave artifact** | −2 | very high cost; rare |
| **The community engaging in collective Concord worship** (a Crowning or Lampset Vigil observance, attended properly by villagers) | −1 | 1× per holiday |
| **Time passing without incident** (each in-game month with no triggers) | −1 | very slow |
| **A full year of dormancy** (no triggers, no leveled-spell casting in the region) | full reset to 0 | extremely rare |

---

## Personal Notice — what ticks it up and down

### Ticks UP

| Trigger | Tick | Source doc |
|---|---|---|
| Touching a Hollow Star artifact directly (mote, blue ribs, etc.) | +1 | `the-notice.md`, M1 |
| Reading 3+ pages of Architect Script | +1 | `world/languages.md` |
| Killing with Dawnweave-tainted weapon | +1 | this doc |
| Accepting a Hollow Star vision-gift (nat 20 death save) | +1 | `survival.md` |
| Carrying a Hollowed Wound 7+ days untreated | +1/week | `survival-realism.md` §A3 |
| Revival from death with Permanent Vision | +2 | this doc + `survival.md` |
| Witnessing a death caused directly by Hollow Star contact | +1 | `sanity-and-spirit.md` H1 |
| **Spillover from World Notice ticks** | +⌈N/2⌉ | this doc |
| Drinking from contaminated water (Slowmere near Converter) | +1 (failed Con DC 12) | `survival-realism.md` §A1 |
| Speaking Architect Script aloud (Voss-Touched feat) | +1 per word | `character-design/build-options.md` |
| Using the Sealcrafter feat to carve a *protective* seal | 0 (no tick) | `character-design/build-options.md` |
| Using a seal to *activate* magic (per Ruin Scholar background) | +1 | `character-design/backgrounds/ruin-scholar.md` |

### Ticks DOWN

| Action | Reduction | Limit |
|---|---|---|
| **Sister Elra's blessing** | −1 | 1× / week |
| **A week at a cleansed spring** | −2 | requires travel; rare |
| **The Long Hush holiday** at the Concord chapel in Calder Vault (leap-year only) | −3 | once per leap year |
| **A personal-sacrifice quest** (DM-narrated) | −1 to −3 | gated; story-locked |
| **Resolving a personal Trauma** in fiction (per `sanity-and-spirit.md` §H2) | −1 | per resolved Trauma |
| **Genuine joy moment** (per Joy → healing in §H6.4) | 0 on Notice; +1 HP/rest 3 days | (joy heals body, not soul) |

---

## How to use at the table

### DM-side

- **Track World Notice behind the screen.** A sticky note at your right hand: `WORLD: __ / 10`. Tick silently. Narrate effects audibly.
- **Cap World Notice at 10.** If it would exceed, **session ends** with whatever cliffhanger the moment supports.
- **Surface World Notice changes through ambient effects, not announcements.** The bell rang; the candles guttered; Sister Elra is suddenly quiet. The players sense it; the DM doesn't say "World Notice is now 7."
- **Personal Notice on each PC sheet** — visible to that player.
- **When Personal and World feedback loop fires** (a PC at 5+ enters a chamber; World ticks +1; spillover +1 to other PCs nearby): narrate the moment of recognition. Players should feel the cycle catching.

### Player-side

- **Track your Personal Notice on your sheet.** Visible to you. Visible to the DM. Not visible to other players unless you choose.
- **Each player decides how their character experiences Notice.** A PC at Notice 3 may keep it secret; a PC at Notice 5 may seek Sister Elra's help; a PC at Notice 7 may refuse to discuss it.
- **Accepting a Hollow Star vision-gift = +1 Notice.** You know the cost when you accept. The choice is the character's.
- **Revival from death = potential +2 Notice.** The cost of coming back from the threshold is real.

---

## Tracking on character sheet

Suggested format:

```
PERSONAL NOTICE
   0  1  2  3  4  5  6  7  8  9  10
        TOUCHED  MARKED  HOLLOWING  BLEEDING  LOST

Last tick up (date / event): _______________
Last tick down (date / event): _______________

ACTIVE FORBIDDEN CHOICE? __________ (refreshes on long rest)
ACTIVE LONG LOOK EFFECT? __________ (clear at 1 long rest)
PERMANENT VISIONS held: ____________________________
```

---

## What this REPLACES (the consolidation map)

The following files now reference The Notice instead of their previous separate trackers. **Do not rewrite the old files** — just understand that they all now feed into this one system.

| Old file/system | Old tracker | New mapping |
|---|---|---|
| `docs/dm-handbook/module-1-dm-flow.md` "Awakening Clock 0-6" | Awakening Clock | **World Notice** (0-10) — keep M1's existing triggers, just expand the scale |
| `homebrew/sanity-and-spirit.md` §H1 "Hollow Star Corruption Tracker 0-6" | Personal Corruption | **Personal Notice** (0-10). The 0-6 thresholds in H1 map to 0-10 here. Forbidden Choice at H1 stage 3-4 = Notice 3-4 (same). H1's "Lost" at 6 = Notice 10 (now harder to reach) |
| `homebrew/character-design/survival.md` §C "Death Visions" | per-roll narrative | Still per-roll, but the *severity* of the vision scales with Personal Notice. Mechanic unchanged. |
| `homebrew/character-design/survival.md` §B Hollowed Wound | Dawnweave-themed wound | Still a Wound. Now also adds +1 Personal Notice when taken. |
| `homebrew/character-design/build-options.md` Voss-Touched / Sealcrafter | feats | Each may tick Personal Notice when used. See "Ticks UP" table above for specifics. |
| `homebrew/sanity-and-spirit.md` §H5 Marked-tier ghosts | high-Notice ghosts | These are now defined as **lingering dead of characters who died at Personal Notice 7+**. The mechanical effect is unchanged. |
| Module 1 cliffhanger triggers | M1-specific Awakening Clock effects | Each fires when World Notice crosses specific thresholds (3, 6, 8, 10) |

### To update later (when convenient)

If you do an editorial pass:

- Update `sanity-and-spirit.md` §H1 to point here as the canonical version. Mark the old 0-6 scale as superseded.
- Update `module-1-dm-flow.md` to use World Notice 0-10 instead of Awakening Clock 0-6 (multiply old stages by ~1.67 for equivalent thresholds).
- Update `survival.md` to clarify which Death Vision effects are baseline vs Notice-thresholded.

**For now**, all old text remains valid — this file is the canonical authority. When in doubt, ask: "What is the PC's Personal Notice? What is the World Notice? What does that level allow?"

---

## Quick reference (rip out, tape to screen)

```
THE NOTICE
  PERSONAL (per PC)    WORLD (per region)
  0-10                  0-10

PERSONAL THRESHOLDS
  0:    clean
  1-2:  touched         bad dreams; ambient noticed
  3-4:  marked          NPCs sense; Forbidden Choice (+1 cost)
  5-6:  hollowing       disadv vs Dawnweave; divine 1-in-6 fail
  7-8:  bleeding        -1 physical stat; +1 strain 1st cast;
                         revival = permanent Vision
  9:    critical        +1/session auto; -1 more physical stat
  10:   LOST             PC → NPC

WORLD THRESHOLDS
  0-2:  dormant
  3-4:  stirring         dust, torches, avoided spots
  5-6:  aware            blue carvings, name whispered DC 11
  7-8:  awake            floors creak, bell rings without hands
  9-10: PRESENCE         Pool Shudder; shrine candles out; SESSION END

INTERACTION
  World +N → PCs nearby get +⌈N/2⌉ Personal
  Personal 7 → World +1 in region
  Personal 10 → World +1 globally

PERSONAL UP
  · touch artifact (+1)        · accept vision-gift (+1)
  · read 3+ pages script (+1)  · revival w/ Permanent (+2)
  · kill w/ Hollowed weapon    · Hollowed Wound 7+ days (+1/wk)
  · Voss-Touched used (+1/word) · World spillover (+⌈N/2⌉)

PERSONAL DOWN
  · Sister Elra blessing (-1, 1/wk)
  · cleansed spring week (-2)
  · Long Hush leap-year (-3)
  · personal-sacrifice quest (-1 to -3)
  · resolving Trauma (-1)

WORLD UP
  · leveled spell in Converter site (+1/cast)
  · PC at Notice 5+ enters chamber (+1)
  · PC at Notice 7+ in region (+1/session)
  · Pool Shudder fires (+1, consumed)
  · Marked ghost manifests (+1)

WORLD DOWN
  · Sister Elra Settling Rite (-1, 1/yr)
  · destroyed Dawnweave artifact (-2, rare)
  · community Concord observance (-1, 1/holiday)
  · year of dormancy (-1; full reset if 1 yr clean)

OLD SYSTEMS NOW EXPRESSIONS OF THE NOTICE
  Death Vision → fires always; severity scales with Personal Notice
  Long Look → triggers at Personal 5+
  Permanent Vision on revival → auto at Personal 7+
  Hollowed Wound → still a Wound + adds +1 Notice
  Awakening Clock → renamed to World Notice
  Hollow Star Corruption → renamed to Personal Notice
```

---

## Cross-references

- Sanity & spirit (the larger spiritual system this is part of): [`sanity-and-spirit.md`](sanity-and-spirit.md)
- Survival (Wounds, Death Visions, healing): [`character-design/survival.md`](character-design/survival.md)
- Survival realism (interactions with hunger/sleep/disease): [`survival-realism.md`](survival-realism.md)
- M1 integration pass (where Notice fires in Module 1 specifically): [`../docs/dm-handbook/module-1-integration.md`](../docs/dm-handbook/module-1-integration.md)
- Module 1 DM flow (the old Awakening Clock — now World Notice for the Fallowton ruin): [`../docs/dm-handbook/module-1-dm-flow.md`](../docs/dm-handbook/module-1-dm-flow.md)
- Weave Strain (interacts with Personal Notice 7+ first-cast strain): [`../docs/campaign/weave-strain-magic.md`](../docs/campaign/weave-strain-magic.md)
- World — Dawnweave Legend (DRAFT — the lore the Notice tracks): [`world/dawnweave-legend.md`](world/dawnweave-legend.md)
- World — Pantheon (Sister Elra's blessing source; Concord rites): [`world/pantheon.md`](world/pantheon.md)
- World — Calendar (Long Hush, Lampset Vigil timing): [`world/calendar.md`](world/calendar.md)
- House rules (player-facing reference): [`house-rules.md`](house-rules.md)
- Player onboarding (what new players learn): [`../docs/player-guide/getting-started.md`](../docs/player-guide/getting-started.md)
