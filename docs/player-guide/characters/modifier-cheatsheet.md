# Modifier & Math Cheat Sheet · Session 1 Party

*How every number on the four sheets is calculated. Use this to spot-check players, answer "what's my bonus?" instantly, and explain the math to first-time players.*

---

## The Formulas (universal)

| What you want | Formula |
|---|---|
| **Ability modifier** | (score − 10) ÷ 2, round **down** |
| **Proficiency Bonus (PB)** | +2 at L1–4 · +3 at L5–8 · +4 at L9–12 |
| **Saving Throw** | Ability mod + (PB if proficient) |
| **Skill Check** | Ability mod + (PB if proficient) + (PB again if Expertise) |
| **Attack Roll** | Ability mod + PB *(Str for melee, Dex for ranged/finesse, casting mod for spells)* |
| **Damage** | Weapon die + Ability mod *(no PB)* |
| **Spell Save DC** | 8 + PB + casting ability mod |
| **Spell Attack** | PB + casting ability mod |
| **AC (light armor)** | armor base + Dex mod |
| **AC (medium armor)** | armor base + Dex mod (capped at +2) |
| **AC (heavy armor)** | fixed armor value, ignores Dex |
| **AC + shield** | + 2 |
| **HP at L1** | max of class hit die + Con mod |
| **HP per level after L1** | (½ hit die + 1) + Con mod, OR roll and add Con mod |
| **Initiative** | Dex mod + (PB if Alert feat) |
| **Passive score** | 10 + skill modifier *(no roll, just a fixed value)* |
| **Carrying capacity (lb)** | Str score × 15 |

---

## Ability Score → Modifier Conversion Table

| Score | 1 | 2-3 | 4-5 | 6-7 | 8-9 | 10-11 | 12-13 | 14-15 | 16-17 | 18-19 | 20 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| **Mod** | −5 | −4 | −3 | −2 | **−1** | **+0** | **+1** | **+2** | **+3** | +4 | +5 |

---

## Ability Scores & Modifiers — All 4 PCs

| | **Vesper** | **Bard** | **Stannis** | **Druid** |
|---|---|---|---|---|
| **STR** | 8 → **−1** | 8 → **−1** | 17 → **+3** | 13 → **+1** |
| **DEX** | 16 → **+3** | 14 → **+2** | 8 → **−1** | 12 → **+1** |
| **CON** | 15 → **+2** | 13 → **+1** | 14 → **+2** | 14 → **+2** |
| **INT** | 11 → **+0** | 10 → **+0** | 10 → **+0** | 10 → **+0** |
| **WIS** | 13 → **+1** | 15 → **+2** | 12 → **+1** | 15 → **+2** |
| **CHA** | 12 → **+1** | 15 → **+2** | 14 → **+2** | 8 → **−1** |
| **PB** | +2 | +2 | +2 | +2 |

---

## Saving Throws — Math Shown

Class save proficiencies in **bold**.

| Save | Vesper (Rogue) | Bard | Stannis (Fighter) | Druid |
|---|---|---|---|---|
| **STR** | −1 | −1 | **+3 +2 = +5** ✓ | +1 |
| **DEX** | **+3 +2 = +5** ✓ | **+2 +2 = +4** ✓ | −1 | +1 |
| **CON** | +2 | +1 | **+2 +2 = +4** ✓ | +2 |
| **INT** | **+0 +2 = +2** ✓ | +0 | +0 | **+0 +2 = +2** ✓ |
| **WIS** | +1 | +2 | +1 | **+2 +2 = +4** ✓ |
| **CHA** | +1 | **+2 +2 = +4** ✓ | +2 | −1 |

> *Save proficiencies come from class: Rogue (Dex, Int) · Bard (Dex, Cha) · Fighter (Str, Con) · Druid (Int, Wis).*

---

## Skill Checks — Math Shown

Only proficient skills listed. **Bold = Expertise (2× PB).**

### Vesper
| Skill | Math | Total |
|---|---|---|
| Acrobatics (Dex) | +3 + 2 | **+5** |
| Athletics (Str) | −1 + 2 | **+1** |
| Insight (Wis) | +1 + 2 | **+3** |
| Perception (Wis) | +1 + 2 | **+3** |
| Performance (Cha) | +1 + 2 | **+3** |
| Sleight of Hand (Dex) | +3 + 2 | **+5** |
| Stealth (Dex) | +3 + 2 | **+5** |
| *Expertise (pick 2)*: e.g. Stealth | +3 + 4 | **+7** |

