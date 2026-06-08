---
type: character-design
category: build-options
since: "homebrew"
tags: [feats, species, lineages, expanded-backgrounds]
updated: 2026-05-23
status: needs-review
---

# Build Options — Feats, Species Lineages, Backgrounds

The player-facing extras beyond ability scores and progression. Custom feats tied to Fallowton themes, species lineage modifications that fit this world, and a template for designing further backgrounds.

This closes the four-bucket Character Design module. With it, a player can fully build a Fallowton-flavored character without ever leaving the homebrew tier.

---

## §A · Custom Origin feats

Origin feats are taken at character creation, granted by background. RAW gives four ([`wiki/feats/`](../../wiki/feats/) Alert, Magic Initiate, Savage Attacker, Skilled). These five add Fallowton-specific options.

Each is **DM-approved at chargen** — they're not universally available; the DM decides which fit which characters.

### Initiated Reader

You studied under a tutor — a scholar of dead languages, a priest who could parse Old Common, a renegade wizard who taught you what was forbidden.

- **Prerequisite:** None at chargen; otherwise DM approval (an in-fiction tutor relationship).
- **Effect:**
  - You gain **Lore (Dawnweave)** if you don't have it. If you already have it, gain one free language from {Old Common, Office-Hand, Liturgical Calendar Script}.
  - You can read Dawnweave Architect Script **silently** without risk. (Speaking it aloud still triggers strain per [`../world/languages.md`](../world/languages.md).)
- **Repeatable:** No.

### Voss-Blooded `[PROPOSAL]`

You carry a trace of the Voss line — that quietly-rumored Fallowton bloodline that walked into the House of First Light sixty-to-a-hundred years ago and came back changed.

- **Prerequisite:** DM approval. Your character has a plausible connection to the Voss family (a great-grandparent; a found heirloom; a name that keeps appearing in dreams).
- **Effect:**
  - You can **recognize a Voss-line object on sight** (the W.V. dagger, certain rings, a particular pattern of carving). This is a free check, not a roll.
  - **Disadvantage** on the **first** Wisdom save against Hollow Star effects each session (the line carries the old wound).
  - **Advantage** on saves to recover from a **Hollowed Wound** (the line knows the work; some of you remembers how to come back).
  - You may take the **Voss-Touched** General Feat later without its normal DM gate.
- **Repeatable:** No.

> `[PROPOSAL]` flag: the Voss bloodline existence as a *playable* lineage commits to it being inheritable. Tune the rate of bloodline transmission with the DM (rare? one in a hundred? everyone in the village distantly?).

### Hedge-Cunning

You learned the unwritten survival manual: which mushroom is which, which sheep is sick, how to set a snare, how to mend a tool with what's in your pack.

