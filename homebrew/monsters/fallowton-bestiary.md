---
type: homebrew-monsters
category: bestiary
since: "homebrew"
tags: [monsters, stat-blocks, bestiary, module-1, module-2]
updated: 2026-05-25
status: needs-review
---

# Fallowton Bestiary

Complete, tabletop-ready stat blocks for the Fallowton campaign, wired into the homebrew systems. Promotes the sketches from [`../../docs/dm-handbook-archive/05-encounter-balance-reference.md`](../../docs/dm-handbook-archive/05-encounter-balance-reference.md) into full 2024-format blocks, and adds deeper-lore creatures for Module 2+.

> **Party-size note.** The encounter reference assumes **3 PCs, level 1**. Your actual party is **4 PCs** (Vesper, Bard, Stannis, Druid). Each block lists a baseline; the **[4-PC]** line gives the adjustment (usually +HP or +1 minion). Use the baseline for 3, the adjustment for 4.

---

## How monsters interact with the homebrew systems

Three campaign systems touch combat. Most monsters don't trigger them — that's intentional (a goblin is just a goblin). Only **Dawnweave-touched** creatures do.

| System | Which monsters trigger it | Effect |
|---|---|---|
| **The Notice** (`../the-notice.md`) | Dawnweave-origin creatures (Edras's blue fire, the Unmade, Blue Motes, Hollowed beasts, Memory-Echoes) | Killing/being-hit by them can tick Personal or World Notice — noted per block under **◆ Notice** |
| **Hollowed Wounds** (`../character-design/survival.md`) | Creatures dealing **Dawnweave-tainted** damage (marked **⟡ Dawnweave damage**) | If their damage drops a PC to 0, the resulting Wound is **Hollowed** (needs cleansing, not just rest) |
| **Weave Strain** (`../../docs/campaign/weave-strain-magic.md`) | Spell-casting near a Converter; not the monsters themselves | Unchanged — the PCs' own casting, not the monster's |

A plain goblin or beast triggers **none** of these. Reserve the homebrew interactions for the ruin's true denizens, or the dread becomes routine.

---

# Part 1 — Module 1 tunnel monsters

## Oath-Bound Dead

*The skeletons of the House's original guards, still keeping a duty they no longer remember.*

```
OATH-BOUND DEAD
Medium Undead, Lawful Neutral

AC 14 (armor scraps + shield)      HP 13 (2d8 + 4)      Speed 30 ft.

STR 13 (+1)  DEX 14 (+2)  CON 15 (+2)  INT 6 (−2)  WIS 8 (−1)  CHA 5 (−3)

Immunities  Poison damage; Exhaustion, Poisoned
Senses      Darkvision 60 ft.; Passive Perception 9
Languages   Understands Old Common but can't speak
CR 1/4 (50 XP)                     Proficiency Bonus +2

TRAITS
• Oath-Slow. If the party entered the tunnel respectfully (no looting, no
  desecration), the Oath-Bound Dead act LAST in round 1 — they are slow to
  judge the living as enemies.
• Blue Echo. When reduced to 0 HP, the skeleton collapses in a harmless blue
  flash. ◆ Notice: World Notice +1 only if the "desecration track" is active
  (the party looted or defiled the dead).

ACTIONS
• Clean Edge. Melee Attack: +4 to hit, reach 5 ft. Hit: 6 (1d6 + 2) slashing.
  (Shortsword only — these guards carry no bows.)
```

**[4-PC] adjustment:** use 2 Oath-Bound Dead as the default encounter (the reference's baseline); for 4 PCs, give one of them HP 18 (3d8+5) as a "sergeant."

**Running them:** they signal old duty and danger — not the whole dungeon day. Don't grind a full skeleton fight *and then* force Edras (per the balance reference). They're a warning shot.

---

## Edras, Last Guard of the Blue Flame

*A kneeling armored skeleton whose ribs hold a blue Dawnweave flame. In life, a Voss — one of the family who walked into the House sixty-to-a-hundred years ago. He is the campaign's first tragic guardian: parley-first, never a random boss.*

```
EDRAS, LAST GUARD OF THE BLUE FLAME
Medium Undead, Lawful Neutral

AC 16 (breastplate)                HP 32 (5d8 + 10)     Speed 25 ft.

STR 14 (+2)  DEX 10 (+0)  CON 14 (+2)  INT 10 (+0)  WIS 14 (+2)  CHA 12 (+1)

Saving Throws  Wis +4
Resistances    Necrotic
Immunities     Poison damage; Exhaustion, Poisoned, Charmed, Frightened
Senses         Darkvision 60 ft.; Passive Perception 12
Languages      Old Common, Common
CR 1 (200 XP)                      Proficiency Bonus +2

TRAITS
• Blue Flame Heart. Edras sheds dim blue light in a 10-ft. radius. His melee
  attacks deal +1 fire damage (⟡ Dawnweave damage — see Hollowed below).
• Oathbound. Advantage on saves against being Charmed or Frightened.
• Voss-Marked. Edras was a Voss. A creature carrying the W.V. dagger, or with
  the Voss-Blooded feat / Voss-Family Lore, has ADVANTAGE on Persuasion to
  parley with him — and he will lower his blade to listen.

ACTIONS
• Rust-Clean Blade. Melee Attack: +4 to hit, reach 5 ft. Hit: 6 (1d8 + 2)
  slashing + 1 fire. ⟡ Dawnweave damage.
• Rebuke the Unworthy (Recharge 5–6). Each creature of Edras's choice within
  15 ft. that he deems unworthy makes a DC 12 Wisdom save or is Frightened of
  him until the end of its next turn.

REACTIONS
• Oath's Pause. When Edras is reduced to 1 HP by a foe who has not desecrated
  the House, he may lower his blade and speak instead of dying. (DM discretion;
  this is his tragedy — he wants to be released, not to win.)

◆ Notice. Defeating Edras through VIOLENCE (rather than parley or release)
  ticks World Notice +1. A PC dropped to 0 by his blue fire takes a HOLLOWED
  Wound (cleansing required).
```

**[4-PC] adjustment:** HP 36 (the reference uses 27 for 3 PCs; 32 baseline / 36 for 4). Do **not** stack him after a full skeleton fight.

**The point of Edras:** he is a *test of how the party treats the dead*, not a damage check. If they're respectful, he tests and warns. If they desecrate, he becomes the consequence. Either way, releasing him (speaking his name, or returning the W.V. dagger) is the "good" outcome — and reduces World Notice by 1.

---

## Nail-Eater Goblin (Minion)

*Scavengers of the Sound tunnel who gnaw iron, bone, and coins. Cruel, not comic.*

```
NAIL-EATER GOBLIN (MINION)
Small Humanoid (Goblinoid), Neutral Evil

AC 12 (scraps)                     HP 7 (2d6)           Speed 30 ft.

STR 8 (−1)  DEX 14 (+2)  CON 10 (+0)  INT 8 (−1)  WIS 8 (−1)  CHA 8 (−1)

Skills      Stealth +6
Senses      Darkvision 60 ft.; Passive Perception 9
Languages   Common, Goblin
CR 1/8 (25 XP)                     Proficiency Bonus +2

TRAITS
• Nimble Escape. The goblin can take the Disengage or Hide action as a Bonus
  Action on each of its turns.
• Iron-Gnaw. If the goblin spends a turn gnawing iron, bone, or coin before
  threatening a target, it has advantage on its next Intimidation check against
  that target. (Flavor pressure, not a damage spike.)

ACTIONS
• Rusty Shiv. Melee Attack: +4 to hit, reach 5 ft. Hit: 4 (1d4 + 2) piercing.
```

## Nail-Eater Goblin (Warrior)

*Used only when one goblin should matter.*

```
NAIL-EATER GOBLIN (WARRIOR)
Small Humanoid (Goblinoid), Neutral Evil

AC 15 (leather + shield)           HP 10 (3d6)          Speed 30 ft.

STR 8 (−1)  DEX 14 (+2)  CON 11 (+0)  INT 8 (−1)  WIS 8 (−1)  CHA 8 (−1)

Skills      Stealth +6
Senses      Darkvision 60 ft.; Passive Perception 9
Languages   Common, Goblin
CR 1/4 (50 XP)                     Proficiency Bonus +2

TRAITS
• Nimble Escape (as Minion).

ACTIONS
• Scimitar. Melee Attack: +4 to hit, reach 5 ft. Hit: 5 (1d6 + 2) slashing.
• Shortbow. Ranged Attack: +4 to hit, range 80/320 ft. Hit: 5 (1d6 + 2)
  piercing.
```

**Flee behavior:** Nail-Eaters flee when bloodied, outmatched, or threatened. **If one escapes toward Grask, Grask is warned** (and World Notice may rise +1).

---

## Grask the Split-Ear

*A mobile goblin mini-boss — hooked blade, dirty poison, a tribe at his back. Low CHA: his menace comes from cruelty and the pack, not charm.*

```
GRASK THE SPLIT-EAR
Medium Humanoid (Goblinoid), Neutral Evil

AC 16 (hide + shield)              HP 27 (5d8 + 5)      Speed 30 ft.

STR 12 (+1)  DEX 14 (+2)  CON 12 (+1)  INT 10 (+0)  WIS 10 (+0)  CHA 8 (−1)

Saving Throws  Dex +4
Skills         Stealth +6, Intimidation +1
Senses         Darkvision 60 ft.; Passive Perception 10
Languages      Common, Goblin
CR 1 (200 XP)                      Proficiency Bonus +2

TRAITS
• Nimble Escape. Disengage or Hide as a Bonus Action.
• Pack Cruelty. Grask has advantage on attacks against a creature if at least
  one allied goblin is within 5 ft. of it.

ACTIONS
• Hooked Blade. Melee Attack: +4 to hit, reach 5 ft. Hit: 6 (1d8 + 2) slashing.
  Once per turn, after this attack, Grask can move up to half his speed without
  provoking Opportunity Attacks (the hook lets him wrench free).
• Nail Spit (Recharge 5–6). Ranged Attack: +4 to hit, range 20 ft. Hit:
  4 (1d4 + 2) piercing, and the target makes a DC 11 Con save or is Poisoned
  until the end of Grask's next turn.

BONUS ACTIONS
• Screech. Each allied goblin within 30 ft. that can hear Grask moves up to
  half its speed toward a target of Grask's choice.
```

**[4-PC] adjustment:** HP 27 baseline (already raised from the 22 in the reference for the larger party). Add **1 Goblin Minion** for 4 PCs; add a Warrior only if the party is thriving. Never run Grask + 2 goblins as the opener.

---

## Breathless Warden

*A Dawnweave archive-guardian: animated armor bound to a map. Dormant until disturbed. AC 18 is brutal at low level, so the puzzle shutdown must be discoverable.*

```
BREATHLESS WARDEN
Medium Construct, Unaligned

AC 18 (plated archive-armor)       HP 33 (6d8 + 6)      Speed 25 ft.

STR 14 (+2)  DEX 11 (+0)  CON 13 (+1)  INT 1 (−5)  WIS 3 (−4)  CHA 1 (−5)

Immunities   Poison, Psychic damage; Charmed, Exhaustion, Frightened,
             Paralyzed, Petrified, Poisoned
Senses       Blindsight 60 ft. (blind beyond this); Passive Perception 6
Languages    —
CR 1 (200 XP)                      Proficiency Bonus +2

TRAITS
• Breathless. Immune to effects requiring breath; can't speak; advantage on
  saves against Thunder.
• Map-Bound. Dormant until a creature touches the archive map, fails the
  archive puzzle, or World Notice in the chamber is high. Until then it is an
  ornament.
• Warden's Duty. Disadvantage on attacks against any creature that has NOT
  touched the map. It guards the archive; it does not hunt the innocent.
• Puzzle Shutdown. Speaking the correct Old Common archive phrase, following
  the guard-prints respectfully, or restoring the map powers the Warden down
  without a fight.

ACTIONS
• Multiattack. The Warden makes two Slam attacks.
• Slam. Melee Attack: +4 to hit, reach 5 ft. Hit: 5 (1d6 + 2) bludgeoning.
```

**[4-PC] adjustment:** HP 33 (official) for 4 PCs; the reference's 26 was a deliberate 3-PC reduction. With AC 18, even at full HP the Warden is dangerous — **always make the shutdown clearly findable.**

> **Dust Mephits** (Wind tunnel harassers) are RAW — use the Monster Manual / Basic Rules block (AC 12, HP 17, CR 1/2). Two of them is already the top of a Medium budget for 3 PCs. Don't run them AND a full Warden fight in the same delve.

---

# Part 2 — Deeper-lore monsters (Module 2+)

These tie directly to the campaign's central horror. Use them sparingly — they are the ruin's *true* denizens, and each one makes The Notice real.

## The Unmade

*A Dawnweave Converter victim, caught mid-conversion when the Sealing froze the machine. Neither alive nor dead. It has no face — the Converter took it. It still prays in Old Common, the last language it knew.*

```
THE UNMADE
Medium Undead, Unaligned

AC 12                              HP 22 (5d8)          Speed 30 ft., hover

STR 10 (+0)  DEX 14 (+2)  CON 10 (+0)  INT 7 (−2)  WIS 10 (+0)  CHA 14 (+2)

Resistances  Necrotic, Cold; Bludgeoning, Piercing, Slashing from nonmagical
             attacks
Immunities   Poison damage; Charmed, Exhaustion, Frightened, Grappled,
             Paralyzed, Poisoned, Prone, Restrained
Senses       Darkvision 60 ft.; Passive Perception 10
Languages    Old Common (it prays; it does not converse)
CR 1/2 (100 XP)                    Proficiency Bonus +2

TRAITS
• Faceless. A creature that ends its turn within 10 ft. and looks directly at
  the Unmade's absent face makes a DC 12 Wisdom save or is Frightened until the
  end of its next turn.
• Sealed Half-Life. The Unmade cannot leave the ruin's wards. Destroying it
  does not free it — it simply stops moving. ◆ Notice: killing an Unmade ticks
  World Notice +1 (you disturbed a sealed soul). RELEASING one via the Sealing-
  rite ritual reduces World Notice by 1 instead.

ACTIONS
• Hollow Touch. Melee Attack: +4 to hit, reach 5 ft. Hit: 7 (2d6) necrotic.
  ⟡ Dawnweave damage. ◆ Notice: a creature already at Personal Notice 3+ that
  takes this damage gains +1 Personal Notice.
• Take a Name (Recharge 6). One creature within 5 ft. makes a DC 12 Wisdom
  save. On a failure, it loses one concrete memory (a name, a face, a
  direction) until the next dawn — per the memory-loss rules in
  `../character-design/survival.md` §C and `../the-notice.md`.
```

**[4-PC] adjustment:** HP 27 (6d8). Two Unmade is a serious fight; pair with the moral weight that these *were people*.

---

## Hollowed Beast

*An animal that lived too close to the waking ruin. Its eyes have filmed blue; it no longer eats or sleeps; its bite carries the rot. Henric's goat — the one that "stared at the hole and hasn't eaten since" — is becoming one of these.*

```
HOLLOWED BEAST (template — example: Hollowed Wolf)
Medium Beast (corrupted), Unaligned

AC 12                              HP 11 (2d8 + 2)      Speed 40 ft.

STR 12 (+1)  DEX 15 (+2)  CON 12 (+1)  INT 3 (−4)  WIS 12 (+1)  CHA 6 (−2)

Resistances  Necrotic
Immunities   Charmed, Frightened (it has nothing left to fear with)
Senses       Darkvision 60 ft.; Passive Perception 13
Languages    —
CR 1/4 (50 XP)                     Proficiency Bonus +2

TRAITS
• Hollow-Eyed. The beast doesn't flee, doesn't tire, and ignores pain. It
  fights to destruction.
• Blue Film. A creature that examines the beast (Wis [Medicine] or Int
  [Nature] DC 12) recognizes the Dawnweave rot — this animal cannot be saved by
  mundane means.

ACTIONS
• Tainted Bite. Melee Attack: +4 to hit, reach 5 ft. Hit: 5 (1d6 + 2) piercing
  + 1 necrotic. ⟡ Dawnweave damage.

◆ Notice. A Hollowed beast appearing near the village is a sign World Notice in
  the region is rising. They are an omen, not just an encounter.
```

**Template use:** apply "Hollowed" to any beast — swap the base stats for a Hollowed Goat (Speed 30, Ram instead of Bite), Hollowed Boar (HP 16, Gore), etc. The constants: Necrotic resistance, immune to Charmed/Frightened, ⟡ Dawnweave bite, blue-filmed eyes, doesn't flee.

---

## Blue Mote Swarm

*The watching motes of the Blue tunnel, gathered into a vigilant cloud. They are not malicious — they are looking for something specific, and you are not it. Yet.*

```
BLUE MOTE SWARM
Medium Swarm of Tiny Constructs (Dawnweave motes), Unaligned

AC 13                              HP 18 (4d8)          Speed 0 ft., fly 30 ft. (hover)

STR 4 (−3)   DEX 16 (+3)  CON 10 (+0)  INT 5 (−3)  WIS 14 (+2)  CHA 6 (−2)

Resistances  Bludgeoning, Piercing, Slashing
Immunities   Charmed, Exhaustion, Frightened, Grappled, Paralyzed, Petrified,
             Prone, Restrained, Stunned
Senses       Blindsight 30 ft.; Passive Perception 12
Languages    —
CR 1/2 (100 XP)                    Proficiency Bonus +2

TRAITS
• Vigilant. The swarm is searching for something specific (per the Module 1
  Wisdom 11 reveal: "not malice — vigilance"). It does not attack a creature
  unless that creature touches a mote, casts a leveled spell nearby, or attacks
  it first.
• Mote Light. The swarm sheds dim blue light in a 10-ft. radius.
• Swarm. Can occupy another creature's space and vice versa; can move through
  any opening large enough for a Tiny construct.

ACTIONS
• Searing Recall. Melee Attack: +5 to hit, reach 0 ft. (must be in the target's
  space). Hit: 5 (2d4) fire, and the target makes a DC 12 Wisdom save or briefly
  relives a vivid memory (lose its Reaction until the start of its next turn).
  ⟡ Dawnweave damage.

◆ Notice. Touching a mote with bare skin (or being hit by Searing Recall) ticks
  the toucher's Personal Notice +1.
```

---

## Memory-Echo

*A Wronged-tier lingering dead (per `../sanity-and-spirit.md` §H5). The "laughing thing" in the Sound tunnel is one of these: something that listened to a dying child and learned the shape of its laugh. Statted here as a template — Wendel Voss, if he manifests, is a Marked-tier version with +10 HP and the Possess action.*

```
MEMORY-ECHO
Medium Undead (echo), Chaotic Neutral

AC 13                              HP 22 (5d8)          Speed 0 ft., fly 40 ft. (hover)

STR 7 (−2)   DEX 16 (+3)  CON 10 (+0)  INT 10 (+0)  WIS 12 (+1)  CHA 15 (+2)

Resistances  Acid, Cold, Necrotic; Bludgeoning, Piercing, Slashing from
             nonmagical attacks
Immunities   Poison damage; Charmed, Exhaustion, Frightened, Grappled,
             Paralyzed, Petrified, Poisoned, Prone, Restrained
Senses       Darkvision 60 ft.; Passive Perception 11
Languages    The languages it knew in life (often Common + Old Common); speaks
             only in STOLEN voices
CR 1 (200 XP)                      Proficiency Bonus +2

TRAITS
• Incorporeal Movement. Can move through creatures and objects as difficult
  terrain. Takes 5 (1d10) force damage if it ends its turn inside an object.
• Mimic Voice. The Echo speaks only in voices it has stolen — a lost child, a
  dead spouse, a villager's missing brother. A creature that hears a voice it
  recognizes makes a DC 12 Wisdom save or is Frightened until the end of its
  next turn.

ACTIONS
• Cold Grief. Melee Attack: +5 to hit, reach 5 ft. Hit: 9 (2d6 + 2) cold.
  ⟡ Dawnweave damage.
• Borrowed Cry (Recharge 5–6). The Echo wails in a stolen voice. Each creature
  within 30 ft. that can hear it makes a DC 12 Wisdom save or takes 5 (2d4)
  psychic damage and is Frightened until the end of its next turn.

◆ Notice. Destroying a Memory-Echo without RESOLVING its wrong (the unburied
  child, the unfinished task) means it re-forms in 1d4 days. Resolving the wrong
  lays it to rest permanently and reduces World Notice by 1.
```

**Marked-tier upgrade (Wendel Voss):** +10 HP (32 total), CR 2 (450 XP), add the action **Possess (Recharge 6):** one creature within 5 ft. makes a DC 13 Charisma save or the Echo enters its body for 1 minute (the target is Incapacitated; the Echo controls it). This is the campaign's seed-thread ghost — handle with care.

---

# Part 3 — Building encounters (4-PC party)

## XP budget by level (4 PCs)

Using the 2024 encounter-building math, a **Moderate** encounter (the target for a real fight) for **4 PCs**:

| Party level | Low (easy) | Moderate (target) | High (dangerous) |
|---|---|---|---|
| **1** | 200 XP | 400 XP | 600 XP |
| **2** | 360 XP | 600 XP | 1,000 XP |
| **3** | 600 XP | 900 XP | 1,400 XP |

(These are the 2024 budgets, ×4 PCs. Use the raw XP of each monster — no "encounter multiplier" in 2024.)

## Sample encounters

| Encounter | Monsters | XP | Level | Difficulty |
|---|---|---|---|---|
| Sound tunnel ambush | 2 Goblin Minions (25 ea) + 1 Warrior (50) | 100 | 1 | Easy (warm-up) |
| Grask's lair | Grask (200) + 1 Goblin Minion (25) | 225 | 1 | Moderate |
| Edras, if it comes to blows | Edras (200) | 200 | 1 | Moderate (one tough foe) |
| The waking dead | 2 Oath-Bound Dead (50 ea) + 1 Unmade (100) | 200 | 1 | Moderate (Notice-heavy) |
| A pack turns | 3 Hollowed Wolves (50 ea) | 150 | 1–2 | Easy–Moderate; omen-flavored |
| Archive guardian | Breathless Warden (200) + 2 Dust Mephits (100 ea) | 400 | 2 | Moderate; or split them |
| The echo of the lost | Memory-Echo (200) | 200 | 2 | Moderate; resolve-the-wrong angle |
| Module 2 finale (sample) | Wendel Voss / Marked Echo (450) + 2 Unmade (100 ea) | 650 | 3 | High; the seed thread pays off |

## DM dials (from the balance reference, still in force)

- **Too easy:** add a Goblin Minion; have Grask Screech early; wake the Warden after a clear warning.
- **Too hard:** Edras speaks instead of attacking; mephits flee; Grask retreats at half HP.
- **Near TPK:** lower needle damage to 1d4; Edras stops at 1 HP to talk; Warden powers down when the phrase is spoken. (And remember Cardinal Rule 2 — a single fudge for a new-player rescue is allowed.)
- **One strong danger per delve, not many stacked.** This is the core principle.

---

## Cross-references

- Encounter-balance reference (the source sketches + balance rulings): [`../../docs/dm-handbook-archive/05-encounter-balance-reference.md`](../../docs/dm-handbook-archive/05-encounter-balance-reference.md)
- M1 integration (where these monsters appear scene-by-scene): [`../../docs/dm-handbook/module-1-integration.md`](../../docs/dm-handbook/module-1-integration.md)
- The Notice (◆ ticks): [`../the-notice.md`](../the-notice.md)
- Wounds & Hollowed (⟡ Dawnweave damage): [`../character-design/survival.md`](../character-design/survival.md)
- Ghosts & lingering dead (Memory-Echo lore): [`../sanity-and-spirit.md`](../sanity-and-spirit.md)
- Combat options (player-facing turn structure): [`../../docs/player-guide/combat-options.md`](../../docs/player-guide/combat-options.md)
- DM Manual — running combat (§2-§4, §9): [`../00-dm-operating-manual.md`](../00-dm-operating-manual.md)
- Module 2 (when built, these monsters populate it)
