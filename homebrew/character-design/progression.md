---
type: character-design
category: progression
since: "homebrew"
tags: [skills, leveling, tiers, downtime]
updated: 2026-05-23
status: needs-review
---

# Progression Systems — Skills, Leveling, Tier Crossings

How characters **grow** in Fallowton. Keep RAW's chassis (the 18 skills, 1-20 level scale, proficiency bonus, ASI cadence). Add Fallowton flavor to skills, design a story-driven leveling method, and put social weight on each tier crossing.

This file covers character growth *between* sessions. Combat-round mechanics live in the [`survival.md`](survival.md) and [`abilities.md`](abilities.md). Build choices (feats, species) come in Bucket 4.

---

## §A · The 18 Skills — Fallowton reading

We use **RAW's 18 skills** (see [`wiki/core/skills-overview.md`](../../wiki/core/skills-overview.md) for canonical descriptions). No new skills — additions live as **Lore sub-specialties** in [`abilities.md`](abilities.md) §C.

What's specific to this campaign: how each skill **reads socially** in Fallowton. Some skills villagers respect; some they tolerate; some they actively distrust.

| Skill | Ability | Fallowton reading | Reaction |
|---|---|---|---|
| **Athletics** | STR | Useful, not impressive. Most villagers have it. | Neutral |
| **Acrobatics** | DEX | Hunters and midwives respect it. Otherwise showboating. | Conditional |
| **Sleight of Hand** | DEX | **Watched.** Villagers track your hands when you have it visibly. | Suspect |
| **Stealth** | DEX | Fine in the Mereswood. Suspect in the village square. | Conditional |
| **Arcana** | INT | **Deeply suspect.** Mark of an outsider or a wizard. Mordren has it openly; that's why he's barely tolerated. | Distrusted |
| **History** | INT | Respected when applied to the village's past. Suspect when applied to *"old things."* Tamsin's free-history is loved; a scholar's Dawnweave-history is feared. | Conditional |
| **Investigation** | INT | Neutral. Villagers expect investigators (Office types) to investigate; you do not earn extra trust for the skill alone. | Neutral |
| **Nature** | INT | **Respected.** The village's livelihood. People will share information with you about the fields, the weather, the woods. | Trusted |
| **Religion** | INT | Varies by which god — see [`../world/pantheon.md`](../world/pantheon.md). Knowledge of the Concord is trusted; knowledge of Dawnweave figures is suspect. | Variable |
| **Animal Handling** | WIS | **Universally respected.** A character who can settle a horse settles the room. | Trusted |
| **Insight** | WIS | Respected. *"Reads people."* Villagers expect adventurers to have it; they're a little disappointed when one doesn't. | Trusted |
| **Medicine** | WIS | **The single most-valued skill in Fallowton.** Sister Elra is venerated. A character with Medicine can earn village trust faster than any other proficiency. | Highly trusted |
| **Perception** | WIS | Respected. *"Sharp eyes."* Hunters and good shepherds have it. | Trusted |
| **Survival** | WIS | Respected, especially in winter. | Trusted |
| **Deception** | CHA | **Suspect always.** Visible competence at lying is a flag villagers fly to remember. | Distrusted |
| **Intimidation** | CHA | Works on outsiders. Works **badly** on Fallowton villagers — Bran will not be intimidated by force. **[HOUSE]: Intimidation against a Fallowton elder by a non-villager has disadvantage** until the elder is shown a concrete reason to fear (a visible Wound from the ruin; a Vision spoken aloud; a corpse). |
| **Performance** | CHA | Bards are charmers; visible charm is suspect. *In private,* Bessa Thorn quietly loves a good song. | Conditional |
| **Persuasion** | CHA | Works fine if backed by CON or WIS. Suspect alone, especially in a stranger (per [`abilities.md`](abilities.md) §A Charisma). | Conditional |

> **[HOUSE] Intimidation gate.** A character cannot use Intimidation to bypass a social scene with a Fallowton elder unless they've shown a tangible cost (a Wound; a Vision; a corpse; a sealed warrant). Plain menace without proof produces *"who do you think you are?"* responses, not compliance. Outsiders without a story do not move Bran by force. This is a campaign-specific gate, not a global one — Intimidation works normally elsewhere.