- **Prerequisite:** None.
- **Effect:**
  - You can **identify** any plant or animal native to the Fallowton region on sight, including whether it's safe to eat or handle.
  - **+2 to Medicine checks** when treating **non-magical** injuries with mundane materials (clean cloth, water, splints, herbs).
  - You can craft basic medicine (1 dose of "village poultice" — equivalent to a Healer's Kit single use) once per long rest using foraged materials.
- **Repeatable:** No.

### Marked by the Bell

You once heard the village bell ring without a hand. Maybe you were a child; maybe you were standing in the wrong field at the wrong hour. Whatever happened, it changed how you walk near the threshold.

- **Prerequisite:** DM approval — a personal-history vignette confirming the experience.
- **Effect:**
  - **Advantage on the first death save** in any session.
  - You can sense (no roll) when an Awakening Clock effect is firing within 60 ft. You don't know the *content* of the effect; you just know one is happening.
  - **Disadvantage** on any Persuasion check where you must convince an NPC that you've never had supernatural experiences. You can't lie about this easily.
- **Repeatable:** No.

### Office-Witness

You were present when the Office of Sealed Practice arrested someone — a neighbor, a relative, a stranger. You watched the four-person squad work. You remember what they did, what they said, and what they left behind.

- **Prerequisite:** None at chargen; otherwise DM approval (a backstory event).
- **Effect:**
  - You can recognize **any of the Office's standard hand-signs, badge styles, and warrant types** on sight.
  - **Advantage on Insight** when reading whether an Office squad is operating with a real writ or improvising authority.
  - **Disadvantage on Persuasion** with the Office until you've earned it (they remember witnesses).
- **Repeatable:** No.

---

## §B · Custom General feats (level 4+)

General feats are taken instead of an Ability Score Improvement at levels 4, 8, 12, 16, 19. These four are campaign-specific. Players can also take any RAW General feat from [`wiki/feats/`](../../wiki/feats/).

### Purified Channel I

You have learned a gentler grip on the broken magical channel. Your first cast of the day passes through cleanly.

- **Prerequisite:** Spellcasting feature; **DM approval** (this is the first Purification step from [`../../docs/campaign/weave-strain-magic.md`](../../docs/campaign/weave-strain-magic.md), normally granted via story milestone).
- **Effect:**
  - Your **first leveled spell cast each long rest causes no Weave Strain.** Cantrips remain free as RAW.
  - Strain damage dice you would have taken from that cast: not rolled.
- **Repeatable:** No. Purified Channel II and III come via story, not feat-slot.

> **Design note:** this is mechanically the Purification I benefit from Weave Strain doc, codified as a feat for DMs who'd rather players unlock it via build than story. The DM should still gate it narratively (the character must have *learned* the gentler grip from someone — Sister Elra; a study with Mordren; a found ritual).

### Sealcrafter

You can carve a temporary protective seal that blocks magic for a short time.

- **Prerequisite:** **Lore (Dawnweave)**; proficiency with Calligrapher's Supplies or Mason's Tools.
- **Effect:**
  - **Action:** Carve a temporary seal in a 5-ft radius. Takes 10 minutes of work (1 dungeon turn). Materials cost: 1 sp of inks or chalk.
  - **Duration:** 1 hour, or until the seal is touched by spell effect.
  - **Effect:** The seal **absorbs 1d4 + 1 levels of incoming hostile magic** targeting the area. (A 2nd-level spell consumes 2 levels of the seal's reservoir; a 4th-level spell consumes 4.) Once depleted, the seal cracks visibly and is gone.
  - **Once per long rest.**
- **Risk:** A character attempting to *activate* an existing Dawnweave seal still risks Overreach per Weave Strain rules. This feat only allows *carving* a temporary protective one.
- **Repeatable:** No.

### Office-Trained

You once served the Office of Sealed Practice. Maybe as a warrant officer, maybe as a sensitive, maybe as an enforcer. You left — by quitting, by escaping, or by being expelled. The skills don't leave.

- **Prerequisite:** **Lore (Crown Law)**; DM approval (your backstory included Office service).
- **Effect:**
  - You gain **Lore (Sealed Practice)** as a new sub-specialty. Questions and advantage apply to Office procedure, warrant-protocol, the chain of command, the sealed-writ format.
  - **Advantage** on Insight when interacting with Office personnel.
  - **Disadvantage** on Persuasion with anti-crown rebels, smugglers, and unlicensed casters — they smell you.
- **Repeatable:** No.

### Voss-Touched

You have learned to speak one word of Architect Script aloud without triggering Overreach.

- **Prerequisite:** **Voss-Blooded** Origin feat OR DM approval (you've found and read a specific seal that taught you).
- **Effect:**
  - **Once per long rest**, you may speak aloud **one word** of Architect Script from a seal you have personally read.
  - The word's effect varies by the seal: most do something minor (a door unlocks, a light kindles, a vision flickers). The DM picks the effect, narrating the spectacle.
  - Speaking the word still costs you **1 Weave Strain** as a leveled spell would. The Voss line lets you do it; it doesn't pay the price for you.
- **Repeatable:** Yes (you can take it again to learn a second word).

### Field Defender (Fighting Style)

You fight like a Fallowton fieldhand defends a barn from wolves.

- **Prerequisite:** Fighting Style class feature.
- **Effect:**
  - When you wield any **agricultural tool** as a weapon (improvised), it counts as a **martial weapon** for you. (Pitchforks, sickles, hayhooks, shovels, threshing flails.)
  - **+1 damage** with improvised weapons made from farm tools.
  - You can use **Strength (Athletics)** to disarm a foe by **hooking** their weapon with a farm tool (e.g., a pitchfork tine through a sword guard). Contest vs the opponent's Strength or Dexterity (their choice).
- **Repeatable:** No.

---

## §C · Species Lineages (Fallowton hooks)

These are **lineage modifications** to RAW species — you pick *instead of* the standard sub-race / lineage options in `wiki/species/`. The chassis (size, speed, base traits) stays RAW; we swap **one specific lineage trait** for a Fallowton-flavored one.

All are `[PROPOSAL]` — they imply lore-canon that the campaign may or may not want. Take or leave each.

### Sinkhole-Touched Human `[PROPOSAL]`

Your family lived near a Converter site, or you were born in the year the sinkhole opened (or some equivalent). Something about your earliest years near the buried Dawnweave shaped you.

- **Available to:** Human species ([`wiki/species/human.md`](../../wiki/species/human.md)).
- **Replace:** The "Heroic Inspiration on long rest" trait.
- **With:** **Sinkhole-Touched.** Once per long rest, when you fail a check related to a Dawnweave seal, an Architect Script reading, or a Hollow Star effect, you may treat the failure as a **partial success** — the seal responds to you slightly more than it should. The DM narrates a hybrid outcome (some of what you wanted, some of what you'd have lost on failure).

### Dawnweave-Blooded Tiefling `[PROPOSAL]`

Your fiendish heritage carries a Dawnweave architect ancestor, not a standard fiend. Your blood remembers what theirs did.

- **Available to:** Tiefling species ([`wiki/species/tiefling.md`](../../wiki/species/tiefling.md)).
- **Replace:** One of the three RAW Tiefling Legacies (Abyssal / Chthonic / Infernal).
- **With:** **Dawnweave Legacy.** You know the **Comprehend Languages** spell as a cantrip (cast at 1st level, no strain). At level 3, you can cast **Detect Magic** as a 1st-level spell once per long rest, no strain. At level 5, you can cast **Speak with Dead** once per long rest, no strain. (Each is a *partial* echo of what the architects could do; the lineage carries fragments.)

### Architect-Descended (any species) `[PROPOSAL]`

Any species can take this as a **universal lineage trait** if the DM approves. You have a known or suspected architect ancestor.

- **Available to:** Any species at chargen.
- **Effect:**
  - You can attempt to **read Dawnweave Architect Script** without proficiency. Roll Intelligence (Arcana) at disadvantage unless you have Lore (Dawnweave).
  - You have **advantage** on the first such reading per long rest if you have Lore (Dawnweave).
  - **Cost:** Architect-Descended characters are **flagged** for the Office of Sealed Practice if they're noticed casting unlicensed magic. A first offense that would normally be a fine becomes a hearing.
- **Repeatable:** No.

### Mereswood Elf (Elf lineage) `[PROPOSAL]`

A fourth Elf lineage choice for your campaign. Elves of the western Mereswood forest, west of Fallowton.

- **Available to:** Elf species ([`wiki/species/elf.md`](../../wiki/species/elf.md)) instead of Drow / High Elf / Wood Elf.
- **Replace:** The standard Wood Elf "Fleet of Foot" speed bonus.
- **With:** **Mereswood Born.** +2 to Survival checks in temperate forests. You don't trigger fallen-leaf rustle when moving stealthily in temperate forest terrain (you know which step to take). You have advantage on Nature checks involving Mereswood-specific plants and creatures.

### Calder-Born Halfling (Halfling lineage) `[PROPOSAL]`

Halflings of Calder Vault, raised in the bureaucratic class — the secretaries, the scribes, the clerks of the diocese. Quick fingers, smarter on paper than most lords.

- **Available to:** Halfling species ([`wiki/species/halfling.md`](../../wiki/species/halfling.md)).
- **Replace:** The Lucky trait.
- **With:** **Calder-Born.** When you make a Charisma check involving a sealed document, a writ, an official letter, or formal court protocol, you have **advantage**, and you may treat any roll of 9 or lower as a 10. You also have proficiency in Office-Hand language (the crown bureaucratic script).

---

## §D · Background design template

We have 5 Fallowton backgrounds (Sinkhole Witness, Ruin Scholar, Failed Apprentice, Mechanist, Village Doctor). More can be designed — by you, by players, by guest DMs. Use this template.

### Template

```
# Background: [Name]

*Homebrew · Fallowton campaign · Formatted like D&D 2024 Basic Rules backgrounds*

[A 1-paragraph evocative opening establishing WHO this person is in or around Fallowton.
This is the heart of the background. Write it last, after the mechanics.]

---

## [Name]

[A 2-3 paragraph deeper character-portrait. Mention specifics: the village, the field,
the family, the thing that pushed them to adventure. Do NOT mention mechanics here.]

**Ability Scores:** [3 of the 6, weighted toward what the background does]

**Feat:** [One Origin feat — Alert, Magic Initiate, Savage Attacker, Skilled,
   OR a Fallowton-specific feat from §A above]

**Skill Proficiencies:** [2 skills]

**Tool Proficiency:** [1 tool that makes thematic sense]

**Equipment:** Choose **A** or **B:**
- **(A)** [Themed kit + 12-15 GP]
- **(B)** **50 GP**

---

## Optional personality prompts

- [3 evocative questions specific to this background — not generic]

## Weave Strain (if you gain magic later)

[1-3 bullets connecting this background's Weave Strain hook to the system.
Either: "Use [class] row" / "Standard rules" / a specific custom mechanic.]

See [Weave Strain Magic — {Background-Name}](../../../docs/campaign/weave-strain-magic.md#custom-fallowton-backgrounds).

---

Spellcasters should read [Weave Strain Magic](../../../docs/campaign/weave-strain-magic.md).
[Any class restrictions or recommendations.]
```

### Suggested future backgrounds

Backgrounds that fit Fallowton but aren't yet written. Each is a candidate for player or DM authorship:

- **Field Soldier** — Conscripted to fight in some crown campaign and returned home. Origin feat: Savage Attacker. Skills: Athletics, Intimidation.
- **Ferry Operator** — You worked the Slowmere river crossings, hearing every traveler's business. Origin feat: Skilled. Skills: Perception, Insight.
- **Postman** — You carried letters between Marrowford, Fallowton, and Calder Vault. You know who corresponds with whom. Origin feat: Alert. Skills: Athletics, Survival.
- **Sister Elra's Apprentice** — A young person who started studying with the village priest. Granted Hedge-Cunning OR Magic Initiate (Cleric). Skills: Religion, Medicine.
- **Quarry Worker** — You worked the Wealdmark chalk quarries. You've seen the stones up close. Granted Hedge-Cunning. Skills: Athletics, Nature.
- **Crown Conscript Deserter** — You served, you fled. The crown knows your name. Origin feat: Alert. Skills: Stealth, Intimidation.

When you (or a player) write one of these, file it in [`backgrounds/`](backgrounds/) following the template above.

---

## §E · Cross-references

- Wiki — RAW species: [`wiki/species/`](../../wiki/species/)
- Wiki — RAW feats: [`wiki/feats/`](../../wiki/feats/)
- Wiki — backgrounds: [`wiki/backgrounds/`](../../wiki/backgrounds/)
- Backgrounds (this module): [`backgrounds/`](backgrounds/)
- Sub-specialty Lores (§C of abilities): [`abilities.md`](abilities.md#c--sub-specialty-lores-the-creative-add-on)
- Weave Strain (Purification system that Purified Channel I implements): [`../../docs/campaign/weave-strain-magic.md`](../../docs/campaign/weave-strain-magic.md)
- World — Dawnweave / Architect Script: [`../world/languages.md`](../world/languages.md) · [`../world/dawnweave-legend.md`](../world/dawnweave-legend.md) (DRAFT)
- World — Office and Crown Law: [`../world/crown-and-office.md`](../world/crown-and-office.md)
- World — Voss-line bloodline canon: [`../world/magic-in-society.md`](../world/magic-in-society.md) (DRAFT)
- House rules — Heroic Inspiration economy (some Origin feats interact): [`../house-rules.md`](../house-rules.md)
- DM Operating Manual — fairness test (relevant for DM-gated feats): [`../00-dm-operating-manual.md`](../00-dm-operating-manual.md#7--ruling-on-the-fly)