### Bard
| Skill | Math | Total |
|---|---|---|
| Animal Handling (Wis) | +2 + 2 | **+4** |
| Insight (Wis) | +2 + 2 | **+4** |
| Nature (Int) | +0 + 2 | **+2** |
| Performance (Cha) | +2 + 2 | **+4** |
| Survival (Wis) | +2 + 2 | **+4** |

**Jack of All Trades (L2)** — add **+1** (half PB) to any non-proficient ability check.

### Stannis
| Skill | Math | Total |
|---|---|---|
| Athletics (Str) | +3 + 2 | **+5** |
| Insight (Wis) | +1 + 2 | **+3** |
| Intimidation (Cha) | +2 + 2 | **+4** |
| Persuasion (Cha) | +2 + 2 | **+4** |
| Survival (Wis) | +1 + 2 | **+3** |

> ⚠️ Verify Insight/Persuasion/Survival source — Human Skillful gives 1 skill in 2024, not 3.

### Druid
| Skill | Math | Total |
|---|---|---|
| Animal Handling (Wis) | +2 + 2 | **+4** |
| Insight (Wis) | +2 + 2 | **+4** |
| Medicine (Wis) | +2 + 2 | **+4** |
| Nature (Int) | +0 + 2 | **+2** |
| Perception (Wis) | +2 + 2 | **+4** |

---

## Combat Stats — Math Shown

| | Vesper | Bard | Stannis | Druid |
|---|---|---|---|---|
| **HP max** | 8 + 2 = **10** | 8 + 1 = **9** | 10 + 2 = **12** | 8 + 2 = **10** |
| **AC** | 11 + 3 = **14** *(Leather)* | 10 + 2 = **12** *(no armor)* OR 11 + 2 = **13** *(Leather)* | **16** *(Chainmail, no Dex)* · **18** with shield | 11 + 1 + 2 = **14** *(Leather + Shield)* |
| **Initiative** | +3 + 2 = **+5** *(Alert)* | +2 + 2 = **+4** *(Alert)* | **−1** *(no Alert)* | +1 + 2 = **+3** *(if Alert)* OR **+1** *(if Skilled instead)* |
| **Speed** | 30 ft *(35 if Wood Elf)* | **35 ft** *(Wood Elf)* | 30 ft | 30 ft |
| **Hit Dice** | 1d8 | 1d8 | 1d10 | 1d8 |

---

## Attack Rolls & Damage — Math Shown

### Vesper (Dex-based, finesse)

| Weapon | To-hit math | To-hit | Damage |
|---|---|---|---|
| Shortsword | +3 (Dex) + 2 (PB) | **+5** | 1d6 + 3 piercing |
| Dagger (melee) | +3 + 2 | **+5** | 1d4 + 3 piercing |
| Dagger (thrown) | +3 + 2 | **+5** | 1d4 + 3 piercing · range 20/60 |
| Shortbow | +3 + 2 | **+5** | 1d6 + 3 piercing · range 80/320 |
| **Sneak Attack** | (only triggers with advantage OR ally within 5 ft of target) | — | **+1d6** to one hit per turn |

### Bard

Pick a weapon (Bards default to dagger or shortsword in 2024):

