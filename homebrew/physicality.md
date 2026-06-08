---
type: homebrew-rules
category: physicality
since: "homebrew"
tags: [encumbrance, carrying, armor, weight, initiative, timing, action-economy]
updated: 2026-05-23
status: needs-review
---

# Physicality — Weight, Armor, and Timing

The body-physics layer of the Fallowton campaign. How weight, armor, and time interact at the table. **Supersedes the "reasonable encumbrance" line in [`house-rules.md`](house-rules.md)** — when this file says weight matters, weight matters.

This is a **homebrew expansion**, not a RAW replacement. We keep the 2024 chassis (HP, actions, initiative as a DEX check) and add four layers:

1. **Weapon weight tiers** — what weapon weight means beyond a number.
2. **Carrying-capacity load tiers** — a four-tier system replacing RAW's binary encumbered/heavily-encumbered.
3. **Armor drawbacks** — heavy armor isn't free; here are its costs.
4. **Initiative & timing** — initiative modified by load; delayed-initiative rule; pre-declared reactions tie-in.

---

## §A · Weapon Weight Tiers

Every weapon has a listed weight (see [`docs/player-guide/weapons-reference.md`](../docs/player-guide/weapons-reference.md)). We group weapons into three tiers for **homebrew interaction purposes**:

| Tier | Weight | Examples |
|---|---|---|
| **Light** | ≤ 3 lb | Dagger (1), Sickle (2), Handaxe (2), Shortsword (2), Rapier (2), Longbow (2), Whip (3), Spear (3) |
| **Medium** | 4–7 lb | Mace (4), Quarterstaff (4), Battleaxe (4), Longsword (3 — borderline), Warhammer (5), Hand Crossbow (3), Glaive (6), Halberd (6), Lance (6), Greatsword (6) |
| **Heavy** | 8+ lb | Greatclub (10), Greataxe (7 — borderline), Maul (10), Heavy Crossbow (18), Pike (18) |

### Homebrew rules tied to weapon weight

> **[HOUSE] Heavy weapons require commitment.** A Heavy-tier weapon (≥ 8 lb) **requires both hands to swing effectively** OR a Strength score of 15+ to wield in one hand (in which case Versatile properties unlock as if RAW). Without one-handed mastery, you can carry the weapon but cannot make an effective attack with it one-handed.

> **[HOUSE] Two-weapon fighting weight limit.** The Light property on a weapon already gates two-weapon fighting, but we add: **the combined weight of both wielded weapons cannot exceed 6 lb** for two-weapon fighting to function. Two daggers (2 lb total) = fine. Two shortswords (4 lb total) = fine. A shortsword + a hand crossbow (5 lb) = fine. Two scimitars (6 lb) = barely allowed. You cannot two-weapon-fight with a Medium pair (e.g., two longswords).

> **[HOUSE] Hefting penalty.** When wielding a weapon whose weight is **more than half your Strength score in pounds**, your attack rolls with that weapon have a flat **−1**. This is small but persistent — a STR 8 wizard using a quarterstaff (4 lb, half = 4, equals threshold = no penalty) is fine. A STR 8 wizard wielding a longsword (3 lb) is fine. But a STR 8 character trying to swing a maul (10 lb) takes the penalty.

---

## §B · Carrying Capacity (Four-Tier Load System)

Replace RAW's binary encumbrance with a **four-tier load system.** Your total carried weight (everything on your person — gear, armor, weapons, coin) determines your load tier. Different tiers impose different penalties.

### The four tiers

For a character with **Strength score X**:

| Tier | Weight range | Penalty |
|---|---|---|
| **Light Load** | 0 to **X × 5** lb | None. You move and fight unencumbered. |
| **Standard Load** | (X×5)+1 to **X × 10** lb | **−1 to initiative.** Stamina counts (see "Long-haul fatigue" below). No movement penalty. |
| **Heavy Load** | (X×10)+1 to **X × 15** lb | **−10 ft speed.** Disadvantage on DEX checks and DEX saves. **−3 to initiative.** |
| **Overload** | (X×15)+1 to **X × 20** lb | **−20 ft speed** (minimum 5 ft). Disadvantage on STR/DEX/CON checks and saves. Disadvantage on attack rolls with non-Heavy weapons (everything feels clumsy when burdened). **−5 to initiative.** Cannot use Reactions. |
| **Beyond Overload** | > X × 20 lb | **You cannot move.** You may drop items as a free action to get back under the limit. |

