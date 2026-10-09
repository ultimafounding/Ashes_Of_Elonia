# Ashes of Elonia

> *The gods abandoned the world a thousand years ago. History buried the reasons. Someone intends to unearth them.*

A full-length D&D 5e campaign (levels 1–20) set in Elonia, c. 1,000 years after the Silence.

## What this is

**Ashes of Elonia** is a mythic-fantasy, archaeology-meets-detective campaign:

- Starts as a salvage job under Port Meridian, ends deciding the future of humanity.
- 6 acts, 12 chapters, ~32 sessions (3–4 hr each).
- Core theme: **Freedom vs. Protection** — *If someone protects you from every consequence, are they helping you, or preventing you from becoming who you could be?*
- Tone: ancient ruins + archival detective work + awe without worship. Think scholars in the dust.

Players uncover suppressed history, the Soul Crisis (the dead failing to pass), and a conspiracy behind "divine return."

**DM spoiler:** the patron Lord Seraphel is the Hidden Tenth, harvesting souls for his own apotheosis. Full secrets in `01_CAMPAIGN/full_story_synopsis.md`.

## Repository structure

```
Ashes_Of_Elonia/
├── 00_SOURCE_OF_TRUTH/     # Locked canon: Campaign Bible v1, Ain Elonar. Overrides everything.
├── 01_CAMPAIGN/            # DM architecture: overview, synopsis, act structure, revelation timeline, milestones
├── 02_WORLD/               # Cosmology, geography, nations, the Nine Celestine, chronology
├── 03_LOCATIONS/           # Gazetteer + key sites: Port Meridian, New Ilya, Lantern Chapel, Khar Vareth, Engine Deep
├── 04_NPCS/                # Seraphel, Brother Cael/Orinth, allies, Avatar of the Last Mercy
├── 05_FACTIONS/            # Ascendants, Church of the Last Light, Keepers, Cartels, Custodians, etc.
├── 06_ADVENTURE/           # Act I–VI chapter manuscripts (the playable campaign)
├── 07_SESSIONS/            # Session splits, prep briefs, running notes, recaps
├── 08_MONSTERS_AND_ITEMS/  # Stat blocks, relics, gear, hazards
├── 09_PLAYER_MATERIAL/     # Safe for players: primer, character creation
├── 10_LIVE_CAMPAIGN_STATE/ # Clocks, party state, logs (empty until play)
├── _templates/             # NPC, location, session-prep templates
```

Subfolder `README.md` files explain each section's purpose and canon authority.

## How to use

**Players — start here:**
1. Read only `09_PLAYER_MATERIAL/players_primer.md`. Everything else is spoilers.
2. Make a level 1 D&D 5e character (milestone leveling, no evil PCs). You start in Port Meridian, hired by salvage factor Helena Voss.

**DMs — run order:**
1. Read `00_SOURCE_OF_TRUTH/Ashes_of_Elonia_Official_Campaign_Bible_v1.md` — locked canon.
2. Read `01_CAMPAIGN/` in order: `campaign_overview.md` → `full_story_synopsis.md` → `act_structure.md` → `revelation_timeline.md` → `milestone_progression.md`.
3. Skim `02_WORLD/` + `03_LOCATIONS/` + `04_NPCS/` + `05_FACTIONS/` for context.
4. Run `06_ADVENTURE/Act I/` onward. Use `07_SESSIONS/sessions_guide.md` to split chapters into nights.
5. Track the 3 global clocks in `10_LIVE_CAMPAIGN_STATE/`: Soul Crisis Tide (6), Seraphel's Convergence (8), Censor's Shroud (4).

Built for Obsidian — Markdown mirrors with wikilinks, tags:
`[ESTABLISHED CANON]` = true, `[DM-ONLY]` = secret truth, `[PLAYER-FACING]` = common knowledge, `[DISPUTED]` = sources disagree, `[UNRESOLVED]` = never answer canonically (Sea Beyond, soul destination, blank final chapter of *Ain Elonar*).

## Canon rules

1. `00_SOURCE_OF_TRUTH/` wins over all drafts.
2. Don't contradict the Immutable Register: present day c. 1,000 AS; Ascendants ≠ evil cult; Soul Crisis caused by the Ascension Engine, not the gods' departure; Brother Cael is Orinth (witness, never oracle); final chapter is blank until players write it.
3. Every revelation needs 3 clues (documentary + material + social). Every answer creates 2 new questions.

Safety: establish Lines/Veils + X-Card before Session 0. Heavy themes: death, grief, souls, institutional gaslighting. See `campaign_overview.md` §9.

## Status & license

In development — Act manuscripts and live state are evolving. Canon source is Bible v1.

CC0 1.0 Universal — see `LICENSE`. Reuse freely.