| Weapon | To-hit math | To-hit | Damage |
|---|---|---|---|
| Dagger (Dex) | +2 + 2 | **+4** | 1d4 + 2 piercing |
| Quarterstaff (Str) | −1 + 2 | **+1** | 1d6 − 1 *(don't use this)* |

### Stannis (Str-based, two-hander)

| Weapon | To-hit math | To-hit | Damage |
|---|---|---|---|
| Greatsword | +3 (Str) + 2 (PB) | **+5** | 2d6 + 3 slashing · **Mastery: Graze** *(on miss, deal Str mod = 3 damage)* |
| Flail | +3 + 2 | **+5** | 1d8 + 3 bludgeoning |
| Javelin (thrown) | +3 + 2 | **+5** | 1d6 + 3 piercing · range 30/120 |
| Javelin (melee) | +3 + 2 | **+5** | 1d6 + 3 piercing |
| **Savage Attacker** | once per turn on a hit, reroll damage dice, take better | — | applies to any weapon |

### Druid

| Weapon | To-hit math | To-hit | Damage |
|---|---|---|---|
| Quarterstaff (Str) | +1 + 2 | **+3** | 1d6 + 1 bludg. · **versatile** 1d8 + 1 two-handed *(but shield occupies a hand)* |
| Dagger (Dex via finesse) | +1 + 2 | **+3** | 1d4 + 1 piercing |
| Sickle | +1 + 2 | **+3** | 1d4 + 1 slashing · **Mastery: Nick** *(extra attack with another Light weapon as part of Attack action)* |

---

## Spellcasting — Math Shown

| | Bard | Druid |
|---|---|---|
| **Casting ability** | Charisma | Wisdom |
| **Spell Save DC** | 8 + 2 (PB) + 2 (Cha) = **12** | 8 + 2 (PB) + 2 (Wis) = **12** |
| **Spell Attack** | 2 (PB) + 2 (Cha) = **+4** | 2 (PB) + 2 (Wis) = **+4** |
| **Cantrips known** | 2 + Druidcraft *(Wood Elf)* | 2 |
| **Spells prepared (L1)** | 4 | 4 |
| **L1 spell slots** | 2 | 2 |
| **Recovery** | Long Rest | Long Rest |
| **Focus** | Musical instrument | Druidic Focus *(Quarterstaff)* or Herbalism Kit |
| **Bardic Inspiration uses** | Cha mod = **2** per Long Rest | — |

**What enemies roll against:**
- A monster trying to *resist* a Bard or Druid spell rolls a saving throw vs DC **12**.
- The Bard or Druid making a *ranged* spell attack rolls **1d20 + 4** vs the target's AC.

---

## Passive Scores

Calculated as **10 + the skill modifier you'd use**. No d20 roll. The DM uses these silently.

| Passive | Vesper | Bard | Stannis | Druid |
|---|---|---|---|---|
| **Perception** *(Wis)* | 10 + 3 = **13** | 10 + 2 = **12** *(or 14 if Keen Senses chose Perception)* | 10 + 1 = **11** | 10 + 4 = **14** |
| **Insight** *(Wis)* | 10 + 3 = **13** | 10 + 4 = **14** | 10 + 3 = **13** *(if prof.)* | 10 + 4 = **14** |
| **Investigation** *(Int)* | 10 + 0 = **10** | 10 + 0 = **10** | 10 + 0 = **10** | 10 + 0 = **10** |

> **DM use:** When a Silent Check fires (Module 1 has many — Mordren's ring flicker, Bessa is scared, Tamsin's grief, etc.), compare the DC against the highest passive score on the table and narrate only to that player.
>
> **Highest passives in this party:**
> - **Perception 14** — Druid *(catches the ring flicker, the goblin smell, the warm millstone)*
> - **Insight 14** — Bard or Druid *(catches Bessa's fear, Bran's fear, Tamsin's grief, Mordren's relief)*
> - **Investigation 10** — nobody is proficient. The party will miss subtle Investigation clues unless they ask out loud.

---

## Carrying Capacity

| PC | Str | Carry max (lb) |
|---|---|---|
| Vesper | 8 | 120 |
| Bard | 8 | 120 |
| Stannis | 17 | **255** |
| Druid | 13 | 195 |

*If a PC carries more than 5× their Str, their speed drops by 10 and they have disadvantage on Str/Dex/Con checks, attacks, and saves (encumbered). Rarely a problem at L1 unless someone tries to haul a body.*

---

## Quick "What's my bonus?" Lookup

| Situation | Vesper | Bard | Stannis | Druid |
|---|---|---|---|---|
| Climb a wall (Athletics) | +1 | −1 *(not proficient)* | **+5** | +1 *(not proficient)* |
| Sneak past a guard (Stealth) | **+5** *(or +7 w/ Expertise)* | +2 *(not proficient)* | −1 | +1 |
| Spot a hidden door (Perception) | **+3** | +2 | +1 | **+4** |
| Convince Bran (Persuasion) | +1 | +2 *(not proficient)* | **+4** | −1 |
| Save vs. Fear/Charm (Wis) | +1 | +2 | +1 | **+4** |
| Save vs. Dragon Breath (Dex) | **+5** | **+4** | −1 | +1 |
| Hit Bran with a sword (melee atk) | +5 *(Dex)* | +4 *(Dex)* or +1 *(Str)* | +5 *(Str)* | +3 *(Str)* |

---

## When in Doubt at the Table

**"What do I roll for X?"** → 1d20 + (ability mod) + (PB if proficient)
**"What's the DC?"** → Easy 10 · Moderate 12 · Hard 14 · Very Hard 15 · Heroic 17
**"Do I have advantage?"** → If yes, roll 2d20, take higher. Disadvantage: take lower. They cancel — never stack.
**"How much damage?"** → Roll weapon die + ability mod (no PB). Critical hit: roll the weapon dice twice, then add the mod once.

---

## Links

- [Party chart (DM)](README.md)
- [Vesper sheet](vesper.md) · [Bard sheet](bard.md) · [Stannis sheet](stannis.md) · [Druid sheet](druid.md)
- [Character creation rules](../fallowton-character-creation.md)
- [Quick combat & skills reference](../quick-reference-combat-skills.md)