### Examples

| STR | Light max | Standard max | Heavy max | Overload max | Cannot carry beyond |
|---|---|---|---|---|---|
| 8 | 40 lb | 80 lb | 120 lb | 160 lb | 160 lb |
| 10 | 50 lb | 100 lb | 150 lb | 200 lb | 200 lb |
| 12 | 60 lb | 120 lb | 180 lb | 240 lb | 240 lb |
| 14 | 70 lb | 140 lb | 210 lb | 280 lb | 280 lb |
| 16 | 80 lb | 160 lb | 240 lb | 320 lb | 320 lb |
| 18 | 90 lb | 180 lb | 270 lb | 360 lb | 360 lb |
| 20 | 100 lb | 200 lb | 300 lb | 400 lb | 400 lb |

### Worked example — a typical level-1 Fighter

STR 14 fighter wearing **Chain Mail (55 lb)** + **Greatsword (6 lb)** + **Dungeoneer's Pack (55 lb)** + a **shield (6 lb, even if stowed)** + 10 GP coin (negligible) = **122 lb**.

Thresholds for STR 14: Light 70 / Standard 140 / Heavy 210.

**This Fighter is at Standard Load.** They take −1 to initiative and need to track stamina (see below), but no movement penalty. If they swap chain mail for plate (65 lb, total 132 lb), they're still Standard. If they pick up 20 lb of loot, they're at 152 — Heavy Load — and need to dump some weight.

### Worked example — a level-1 Wizard

STR 8 wizard wearing **no armor** + **Quarterstaff (4 lb)** + **Scholar's Pack (22 lb)** + **Arcane Focus (1-3 lb)** + **Spellbook (3 lb)** + a few **Daggers (2 lb total)** = **~34 lb**.

Thresholds for STR 8: Light 40.

**This Wizard is at Light Load.** No penalties. They could carry another 6 lb before crossing into Standard.

### Long-haul fatigue (Standard Load and above)

Carrying Standard Load or more over **multi-hour travel** taxes the body. After each **4 consecutive hours of travel** carrying at least Standard Load:

- Make a **Constitution save** (DC 10 at Standard / DC 12 at Heavy / DC 15 at Overload).
- **Fail:** gain **1 level of exhaustion** (per [`wiki/conditions/exhaustion.md`](../wiki/conditions/exhaustion.md): −2 to all d20 tests per level + −5 ft Speed per level).
- **Success:** no effect.

A long rest clears 1 level of exhaustion as RAW. So a Heavy-Load Fighter on a 12-hour forced march makes 3 saves — and if they fail any, they're exhausted by the time they arrive. (This is why pack mules exist.)

### Containers and storage

A container's contents count toward your load. Putting heavy items in a **handcart**, on a **mount**, or in a **bag of holding** (rare) removes that weight from your personal load.

- **Handcart:** carries 200 lb. Speed of cart-pushed travel = your unencumbered speed minus 10 ft.
- **Mule:** carries 400 lb. Travel speed = 30 ft. Hates loud places.
- **Riding horse:** carries 480 lb (incl. rider). Travel speed = 60 ft.
- **Wagon (drawn by 2 horses):** carries 2,000 lb. Travel speed = 30 ft.

If you're in Fallowton, a mule rents from Bran's farm for 5 sp / day. A wagon rents from the village stables for 2 gp / day. A handcart is sold at Marrowford for 5 gp.

---

## §C · Armor Drawbacks (Homebrew Costs)

RAW has some armor costs already:
- Heavy armor: −10 ft speed if STR < armor's listed Strength requirement.
- Stealth disadvantage: explicit for most medium and heavy armor.

We layer **four homebrew drawbacks** on top.

### 1 · Heat exhaustion (heavy and medium armor in warm conditions)

Wearing **medium or heavy armor** in **hot weather** (summer day; near a forge or open flame for >10 minutes; in an enclosed dungeon room with active fire) imposes a stamina check.

- **Every hour of exposure:** Constitution save.
  - **Heavy armor:** DC 12.
  - **Medium armor:** DC 10.
  - **Light armor:** no check.
- **Fail:** gain 1 level of exhaustion. Failed Constitution checks for this stack with Long-Haul Fatigue checks.
- **Mitigation:** unbuckling armor for the duration removes the check (1 minute to remove medium; 5 minutes to remove heavy). You can carry it nearby; the check is for *wearing*, not for *having.*

