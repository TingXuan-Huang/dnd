---
type: character-design
category: survival
since: "homebrew"
tags: [hp, wounds, death-saves, healing, hollow-star]
updated: 2026-05-23
status: needs-review
---

# Survival Systems — HP, Wounds, Death

The RAW chassis stays intact: HP per class as RAW, death saves at 3-vs-3, long rest restores HP. We layer two new mechanics on top that tie combat consequences to the campaign's themes.

- **Wounds** make combat consequences real *for the body* — what happens after you survive 0 HP.
- **Death Visions** make near-death real *for the soul* — what the Hollow Star sees when you flirt with the threshold.

Both are additive. A table can drop either layer without breaking the other.

---

## §A · HP in Fallowton (the social reading)

Mechanically, HP works exactly as in [`wiki/core/hit-points.md`](../../wiki/core/hit-points.md). Socially, HP **carries weight in this village** because most people have very little of it.

| Who | Approximate HP | What villagers think |
|---|---|---|
| A child | 1–3 | invisible to combat |
| A villager | 3–6 | "they're soft; mind them" |
| A trained guard | 8–12 | "they can handle a fight" |
| A village elder | 4–8 | wisdom is what they bring, not steel |
| A level-1 PC | 8–15 | **already exceptional.** Bran's grandson is not coming home from soldier training, but you walked here from somewhere |
| A level-3 PC | 20–35 | *"marked,"* whispered. People stand differently around you |
| A level-5 PC | 35–55 | *"blessed"* OR *"warned"* — Mordren-tier presence |
| A level-10 PC | 70–100 | the village hasn't seen one in living memory |

**Villagers can feel this.** A high-HP PC walking into the Bent Plow Inn shapes the room without speaking. NPCs adjust:

- **Bran** is more deferent to high-HP strangers but more suspicious of their motives.
- **Bessa** is more curious; she'll ask probing questions over the second drink.
- **Sister Elra** is more careful — high-HP often means high-violence somewhere in your past.
- **Children** keep watching you when their parents tell them not to.

> **[HOUSE] No mechanical penalty, just texture.** This is for DM narration, not a stat block. But if you're playing a Bucket-2 campaign and the PCs are level 5+, the village's responses should reflect that they're walking among legends.

### HP calculation

- Level 1: HD max + CON modifier (RAW; see [`wiki/concepts/character-creation.md`](../../wiki/concepts/character-creation.md))
- Each level thereafter: roll HD or take average + CON modifier (RAW)
- See [`wiki/core/hit-points.md`](../../wiki/core/hit-points.md) for the full math

We use RAW HP. No homebrew overlay on the calculation itself.

---

## §B · Wounds (the body)

When you drop to 0 HP and survive, **you take one Wound.** A Wound is a narrative + light-mechanical effect that persists until properly healed. Wounds make near-death stick in a way RAW HP doesn't.

### When you take a Wound

You drop to 0 HP, then return to consciousness (via stabilizing, healing, or 3 death-save successes). At that moment, **take one Wound** from the table below.

- The DM picks which Wound based on what dropped you (a crushing weapon → broken rib; a fall → twisted ankle; a magical attack from a Dawnweave seal → Hollowed).
- The player may suggest a Wound that fits the fiction. DM has final say.
- Wounds are visible. Other characters notice. Villagers comment.

### When you do NOT take a Wound

