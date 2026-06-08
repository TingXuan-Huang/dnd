# D&D Keep — Curated 5.5e Game Kit

The keepable parts of two former Desktop folders (`dnd/` and `dnd_glossary/`),
consolidated into one clean kit on **2026-06-07**. Built by a non-destructive
copy — the originals were untouched, so once you've looked this over you can
delete `dnd/` and `dnd_glossary/`.

**Total: ~66 MB · 838 markdown pages · 378 monster stat blocks · 12 HTML maps.**
(Down from ~131 MB across the two originals.)

---

## Start here

| You are… | Open |
|---|---|
| A DM learning to run *any* game | [`homebrew/00-dm-operating-manual.md`](homebrew/00-dm-operating-manual.md) — the 1,200-line craft manual (interference dial, pacing, spotlight, improv, rulings) |
| Running the **Fallowton** campaign | [`docs/dm-handbook/`](docs/dm-handbook/) (at-the-table kit) + [`docs/dm-handbook-archive/`](docs/dm-handbook-archive/) (story, decisions, encounter balance, maps guide) |
| A **player** at the table | [`docs/player-guide/getting-started.md`](docs/player-guide/getting-started.md) |
| Looking up a **rule** | [`wiki/`](wiki/) (cited, wikilinked) — start at [`index.md`](index.md) |
| Looking up a **monster / item / spell** | [`rules-catalog/`](rules-catalog/) (data + the full bestiary) |
| Adding **homebrew** grit | [`homebrew/`](homebrew/) — survival, physicality, wounds, sanity, the Notice, Weave Strain |

---

## What's in here

| Folder | What it is | Came from |
|---|---|---|
| [`homebrew/`](homebrew/) | DM Operating Manual, house rules, the gritty/horror rule systems (survival-realism, physicality, sanity-and-spirit, the-notice), custom backgrounds & build options, the Fallowton bestiary, and the world lore (`world/`) | `dnd/homebrew/` |
| [`docs/`](docs/) | The Fallowton campaign: player guide, DM handbook (+ archive), player characters, campaign rules, and all the hand-built **HTML battle maps** | `dnd/docs/` |
| [`wiki/`](wiki/) | Citation-disciplined 5.5e rules glossary — core mechanics, combat, conditions, concepts, class features, feats, species, subclasses | `dnd/wiki/` |
| [`print/`](print/) | D&D Beyond **Basic Rules 2024**, pre-extracted as readable chapters | `dnd/print/` |
| [`raw/`](raw/) | Immutable source material the wiki cites (Artificer UA playtest, errata, Sage Advice, SRD 5.2, web clips) | `dnd/raw/` |
| [`raw crawl content/`](raw%20crawl%20content/) | Unprocessed firecrawl dumps — one large markdown file per section (classes, stat blocks, equipment, magic items, rules glossary, spells); the raw source the wiki & catalog were built from | `dnd/raw crawl content/` |
| [`rules-catalog/`](rules-catalog/) | Granular one-page-per-entity reference: **378-monster bestiary**, equipment, spells, classes, rules glossary, DM toolbox (traps/poison/curses), origins | `dnd_glossary/` |
| [`concept_images/`](concept_images/) | 3 AI concept-art PNGs (ruin hall, sinkhole, village) | `dnd/concept_images/` |
| [`dmg-tracking-sheets/`](dmg-tracking-sheets/) | The combined blank DMG tracking forms (1 PDF, all 9 sheets) + the filled Fallowton settlement sheet | `dnd/dmg-tracking-sheets/` |
| [`CLAUDE.md`](CLAUDE.md) | The wiki's operating manual — citation format, templates, conventions | `dnd/CLAUDE.md` |
| [`quick_reference.md`](quick_reference.md) | One-page skills table & basics | `dnd/quick_reference.md` |
| `DND_2024_Character_Creation_Guide.docx` | Word version of the character-creation guide | `dnd/` |

---

## Two rules references — why there are two

You asked to "merge the best of both," and the two sources are genuinely
**complementary**, so both are kept side by side:

- [`wiki/`](wiki/) is the **cited, wikilinked primary** — best for *understanding*
  rules (how conditions compose, what a class feature does, edge-case concepts).
  Every claim cites a source. But it has **no bestiary** and few full spells.
- [`rules-catalog/`](rules-catalog/) is the **granular data** — best for *lookup*
  (a goblin's stat block, an item's price). It carries the **378-monster
  bestiary** the wiki lacks, plus equipment/spell/class catalogs.

They overlap on classes and equipment. If you later want only one, keep `wiki/`
for prose rules and `rules-catalog/` for the bestiary — that's the non-redundant core.

---

## What was left behind (safe to delete from the originals)

Nothing unique was dropped. For the record, these were **excluded** as redundant,
regenerable, or scratch:

**From `dnd/`:**
- 9 individual blank tracking-sheet PDFs — identical to the kept `combined-tracking-sheets.pdf` (verified: 9 sheets = 9 pages). Saved ~51 MB.
- `concept_images_archieved/` — 9.8 MB of superseded art (kept the 3 current images).
- `homebrew/TODO.md` — wiki-building project tracker (not a game asset).
- `log.md` — wiki changelog. `reference_dm.md` — duplicate of `quick_reference.md`.
- `.firecrawl/`, `.lint/`, `.claude/`, `.DS_Store` — tooling/scratch.

**From `dnd_glossary/`:**
- `references/` — 808 auto-generated D&D Beyond link-stubs (9 lines each, no real content; nothing else linked *to* them).
- `.build_references.py` — the script that regenerates those stubs.
- `.DS_Store`.

---

## Notes

- **Links are preserved.** The original `dnd/` layout (`homebrew/`, `docs/`,
  `wiki/`, `print/` as siblings) was kept intact, so all relative links and
  wikilinks still resolve. The only edits: 4 dead links to the removed `TODO.md`
  were de-linked (text kept).
- `CLAUDE.md` is the wiki's own operating manual; if you open this folder in
  Claude Code it will load as project context — that's intentional and harmless.
