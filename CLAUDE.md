# D&D 5.5e Rules Wiki — Operating Manual

This file tells Claude (or any LLM agent) how to work in this repository. It is the single source of truth for conventions. When in doubt, follow this file. When a convention here proves wrong in practice, propose an edit — don't silently deviate.

## Purpose

A queryable, citation-disciplined wiki of D&D Fifth Edition (2024 revision, "5.5e"), plus the Artificer class (UA 2024 playtest). Built to answer rules questions fast, with verifiable references back to source material.

## Three-Layer Architecture

```
raw/    → Immutable raw sources (new sources go here). Never edit.
print/  → Immutable: D&D Beyond Basic Rules 2024, pre-extracted. Never edit.
wiki/   → LLM-maintained. One page per entity. Edit freely under the conventions below.
```

You (the LLM) own `wiki/`, `index.md`, and `log.md`. Everything else is read-only.

## Source Precedence

When two sources conflict, the higher-ranked source wins. Always cite which won.

1. **Official errata** (`raw/errata/`) — overrides original printings.
2. **2024 PHB / DMG / MM**, mirrored in `print/` as Basic Rules 2024.
3. **Sage Advice Compendium** (`raw/sage-advice/`).
4. **SRD 5.2** (`raw/srd-5.2/`) when present.
5. **Supplements** (TCoE, etc.) — authority limited to their scope.
6. **Unearthed Arcana** (`raw/artificer/`) — tag as `playtest`. Conditional authority.
7. **Web clips / fan wikis** (`raw/web-clips/`) — starting points; verify against official.

## Citation Format

Every rules claim in `wiki/` must cite at least one raw source.

| Source           | Format                              | Example                                                   |
|------------------|-------------------------------------|-----------------------------------------------------------|
| `print/` chapter | `[BR-2024 §{file}#{anchor}]`        | `[BR-2024 §03-character-classes#Barbarian]`               |
| Owned book       | `[{abbrev} p.{page}]`               | `[TCoE p.9]`                                              |
| UA               | `[UA {year} {topic}, {date}]`       | `[UA 2024 Artificer, 2024-04-15]`                         |
| Sage Advice      | `[SAC v{ver} p.{page}]`             | `[SAC v3.0 p.22]`                                         |
| Web              | `[{site}, accessed {date}]`         | `[dnd5e.wikidot.com/spell:fireball, accessed 2026-05-21]` |

When paraphrasing, cite at end of paragraph. When quoting, cite at end of quote.

## Wikilinks

Obsidian-style: `[[snake-case-slug]]`. Slug = filename without `.md`. Lint catches dangling links. For aliased display: `[[fireball|Fireball (3rd-level evocation)]]`.

## Wiki Page Templates

Templates live in `wiki/_templates/`. Don't drift from them. Every page has YAML frontmatter and a standard body shape.

### Required frontmatter on every page

```yaml
---
type: spell | class | subclass | feature | feat | species | background | monster | condition | equipment | magic-item | concept | ruling
sources: [BR-2024, UA-2024, ...]                  # which raw layers feed this page
since: "5.5e" | "5e-pre-revision" | "playtest"    # which edition the rules reflect
tags: [...]
updated: YYYY-MM-DD
---
```

### Type-specific extras

- **spell:** `level`, `school`, `classes`, `ritual` (bool), `concentration` (bool)
- **class:** `hit-die`, `primary-ability`, `subclasses`
- **subclass:** `class`, `level-gained`
- **feature:** `class`, `level-gained`
- **feat:** `category` (origin|general|fighting-style|epic-boon), `prerequisites`, `repeatable`
- **species:** `size`, `speed`, `traits`
- **background:** `ability-scores`, `feat`, `skills`, `tools`
- **monster:** `cr`, `creature-type`, `size`, `alignment`
- **condition:** none extra
- **equipment:** `subtype` (weapon|armor|tool|gear), `cost`, `weight`
- **magic-item:** `rarity`, `attunement`
- **concept:** none extra
- **ruling:** `question`, `answered`

## Directory map for `wiki/`

```
core/         General mechanics (D20 tests, advantage, rest, conditions overview)
combat/       Combat-specific rules (actions, opportunity attacks, cover, grapple)
classes/      One page per class
classes/_features/   Long class-feature descriptions linked from class pages
subclasses/   One page per subclass
species/      One page per species (formerly "race")
backgrounds/  One page per background
feats/        One page per feat
spells/       One page per spell
equipment/    One page per item or item category
magic-items/  One page per magic item
conditions/   One page per condition (15 official + any added)
concepts/     Cross-cutting topics (bounded accuracy, action economy)
rulings/      Saved Q&A from query operations
```

## Workflows

### `/ingest <path>` — add a new source

1. Read the source file in full.
2. Identify every entity it describes: spells, classes, features, feats, conditions, etc.
3. For each entity: create or update a `wiki/` page using the appropriate template.
4. Ensure citations back to the source are correct on every page touched.
5. Update `index.md`: add new pages to their category sections (sorted alphabetically).
6. Append a `log.md` entry: `## [YYYY-MM-DD] ingest | {source} | {N pages touched}`.
7. Report: new pages, updated pages, ambiguities skipped.

### `/query <question>` — answer a rules question

1. Read `index.md` first to find candidate pages.
2. Pull 2-5 relevant pages.
3. Synthesize an answer. Every factual claim cites at least one source.
4. If the wiki has contradictory info, surface it; don't paper over it.
5. If the answer involved meaningful synthesis, offer to save as `wiki/rulings/{slug}.md` so it compounds.
6. Append: `## [YYYY-MM-DD] query | {one-line question}`.

### `/lint` — health check

Scan for:
- **Dangling links** — `[[wikilink]]` pointing to a non-existent file.
- **Orphan pages** — pages with zero inbound links.
- **Missing citations** — claims without a `[…]` reference.
- **Drift from template** — missing required frontmatter fields.
- **Stale frontmatter** — `updated:` predates the last actual edit.
- **Contradictions** — same fact stated differently on two pages.
- **Missing pages** — concepts referenced repeatedly but lacking a page.

Report findings. Don't auto-fix unless asked.

## Paraphrasing conventions

You will paraphrase rules text. Three hard rules:

1. **Preserve numbers exactly.** Damage dice, ranges, durations, DCs, costs — never round.
2. **Preserve trigger conditions exactly.** "When you", "If a creature", "As a reaction" — load-bearing.
3. **Compress narrative flavor; keep mechanics tight.** Cut flavor sentences; never cut mechanics.

When in doubt, quote verbatim and cite.

## Glossary

- **5.5e / 2024 revision:** PHB Sept 2024, DMG Nov 2024, MM Feb 2025. Still "Fifth Edition" but with significant rule changes.
- **5e-pre-revision:** 2014 PHB content. Use when content predates 2024 and hasn't been updated.
- **BR-2024:** Free Basic Rules on D&D Beyond, 2024. Subset of full PHB. Source for `print/`.
- **UA:** Unearthed Arcana. Playtest material. Non-final.
- **SAC:** Sage Advice Compendium. Periodic official ruling document.
- **TCoE:** Tasha's Cauldron of Everything (2020). Pre-revision Artificer originated here.
