# Combat Options — Everything You Can Do on Your Turn

The complete menu of combat actions for the Fallowton campaign: RAW 2024 options + every homebrew layer (Wounds, The Notice, Weave Strain, physicality initiative, the stakes rule). For the one-page version, see [`quick-reference-combat-skills.md`](quick-reference-combat-skills.md). This is the deep reference.

---

## Your turn — the structure

On your turn, in any order, you may use:

| Slot | How many | What |
|---|---|---|
| **Movement** | Up to your Speed | Can split: move, attack, move again. |
| **Action** | 1 | The big choice (see the menu below). |
| **Bonus Action** | 1 — *only if a feature grants one* | Two-weapon attack, Cunning Action, Healing Word, Second Wind, etc. |
| **Reaction** | 1 between turns | Opportunity Attack, Counterspell, Shield, a Readied action. |
| **Free Object Interaction** | 1 | Draw/sheathe a weapon, open a door, drop something, pull a torch. |

You do **not** have to use all of them. "I move and Dodge" is a complete turn.

---

## The Action menu (your 1 action)

| Action | What it does |
|---|---|
| **Attack** | One attack with a weapon or unarmed strike. (Extra Attack at higher levels = more.) |
| **Cast a Spell** | A spell with a casting time of 1 action. **Triggers Weave Strain if leveled** (see below). |
| **Dash** | Gain extra movement equal to your Speed this turn. **[HOUSE] Sprint Dash** below. |
| **Disengage** | Your movement doesn't provoke Opportunity Attacks this turn. |
| **Dodge** | Attacks against you have disadvantage; your Dex saves have advantage. Until your next turn. |
| **Help** | Give an ally advantage on one attack or check. **[HOUSE]: you must be within 5 ft OR able to physically participate.** |
| **Hide** | Dex (Stealth) vs the passive Perception of those who'd notice. Success = you're Unseen. |
| **Influence** | Attempt to sway a creature mid-combat (Persuasion/Deception/Intimidation). Rarely works on a creature actively fighting you. |
| **Magic** | Use a magic item or a special magic feature that calls for the Magic action. |
| **Ready** | Pick a trigger + an action or movement to take when it fires (uses your Reaction). |
| **Search** | Wis (Perception) or Int (Investigation) to find something in the scene. |
| **Study** | Int check (Arcana, History, etc.) to recall or analyze something mid-combat. |
| **Utilize** | Interact with a second object beyond your free interaction (operate a lever, etc.). |

---

## Attacking — the math

| Attack type | To hit | Damage |
|---|---|---|
| **Melee weapon** | d20 + ability mod + prof (if proficient) | weapon die + ability mod |
| **Ranged weapon** | d20 + Dex + prof | weapon die + Dex |
| **Finesse weapon** | d20 + (Str OR Dex, your choice) + prof | weapon die + same mod |
| **Thrown weapon** | as melee (Str) or finesse | weapon die + mod |
| **Spell attack** | d20 + spellcasting mod + prof | per spell |
| **Spell save** | target rolls vs your DC (8 + mod + prof) | per spell |

**Critical hit (natural 20):** [HOUSE] **max your damage dice + roll your damage dice** (e.g., greatsword crit = 12 + 2d6 + Str). This is stronger than RAW double-dice; see [`../../homebrew/house-rules.md`](../../homebrew/house-rules.md).

**Damage types** matter — some monsters resist/are immune to bludgeoning, piercing, or slashing. See [`weapons-reference.md`](weapons-reference.md) §B.

---

## Weapon Mastery (martial classes)

If your class grants **Weapon Mastery** (Barbarian, Fighter, Paladin, Ranger, Rogue at level 1; you pick 2-3 weapons), each weapon has ONE mastery that triggers on your attack:

| Mastery | Effect |
|---|---|
| **Cleave** | Hit → free attack vs a 2nd creature within 5 ft. Once/turn. |
| **Graze** | Miss → still deal ability-mod damage. |
| **Nick** | Two-weapon extra attack folds into your Attack action (frees Bonus Action). |
| **Push** | Hit → push target up to 10 ft (Large or smaller). |
| **Sap** | Hit → target has disadvantage on its next attack. |
| **Slow** | Hit → target's speed −10 ft until your next turn. |
| **Topple** | Hit → target Con save or knocked Prone. |
| **Vex** | Hit → advantage on your next attack vs that target. |

