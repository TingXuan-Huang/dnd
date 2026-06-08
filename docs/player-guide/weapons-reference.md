# Weapons Reference — Full 2024 List

Complete weapons catalog for the Fallowton campaign. Combines the BR-2024 free-rules sample (already in [`equipment-reference.md`](equipment-reference.md)) with the full 2024 PHB weapons list, plus an explanation of every stat column, every weapon property, and every weapon mastery.

> **What goes where.** BR-2024 free rules ship with **11 weapons** (a sample). The full 2024 PHB ships with **~35 weapons**. Both use the same property and mastery systems. Weapons in the BR-2024 sample are marked with **★** in the tables below; weapons that require PHB 2024 are unmarked but still legal at this table.

---

## §A · How to read a weapon stat row

Every weapon has these columns:

| Column | What it means |
|---|---|
| **Name** | The weapon's standard name. Some weapons have regional or class-specific names (a "saber" is a scimitar). |
| **Cost** | Buy price in coin. **CP** = copper piece (1/100 GP), **SP** = silver (1/10 GP), **GP** = gold, **PP** = platinum (10 GP). |
| **Damage** | The damage roll *on a hit*. Format: `XdY` + **damage type**. Example: `1d6 slashing` means roll one six-sided die for damage and the damage type is slashing. You also add your **ability modifier** (STR for melee, DEX for ranged or Finesse weapons) — that's separate from the listed die. |
| **Weight** | How much it weighs (pounds). Matters for encumbrance and carrying capacity. Most adventurers carry ≤ STR × 15 lb total without trouble. (In this campaign we use the [HOUSE] light-encumbrance rule — DM calls it out only when it matters.) |
| **Properties** | Special characteristics of the weapon (Finesse, Light, Heavy, Reach, etc.). See §C below. |
| **Mastery** | A signature trick the weapon enables IF you have the **Weapon Mastery** feature (most martial classes). 2024 added these. See §D. |

### How the math works

When you attack with a weapon:

