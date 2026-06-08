---
type: homebrew-rules
category: survival-realism
since: "homebrew"
tags: [hunger, thirst, sleep, disease, light, falling, tolerance, adaptation]
updated: 2026-05-23
status: needs-review
---

# Survival Realism — The Body Keeps Score

The body has needs and the body remembers. This file layers realism onto the RAW chassis: hunger, thirst, sleep, disease, falling, suffocation, drowning, vision/light — plus the **adaptive systems** (tolerance, hereditary dispositions, allergies) that make this campaign feel like a real world rather than a series of identical resets.

Companion file: [`sanity-and-spirit.md`](sanity-and-spirit.md) — the mental/spiritual side. The two interlock: A6 (tolerance) talks to H6 (mind-body bleed); A2 (sleep) talks to H6 (insomnia → cognition).

---

## §A1 · Hunger & Thirst

A medium-sized creature needs **1 lb food + 1 gallon water per day** to function. Falling short has progressive consequences.

### Hunger curve

| Days without food | Effect |
|---|---|
| Days 1 to **CON + 3** | No effect. Body has reserves. |
| Day **CON + 4** | **Con save DC 10**; fail = 1 level of exhaustion |
| Each subsequent day | **DC +2** on the save; fail = +1 exhaustion (stacking) |

Recovery: a single full meal + 24 hours of rest clears **one** level of exhaustion from hunger.

### Thirst curve (much faster)

| Days without water | Effect |
|---|---|
| Day 1 | No effect. |
| Day 2 | **Con save DC 12**; fail = 1 level of exhaustion |
| Day 3 | **DC 15**; fail = +1 exhaustion |
| Day 4+ | **DC 18 then 20**; fail = +1 each |

Recovery: a full water ration + 24 hours of rest clears one exhaustion from thirst.

### [HOUSE] Magical food

| Spell / item | Hunger | Thirst | Special |
|---|---|---|---|
| **Goodberry** | satisfies | does **NOT** satisfy | After 3 consecutive days of Goodberry-only, characters feel hollow: **−1 to all morale-adjacent checks** (Insight to read allies, Persuasion to inspire) until they eat real food. The body knows when it's been cheated. |
| **Create Food and Water** | satisfies | satisfies | Tastes of nothing. After 5 consecutive days of this only, characters take a **Wisdom check DC 12 or lose 1 day of joy-eligibility** (per H6). |
| **Heroes' Feast** | satisfies 24 hrs | satisfies 24 hrs | Also clears 1 hunger-related exhaustion. Real food, real magic. |

### [HOUSE] Foraging mechanic

When traveling outside settled areas, the party makes **one Survival check at the start of each travel day**. One PC rolls (the highest Survival proficient).

| Terrain | Forage DC |
|---|---|
| Fallowton plains, farmland | DC 10 |
| Mereswood edge, mixed woodland | DC 12 |
| Cinderfen, peat fen | DC 15 |
| Wealdmark chalk hills | DC 18 |
| Bracken Downs (sparse sheep country) | DC 20 |

Yield by margin:
- **Beat DC by 0**: 1 day's rations for self
- **Beat by 5+**: 1 day's rations for the whole party
- **Beat by 10+**: 2 days' rations + 1 useful herb / animal trophy
- **Failure**: no forage today; carried rations deplete normally
- **Failure by 5+**: you ate something you shouldn't have. Con save DC 12 or take 1d4 hours of mild illness (disadvantage on next check)

Characters with **Lore (Hedge)** add **+2** to forage checks in any region they've seen before.

### Edge cases

- **Dawnweave-touched plants** (e.g., the mushroom ring in the lower north field): Con save DC 13 or take a temporary Hollowed-light effect for 1 long rest (−1 max HP; cleared on safe rest)
- **Drinking from the Slowmere**: safe most places. Within 1 mile downstream of an exposed Converter site: Con save DC 12 or gain 1 tick of Hollow Star Corruption (see [`sanity-and-spirit.md`](sanity-and-spirit.md) §H1)
- **Fasting as oath / roleplay**: no mechanical penalty. Villagers notice and judge (Persuasion DC −2 with Sister Elra; +2 with Mordren, who respects deliberate discipline)

---

## §A2 · Sleep Deprivation

Sleep skipped accumulates as cognitive and physical debt.

### Curve

