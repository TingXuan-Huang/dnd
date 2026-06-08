---
type: homebrew-rules
category: sanity-spirit
since: "homebrew"
tags: [corruption, hollow-star, trauma, soul, funeral, ghosts, mind-body]
updated: 2026-05-23
status: needs-review
---

# Sanity & Spirit — When the Body Cannot Contain What Happened

The mental and spiritual realism layer. Hollow Star corruption, PTSD/trauma, what happens to souls, funeral rites, ghosts, the mind-body bleed-through, and the burnout of healers.

Companion file: [`survival-realism.md`](survival-realism.md) — the physical side. They interlock: A2 (sleep deprivation) talks to H6 (insomnia → cognition); A6 (tolerance) talks to H6 (the body's adaptation under mental stress).

This file contains **lore proposals** marked `[PROPOSAL]` — specifically the Concord soul-passage cosmology in H3 and the funeral rite details in H4. Mechanics can stand without locking the lore; you can accept the mechanics and revise the lore wording when you do the lore-review pass.

---

## §H1 · Hollow Star Corruption Tracker

A **personal** sanity tracker that sits above the per-day Death Vision Long Look (from `character-design/survival.md` §C). Tracks cumulative Hollow Star exposure across a campaign.

### The scale

**0–6**, personal to each PC. Track on character sheet. Players know their current corruption. The DM tracks any silent ticks behind the screen.

```
HOLLOW STAR CORRUPTION
  0  ─  1  ─  2  ─  3  ─  4  ─  5  ─  6
  clean             touched   marked  hollowing  LOST
```

### What ticks corruption UP

| Event | Tick |
|---|---|
| Witnessing a death **caused directly by Hollow Star contact** | +1 |
| **Using Dawnweave magic from a seal** (per Sealcrafter feat, Voss-Touched, etc.) | +1 per use |
| Accepting a **Hollow Star vision** (nat 20 on a death save info-gift) | +1 |
| Reading certain **forbidden Dawnweave texts** at length (3+ pages of Architect Script) | +1 |
| Killing a sentient creature with **Dawnweave-tainted means** (a Hollowed weapon; a seal-channeled spell) | +1 |
| **Permanent vision** from revival (per `survival.md`) | automatic +2 on revival |
| Drinking from a contaminated water source (per `survival-realism.md` §A1, Slowmere within 1 mi of Converter) | +1 (per failed Con save) |
| **Hollowed Wound** carried 7+ days untreated | +1 per week |

### What ticks corruption DOWN

| Action | Reduction | Limit |
|---|---|---|
| **Sister Elra's blessing** | −1 | 1×/week |
| **A week at a cleansed spring** | −2 | requires travel; rare |
| **The Long Hush** (leap-year-only Concord holiday at Calder Vault chapel) | −3 | once per leap year per character |
| **A personal-sacrifice quest** (DM-narrated) | −1 to −3 | gated; story-locked |
| Resolving a personal Trauma in fiction (see H2) | −1 | per resolved Trauma |

### Threshold effects

| Corruption | Stage | What it does |
|---|---|---|
| **0** | Clean | Nothing. The body and the soul are aligned. |
| **1–2** | **Touched** | Bad dreams; occasional insomnia (intersects A2). Once per session, an ambient phenomenon notices you (the mushroom ring tilts toward you; a crow perches; a candle gutters when you speak). No mechanical penalty yet. |
| **3–4** | **Marked** | NPCs sense it without being told (*"they see something behind your eyes"*). **Forbidden Choice unlocked**: once per long rest, you may consult the Hollow Star for **one useful piece of campaign information** — but you take **+1 corruption** as the cost. The carrot. |
| **5** | **Hollowing** | **Disadvantage on saves vs charm and fear** from Dawnweave sources. Villagers shy away unprompted. Children stop talking when you enter the room. Your **divine magic has a 1-in-6 chance to falter** when cast (the channel is contested). The **Hollowed Wound** healing time doubles for you. |
| **6** | **Lost** | The PC becomes an NPC. Player rolls a new character. The old PC may return later as antagonist or as an NPC ally with their own broken agency. The Hollow Star has not killed them; it has *kept* them. |

### [HOUSE] Mechanical interactions

- **Weave Strain at high corruption**: at corruption 3+, your **first leveled spell each long rest costs +1 strain on top of the normal cost.** The channel is contaminated; you pay extra to push through.
- **Office detection**: an Office Sensitive's bone-and-silver pendulum **detects corruption 3+** automatically within 60 ft. They will pursue it as a "public safety concern."
- **Children's reactions**: kids in Fallowton specifically — they notice corruption 2+ before adults teach them what to do. Their reaction is informative for the table: a child going silent when a PC walks in is the cleanest tell.

### Tracking

```
CHARACTER:  __________________________
CORRUPTION: 0  1  2  3  4  5  6     [Stage: __________]

Last tick up (date / event): _______________
Last tick down (date / event): _______________

ACTIVE FORBIDDEN CHOICE? __________ (refreshes on long rest)
```

---

## §H2 · PTSD / Trauma

The psychological aftermath of surviving things the mind wasn't built for. Lighter and more roleplay-driven than Corruption (which is cosmic); Trauma is **personal**.

### Trigger events

A character takes a Trauma when any of these happen:

| Trigger | Source |
|---|---|
| **Surviving a Hollow Star Long Look** | `character-design/survival.md` §C |
| **Coming back from death** (Revivify, Raise Dead, etc.) | automatic |
| **Witnessing an ally's permanent death** (no revival possible — body lost, soul gone too long) | session moment |
| **Specific Wound types lingering 7+ days** | Voice Loss, Eye Injury, Hollowed |
| **Killing a child or someone clearly innocent** | DM-narrated moment |
| **Being held captive / tortured** for 1+ in-game days | session moment |

### Effects (player picks one from each new Trauma)

When a Trauma is taken, the player picks **one effect**. Effect lasts until the trigger is **confronted in fiction** (returning to the place; meeting the person; finishing the unfinished task).

| Effect | Mechanic |
|---|---|
| **Insomnia** | Each session starts at −1 d20 (the previous night was bad); doesn't catch up on safe rests until Trauma resolves; stacks with A2 sleep deprivation |
| **Trigger-NPC** | One specific NPC. When you see them, **disadvantage on social rolls** until the scene ends. |
| **Trigger-Location** | One specific place. Entering it requires **Wis save DC 12 or be Shaken** (disadvantage on the first roll there) for the duration of the visit. |
| **Trigger-Item** | One specific item type (the weapon that wounded you, the brand of armor, a specific instrument). Seeing or handling it triggers a 1-round freeze. |
| **Trust-Wound** | You cannot Help an ally for a session per week; your character is too closed off. |
| **Faith-Wound** (clerics, paladins only) | Your spell DCs drop by 1 for the duration. The connection has been damaged. |

### Stacking Traumas

A character may carry **multiple active Traumas at once**. Each new Trauma adds to the pile; new doesn't overwrite old. **Limit:** 3 active Traumas at a time. After 3, the 4th triggers a Corruption tick instead (see H1) — the soul can't hold any more without bleeding.

### Treatment

| Method | Effect |
|---|---|
| **Sister Elra's presence + 1 week of conversation** | Resolves 1 Trauma; she charges nothing |
| **A close ally's care over 3+ sessions** | Resolves 1 Trauma; player describes how |
| **Confronting the trigger in fiction** | Resolves the specific Trauma instantly |
| **Greater Restoration** | Removes 1 active Trauma; not all of them |
| **A personal-sacrifice quest** | Resolves up to 3 Traumas; DM-narrated; usually irrevocable cost (a memory; a relationship; a piece of identity) |

### Edge cases

- **Trauma in casters**: a caster whose Trauma is Trigger-NPC and that NPC starts casting a spell at them — their next leveled spell costs **double Weave Strain** (the body fights the channel). This is the H6 mind-body bleed kicking in.
- **NPCs developing trauma in response to PC actions**: the village child who saw you kill the bandit develops their own Trigger-Item trauma (your weapon). This affects future scenes; the child reacts wrong around you. DM tracks NPC trauma like PC trauma but invisibly.
- **Trauma chains**: a Trauma left untreated for 6+ sessions may *generate a second trauma* on its own (the wound has festered into a wider wound). DM-discretion.

---

## §H3 · Soul Mechanics `[PROPOSAL]`

The cosmology of the soul in this world. Where souls go, what Raise Dead really does, the Hollow Star's interest. **Lore proposal** — accept or revise the cosmology while keeping the mechanics.

### `[PROPOSAL]` The 7-day crossing

When a creature dies, their soul **begins the crossing** toward its Concord patron (per [`world/pantheon.md`](world/pantheon.md)). The journey takes **7 in-game days**.

- **Day 0–7**: soul is *still close*. Raise Dead works easily; the spell pulls the soul back.
- **Day 8–30**: soul has *begun crossing*. Raise Dead requires a **Persuasion contest against the patron's resistance** (DM rolls 1d20 + 10 + an additional +1 per day past 7). Spell may fail.
- **Day 30+**: soul has *crossed*. Only the most powerful magic (Resurrection, Wish, or specific story milestones) can return them — and the soul may refuse.

### Raise Dead in detail (using this homebrew)

When the spell is cast:

1. **Caster makes a Persuasion check** (Cha + spell ability mod) against the patron's resistance.
2. **The soul makes its own Wisdom save** to refuse: DC 10. The dying character (or DM playing them) decides whether to refuse.
   - **A character whose campaign goals are unfinished** has advantage on returning (they *want* back).
   - **A character who died "good"** (saving allies, fulfilled, at peace) has advantage on the save to refuse return.
3. **The Hollow Star may interfere** if the corpse lingered within 100 ft of an active Converter site or carried a Permanent Vision: roll d20; on a 1, the Hollow Star takes the soul instead. The spell appears to succeed but the body wakes wrong (this becomes a Marked-tier ghost on H5).

### The Hollow Star's interest in souls

`[PROPOSAL]`: The Hollow Star **tastes every soul that passes near it**. Souls near Converter sites at death are noted, sampled, sometimes followed. Most pass unharmed; the Hollow Star is patient.

- Souls **revived after a Permanent Vision** (per `survival.md`) are **inherently flagged**. The Hollow Star may revisit them.
- The Hollow Star **does not eat souls.** It *samples* them — keeping a faint echo, the way you might keep an interesting word someone said.
- A soul that has been sampled may **revisit the Hollow Star** in dreams. This is what generates the "vision dreams" in A2.

### Soul-binding artifacts (rare; Dawnweave-era)

Some Dawnweave-era artifacts can bind a soul outside its body — to a weapon, a place, an heirloom. These are vanishingly rare; the campaign should never have more than 1-2 in play at a time.

- Bound souls **cannot cross**; they are stuck.
- Bound souls **may communicate** with the holder (the dagger whispers; the weapon hums when its old wielder's name is spoken).
- Bound souls **may be released** by destroying the binding artifact OR via specific Concord ritual (rare and dangerous).

The **W.V. dagger** (per `module-1-checks.md` and `character-design/build-options.md` Voss-Blooded) is `[PROPOSAL]` candidate for a bound-soul artifact — Wendel Voss's soul lingers in it, fragment.

### Sister Elra's view on resurrection

`[PROPOSAL]`: Sister Elra views Raise Dead as **necessary but always costly**. She will perform it for villagers (her own people) without judgment but will require an honest accounting of how the death happened. For outsiders, she requires a Persuasion check DC 14 to convince her *this revival serves the world, not just the survivor*.

---

## §H4 · Funeral Rites `[PROPOSAL]`

How the dead are buried in this world. **Lore proposal** — accept the rites or revise the words.

### `[PROPOSAL]` Fallowton folk burial

The village dead are buried in the chapel cemetery. The rite:

- **Body placed in the third row from the chapel wall** (newer dead are closer to the chapel; older dead farther; the row pattern goes backward across generations)
- **Tools placed at the head**, not at the feet (so the dead can pick them up easily in the next life)
- **Salt sprinkled on the chest** (Fallowton-specific; the salt is from the seal at the south hedge, a Dawnweave-remnant)
- **A name spoken three times** by a family member (so the dead remember who they were)
- **The chapel bell rung once** (a single ring; not the village-bell)
- **The grave left open until dawn** the next day (to let the soul out clean)

### `[PROPOSAL]` Concord rites (Sister Elra leads)

Beyond folk burial, Concord priests add:

- **Specific words** spoken in Old Common over the body — Sister Elra's chant
- **Candles at the four corners** of the grave for one night
- **The holy symbol placed on the breastbone** (the patron's symbol — for most Fallowton villagers, Vassa's lamp)
- **Sister Elra's blessing on the soul** (passes safely to its Concord destination)

This adds protection against **Hollow Star sampling** — Concord rites count as 1 in-game day of distance per actual day. A properly-blessed corpse is *gone* faster.

### `[PROPOSAL]` Crown-mandated rites for soldiers / nobles

For Office personnel, nobility, and licensed practitioners:

- **Ceremonial sword across the body** (for those who served)
- **Sealed warrant signed off by a magistrate** (so the death is recorded properly with the crown)
- **A salt-paper letter** burned at the grave (so the crown's records release them)

Without these, the crown may dispute the death (rare; usually fine).

### What happens if burial is NOT done properly

| Improper element | Risk |
|---|---|
| No body to bury (lost in ruin) | Empty-grave ceremony; soul *might* still cross safely (Sister Elra weighs in) |
| Refused burial (suspected criminal, suicide, magic-touched without rites) | Body burned outside village; **risk of haunting** at the burn site |
| Burial too close to a Converter site (<5 miles) | The Hollow Star samples the soul; risk of becoming a Marked-tier ghost (H5) |
| Folk burial without Concord rites | Soul takes 3-7 days longer to cross; raises risk of Hollow Star interference |
| Wrong tool placed at head (or no tool) | Common minor superstition; villagers will be uneasy but no mechanical effect |

### Edge cases

- **Suicide in Fallowton**: traditionally refused folk burial; family must take the body to Marrowford for the diocese to handle. Painful, social cost. Sister Elra has refused this once and grieved it for years.
- **Magic-touched deaths**: a character whose corruption was 3+ at death is buried with **extra salt and an iron nail through the wrist** (folk practice to prevent the soul from being pulled back by the Hollow Star)
- **Bodies that don't decompose**: a Hollowed corpse may *not* decay normally. Villagers know what this means. Fire is the answer.

---

## §H5 · Ghosts & Lingering Dead

Some dead don't fully leave. What ghost-ness means in this world.

### The four categories of lingering dead

| Category | Who | What they can do | How to put to rest |
|---|---|---|---|
| **The Unmade** | Dawnweave Converter victims — souls *caught* mid-conversion when the Sealing happened; incomplete | Whispered presence; ambient effects (the Awakening Clock 3+ whispers); rare manifestations as faceless figures | A specific Sealing-rite ritual (requires Lore (Dawnweave) + Concord priest); also: the original Converter being destroyed |
| **The Wronged** | People murdered, betrayed, refused burial; their souls did not cross peacefully | Can manifest visibly under specific conditions (anniversaries, full moon, near where they died); can speak; can harm if extremely strong | The original wrong is undone (perpetrator brought to justice, debt paid, name cleared) OR proper burial + Sister Elra's blessing |
| **The Unfulfilled** | Died with one task unfinished; usually a personal task (raising a child; finishing a book; reconciling with someone) | Faint manifestations; usually appear as the person they were; ask for the task to be finished | Finish the unfinished task in their name |
| **The Marked** | Revived characters who carried a Permanent Vision and then died again; their final Vision lingers as a presence | The most dangerous; can possess weakly-minded creatures within 60 ft; can guide other lingering dead | Greater Restoration on the body + Sister Elra's complete blessing + closure with the original death scene |

### `[PROPOSAL]` Specific named lingerings in this campaign

- **Wendel Voss** (W.V., per Module 1) — **Marked-tier**. His soul lingers in the W.V. dagger (per H3 soul-binding). May appear if the dagger is wielded by someone of Voss blood. The dagger whispers his name in old Voss-line dialect.
- **The Unmade** under Fallowton — hundreds; their whispered presence IS the Awakening Clock. Each clock tick is a different soul brushing the surface.
- **A small unnamed Unfulfilled** lingering near the Bent Plow Inn — a serving girl who died in childbirth 60 years ago; appears as a faint shape near the hearth on cold nights. Sister Elra knows; she lights a candle for her every Lampset.

### What ghosts can DO mechanically

| Ghost capability | Effect |
|---|---|
| **Manifest visibly** | Players see a translucent figure; Wis save DC 12 or be momentarily Shaken |
| **Speak** | Audible to one or more characters (DM chooses); whispered prayer, name, command |
| **Move objects** | Light objects (candles, dust, a coin); requires the ghost to be at its strongest |
| **Harm** | Only Wronged-tier and Marked-tier can do real damage. Wronged: cold-touch attack (1d6 cold per round). Marked: possession attempt (Wis save DC 14 or be controlled for 1 round) |
| **Guide other lingering** | Marked-tier only; can summon another lingering soul within 1 mile |

### Edge cases

- **PCs who become ghosts**: a PC who dies and is not revived may become a lingering dead, playable as an NPC echo. Player consents to this; DM facilitates.
- **The Office hunting lingering dead**: the Office considers lingering dead a "public safety concern." Their procedure: identify, contain via a binding ritual, dispatch via Concord priest. Some lingerings escape; some are *kept* by sensitives for their information value (controversial).
- **Sister Elra settling**: she can perform a Settling Rite to put a lingering soul to rest. Takes 1 in-game week at the location of the death; she does this 1× per year. The rest of the year she carries the names she has not settled.

---

## §H6 · Mind → Body Bleed (the bleed-through)

The mind doesn't stay in the head. Mental states manifest physically. Six bleed mechanics.

### H6.1 · Corruption → Physical Stats

- **Corruption 3+**: lose **1 from a randomly rolled physical stat** (DM rolls 1d3 — STR / DEX / CON). The cost is real and tracked.
- **Corruption 5+**: lose **another 1** from a physical stat. The DM may roll the same stat again or a new one.
- **Corruption 6 (Lost)**: lose **1 maximum HP per level**. The soul has gone first; the body is going next.

Restoration: corruption ticking back down restores the lost stats in reverse order (last-lost first).

### H6.2 · Trauma → Spellcasting

- Each **active Trauma** raises your **Concentration save DC by +2** for any concentration spell duration
- A PC with **2 active Traumas**: concentration is meaningfully harder; consider this when picking spells
- A PC with **3+ active Traumas**: their **first leveled spell each day costs double Weave Strain.** The channel is fighting the body
- A **Faith-Wound Trauma** (clerics, paladins) reduces all your spell DCs by 1 until resolved (see H2)

### H6.3 · Stress → Physical Performance

"Chronic stress" = **3+ consecutive in-game days** of any combination of:

- Sleeping in armor (per `physicality.md` §C)
- Forced march at Standard+ Load (per `physicality.md` §B)
- Hostage-style situation (you cannot leave; you are watched)
- Unresolved debt anxiety (owed someone significant money or favor)
- Active Trauma (per H2)

After 3 consecutive days of chronic stress:

- **−1 to STR checks and saves** until resolved
- Resolution: a **full day at peace** (no danger, no obligations, no clocks ticking) + an **Insight check from a trusted friend** (Wis DC 10) to verify you're processing it. Failure on the Insight = stress continues.

### H6.4 · Joy → Accelerated Healing

A character who finds **genuine joy** in a day (DM and player agree):

- A holiday observance with friends (Barleynight, Lampset Vigil, etc.)
- A romance milestone (a confession; a kiss; a marriage day)
- A roleplayed reunion with someone you love
- An artistic victory (completed song, finished writing, won contest)

Gains:

- **+1 HP per long rest for the next 3 days**
- **Reduces one ongoing Wound's recovery time by half**

This is a real medicine in this world. Joy heals. The campaign should leave room for it.

### H6.5 · Despair → Exhaustion

**Genuine despair** counts as **1 level of exhaustion** until the source is addressed in fiction. Triggers:

- Losing an irreplaceable person
- Being told a truth that breaks your worldview (a major NPC betrayed you; the Dawnweave was real and yes, the Office knows; your patron god is silent)
- Witnessing an act that crosses your moral line

Suppression: spells like **Calm Emotions** suppress despair for the duration but don't resolve it. The exhaustion *returns* the moment the spell ends.

Resolution: confronting the source of despair in fiction. Player describes how. DM verifies it lands.

### H6.6 · Insomnia → Cognition

Bridges to `survival-realism.md` §A2.

- 1 night insomnia: **−1 to INT and WIS checks** for the day (separate from sleep-deprivation general penalty)
- 2+ nights: enters general sleep deprivation territory (see A2)
- **Insomnia from active Trauma** (per H2): each session starts with this penalty automatically

The mind is the body. The body is the mind. Treat them as one.

---

## §H7 · Emotional Labor / Healer Burnout

(Lighter version exists in `survival-realism.md` §A7.6; this is the full mechanism.)

### Who this applies to

Characters whose primary role at the table is **healer / emotional support** for the party:

- Cleric (any subclass focused on healing)
- Bard (Lore college, healing-focused build)
- Druid (Life-tier healing)
- Paladin (Lay on Hands + Healing Word build)
- Sister Elra if she's an NPC follower or PC

A character can also opt into this if they're roleplaying as the party's caretaker even without healing class features.

### The burden track

A character whose primary role is healer / emotional support accumulates **burden** as follows:

- **+1 burden** per session where you cast **3+ healing spells**
- **+1 burden** per session where you emotionally supported an ally through a scene (the player narrates it; DM verifies)
- **+1 burden** per session where you absorbed a Trauma trigger for an ally (you stood between them and the source)

Burden caps at **6**.

### Threshold effects

| Burden | Effect |
|---|---|
| **0–2** | None. You're sustainable. |
| **3** | **−1 to Concentration saves** until you take a session off (see Recovery below) |
| **4** | Your first healing spell each day **heals 1d4 less** |
| **5** | Your second healing spell each day **does not work at all** for 24 hours (the channel refuses) |
| **6** | **Faith-Wound** Trauma triggered (per H2); your spell DCs drop by 1 until you recover |

### Recovery — taking a session off

Burden reduces by **1 per session** when the player **does NOT cast healing spells AND does NOT take the role of emotional caretaker**. Selfish play. Vacation. Solo work.

This is the campaign's permission to **let the cleric have a session about themselves**.

### Sister Elra's own burden

Sister Elra carries a burden of **5** at campaign start (years of village healing). She's at the edge. The campaign should leave room for her to recover or to break.

If a PC notices and helps her — relieves her of one healing duty, sits with her for an evening, offers to handle a difficult villager — her burden reduces by 1. This is a real social mechanic.

---

## Quick reference (rip out, tape to screen)

```
HOLLOW STAR CORRUPTION (0-6)
  Ticks up:  Hollow Star contact, Dawnweave seal use, Permanent Vision (+2),
             Hollowed Wound 7d untreated, contaminated water (failed save)
  Ticks down: Sister Elra (-1/wk), cleansed spring (-2), Long Hush (-3/leap-yr),
              personal-sacrifice quest, resolving Trauma
  Thresholds: 3+ = NPCs notice; Forbidden Choice unlocked (+1 corruption cost)
              5 = Hollowing — disadvantage charm/fear, divine magic falters
              6 = LOST — PC becomes NPC

TRAUMA  (max 3 active before next triggers Corruption)
  Triggers: Long Look, Revival, witnessed permanent death, lingering Wound,
             killing innocent, captivity
  Pick effect: Insomnia · Trigger-NPC · Trigger-Location · Trigger-Item ·
                Trust-Wound · Faith-Wound (cleric/paladin)
  Resolves: confronting trigger in fiction, Sister Elra week, ally over 3 sessions,
            Greater Restoration, personal-sacrifice quest

SOUL CROSSING (7 days)
  0-7 d:    Raise Dead easy
  8-30 d:   Persuasion contest (DM rolls +1/day past 7)
  30+ d:    Resurrection / Wish / story
  d20 on 1: Hollow Star takes (if near Converter)

FUNERAL (Fallowton folk):
  3rd row from chapel · tools at head · salt on chest · name x3 · bell once

GHOSTS (4 tiers): Unmade · Wronged · Unfulfilled · Marked
  Resolve: sealing ritual / undo wrong / finish task / Greater Rest+blessing

MIND-BODY BLEED
  Corruption 3+: -1 random physical stat
  Trauma each:  Concentration DC +2
  3+ Traumas:    1st leveled spell costs 2× strain
  Chronic stress (3 days): -1 STR until resolved
  Joy:           +1 HP/long rest x3 days + 1 Wound healing half-time
  Despair:       +1 exhaustion until addressed
  Insomnia 1 night:  -1 INT/WIS d20

HEALER BURDEN (0-6)
  3: -1 Concentration · 4: 1st heal -1d4 · 5: 2nd heal/day fails ·
  6: Faith-Wound Trauma
  Reduce: -1/session WITHOUT healing or emotional caretaking
```

---

## Cross-references

- Companion file (physical realism): [`survival-realism.md`](survival-realism.md)
- Survival.md (HP, Wounds, Death Visions — Long Look ties here): [`character-design/survival.md`](character-design/survival.md)
- Weave Strain (the magical cost-system corruption parallels): [`../docs/campaign/weave-strain-magic.md`](../docs/campaign/weave-strain-magic.md)
- World — Pantheon (Concord, the gods souls cross to): [`world/pantheon.md`](world/pantheon.md)
- World — Calendar (Long Hush, Lampset Vigil holiday timing): [`world/calendar.md`](world/calendar.md)
- World — Dawnweave Legend (DRAFT — the Hollow Star mythos): [`world/dawnweave-legend.md`](world/dawnweave-legend.md)
- World — Magic in Society (DRAFT — Voss line and bloodlines): [`world/magic-in-society.md`](world/magic-in-society.md)
- Character Design — Voss-Blooded feat (interacts with Marked ghosts): [`character-design/build-options.md`](character-design/build-options.md)
- DM Manual — Cardinal Rule 2 (fudging only on TPK-from-bad-luck): [`00-dm-operating-manual.md`](00-dm-operating-manual.md)
- Module 1 — Awakening Clock (the Unmade whispering): [`../docs/dm-handbook/module-1-dm-flow.md`](../docs/dm-handbook/module-1-dm-flow.md)