Full list of which weapon has which mastery: [`weapons-reference.md`](weapons-reference.md) §D. You swap masteries only on a long rest.

---

## Two-weapon fighting

- Attack with a **Light** weapon → Bonus Action attack with a second Light weapon.
- Off-hand attack doesn't add your ability mod to damage **unless** you have the Two-Weapon Fighting style.
- **[HOUSE] combined weight ≤ 6 lb** for both weapons (per [`../../homebrew/physicality.md`](../../homebrew/physicality.md) §A).
- **Nick mastery** lets the off-hand attack fold into your Attack action, freeing the Bonus Action.

---

## Spellcasting in combat

- **1 action** for most combat spells (some are Bonus Action, like Healing Word; some are Reactions, like Shield/Counterspell).
- **Concentration:** one concentration spell at a time. Take damage → Con save (DC 10 or half the damage, whichever higher) to maintain. **[HOUSE]:** active Trauma raises this DC by +2 (per [`../../homebrew/sanity-and-spirit.md`](../../homebrew/sanity-and-spirit.md)).
- **Weave Strain:** every **leveled** spell (using a slot) adds +1 Strain and a cost. Cantrips are usually free. **Read [`../campaign/weave-strain-magic.md`](../campaign/weave-strain-magic.md).**
- **The Notice:** casting a leveled spell inside or near a Converter site ticks **World Notice +1** (per [`../../homebrew/the-notice.md`](../../homebrew/the-notice.md)). Casting at Personal Notice 7+ costs +1 extra Strain on your first daily cast.
- **Components in the dark:** material components need a free hand + light; in pitch dark, Sleight of Hand DC 12 (per [`../../homebrew/survival-realism.md`](../../homebrew/survival-realism.md) §A4).

---

## Movement options

- **Difficult terrain:** each foot costs 2 (rubble, mud, the Cinderfen fen).
- **Climbing / swimming:** each foot costs 2 (or an Athletics check if hard). Heavy armor underwater = Athletics DC 15 per round.
- **Jumping:** long jump = Str score in feet (with a 10-ft running start); high jump = 3 + Str mod feet.
- **Prone:** drop is free; standing costs half your speed. Attacking while prone = disadvantage; melee attacks against you = advantage; ranged against you = disadvantage.
- **[HOUSE] Load tier affects speed:** Heavy Load = −10 ft; Overload = −20 ft (per physicality §B).
- **Squeezing** through a tight space: treated as difficult terrain; attacks against you have advantage.

---

## Defensive options

- **Dodge** (action): attackers have disadvantage; you have advantage on Dex saves.
- **Cover:** half cover = +2 AC & Dex saves; three-quarters = +5; total cover = can't be targeted directly. (Use the stone columns in the ruin.)
- **Disengage** (action): move without provoking.
- **Shield spell** (reaction, if you have it): +5 AC until your next turn.
- **Second Wind** (Fighter bonus action): regain 1d10 + level HP.

---

## The homebrew combat layer (what's different in Fallowton)

### Initiative (modified)

```
Initiative = 1d20 + DEX mod + Load Penalty + Awareness + (Alert feat +5)
```
- Load Penalty: Light 0 / Standard −1 / Heavy −3 / Overload −5
- Awareness: normal 0 / surprised −5 / alerted +2
- Full formula: [`../../homebrew/physicality.md`](../../homebrew/physicality.md) §D.

### [HOUSE] Delayed Initiative

On your turn, declare *"I delay X slots"* (1-10). Your turn ends; you re-enter X slots later with **half movement** that round. Use it to wait for an ally.

### [HOUSE] Sprint Dash