| Consecutive nights without sleep | Effect |
|---|---|
| **1** | **−1 to all d20 tests** for the next 24 in-game hours |
| **2** | 1 level of exhaustion |
| **3+** | 1 additional level of exhaustion **per night beyond 2** |

### Recovery

A single long rest at a **safe location** (no Awakening Clock; no danger trigger) resets the sleep debt fully. A long rest in a dangerous area (interrupted; clock ticks) does NOT reset — you wake with the debt still running.

### Half-rest interaction

The "sleeping in medium/heavy armor" rule from [`physicality.md`](physicality.md) §C counts as a partial rest:

- Half-rest in armor = "1 successful catch-up night" but reduced effect: clears 1 night's penalty regardless of how many were carried. The body relaxed enough to recover *something*, not everything.

### [HOUSE] Magical sleep

| Source | Counts as real rest? |
|---|---|
| **Sleep** spell forced on you | Yes (the channel made you sleep deeply) |
| **Dream** spell | No (you're being visited, not resting) |
| **Hollow Star vision-dream** (see [`sanity-and-spirit.md`](sanity-and-spirit.md) §H1) | No — counts as additional insomnia stress |
| **Knock-out from damage** | No (you were unconscious; that's not sleep) |

### Insomnia from Wounds / Long Look

- A character with active **Insomnia** as a Trauma (see [`sanity-and-spirit.md`](sanity-and-spirit.md) §H2) takes the **1-night penalty automatically** each session (the day starts at −1), and full sleep does not catch them up until the Trauma is addressed in fiction
- This stacks with deprivation if the player also skips sleep — they pay both

### Edge cases

- **Watch shifts during long rest** (2 of 8 hours awake): partial; counts as full sleep
- **Healing trance** (elven 4-hour rest): treated as a full long rest for these rules; elves don't carry the same sleep debt
- **A long rest in a tavern with noise + drinking**: 50% chance counts as full, 50% counts as half (DM rolls)
- **Caffeine-equivalent** (Fallowton has *strong tea*): allows you to *function* through a single missed night with no penalty, but tomorrow's exhaustion gain is doubled (you're borrowing)

---

## §A3 · Disease & Infection

The most thematically powerful subsystem in this file. Ties wounds (per [`character-design/survival.md`](character-design/survival.md)) into a progression and to Sister Elra's role.

### Wound → Infection rule

The following Wounds (from `survival.md` §B's 12-entry table) are **open wounds**:

- **Bleeding Gash** (slashing)
- **Severed Tendon** (slashing)
- **Eye Injury** (slashing/piercing)
- **Punctured Lung** (piercing)

When an open Wound is left untreated for **3+ in-game days** (no Medicine + kit; no Sister Elra blessing; no Lesser Restoration), the character begins **daily Con saves DC 12**. On a fail, **sickness onset.**

### Sickness progression (3 stages)

| Stage | Duration | Effect |
|---|---|---|
| **1 · Onset** | 1d4 days | −1 to all d20 tests; fever; visible sweating |
| **2 · Acute** | 2d4 days | 1 level of exhaustion; halved long-rest HP recovery; villagers notice and may quarantine |
| **3 · Severe** | until cured or 1d6 days | 2 levels of exhaustion; Con save DC 15 each long rest or take 1d6 damage (cannot be reduced below 0; lethal if untreated) |

Progression: each long rest, untreated character makes a Con save DC 15. **Fail = advance one stage.** **Success = hold.** Two consecutive successes = regress one stage.

### Hollowed-as-disease

The **Hollowed** Wound (per `survival.md` §B #10) is **NOT** a normal disease. It's a rot of the channel, not the flesh. It uses its own healing rules (cleansing magic, Sister Elra's blessing, or a week at a cleansed spring). However:

- A Hollowed Wound + another open Wound: both progress. The Hollowed makes the other Wound's sickness Con saves **−2** (the rot weakens the body's natural defenses).
- A character with Hollowed at Stage-2 Acute sickness can transmit Hollowed-light to bedside attendants who fail Wis save DC 13 (the channel reaches outward).

### Treatment

| Method | Effect |
|---|---|
| **Medicine DC 12 + kit + 4 hours bedrest** | Halts progression for 24 hours. Repeated checks each day. |
| **Medicine DC 15 + kit + 3 long rests (a week)** | Reverses one stage |
| **Lesser Restoration** | Removes Stage 1 entirely. At Stage 2-3: removes 1 stage. |
| **Greater Restoration** | Removes any stage; clears the wound's infection track entirely (the Wound remains until healed normally) |
| **Sister Elra's blessing (1/week)** | Halts progression for one full week + reduces the stage by 1. She refuses if she thinks the patient deserves the consequence — Wisdom DC 12 to read her mood. |
| **Cleansed spring (1 week)** | Reverses two stages; clears Hollowed if active |

### Magical diseases (mummy rot, lycanthropy, etc.)

These remain RAW. They follow their canonical rules; this homebrew system layers underneath them as the **mundane infection layer**. A character could simultaneously have:

- A Bleeding Gash (mundane) at Stage 1 sickness
- AND mummy rot (magical RAW)

Treat them as independent tracks. Mummy rot's RAW progression interacts only with magical cures; mundane infection follows this section.

### Contagion between PCs

Most mundane infections in this campaign are **wound-borne**, not airborne. PCs are not contagious to each other unless they're sharing a wound's blood (e.g., a healer reopening a wound to drain it). However, **Hollowed transmission** (above) is a real concern in close quarters.

A specific exception: **plague years** (DM-narrated; tied to the world setting), where airborne disease overrides individual mechanics. A village quarantine becomes the focus.

### Edge cases

- A PC with **Lore (Hedge)** automatically halts the progression of their own minor sickness once per session via foraged herbs
- A PC with **Village Doctor** background can grant another PC a Medicine DC 14 short-rest check to halt progression (per their existing background hook)
- A character at Stage 3 Severe who reaches 0 HP from the sickness damage dies — **NO death saves**. This is a slow, telegraphed death; the player knows the danger several sessions before it happens.

---

## §A4 · Vision & Light

Light conditions, mechanically tightened with three [HOUSE] additions.

### Standard RAW

- **Bright light**: normal vision; no penalties
- **Dim light**: lightly obscured area; **disadvantage on Perception checks that rely on sight**
- **Darkness**: heavily obscured; effectively **Blinded** for sight-only purposes
- **Darkvision**: dim → bright (for you); dark → dim (for you). You see in shades, not colors.

### [HOUSE] Dawnweave script in low light

Reading **Architect Script** or any Dawnweave seal (per [`world/languages.md`](world/languages.md)):

- **Bright light**: normal Arcana / Religion DC
- **Dim light**: **DC +3**
- **Darkness**: **cannot attempt at all**, even with darkvision (the script's meaning requires *real* light)

This is because Architect Script encodes meaning in subtle marks darkvision flattens out.

### [HOUSE] Spell components in light/dark

- **Verbal**: works in any light
- **Somatic**: works as long as you have a free hand or focus and can move
- **Material**: requires you to handle the component — in pitch darkness, **DC 12 Sleight of Hand** to retrieve from your component pouch without dropping or wasting; failure = spell fails and component consumed

### [HOUSE] Sunlight in the ruin

In **awakened Converter chambers** (Awakening Clock 4+), direct sunlight introduced via a held torch, the Light cantrip, or sunshine through an opening:

- **Suppresses Awakening Clock by 1 stage temporarily** (10 minutes)
- The ruin reacts: a cracking sound; cold breeze from below; the carvings flicker visibly

This is a hint that light *suppresses the Hollow Star* mechanically. Players who notice can exploit it.

### Light source ranges (canonical for this campaign)

| Source | Bright | Dim | Duration |
|---|---|---|---|
| Torch | 20 ft | 40 ft total | 1 hour |
| Lamp | 15 ft | 30 ft | 6 hours / flask |
| Hooded Lantern | 30 ft | 60 ft | 6 hours / flask |
| Bullseye Lantern | 60 ft cone | 120 ft cone | 6 hours / flask |
| Light cantrip | 20 ft | 40 ft | 1 hour |
| Daylight spell | 60 ft | 120 ft | 1 hour |
| Continual Flame | 20 ft | 40 ft | permanent |

The **Hooded Lantern** is the best general light source; the **Bullseye** is best for tunnels.

### Edge cases

- **The blue motes in the ruin** (Module 1): these are **dim light** sources within 5 ft of themselves. They do NOT count as torches for the Awakening Clock suppression.
- **Bioluminescent moss** in deeper Converter chambers: **dim light** within 10 ft. Natural; can't be carried; doesn't suppress.
- **Light in a fog**: bright reduces to dim; dim reduces to darkness. Adjust ranges accordingly.

---

## §A5 · Falling, Drowning, Suffocation

Environmental damage and held-breath, with one tightening rule and one campaign-specific addition.

### Falling

- **RAW**: 1d6 bludgeoning per 10 ft fallen, max 20d6 (at 200+ ft). Land Prone.
- **[HOUSE] Acrobatics DC 15**: reduce damage by **half** on a success (rounded down)
- **[HOUSE] Catch by ally** (within 5 ft of landing zone, free hand): Reaction; opponent's Dex (Acrobatics) DC 15 to soften — caught character takes only half damage

### Specific falls in this campaign

| Fall | Damage |
|---|---|
| Sinkhole into ruin (~25 ft) | 2d6 base; half on Acrobatics DC 12 |
| From the Bent Plow Inn loft (~12 ft) | 1d6 |
| Down the descent stairs slip (per `module-1-checks.md`) | 1d4 + drop one held item one step |
| From a horse at gallop | 1d6 falling + Con save DC 10 or knocked Prone |
| From a horse at gallop **in heavy armor** | per `physicality.md` §C: additional 1d6 |

### Drowning

| Phase | Mechanics |
|---|---|
| **Held breath** | Up to **1 + Con modifier** minutes (min 30 seconds). At the end, you start drowning. |
| **Drowning** | When you can't breathe, you drop to **0 HP at the start of your next turn**. You begin death saves (per RAW). |
| **In armor** | **−1 minute** of held breath per category (heavy/medium/light); heavy in deep water = **Athletics DC 15** every round to stay above water |
| **In overload** (per `physicality.md`): | swimming requires Athletics DC 15 to make any progress; without success, you sink |

### Suffocation (carbon dioxide buildup in sealed rooms)

Different from drowning; happens when air runs out in a sealed chamber.

- **Room size matters**: a sealed Converter chamber (~50 ft × 50 ft × 20 ft, no air supply) lasts ~6 hours for 4 humans
- After breathable air runs out: drowning rules apply (held breath + 0 HP)
- **The Converter consumes air** in awakened chambers (Awakening Clock 4+): air depletion rate doubles. A 6-hour room becomes a 3-hour room.

### Edge cases

- **Stunned mid-fall**: no Acrobatics check; full damage
- **Featherfall** (spell): negates all fall damage RAW; takes effect as a Reaction; can be cast on others
- **Catching yourself on a ledge** (Reach to ledge during fall): Dex (Acrobatics) DC 15; success = grabbed ledge, take half damage and end fall

---

## §A6 · Tolerance & Adaptation (the body remembers)

The body learns. Six homebrew adaptation tracks: healing potion tolerance, alcohol/poison tolerance, antitoxin dependency, painkiller numbness, magic-buff tolerance, save-target adaptation.

### A6.1 · Healing Potion Tolerance

Each healing potion consumed in a **24-hour window** heals progressively less.

| Potion # in 24 hrs | Effect |
|---|---|
| 1st | Full rolled healing |
| 2nd | **−1 die step** (1d4+2 → 1d2+2; 2d4+2 → 1d4+2) |
| 3rd | **−2 die steps** (1d4+2 → +2 flat; 2d4+2 → 1d2+2) |
| 4th+ | **1 HP minimum** (the body refuses; the channel laughs) |

Reset: **a safe long rest** (no Awakening Clock ticking; no interruption). Half-rests do not reset tolerance.

**Lore:** healing magic is borrowed through the broken Weave. The more you borrow in a day, the more the body protests. This is consistent with the entire Weave Strain economy — magic costs, even when others pay.

### A6.2 · Alcohol & Poison Tolerance

After **5+ exposures** to the same poison or alcohol type in the same season:

- **+1 to Con saves** against that specific substance (you've adapted)
- **−1 die step** of effect to mild doses (you need stronger drinks/poisons to feel anything)

After **20+ exposures**:

- **+2 to Con saves** (permanent within that campaign)
- **Mild doses do nothing** — only the heaviest hits affect you
- **Cost**: you've damaged the relevant organ; Con saves vs **other** poisons drop by 1 (your defenses are spent on this one)

### A6.3 · Antitoxin Dependency

Using **antitoxin or similar specific remedies 5+ times in a month**:

- Your **natural Con vs poison drops by 1** until you've gone a full week without it (the body relied on the cure and forgot the defense)
- After 1 week clean: defense restores

**Lore:** the channel of healing knows when it's being used as a crutch and pulls back.

### A6.4 · Painkiller Numbness

Specific to Fallowton-region herbs (Sister Elra knows three: bitter mint, ash-leaf, white poppy):

- 1st-3rd use: standard pain relief (Wis save DC 10 to maintain combat focus while wounded — auto-pass with painkiller)
- 4th-6th use: half-effect; you feel some pain
- 7th+ use in a season: **no relief**, AND **disadvantage on Insight to recognize your own danger state** (you can't tell when a Wound is serious because your body has stopped warning you)

### A6.5 · Magic-Buff Tolerance

When buff spells (**Bless, Bane, Hunter's Mark, Hex, Aid, Faerie Fire, etc.**) are cast on you 5+ times in a single long-rest window, the next cast of that *spell* (across all casters) has half its bonus.

- A Bless-bonus of 1d4 becomes **1d2** on the 6th application
- A 5-temp-HP Aid becomes **2 temp HP**

**Resets:** a safe long rest.

**Lore:** the recipient's channel adapts. The body and soul reject repetition. This is why Mordren says *"prayers spoken too often lose their tongue."*

### A6.6 · Save-Target Adaptation

Within a **single session**, success and failure on saves compound.

- **3 successful saves against the same condition type** (e.g., Charm, Frightened, Poisoned, Stunned): **advantage** on the next save of that type
- **3 failed saves against the same type**: **disadvantage** on the next save

This is **within a session only.** Resets between sessions.

**Lore:** the body finds the rhythm of fighting back, or the rhythm of yielding. Both are real. Patterns compound.

---

## §A7 · Extended Physical Realism

Six smaller mechanics for further realism: allergies, hereditary dispositions, hormonal effects, mental fatigue, plus interactions.

### A7.1 · Allergies & Intolerances

At chargen, a player may declare **one allergy or intolerance**. Free, no cost; flavor + occasional bite.

| Example | Effect |
|---|---|
| Bee venom | If stung, Con save DC 14 or 1d6 poison + 1 hour swelling (disadv on Persuasion in that hour) |
| Lactose | Drinking dairy → 4 hours of disadvantage on Stealth (you're audibly uncomfortable) |
| Specific food (mushrooms, shellfish, nuts) | Eating → similar to bee venom in severity |
| Wool | Skin reacts to wool armor padding → disadvantage on long rest comfort |
| Pollen (Greenstir / Sownmonth) | Seasonal; sneezing → disadv on Stealth in spring |

DMs can mechanically *exploit* allergies in fiction — an NPC offering "salt mushroom" to a guest with a mushroom allergy is now a tactical threat.

### A7.2 · Hereditary Dispositions

Some bloodlines carry traits. Voss line is canon (per `character-design/build-options.md`). Other rare bloodlines (DM may add):

| Bloodline | Trait |
|---|---|
| Voss | +1 vs Hollowed recovery; -1 first Wis save vs Hollow Star (per existing feat) |
| Crebb (Office sensitive line) | +1 to Wisdom (Perception) sight checks; once per long rest, may detect active magic within 30 ft |
| Tann (Office sensitive line) | +1 to Insight; once per session, sense a lie aloud (DC 15 Insight free) |
| Old crown blood (rare; Verant-distant) | Disadvantage on the first save vs Office Sensitive's pendulum detection (they notice you) |
| Mereswood elf-kin (rare; mixed heritage) | +1 to Survival in forests; +1 to Stealth in temperate woods |

DM-gated: these are not chargen options; they emerge in fiction over time.

### A7.3 · Hormonal & Cyclic Effects

Optional [OPTIONAL] flavor track for tables that want it.

- **Aging**: +1 to one mental stat per decade past 30 (max +3 by age 60); −1 to one physical stat per decade past 50 (max −3 by age 80). Reroll on death save with disadvantage if older than 70.
- **Menstrual cycle**: 1-2 days per month of disadvantage on STR-based checks (cramping); 1-2 days of advantage on Insight (heightened perception). Both player-controlled.
- **Puberty (12-17)**: characters in this age band have +1 to Cha but −2 to social-norm awareness (clumsy)
- **Pregnancy**: −5 ft speed in 3rd trimester; disadvantage on combat with Con save before any cast or strain action

These are all opt-in — if a player wants them, they're available; otherwise ignore.

### A7.4 · Mental Fatigue from Prolonged Concentration

Outside of combat, sustained Concentration spells tax the channel.

- Every **hour** that you maintain a Concentration spell outside combat, **Con save DC 10** (rising by +1 per additional hour)
- **Fail**: the spell drops
- **Pass**: continue

This is for spells like *Detect Magic, Locate Object, Pass Without Trace* that are typically cast and "left running" for hours. The cost is real; you can't just leave concentration on indefinitely.

### A7.5 · Children of Casters (faint strain markers)

Children born to a parent with active Weave Strain habits (5+ years of regular leveled casting) carry faint marks:

- A child of two casters: **visible to anyone with Lore (Dawnweave) or Lore (Hedge)** as "marked"
- A child of one caster: visible only to those with Lore (Dawnweave)
- Marks may manifest as small physical features (one grey eye; cold fingertips; a hairline that grows back curlier each year)
- **No mechanical penalty by default**, but in some Office districts these children are *flagged* — the Office may inspect families with multiple "marked" children

This is lore-flavor; mechanically zero impact unless DM declares.

### A7.6 · Emotional Labor / Healer Burnout

(Note: this also lives in `sanity-and-spirit.md` §H7. Briefly here:)

A character whose primary role at the table is **healer / emotional support** for the party (Cleric, Bard with healing focus, Sister Elra herself if she's a PC) accumulates emotional load:

- Each session where you cast 3+ healing spells AND have emotionally supported an ally through a scene: gain 1 "burden"
- At 3 burden: −1 to Concentration saves until you take a session off
- At 5 burden: your first healing spell each day heals 1d4 less

Recovery: a session spent *not* healing or supporting (selfish play; vacation; solo work).

---

## Quick reference (rip out, tape to screen)

```
HUNGER:    Days 1 to CON+3 = no effect.
           CON+4 onward: Con save DC 10, +2/day, fail = 1 exhaustion.

THIRST:    Day 1 = no effect.
           Day 2: DC 12. +2/day.

GOODBERRY: hunger yes; thirst NO. 3+ days hollow = -1 morale.

FORAGE:    DC 10/12/15/18/20 by region (plains→Wealdmark).
           Beat by 5 = whole party; 10 = +herb. Lore(Hedge) = +2.

SLEEP:     1 missed = -1 d20 day. 2 = 1 exh. 3+ = stacking.
           Safe long rest resets fully.

INFECTION: Open Wound 3+ days untreated = Con save DC 12.
           Fail = 3-stage sickness. Sister Elra blessing halts.

LIGHT:     Dawnweave script in dim = DC +3. In dark = cannot.
           Light suppresses Awakening Clock in awakened rooms.

FALL:      RAW 1d6/10ft. Acrobatics DC 15 = half.
DROWN:     1 + CON mod minutes held. -1 per armor tier.

POTION TOLERANCE (24-hr window)
  1st: full · 2nd: -1 step · 3rd: -2 steps · 4th+: 1 HP

ALCOHOL/POISON: 5+ exposures = +1 Con save, -1 step effect.
                20+ = +2 save, mild doses null, OTHER poisons -1.

ANTITOXIN: 5+ uses/month = -1 natural Con vs poison until 1 wk clean.

PAINKILLER: 7+ uses/season = no relief + disadv on self-Insight.

MAGIC BUFF: 5+ stacks in long-rest window = next half effect.

SAVE-TARGET ADAPT: 3 saves in session = adv on 4th.
                   3 fails = disadv on 4th.

CONCENTRATION OOC: Con save DC 10/hr, +1 per additional hr.

ALLERGIES: 1 free at chargen. Flavor + bite when triggered.
```

---

## Cross-references

- Mind-body bleed companion file: [`sanity-and-spirit.md`](sanity-and-spirit.md)
- Survival.md (HP, Wounds, Death Visions): [`character-design/survival.md`](character-design/survival.md)
- Physicality (weight, armor, timing): [`physicality.md`](physicality.md)
- Weave Strain (the magic-cost economy this all interlocks with): [`../docs/campaign/weave-strain-magic.md`](../docs/campaign/weave-strain-magic.md)
- Wiki — conditions (exhaustion especially): [`../wiki/conditions/`](../wiki/conditions/)
- House rules — to be updated to reference this file: [`house-rules.md`](house-rules.md)
- Session time tracker (in-game time for hunger/thirst tracking): [`../docs/dm-handbook/session-time-tracker.md`](../docs/dm-handbook/session-time-tracker.md)