- If you're healed to >0 HP **without dropping** (e.g., Healing Word at 1 HP before damage).
- If your only damage was non-physical and your save was passed (e.g., a Wisdom save against the ruin's whisper at 0 outcome).
- If a Sister Elra blessing (or equivalent) was active when you went down.

### The Wound table

| # | Wound | Trigger (damage type) | Mechanical bite |
|---|---|---|---|
| **1** | **Broken Rib** | bludgeoning, fall | Disadvantage on STR (Athletics) involving the chest (climb, swim, push). |
| **2** | **Concussion** | bludgeoning, magical psychic | Disadvantage on INT and WIS checks. Each long rest, may attempt Medicine DC 14 — success clears even without kit. |
| **3** | **Twisted Ankle** | bludgeoning, fall | Speed −10 ft. Disadvantage on DEX (Acrobatics). |
| **4** | **Punctured Lung** | piercing | Cannot Dash. Disadvantage on CON checks involving breath, sustained effort, or holding breath. |
| **5** | **Severed Tendon** | slashing, dragon claw | One limb unusable (DM picks). If dominant arm: disadvantage on attack rolls. If a leg: speed halved on top of any other penalty. |
| **6** | **Bleeding Gash** | slashing | Lose 1d4 HP at the start of each long rest until healed (the wound reopens at night). Medicine DC 12 + kit closes it. |
| **7** | **Burn** | fire | Visible disfigurement. Disadvantage on Persuasion with anyone who hasn't seen worse. Needs 3 long rests + 1 Medicine DC 12 check to fully clear. |
| **8** | **Numb Extremity** | cold | Disadvantage on DEX (Sleight of Hand) and any fine-motor check with the affected limb. |
| **9** | **Nerve Damage** | lightning, electricity | Random twitching. Disadvantage on Stealth. Each long rest roll d6: on 1–2, the next save DC tied to this wound +1; on 5–6, the twitch eases (no advantage, but no penalty next session). |
| **10** | **Hollowed** ⚠️ | necrotic, Dawnweave magical, House of First Light | A creeping cold under the skin. −1 to maximum HP until healed. Each death save while wounded triggers a Death Vision check (see §C). **Healing requires cleansing magic** (Lesser Restoration or higher) OR Sister Elra's blessing OR a full week at a cleansed spring. |
| **11** | **Voice Loss** | psychic, magical | Cannot speak above a whisper. Disadvantage on Persuasion, Intimidation, and verbal-component spell casting. Heals after 3 long rests OR Heal/Greater Restoration. |
| **12** | **Eye Injury** | slashing, piercing | Disadvantage on WIS (Perception) sight-based and on ranged attack rolls. If both eyes affected: Blinded condition. Heals on long rest + Medicine DC 14 with kit, OR permanently if untreated 7+ days. |

> **[HOUSE] DM may invent new Wounds.** Unusual damage situations (Awakening Clock effects, Hollow Star contact, specific monsters) can produce Wounds not on this table. Examples: *Memory Wound* (one Lore inaccessible until cleansed), *Echoing Wound* (you hear the carvings whisper at night).

### Stacking Wounds

| Wounds carried | What it means |
|---|---|
| **1** | A real bite. Manageable. The party can press on. |
| **2** | You're hurting. Start finding a healer in the next 1–2 days. |
| **3** | **Serious.** Any failed death save while at 3+ wounds counts as **2 fails** instead of 1. The next near-death is much closer to death. |
| **4+** | **Triage.** The party should evacuate. You're not making it to the next combat without a healer. |

### Healing Wounds (standard)

- **Long rest + Medicine DC 12 (with kit OR a healer present):** clears **one Wound** per long rest. Failed check: the rest didn't clear it; try again next long rest.
- **Lesser Restoration:** clears one Wound, any type (except Hollowed — that needs the spell *or* a blessing *or* a cleansed spring).
- **Greater Restoration:** clears two Wounds OR removes the cumulative Hollow Star sample effects (see §C).
- **Heal:** clears all Wounds. Removes 24-hour memory loss. Cannot remove permanent Visions.
- **Spare the Dying:** stabilizes RAW; if cast at exactly 0 HP **before** the player rolls their first death save, the patient avoids the Vision for this incident (but still takes a Wound on revival).
- **Sister Elra's blessing** (1/week, Fallowton-specific): clears one Wound and one Hollow Star sample effect. Requires a quiet evening at the village shrine. She gives it freely to villagers and trusted travelers; she refuses a licensed wizard who didn't ask politely.

> **Cross-reference:** the [`homebrew/house-rules.md`](../house-rules.md) "rest schedule" rule (long rests in dangerous areas can be interrupted; Awakening Clock continues to tick) interacts directly with wound healing — a long rest in the ruin doesn't clear wounds (or HP, by RAW) if interrupted before 8 uninterrupted hours.

---

## §C · Death Visions (the soul)

When you make a death save, **the player narrates a brief vision** — a flash of memory, sensation, or perception. The vision is *what the Hollow Star sees when it looks at you across the threshold.* You are not dying; you are being *examined*.

Pass/fail are mechanically RAW. Visions are flavor + occasional gift + occasional cost.

### How a death save plays out

| Roll | Mechanical (RAW) | Vision (narrated by player) |
|---|---|---|
| **Nat 20** | Regain 1 HP, stand up | **The Hollow Star slips you something.** The DM hands you one piece of useful campaign information you didn't have. |
| **Pass (10+)** | Counts toward 3 successes | A vivid memory or sense impression — player describes it. Free roleplay. No mechanical effect. |
| **Fail (≤9)** | Counts toward 3 fails | Something slipping — player describes what feels less real than it should. Free roleplay. |
| **Nat 1** | Counts as 2 fails | **A small memory slips for 24 in-game hours.** A name. A face. A direction. (See "Losing a Memory" below.) |
| **3 fails (death)** | Character dies | The final vision is the last thing. Player describes what their character sees as they go. If they're brought back later (Revivify, Raise Dead), the Vision **lives on the sheet permanently.** |

### Player-narrated visions — what to describe

This is **free narrative space** for the player. Some prompts to seed it:

- *A childhood smell — burning hay, river mud, your grandmother's kitchen*
- *A face you haven't thought of in years*
- *A sound — the village bell, a song you forgot you knew, a name spoken once*
- *A view from somewhere you've never been*
- *A taste, sharp and specific*

The DM does not gate this with rolls. It's the player's moment.

### The Nat 20 gift — what "useful campaign info" looks like

The DM hands the PC one specific piece of information. The Hollow Star isn't a friend — but it's *interested* in this PC, and revealing things to them serves its own curiosity. Possibilities at this campaign's level:

- *You remember Mordren's ring flickered blue at the inn — the moment the three farmers said "cave."*
- *You realize the carving on the descent stairs matches the rhythm of a prayer Sister Elra chanted yesterday.*
- *You know — from where you cannot say — that the Voss family is buried in the third row from the chapel wall.*
- *You catch the word "First Light" in the wind, and you know which direction it came from.*

Treat this like a free Lore-question (per [`abilities.md`](abilities.md) §C) but applied campaign-wide. The DM picks based on what's most useful for the next scene; don't telegraph plot.

### The Nat 1 cost — losing a memory

For the next 24 in-game hours, your character cannot recall **one specific thing**. The DM picks; the player roleplays the gap. Examples:

- A **name** they should know (an NPC's name; a place; a person from their backstory)
- A **face** they should recognize (when meeting a known NPC, they don't know who it is for one scene; the NPC may take offense)
- A **direction** they should remember (the way back to the inn; which tunnel they came from)
- A **skill they should know how to use** (one ability check has disadvantage, once during the 24 hours)

The memory returns automatically at the next dawn. The DM should pick something with **roleplay weight, not session-breaking weight** — losing the way to the inn is poignant; losing your character's own name is not.

### Cumulative effect — the Hollow Star Long Look

If you accumulate **5 or more death saves in a single in-game day** (passes or fails, both count), the Hollow Star has spent enough time at the threshold to take a longer look. The DM picks one:

- **A Lore you have becomes briefly inaccessible** until your next long rest.
- **A friend's face becomes harder to picture** — disadvantage on your next Persuasion or Insight check involving that friend.
- **Your dreams next long rest are vivid in a way you don't like** — DM narrates. Possibly a vision the Hollow Star planted (a question, an instruction, a glimpse of somewhere you shouldn't know).

This is a **strong deterrent against TPK-flirting** without being lethal. Cleansed by Greater Restoration, Sister Elra's blessing, or a week at a cleansed spring.

### Permanent visions (revived characters)

If your character dies and is later revived (Revivify, Raise Dead, etc.), the **final Vision lives on your sheet permanently.** Not a mechanical penalty — a *fact about your character.*

- The PC remembers the experience of dying.
- The Vision is theirs to roleplay; it shapes future decisions.
- Other characters who knew them well may notice they're a little different now (Insight DC 14 to articulate what changed).

A character can have multiple permanent visions if revived multiple times. Each is a scar on the soul, in the way Wounds are scars on the body.

---

## §D · Healing & Recovery Summary

### HP recovery (RAW, with one house-rules tie-in)

- **Short rest:** Hit Dice spending as RAW
- **Long rest:** full HP restored + half Hit Dice (RAW)
- **[HOUSE]:** Long rests in dangerous areas can be interrupted, and the Awakening Clock continues to tick (see [`house-rules.md`](../house-rules.md))

### Wound recovery (standard, per Bucket 2 design)

- Long rest + Medicine DC 12 (with kit OR healer): one Wound cleared
- Healing magic (Lesser/Greater Restoration, Heal): cleared per spell scaling above
- Sister Elra's blessing (1/week): one Wound + one Long Look effect cleared

### Death Vision recovery

- 24-hour memory loss: returns automatically at dawn
- Hollow Star Long Look effects: 1 long rest (or magical cleansing) for most; some require a week at a cleansed spring
- **Permanent visions (from death + revival):** **never recover.** They are part of who the character is now.

### Quick reference (rip out, tape to screen)

```
0 HP, SURVIVED → take 1 Wound from table (§B)
                  Healing: long rest + Medicine DC 12 + kit/healer

DEATH SAVE:
  Nat 20  → Hollow Star gift (DM hands you info)
  Pass    → player narrates a memory
  Fail    → player narrates something slipping
  Nat 1   → lose 1 small memory for 24 in-game hours
  3 fails → die; final Vision lives on sheet if later revived

5+ DEATH SAVES IN A DAY → Hollow Star Long Look (DM picks effect)

3+ WOUNDS CARRIED      → any failed death save counts as 2 fails

WOUND HEAL              = long rest + Medicine DC 12 (one per rest)
HOLLOWED WOUND HEAL     = cleansing magic OR Sister Elra OR a week at a spring
LONG LOOK HEAL          = long rest, OR Greater Restoration, OR Sister Elra
PERMANENT VISION HEAL   = never. It's yours.
```

---

## Cross-references

- Wiki — HP: [`wiki/core/hit-points.md`](../../wiki/core/hit-points.md) · [`wiki/core/initiative.md`](../../wiki/core/initiative.md)
- Wiki — Conditions (the 15 official): [`wiki/conditions/`](../../wiki/conditions/) · particularly [[unconscious]], [[exhaustion]]
- Weave Strain (the parallel cost-system for casters): [`../../docs/campaign/weave-strain-magic.md`](../../docs/campaign/weave-strain-magic.md)
- House rules — death save secrecy, rest schedule: [`../house-rules.md`](../house-rules.md)
- DM Operating Manual — Cardinal Rule 2 (fudging only in TPK-from-bad-luck on a setup combat OR new-player-rescue Session 1): [`../00-dm-operating-manual.md`](../00-dm-operating-manual.md#2--the-interference-dial)
- Sister Elra blessing reference: [`../../docs/dm-handbook/module-1-npcs.html`](../../docs/dm-handbook/module-1-npcs.html)
- Dawnweave / Hollow Star lore: [`../world/dawnweave-legend.md`](../world/dawnweave-legend.md) (DRAFT) · [`../world/magic-in-society.md`](../world/magic-in-society.md) (DRAFT)