1. Roll a d20. Add your **proficiency bonus** (if you're proficient with that weapon class — Simple or Martial). Add your **attack ability modifier** (STR for most melee; DEX for ranged or Finesse).
2. Compare the total to the target's **Armor Class (AC)**. If you meet or beat it, you hit.
3. On a hit, roll the **damage dice** listed for the weapon. Add the **same ability modifier** you used to attack.
4. Apply the **damage type** (the target may have resistance or vulnerability).
5. Apply the **mastery effect** if you have one and the weapon supports it.

Critical hit (natural 20 on attack roll): **roll all damage dice twice**, then add modifier once. (Some house rules change this — see [`../../homebrew/house-rules.md`](../../homebrew/house-rules.md) §"Critical hits": this campaign uses **max + roll** instead of double-roll.)

---

## §B · Damage types

Weapons deal **physical damage** of three types. Some monsters and some armor interact differently with each.

| Type | Notes |
|---|---|
| **Bludgeoning** | Crushing impact. Mauls, clubs, slings. Some constructs resist piercing/slashing but not this. |
| **Piercing** | Stabbing or puncturing. Daggers, rapiers, arrows, spears. |
| **Slashing** | Cutting. Swords, axes, scimitars. |

Some monsters have **resistance** (half damage) or **immunity** (zero damage) to a specific physical type. A skeleton might resist piercing (arrows pass through bone joints); a slime might be immune to slashing entirely. The DM tells you when this matters.

A few weapons in the campaign may eventually deal **non-physical** damage (Dawnweave-touched items, see [`../campaign/weave-strain-magic.md`](../campaign/weave-strain-magic.md)). When a weapon does, its damage type changes to whatever the magic specifies (radiant, necrotic, force, fire, etc.).

---

## §C · Weapon Properties (all 10 explained)

| Property | What it does |
|---|---|
| **Ammunition** | The weapon needs ammunition (arrows, bolts, bullets). You must have the right ammo to use the weapon. Pull out one piece per attack as part of the attack itself. You can recover half of expended non-damaged ammunition after combat (rounded down). |
| **Finesse** | You choose whether to use **STR or DEX** for the attack and damage rolls. (Daggers, rapiers, shortswords, scimitars, whips, darts.) High-DEX rogues love Finesse weapons. |
| **Heavy** | Small creatures have **disadvantage** on attack rolls with this weapon. (Greataxe, greatsword, halberd, etc.) Halflings and gnomes look elsewhere. |
| **Light** | A Light weapon can be paired with another Light weapon to enable **two-weapon fighting** as a Bonus Action. (Daggers, shortswords, handaxes, scimitars, sickles, light hammers.) |
| **Loading** | After firing once with this weapon, you can't fire again with this weapon on the same turn — even if you have multiple attacks. (Crossbows, blowgun, sling.) |
| **Range** | Indicates the weapon is ranged. The two numbers in parentheses are **normal range / long range** in feet. Beyond normal range, you attack with **disadvantage**. You cannot attack at all beyond long range. Example: a longbow shows `Ammunition (150/600)` — normal up to 150 ft, disadvantage 150–600 ft, impossible past 600 ft. |
| **Reach** | The weapon adds **5 ft to your melee reach** — you threaten enemies 10 ft away instead of 5 ft. (Glaive, halberd, lance, pike, whip.) Excellent for opportunity attacks. |
| **Thrown** | You can throw this melee weapon as a **ranged attack** using the same ability modifier you'd use for melee. The Thrown range (e.g., 20/60) works like ranged Range above. (Daggers, handaxes, javelins, spears, darts, light hammers, tridents.) |
| **Two-Handed** | The weapon requires **two hands** to use. You cannot wield a shield or a focus in the off-hand while holding it. (Greatswords, polearms, most bows.) |
| **Versatile** | One-handed by default, but you can wield with two hands for a **bigger damage die** shown in parentheses. Example: `Longsword 1d8, Versatile (1d10)` — 1d8 one-handed, 1d10 with both hands. |

See [`../../wiki/core/weapon-properties.md`](../../wiki/core/weapon-properties.md) for the canonical wiki entry and individual property pages.

---

## §D · Weapon Masteries (all 8 — new in 2024)

Weapon Mastery is a class feature most **martial classes** get (Barbarian, Fighter, Paladin, Ranger, Rogue) at level 1; some others at later levels. You start with **mastery slots** — usually 2 or 3 weapons at level 1, growing to ~5 at high levels. You pick which weapons you have mastery over from the list of weapons you're proficient with.

When you make an **attack with the weapon-property-action** (i.e., a normal attack action with that weapon), the mastery triggers in addition to the damage. **Each weapon has exactly one mastery.**

| Mastery | What triggers + effect |
|---|---|
| **Cleave** | On a hit with a melee attack, you can make a free attack against a **second creature within 5 ft** of the first target. Once per turn. (Greataxe, halberd.) |
| **Graze** | If your attack **misses**, you still deal damage equal to your **ability modifier** (the modifier you'd have added on a hit). (Glaive, greatsword.) |
| **Nick** | When you make the extra attack from **two-weapon fighting** (your Bonus Action attack), you can make it as part of your Attack action instead, freeing your Bonus Action for something else. (Dagger, light hammer, sickle, scimitar.) |
| **Push** | On a hit, you can push the target **up to 10 ft directly away** from you. The target must be Large size or smaller. (Greatclub, pike, warhammer, heavy crossbow.) |
| **Sap** | On a hit, the target has **disadvantage on its next attack roll** before the start of your next turn. (Mace, flail, longsword, morningstar, war pick, spear.) |
| **Slow** | On a hit, the target's **speed is reduced by 10 ft** until the start of your next turn. (Club, javelin, light crossbow, longbow, sling, whip.) |
| **Topple** | On a hit, the target must make a Constitution saving throw (DC = 8 + your proficiency bonus + your ability modifier) or be knocked **Prone**. (Quarterstaff, battleaxe, lance, maul, trident.) |
| **Vex** | On a hit, you have **advantage on your next attack roll against that target** before the end of your next turn. (Dagger, handaxe, shortsword, rapier, dart, shortbow, hand crossbow, blowgun.) |

See [`../../wiki/core/weapon-mastery.md`](../../wiki/core/weapon-mastery.md) for the canonical wiki page.

> **Important:** if you change which weapon you have mastery in, that change happens during a **long rest** (you study/practice it). You can't swap mastery mid-combat.

---

## §E · Simple weapons (full list)

Simple weapons require **Simple Weapon Proficiency** — almost everyone has it (every class grants it).

### Simple melee weapons

| Weapon | Damage | Properties | Mastery | Weight | Cost |
|---|---|---|---|---|---|
| Club | 1d4 bludgeoning | Light | Slow | 2 lb | 1 sp |
| **★** Dagger | 1d4 piercing | Finesse, Light, Thrown (20/60) | Nick | 1 lb | 2 gp |
| Greatclub | 1d8 bludgeoning | Two-Handed | Push | 10 lb | 2 sp |
| **★** Handaxe | 1d6 slashing | Light, Thrown (20/60) | Vex | 2 lb | 5 gp |
| **★** Javelin | 1d6 piercing | Thrown (30/120) | Slow | 2 lb | 5 sp |
| Light Hammer | 1d4 bludgeoning | Light, Thrown (20/60) | Nick | 2 lb | 2 gp |
| **★** Mace | 1d6 bludgeoning | — | Sap | 4 lb | 5 gp |
| **★** Quarterstaff | 1d6 bludgeoning | Versatile (1d8) | Topple | 4 lb | 2 sp |
| Sickle | 1d4 slashing | Light | Nick | 2 lb | 1 gp |
| **★** Spear | 1d6 piercing | Thrown (20/60), Versatile (1d8) | Sap | 3 lb | 1 gp |

### Simple ranged weapons

| Weapon | Damage | Properties | Mastery | Weight | Cost |
|---|---|---|---|---|---|
| Dart | 1d4 piercing | Finesse, Thrown (20/60) | Vex | ¼ lb | 5 cp |
| **★** Light Crossbow | 1d8 piercing | Ammunition (80/320), Loading, Two-Handed | Slow | 5 lb | 25 gp |
| **★** Shortbow | 1d6 piercing | Ammunition (80/320), Two-Handed | Vex | 2 lb | 25 gp |
| Sling | 1d4 bludgeoning | Ammunition (30/120) | Slow | — | 1 sp |

---

## §F · Martial weapons (full list)

Martial weapons require **Martial Weapon Proficiency**. Granted to Barbarian, Fighter, Paladin, Ranger, and the martial subclasses of other classes. **Wizards, Sorcerers, Warlocks, Druids, and Monks** generally cannot wield martial weapons without a feat (Weapon Master, Magic Initiate adjacent features, etc.).

### Martial melee weapons

| Weapon | Damage | Properties | Mastery | Weight | Cost |
|---|---|---|---|---|---|
| Battleaxe | 1d8 slashing | Versatile (1d10) | Topple | 4 lb | 10 gp |
| Flail | 1d8 bludgeoning | — | Sap | 2 lb | 10 gp |
| Glaive | 1d10 slashing | Heavy, Reach, Two-Handed | Graze | 6 lb | 20 gp |
| Greataxe | 1d12 slashing | Heavy, Two-Handed | Cleave | 7 lb | 30 gp |
| **★** Greatsword | 2d6 slashing | Heavy, Two-Handed | Graze | 6 lb | 50 gp |
| Halberd | 1d10 slashing | Heavy, Reach, Two-Handed | Cleave | 6 lb | 20 gp |
| Lance | 1d10 piercing | Heavy, Reach, Two-Handed* | Topple | 6 lb | 10 gp |
| Longsword | 1d8 slashing | Versatile (1d10) | Sap | 3 lb | 15 gp |
| Maul | 2d6 bludgeoning | Heavy, Two-Handed | Topple | 10 lb | 10 gp |
| Morningstar | 1d8 piercing | — | Sap | 4 lb | 15 gp |
| Pike | 1d10 piercing | Heavy, Reach, Two-Handed | Push | 18 lb | 5 gp |
| Rapier | 1d8 piercing | Finesse | Vex | 2 lb | 25 gp |
| Scimitar | 1d6 slashing | Finesse, Light | Nick | 3 lb | 25 gp |
| **★** Shortsword | 1d6 piercing | Finesse, Light | Vex | 2 lb | 10 gp |
| Trident | 1d8 piercing | Thrown (20/60), Versatile (1d10) | Topple | 4 lb | 5 gp |
| War Pick | 1d8 piercing | Versatile (1d10) | Sap | 2 lb | 5 gp |
| Warhammer | 1d8 bludgeoning | Versatile (1d10) | Push | 5 lb | 15 gp |
| Whip | 1d4 slashing | Finesse, Reach | Slow | 3 lb | 2 gp |

*Lance: One-handed if mounted; otherwise Two-Handed. Mounted lance does NOT have disadvantage against adjacent (5 ft) enemies; on foot, disadvantage against creatures within 5 ft.

### Martial ranged weapons

| Weapon | Damage | Properties | Mastery | Weight | Cost |
|---|---|---|---|---|---|
| Blowgun | 1 piercing | Ammunition (25/100), Loading | Vex | 1 lb | 10 gp |
| Hand Crossbow | 1d6 piercing | Ammunition (30/120), Light, Loading | Vex | 3 lb | 75 gp |
| Heavy Crossbow | 1d10 piercing | Ammunition (100/400), Heavy, Loading, Two-Handed | Push | 18 lb | 50 gp |
| **★** Longbow | 1d8 piercing | Ammunition (150/600), Heavy, Two-Handed | Slow | 2 lb | 50 gp |

---

## §G · Ammunition

Ranged weapons need ammunition. Buy in stacks; carry on belt or in quiver. Weight is generally negligible unless you're going to extremes.

| Ammo | Used by | Cost (stack of 20) | Weight (stack) |
|---|---|---|---|
| Arrows | Shortbow, Longbow | 1 gp | 1 lb |
| Crossbow bolts | Light/Heavy/Hand Crossbow | 1 gp | 1½ lb |
| Sling bullets | Sling | 4 cp | 1½ lb |
| Blowgun needles | Blowgun | 1 gp | 1 lb |

After combat, recover **half (rounded down)** of expended non-broken ammunition automatically with a quick search of the battlefield.

---

## §H · Special considerations

### Two-weapon fighting (using Light weapons)

You can attack with a Light weapon in your off-hand as a **Bonus Action** if your main-hand attack was also with a Light weapon (or with two Light weapons, you can use either). The off-hand attack does NOT add your ability modifier to damage by default — unless your class has a Fighting Style that says it does (Two-Weapon Fighting Style; see [`../../wiki/feats/two-weapon-fighting.md`](../../wiki/feats/two-weapon-fighting.md)).

**Nick mastery** (Dagger, Light Hammer, Sickle, Scimitar) lets you make this off-hand attack as part of your **Attack action** instead of using your Bonus Action — freeing the Bonus Action for something else.

### Reach weapons (5-ft extra)

A Reach weapon threatens enemies up to **10 ft away** for melee attacks AND opportunity attacks. Crucial when you want to keep enemies at range or punish movement.

If you have a Reach weapon and an enemy provokes an opportunity attack at 10 ft (e.g., trying to dash past you), you can still hit them.

### Mounted combat (Lance)

When mounted, you wield a Lance one-handed; the normal "disadvantage within 5 ft" goes away. This is the only weapon with a mount-specific rule in the core list.

### Improvised weapons (farm tools, furniture, rocks)

Anything you grab and swing that isn't designed as a weapon is an **improvised weapon**. Damage 1d4 unless the DM rules otherwise. No proficiency, no mastery.

**[HOUSE] EXCEPTION for Field Defender Fighting Style** (see [`../../homebrew/character-design/build-options.md`](../../homebrew/character-design/build-options.md) §B): if you have the **Field Defender** feat, agricultural tools (pitchfork, sickle-as-tool, hayhook, shovel, threshing flail) count as martial weapons for you, +1 damage with improvised weapons made from farm tools.

### Silvered weapons & magical weapons

Some monsters (werewolves, certain devils, certain undead) **resist non-magical attacks**. To bypass that resistance:

- **Silvered** weapons (regular weapon + 100 gp of silver coating, takes a smith one day): non-magical but counts as magical for resistance purposes against specific monster types (lycanthropes especially).
- **Magical** weapons (rare and usually heirloom in this campaign — see [`../../homebrew/world/magic-in-society.md`](../../homebrew/world/magic-in-society.md) DRAFT): always bypass non-magical resistance.

In Fallowton, **Tamsin Bellows can silver a weapon** — base cost 100 gp plus 3 days' labor. The cost is steep because silver is more useful in trade than in steel.

---

## §I · Fallowton-specific weapon notes

### Tamsin Bellows' services (the village smith)

| Service | Cost | Notes |
|---|---|---|
| Sharpening (any martial weapon) | 5 sp – 1 gp | Persuasion DC 12 to haggle down 1 sp; on fail she raises 1 sp out of irritation |
| Repair (broken weapon) | 1/2 weapon cost + 1 day | She'll prioritize Fallowton villagers over outsiders unless they've earned her trust |
| Silvering (see §H) | 100 gp + 3 days | Limited by silver availability; she may make you wait |
| Custom forging (a knife, a spearhead, an axe blade) | Full weapon cost + 1d4 days | She insists on inspecting the wood handle herself |
| Identification ("what *is* this") | Free | She'll volunteer it; rolling for it would be insulting |

She will NOT:

- Sharpen anything she suspects is Dawnweave-touched (refuses politely, returns the weapon, doesn't speak about it again).
- Make weapons that look "ceremonial" or "wrong" (her hands shake; she stops). Her grief about her husband's death five winters ago shapes this.
- Work for the Office. If you arrive with a sealed warrant requiring forging work, she'll cite a "scheduled rest" and the work won't happen until you bring a non-Office party member.

### What's available in the village

Fallowton is a farming village, not a market town. **Available off-the-shelf:**

- Daggers (~3-4 in the village; new ones cost 2 gp from Tamsin)
- Spears (~10 in the village; Bran has a stash for the village watch)
- Handaxes (~6; almost every fieldhand owns one)
- Shortbows (~3-4 hunters in the village; arrows on order)
- Quarterstaves (every adult has one of these around)
- Slings (older children play with these)

**NOT available in the village** (buy in Marrowford, 1 day east, or at Calder Vault, 4 days east):

- Any heavy / two-handed martial weapon (no demand here)
- Crossbows of any kind (the village has none; Office squads carry them)
- Rapiers, scimitars (no nobility live here)
- Tridents, lances, polearms, war picks (no use case)

**NEVER available, even in Marrowford** (buy in Calder Vault, with a writ, or commission):

- Hand crossbow (regulated by the Office as a "concealable assassin's tool")
- Custom-balanced weapons for specific Fighting Styles

### Improvised farm-tool weapons (with [HOUSE] Field Defender)

| Tool | Equivalent | Notes |
|---|---|---|
| Pitchfork | Spear (1d6 piercing, Thrown 20/60, Versatile 1d8) | Tines instead of point; loses Thrown |
| Threshing Flail | Flail (1d8 bludgeoning) | The classic "two-handed grain-thresher" wielded as a weapon |
| Sickle (the actual farm tool) | Sickle (1d4 slashing, Light, Nick mastery) | Same thing; just labeled honest |
| Shovel | Quarterstaff (1d6 bludgeoning, Versatile 1d8) | Wide blade adds reach unconventionally |
| Hayhook | Handaxe (1d6 slashing, Light, Vex mastery) | One-handed hooking grip |
| Carpenter's hammer | Light Hammer (1d4 bludgeoning, Light, Nick) | Same thing; the trade tool stat |

Without Field Defender, all of the above are **improvised weapons** (1d4, no proficiency, no mastery).

---

## Cross-references

- BR-2024 sample weapons (with prices and links): [`equipment-reference.md`](equipment-reference.md)
- Wiki — weapon properties (canonical, with citations): [`../../wiki/core/weapon-properties.md`](../../wiki/core/weapon-properties.md)
- Wiki — weapon mastery (canonical): [`../../wiki/core/weapon-mastery.md`](../../wiki/core/weapon-mastery.md)
- Wiki — individual weapon pages (BR-2024 sample only): [`../../wiki/equipment/`](../../wiki/equipment/)
- Wiki — armor combined table: [`../../wiki/equipment/armor.md`](../../wiki/equipment/armor.md)
- House rules — critical hits, weapon swap, healing potions: [`../../homebrew/house-rules.md`](../../homebrew/house-rules.md)
- Homebrew — Field Defender feat (farm tools as martial): [`../../homebrew/character-design/build-options.md`](../../homebrew/character-design/build-options.md)
- Module 1 NPCs — Tamsin Bellows (the smith): [`../dm-handbook/module-1-npcs.html`](../dm-handbook/module-1-npcs.html)

---

*Stats above match the 2024 PHB. If a future rules update changes an entry, the official source wins. For BR-2024 free-rules subset (★), see also the existing [`equipment-reference.md`](equipment-reference.md).*