> **[OPTIONAL]** Turn this rule on for summer-set campaigns or hot-region travel. Turn it off for winter campaigns. Calendar season ([`world/calendar.md`](world/calendar.md)) determines what counts as "hot."

### 2 · Sleeping in armor

A **long rest** taken in **medium or heavy armor** (without unbuckling) restores only **HALF** of what a long rest normally restores:

- **HP restored:** half (rounded down)
- **Hit Dice restored:** half (rounded down)
- **Spell slots:** full restoration as RAW (the channel resets regardless of comfort)

Why: nobody sleeps well in chain mail. The body braces and tenses; the rest is not real rest.

This applies even with the [HOUSE] "long rest in dangerous areas" rule from `house-rules.md` — if you can't doff your armor for safety reasons, you still pay the half-rest cost.

### 3 · Armor donning in combat

[HOUSE] **You cannot don any armor during a combat encounter.** Doffing in combat is *possible* (5 min for medium, 10 for heavy — taking that long means you spend most of the combat undressing) but typically a bad idea.

The RAW donning times (1 min light, 5 min medium, 10 min heavy) and doffing (1, 1, 5) still apply outside combat.

### 4 · Mounted falls in heavy armor

[HOUSE] If you are mounted and your mount is reduced to 0 HP (or you're forced off it), you take **1d6 bludgeoning damage** from the fall while in **heavy armor**. Medium armor: 1d4. Light or no armor: none.

This represents the historical reality that armored knights frequently died from falls, not from blade wounds.

### 5 · Movement penalty (RAW + minor amendment)

RAW: Heavy armor imposes −10 ft speed if STR < required.

[HOUSE] We extend: **Heavy armor always imposes −5 ft speed** (regardless of STR), with the additional −10 ft if STR is below the listed requirement. This represents the bulk and weight of plate or chain even on a strong character.

| Armor type | STR req | Speed penalty (homebrew) |
|---|---|---|
| Chain Mail | STR 13 | −5 ft baseline; −15 ft if STR < 13 |
| Splint | STR 15 | −5 ft baseline; −15 ft if STR < 15 |
| Plate | STR 15 | −5 ft baseline; −15 ft if STR < 15 |
| All medium armor | none | No baseline. Stealth disadvantage applies as RAW. |
| All light armor | none | None. |

> **Why apply −5 ft baseline to heavy armor?** Even a STR 18 fighter in plate moves slightly slower than they would in chain — physics doesn't care how strong you are. The penalty is mild (one square in grid terms); the message is "heavy armor isn't free."

---

## §D · Initiative & Timing

Initiative determines **turn order** in combat. RAW: roll d20 + DEX modifier + any bonuses. We add weight load penalty and a delayed-initiative rule.

### Initiative formula (homebrew)

```
Initiative = 1d20 + DEX modifier
           + Load Penalty (from §B)
           + Awareness modifier
           + Heroic Inspiration (if spent)
           + Alert feat (+5, RAW)
```

- **Load Penalty** (negative number applied to roll):
  - Light Load: 0
  - Standard Load: −1
  - Heavy Load: −3
  - Overload: −5
- **Awareness modifier:**
  - **+0 default** (normal awareness)
  - **−5 surprised** (you didn't see the threat coming; this is harsher than RAW's "lose your first turn")
  - **+2 alerted** (an ally warned you, you were hiding and saw them first, etc.)

### Round structure (RAW reminder)

A combat round = 6 seconds in the fiction.

On your turn you can take **all of these in any order** during your turn:

| Type | How many per turn | What |
|---|---|---|
| **Movement** | Up to your Speed total | Can split between actions (move, attack, move) |
| **Action** | 1 | Attack, Cast a Spell, Dash, Disengage, Dodge, Help, Hide, Magic, Ready, Search, Study, Utilize, Influence |
| **Bonus Action** | 1, only if a feature grants it | Class features, two-weapon fighting, Cunning Action, etc. |
| **Reaction** | 1 between turns | Opportunity Attack, certain spells, Held Action trigger |
| **Free Object Interaction** | 1 per turn | Draw weapon, open door, drop item, sheathe weapon |

For canonical descriptions see [`wiki/concepts/rhythm-of-play.md`](../wiki/concepts/rhythm-of-play.md).

### [HOUSE] Pre-declared Reactions

You may state your reaction intent **before** initiative returns to you. Once stated, the DM tracks whether the trigger fires. You may **change your declared reaction** between others' turns (per [`house-rules.md`](house-rules.md)).

Example: *"I'll use my reaction to Counterspell if anyone casts an attack spell."* Then if a goblin shaman starts casting Fire Bolt before your turn, the DM asks you whether to fire the reaction, and you decide live.

### [HOUSE] Delayed Initiative

You may **delay** on your turn — pushing your initiative slot later by a chosen number of positions:

- **On your turn:** declare *"I delay X slots."* (X is 1 to 10.)
- Your turn ends immediately; you take no actions this round.
- You re-insert into initiative **X slots later in initiative order**.
- On your delayed slot, you take a normal turn — but with **half movement that round** (you spent half the round watching for your moment).
- You can only delay once per round.

When useful: waiting for an ally to set up; holding for a specific trigger; resetting initiative order so you can coordinate.

### [HOUSE] Surprised vs Alert

RAW surprised rule (lose your first turn) is replaced:

- **Surprised characters take −5 to initiative** (per Awareness above).
- They do NOT lose their entire turn — they just go later, and their first turn has **disadvantage on attack rolls.**
- This is gentler than RAW (a surprised character is still in the fight) but the disadvantage means they're scrambling.
- **Alert feat (RAW):** the +5 to initiative makes surprise functionally impossible — you're never surprised.

> Rationale: RAW "lose your first turn" feels punishing in a one-encounter fight. The disadvantage-on-attacks version still hurts but doesn't make a player feel removed from the table.

### [HOUSE] Sprint as a Full-Action Dash

When you take the **Dash action** to use your full movement (2× speed in one turn):

- You double your speed total for the turn (RAW).
- **[HOUSE]:** All attacks against you this round have **disadvantage** (you're moving fast).
- **[HOUSE]:** You have **disadvantage on attacks you make this turn** (you're not aiming carefully).
- Useful when you need to *cover ground* — chasing, fleeing, repositioning across the battlefield.

---

## §E · Time Outside Combat

For the canonical reference see [`docs/dm-handbook/session-time-tracker.md`](../docs/dm-handbook/session-time-tracker.md). Key principles:

- **Time advances on scene change**, not every minute.
- **Dungeon turns** = 10 minutes each. Use when the party is in a dangerous timed space.
- **Short rest** = 1 hour. **Long rest** = 8 hours (with the half-rest penalty above if armored).
- **Travel rates:**
  - Slow pace: 1 mile in 30 minutes (sneaking, foraging, careful)
  - Normal pace: 1 mile in 20 minutes
  - Fast pace: 1 mile in 15 minutes (no Perception checks while moving)
- **Day's travel:** 24 miles on foot, 32 miles on horseback.

> **Carrying capacity affects travel too.** A character in **Standard Load** or above adds **+10% to travel time** per Standard threshold. A Heavy Load doubles the time for a forced march. Overload halves the day's travel distance.

---

## §F · Practical Examples

### Common loadouts and their tiers

#### "Standard Fighter" — STR 15, plate, longsword + shield + dungeoneer's pack

Plate (65) + longsword (3) + shield (6) + pack (55) = **129 lb.** STR 15 thresholds: Light 75 / Standard 150. **Standard Load.** Initiative −1; needs to watch fatigue on long marches.

#### "Stealthy Rogue" — STR 10, leather, two shortswords, burglar's pack

Leather (10) + two shortswords (4) + pack (42) + thieves' tools (1) = **57 lb.** STR 10 thresholds: Light 50 / Standard 100. Just over the line — **Standard Load.** Drop the lantern (3 lb) or a torch or two and they're Light.

#### "Pure Wizard" — STR 8, no armor, scholar's pack, focus, daggers

No armor + quarterstaff (4) + scholar's pack (22) + arcane focus (3) + 3 daggers (3) + spellbook (3) = **35 lb.** STR 8 thresholds: Light 40 / Standard 80. **Light Load.** No penalties.

#### "Ranger with Bow" — STR 12, studded leather, longbow + shortsword + explorer's pack

Studded leather (13) + longbow (2) + shortsword (2) + pack (55) + quiver with 40 arrows (2) = **74 lb.** STR 12 thresholds: Light 60 / Standard 120. **Standard Load.** Initiative −1; watch fatigue on multi-day travel.

#### "Burden-Bearing Knight" — STR 18, plate, polearm + dungeoneer's pack

Plate (65) + halberd (6) + pack (55) = **126 lb.** STR 18 thresholds: Light 90 / Standard 180. **Standard Load.** Even at maximum mortal strength, plate + a full pack puts you in Standard. Initiative −1 baseline.

### When you should care vs when to wave it off

**The DM should call out load tier checks** when:
- A player picks up significant new gear (loot, a new weapon, a wounded ally).
- A player wants to perform a DEX-heavy action (climb, swim, jump, balance, sneak).
- A travel scene starts.
- A combat round of initiative is rolled.

**The DM can wave it off** when:
- The party is in a safe area with no time pressure.
- The action wouldn't be affected (a Persuasion check doesn't care about load).
- The fiction makes it irrelevant ("you're in a market square, you've left your pack at the inn").

---

## §G · Updating `house-rules.md`

This file **replaces** one line from [`house-rules.md`](house-rules.md):

> ❌ ~~**Encumbrance philosophy** — "Carry what's reasonable; we'll call it out when it matters." No strict weight tracking unless DM names it.~~

Replace with:

> ✅ **Encumbrance & weight** — see [`physicality.md`](physicality.md) for the four-tier carrying-capacity system, weapon weight tiers, and armor drawbacks.

When you re-read `house-rules.md`, edit that line yourself or ping me to do it.

---

## §H · Quick reference (rip out, tape to screen)

```
CARRYING CAPACITY (STR = X)
  Light Load:      0 — X×5      no penalty
  Standard Load:   X×5 — X×10   -1 init, fatigue checks
  Heavy Load:      X×10 — X×15  -10 ft, disadv DEX, -3 init
  Overload:        X×15 — X×20  -20 ft, disadv everything, -5 init, no reactions
  Max:             X×20         hard limit

WEAPON WEIGHT
  Light:   ≤3 lb   no homebrew tax
  Medium:  4-7 lb  no homebrew tax
  Heavy:   8+ lb   two-handed OR STR 15+ for one-handed swing
  Hefting penalty: weapon weight > STR/2 → -1 to attacks

ARMOR DRAWBACKS [HOUSE]
  Heavy armor:  -5 ft baseline + RAW STR-requirement penalty
  Hot wearing:  Con save / hour [OPTIONAL — season-gated]
  Sleeping in:  half HP + half HD restored on long rest
  Don in combat: cannot
  Mounted fall: 1d6 (heavy), 1d4 (medium), 0 (light)

INITIATIVE
  = 1d20 + DEX + Load Penalty + Awareness + (Alert +5, RAW)
  Surprised: -5 + disadv on first turn's attacks (gentler than RAW)
  [HOUSE] Delay: push N slots later, lose half movement that round
  [HOUSE] Sprint Dash: disadv on attacks AND attacks against you

LONG-HAUL FATIGUE
  4 hrs at Standard+: Con save (10/12/15)
  Fail: 1 exhaustion
```

---

## §I · Cross-references

- House rules (line about encumbrance to update): [`house-rules.md`](house-rules.md)
- Weapons list with weights: [`../docs/player-guide/weapons-reference.md`](../docs/player-guide/weapons-reference.md)
- Armor combined table: [`../docs/player-guide/equipment-reference.md`](../docs/player-guide/equipment-reference.md) · [`../wiki/equipment/armor.md`](../wiki/equipment/armor.md)
- Session time tracker (canonical out-of-combat time): [`../docs/dm-handbook/session-time-tracker.md`](../docs/dm-handbook/session-time-tracker.md)
- Action economy and rhythm of play: [`../wiki/concepts/rhythm-of-play.md`](../wiki/concepts/rhythm-of-play.md)
- Conditions — exhaustion: [`../wiki/conditions/exhaustion.md`](../wiki/conditions/exhaustion.md)
- Initiative wiki: [`../wiki/core/initiative.md`](../wiki/core/initiative.md)
- DM Operating Manual — Time & Pacing (§4) and Ruling on the Fly (§7): [`00-dm-operating-manual.md`](00-dm-operating-manual.md)
- Character Design — survival/wounds tie-in (heavy load → exhaustion → wound recovery slower): [`character-design/survival.md`](character-design/survival.md)