Full Dash to cover ground: double speed, BUT disadvantage on your attacks this turn AND attacks against you have disadvantage (you're moving fast).

### [HOUSE] Pre-declared Reactions

State your reaction intent before your turn comes up (*"I Counterspell if anyone casts an attack spell"*). DM tracks the trigger; you can change it between turns.

### [HOUSE] Stakes-required for cinematic actions

Want to swing on a chandelier, kick a brazier, topple a cart? The DM says **YES-IF** — the IF names what failure costs. *"Yes if Acrobatics DC 13; fail = you fall prone in the fire's path."* Creative play is rewarded with consequences worth rolling for.

### Wounds (when you hit 0 and survive)

Drop to 0 HP, then get back up (stabilize / heal / 3 death-save successes) → **take one Wound** from the 12-entry table (broken rib, twisted ankle, bleeding gash, etc.). It lingers until healed. 3+ Wounds = failed death saves count double. Full system: [`../../homebrew/character-design/survival.md`](../../homebrew/character-design/survival.md).

### Death Visions (when you roll a death save)

The player **narrates a brief vision** on each death save. Nat 20 = the Hollow Star slips you useful info (+1 Notice if you accept). Nat 1 = lose a small memory for 24 hours. 3 fails = death; your final Vision lives on your sheet if revived.

### The Notice in combat

- Killing with a Dawnweave-tainted weapon: +1 Personal Notice.
- A Hollowed Wound (Dawnweave-source damage): +1 Personal Notice when taken.
- Fighting inside an awakened Converter chamber raises World Notice, which spills onto you.
- Full system: [`../../homebrew/the-notice.md`](../../homebrew/the-notice.md).

---

## Conditions quick cheat (the 15)

| Condition | The gist |
|---|---|
| Blinded | Auto-fail sight checks; disadv your attacks, adv attacks vs you |
| Charmed | Can't harm charmer; charmer adv on social with you |
| Deafened | Auto-fail hearing checks |
| Frightened | Disadv checks/attacks while source visible; can't approach it |
| Grappled | Speed 0; disadv attacks vs anyone but grappler |
| Incapacitated | No actions, bonus, reactions |
| Invisible | Adv your attacks, disadv attacks vs you; can't be seen |
| Paralyzed | Incapacitated + can't move; auto-fail Str/Dex saves; melee crit within 5 ft |
| Petrified | Stone; incapacitated; resist all damage |
| Poisoned | Disadv on attacks and ability checks |
| Prone | Crawl or stand (half speed); disadv your attacks; mixed for attacks vs you |
| Restrained | Speed 0; disadv your attacks & Dex saves; adv attacks vs you |
| Stunned | Incapacitated; auto-fail Str/Dex saves; adv attacks vs you |
| Unconscious | Incapacitated + prone + unaware; melee crit within 5 ft |
| Exhaustion | −2 per level on d20 tests; −5 ft speed per level; die at 6 |

Full pages: [`../../wiki/conditions/`](../../wiki/conditions/).

---

## A worked combat round (Vesper the Rogue, level 1)

> Vesper (Rogue, DEX 16, AC 14, shortbow + dagger) faces a goblin 25 ft away.
>
> **Initiative:** 1d20 + 3 (DEX) + 0 (Light Load) = rolls 14 → **17**.
> **Movement:** moves 15 ft to a stone column (half cover from the goblin's bow — +2 AC).
> **Action — Attack** with shortbow: d20 + 3 (DEX) + 2 (prof) = rolls 12 → 17 vs goblin AC 15 → **hit.** Damage: 1d6 + 3 = 7 piercing. **Vex mastery** → advantage on her next attack vs this goblin.
> **Bonus Action — Cunning Action (Rogue):** Hide. Dex (Stealth) vs goblin passive Perception.
> **No Weave Strain** (no spell). **No Notice tick** (mundane weapon).
>
> Next turn, if the goblin can't find her, her shortbow attack has advantage (Vex) AND she's Unseen (advantage again — doesn't stack, but she gets Sneak Attack damage since she has advantage). She adds +1d6 Sneak Attack.

---

## Cross-references

- One-page combat cheat: [`quick-reference-combat-skills.md`](quick-reference-combat-skills.md)
- Weapons (full list + masteries + properties): [`weapons-reference.md`](weapons-reference.md)
- Weave Strain (casting cost): [`../campaign/weave-strain-magic.md`](../campaign/weave-strain-magic.md)
- The Notice (combat ticks): [`../../homebrew/the-notice.md`](../../homebrew/the-notice.md)
- Physicality (initiative, load, sprint, delay): [`../../homebrew/physicality.md`](../../homebrew/physicality.md)
- Wounds & Death Visions: [`../../homebrew/character-design/survival.md`](../../homebrew/character-design/survival.md)
- Conditions: [`../../wiki/conditions/`](../../wiki/conditions/)
- DM-side combat running: [`../dm-handbook/`](../dm-handbook/) + DM Manual [`../../homebrew/00-dm-operating-manual.md`](../../homebrew/00-dm-operating-manual.md) §2-§4