---

## §B · Leveling — Milestone with Story Beats

We use **milestone leveling**, not XP. The DM declares level-ups at specific story beats. Why milestone:

- This campaign is built around narrative arcs (Module 1, Module 2, etc.), not encounter grinding.
- Weave Strain makes XP-per-kill metrics weird (a wizard who clears a fight via leveled spells costs themselves strain, but earns the "same" XP as a martial who didn't).
- Sessions vary wildly in combat density. XP would punish social and exploration sessions.

### When level-ups happen (Module 1 onward)

| Level | Trigger |
|---|---|
| **1 → 2** | After the cliffhanger of Module 1. (PCs returned to the surface; the ruin remembers them now.) |
| **2 → 3** | After completing one full tunnel in Module 2 (Edras / Grask / Breathless Warden). |
| **3 → 4** | After clearing the second tunnel OR after the first major political reveal (Office, Voss line). |
| **4 → 5** | After the first true confrontation with what's under the House of First Light. **Tier crossing — see §D.** |
| **5 → 6** | Major investigative milestone (a Converter outside Fallowton confirmed). |
| ... | DM judgment from here, roughly one level per major story beat. |

Module 1 → 4 levels of play. Modules 2-5 → another ~6. Modules beyond → tier 3-4. Pacing tunes to your group's session rhythm.

### Story Beats — the level-up moment

Whenever a character levels up, in addition to their RAW gains (HP, features, proficiency bonus increases, ASIs as appropriate), the **player picks one Story Beat** that fires *narratively*. This is not a stat bonus — it's a story moment the DM will weave into the next session.

| Beat | What the player declares | What the DM does next session |
|---|---|---|
| **1 · Recover** | "I recover something the world had taken from me." (A small memory; a piece of identity; a forgotten skill.) | DM narrates the recovery within the first scene of next session. Examples: a face you'd lost comes back; a song you knew as a child returns; you remember a phrase you'd forgotten in Old Common. |
| **2 · Study** | "I'm studying toward Lore (X)." (Names a specific Lore — must be one not yet known.) | The Study Beat counts as one step toward unlocking the Lore at the next tier crossing. Four Study Beats = automatic Lore at next tier; alternatively, an in-fiction event can grant it sooner. |
| **3 · Contact** | "I want to make a new contact in the world." (Names a type of contact — *"someone in Calder Vault who can post a letter"* / *"a smuggler in the Mereswood"* / *"a priest who'll receive me at the Concord chapter house."*) | DM names that NPC, gives them a one-line sketch, and ensures they appear in a future session. The PC has a friend or ally there. |
| **4 · Pay** | "I'm paying off a debt." (Literal or metaphorical — money, social obligation, an emotional reconciliation, a Wound that lingered.) | DM resolves the debt within the next 1-2 sessions, often with an emotional weight. A literal gold debt is cleared; a Wound is healed; a NPC the PC wronged forgives them. |
| **5 · Witness** | "My character witnesses something." | DM narrates a vision or revelation that shifts how the PC understands the world. Could be a Hollow Star vision, a Dawnweave history reveal, a glimpse of a future event, an overheard prayer that names something. |

> **[HOUSE] Story Beats are player-driven, DM-resolved.** The player declares the beat; the DM weaves the answer. Players should not pre-write the answer; the joy is the DM's interpretation. If a player wants something very specific, talk to the DM directly (not via Story Beat).

> **[HOUSE] One beat per level.** No double-dipping. Save unused beats for next level? **No.** If you don't declare one, you lose it. Forces players to engage with the system.

### Alternative: XP-based leveling (if you'd rather)

If your table prefers XP, use BR-2024's standard XP table ([`wiki/concepts/xp-and-advancement.md`](../../wiki/concepts/xp-and-advancement.md)). Add Story Beats on top — they're independent of the leveling method. XP players still pick one Beat per level-up.

> **[HOUSE] XP variant:** if you go XP-based, award XP not just for combat but for **exploration milestones, social victories, and Dawnweave-discovery beats**. Specifically:
> - Investigating a new ruined chamber: 50 XP × CR-equivalent
> - Convincing an elder NPC to act against their initial inclination: 100 XP × tier
> - Translating an Old Common chant or Architect Script passage: 100 XP × source rarity
> - Surviving a Hollow Star Long Look without spending revival magic: 200 XP × tier

This makes XP track the campaign's themes, not just combat.

---

## §C · Per-level mechanical reminders (RAW)

Use RAW for the mechanical content of each level. The Beat system adds narrative; it does not replace HP, features, or proficiency bumps.

### Levels 1–4 (Tier 1)

- **Level 1:** Max HD + CON modifier. Background grants Origin feat + [HOUSE] +1 to one of background's listed abilities (see [`abilities.md`](abilities.md) §B). One Lore at chargen.
- **Level 2:** Class feature (varies). Roll HD or take average.
- **Level 3:** Subclass chosen. (Wizard's First Specialization, etc.)
- **Level 4:** First ASI. Proficiency bonus stays +2.

### Levels 5–10 (Tier 2)

- **Level 5:** Tier crossing — see §D. Proficiency bonus to +3. Extra Attack (most martials). Third-level spells. **Second Lore unlocks if Study Beats accumulated.**
- **Level 6:** Class features.
- **Level 7:** Class features.
- **Level 8:** Second ASI.
- **Level 9:** Fifth-level spells (full casters).
- **Level 10:** Class features.

### Levels 11–16 (Tier 3)

- **Level 11:** Proficiency bonus to +4. Major class features. Sixth-level spells. **Tier crossing.** **Third Lore unlocks.**
- ... (RAW per class)

### Levels 17–20 (Tier 4)

- **Level 17:** Proficiency bonus to +6. Ninth-level spells. **Tier crossing.** **Fourth Lore unlocks.** Epic Boons available at level 19 ASI.
- **Level 20:** Capstone class feature.

> **[HOUSE] HP per level after L1.** Take the average + CON modifier, OR roll the HD with a re-roll allowed on any result below half the HD (so 1d12 must result in 7+ on the reroll if first roll was below 6). This keeps HP from being heartbreaking while preserving some variance.

---

## §D · Tier Crossings (the social consequence)

Each tier crossing carries weight in Fallowton specifically. Villagers can read your tier in your bearing, your wounds, your retinue. The crossing isn't just mechanical; it's social.

| Tier | Reached at | What villagers say |
|---|---|---|
| **1** | Levels 1–4 | *"They came to help with the sinkhole."* You are a curiosity. The village watches you but does not yet trust you. |
| **2** | Level 5 | *"They went down and came back. We didn't think they would."* Bran calls you by name. Henric offers you a seat at his table. Sister Elra remembers you in her prayers (whatever that means). |
| **3** | Level 11 | *"They've been to Calder Vault. They came back changed."* Bran offers you his chair when you visit. Children stop talking when you enter the room. The Office files a new entry under your name. |
| **4** | Level 17 | *"They were in Highmoor. The Crown knows them."* Children are kept away during your visits. Sister Elra speaks to you only in Old Common, when she speaks at all. The village may treat your arrival as a holiday or a curse, depending on what you bring back. |

### Tier crossing rituals

Each tier crossing **fires a specific event** in Fallowton when the party returns to the village after that level-up:

- **Tier 2 (after L5):** **The Quiet Welcome.** When you walk into the Bent Plow Inn, the conversation pauses for one second longer than it should. Then Bessa Thorn pours you a drink without asking what you want — and the drink is *not* the cheap one she normally serves outsiders.
- **Tier 3 (after L11):** **The Standing Up.** Bran Elderfield stands when you enter the Elder's Hall. He has not done this for anyone alive. The other elders take their cue from him.
- **Tier 4 (after L17):** **The Closing of the Doors.** Some houses close their shutters when you arrive in the village square. Others throw them open. There is no in-between. The village's old prophecy gets recited — *"the marked ones return to the field where it started."* Sister Elra walks to meet you herself, and what she says is in Old Common, and you understand it because by Tier 4 you should.

The DM narrates the appropriate ritual on first return to Fallowton after the crossing. **Do not narrate it twice for the same tier** — the village is not surprised the second time.

---

## §E · Downtime progression (preview)

Between adventures, characters can pursue **downtime activities** that produce mechanical or narrative effects. The full system lives in a future doc (TODO TASK-202: Downtime & Carousing); this section previews what kinds of things will be available.

### Anticipated downtime activities

- **Working the fields** (1 week / season): clear a Wound; gain favor with one randomly-rolled Fallowton villager.
- **Studying with Mordren** (1 week + payment): one step toward unlocking a new Lore (Dawnweave or Crown Law). Strains the relationship with the village.
- **Helping at the shrine** (1 week): gain a free Sister Elra blessing usable on demand for the next month. Sister Elra learns something about you you didn't intend to share.
- **Hunting in the Mereswood** (3-7 days): gain rations + a chance for a specific encounter (a stocked NPC; a Dawnweave-touched creature; nothing at all).
- **Courting a villager** (variable): you grow a relationship in the village. Mechanical effect TBD; narrative effect: an NPC you can rely on.
- **Posting a letter to Calder Vault** (1 day): the letter is read by an Office agent within a week. Useful or risky depending on what you sent.
- **Crafting / repairing** (RAW tool proficiencies): see [`wiki/equipment/`](../../wiki/equipment/).
- **Carousing** (one evening): see future doc; comes with consequences ranging from a friend made to a hangover to a debt.

Downtime is **time-gated** (one activity per week of downtime), **consequence-bearing** (every activity has a cost), and **tied to the Calendar** ([`../world/calendar.md`](../world/calendar.md) — you cannot court someone the week before Lampset Vigil; you cannot work the fields in Longnight).

The full table lands in TASK-202.

---

## Quick reference (rip out, tape to screen)

```
SKILLS (18 RAW)
  Trusted:        Medicine, Animal Handling, Insight, Nature, Survival, Perception
  Respected:      Athletics, History (village topics), Religion (Concord)
  Conditional:    Persuasion, Performance, Acrobatics, Religion (Dawnweave),
                  Stealth (woods OK / village suspect), History (old things)
  Suspect:        Arcana, Sleight of Hand, Deception
  Distrusted:     Intimidation vs Fallowton elders (disadv without proof)

LEVELING = MILESTONE (this campaign)
  Story beats per level-up — pick one:
    1. Recover (something the world took)
    2. Study (toward a new Lore)
    3. Contact (DM names an NPC)
    4. Pay (a debt — literal or emotional)
    5. Witness (a vision or revelation)
  Use it or lose it. No banking.

TIER CROSSINGS (social):
  T1 (1-4):   "They came to help with the sinkhole."
  T2 (L5):    "They came back." (The Quiet Welcome)
  T3 (L11):   "They went to the city." (The Standing Up)
  T4 (L17):   "The Crown knows them." (The Closing of the Doors)

[HOUSE] HP per level after L1: average OR re-roll any HD below half.
[HOUSE] Intimidation vs Fallowton elders requires concrete proof.
```

---

## Cross-references

- Wiki — skills: [`wiki/core/skills-overview.md`](../../wiki/core/skills-overview.md) · individual skill pages in [`wiki/core/`](../../wiki/core/)
- Wiki — leveling: [`wiki/concepts/xp-and-advancement.md`](../../wiki/concepts/xp-and-advancement.md)
- Wiki — multiclassing: [`wiki/concepts/multiclassing.md`](../../wiki/concepts/multiclassing.md)
- Sub-specialty Lores: [`abilities.md`](abilities.md) §C
- Survival (HP, Wounds, Visions): [`survival.md`](survival.md)
- Downtime (full system planned but not yet written)
- World — Calendar (downtime tie-ins): [`../world/calendar.md`](../world/calendar.md)
- World — Pantheon (Religion skill nuance): [`../world/pantheon.md`](../world/pantheon.md)
- World — Geography (Calder Vault, Mereswood, etc.): [`../world/geography.md`](../world/geography.md)
- DM Operating Manual — DC ladder and the fixed-rung rule: [`../00-dm-operating-manual.md`](../00-dm-operating-manual.md#3--when-to-roll)
