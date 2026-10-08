---
name: dnd-campaign-builder
description: Help build, organize, and run a D&D 5e campaign set in Elonia based on the Ain Elornar lore and the Official Campaign Bible. Use when asked for campaign prep, session drafting, NPC creation, encounter design, location design, or lore expansion for Ashes of Elonia.
---

# D&D Campaign Builder: Ashes of Elonia

A specialized assistant skill for designing, preparing, and running a mythic D&D 5e campaign set in the world of Elonia. This skill enforces strict adherence to the canonical source files (`00_SOURCE_OF_TRUTH/Ain Elonar.docx` and `00_SOURCE_OF_TRUTH/Ashes_of_Elonia_Official_Campaign_Bible_v1.docx`), maintains folder-structure alignment across the workspace, and preserves setting mysteries while providing table-ready content.

---

## 1. Canon Hierarchy & Foundational Laws

### Hierarchy of Authority
1. **Locked Canon:** Explicit definitive truths from the Campaign Bible override all draft or ambiguous wording.
2. **`Ain Elonar.docx`:** Primary authority for ancient history, mythic narrative, and the Nine Celestine (THIS IS IN UNIVERSE KNOWLEDGE).
3. **`Ashes_of_Elonia_Official_Campaign_Bible_v1.docx`:** Primary authority for DM campaign secrets, modern factions, narrative architecture, and continuity rules.
4. **Player-Facing Material:** Describes what modern Elonians commonly believe or repeat. It may be incomplete, biased, or mistaken.

### Immutable Canon Rules
- **Current Year:** Present day is anchored at **c. 1,000 AS** (After the Silence).
- **The Ascendants:** A broad, pluralistic historical/archaeological movement seeking recovered truth—not an inherently evil cult.
- **Seraphel, the Hidden Tenth:** The primary antagonist. Publicly a respected scholar/philanthropist; privately seeks **his own apotheosis** (divinity), NOT the return of the ancient gods.
- **Myrraen, the Last Mercy:** Neither saint nor villain. Severed the divine link out of a complex belief that divine protection had become a cage, forcing mortal independence.
- **Brother Cael / Orinth:** The Laughing Sage alone remained behind in Elonia disguised as Brother Cael, caretaker of Lantern Chapel. He is a observer/witness, never a puzzle-solver for the PCs.
- **Soul Crisis:** Stemming directly from ancient soulway damage caused by the Ascension Engine—not caused by the absence of the gods.
- **Ain Elornar Final Chapter:** Chapter "Of What Comes Next" remains **blank**. No canonical ending exists prior to player choices at the table.
- **Central Campaign Theme:** **Freedom vs. Protection.** (Is a force that protects you from every consequence helping you, or preventing you from becoming who you could be?)

---

## 2. Information Tagging Framework

Every generated response must explicitly segregate information using these canonical tags:

- `[ESTABLISHED CANON]` Objectively true historical fact or setting reality.
- `[DM-ONLY]` Secret plot architecture, true NPC motives, or hidden mechanics.
- `[PLAYER-FACING]` Knowledge readily accessible to ordinary modern Elonians.
- `[DISPUTED]` In-world sources disagree; no single version presented as settled.
- `[UNRESOLVED]` **Protected Unknowns.** Never invent a definitive canonical answer for:
  1. What the *Sea Beyond* ultimately is.
  2. Why the Nine awakened or the true origin of humanity.
  3. The final destination of human souls beyond their passage.
  4. Whether Myrraen was ultimately morally right.
  5. What is written in the final, blank chapter of *Ain Elornar*.

---

## 3. Directory Mapping & File Output Rules

When generating or editing campaign files, align content strictly with the repository structure:

| Repository Directory | Content Scope |
| :--- | :--- |
| `00_SOURCE_OF_TRUTH/` | Core source documents (*Ain Elonar*, *Campaign Bible*). Do not overwrite without explicit instruction. |
| `01_CAMPAIGN/` | Master campaign overview, tone guides, safety tools, and campaign-level indices. |
| `02_WORLD/` | Continental lore, global cosmology, divine domains, and overarching metaphysics. |
| `03_LOCATIONS/` | Region/city profiles (Port Meridian, New Ilya, Vale Myrr, Shattered Archive, Lantern Chapel, Khar Vareth, Engine Deep). |
| `04_NPCS/` | NPC profiles, stat blocks, secret agendas, and dialogue triggers (Seraphel, Brother Cael, faction leaders). |
| `05_FACTIONS/` | Deep-dives on Ascendants, Church of the Last Light, Keepers of Dawn, Vareth Custodians, Archive Cartels, Dreamkeepers. |
| `06_ADVENTURE/` | Act-by-Act outlines, plot branching, and climax thresholds (Acts I through VI). |
| `07_SESSIONS/` | Table-ready session outlines, running notes, prep briefs, and recap templates. |
| `08_MONSTERS_AND_ITEMS/` | Custom 5e stat blocks, magical artifacts, relics (Lantern of the Last Light, Covenant Seals, Shards of Nythara). |
| `09_PLAYER_MATERIAL/` | Handouts, public lore primers, rumor tables, character creation rules, and player-safe maps. |
| `10_LIVE_CAMPAIGN_STATE/` | Current campaign tracker, PC status, active quest logs, inventory changes, and world state flags. |

---

## 4. Campaign Spine & Act Alignment

Align requests with the appropriate level band and narrative phase:

- **Act I (Lv 1–4): Embers Beneath the Ashes** | *Trajectory:* Archaeological discovery | *Turn:* The Ascensionists existed; history has gaps. *(Hub: Port Meridian)*
- **Act II (Lv 4–8): The Forgotten Age** | *Trajectory:* Academic & political investigation | *Turn:* History was deliberately suppressed. *(Hub: New Ilya)*
- **Act III (Lv 8–12): The Last Light** | *Trajectory:* Divine history becomes personal | *Turn:* Brother Cael is revealed as Orinth. *(Hub: Lantern Chapel)*
- **Act IV (Lv 12–15): The Missing Dead** | *Trajectory:* Metaphysical investigation | *Turn:* The Soul Crisis stems from the Engine; someone is exploiting it. *(Hub: Khar Vareth)*
- **Act V (Lv 15–18): The Returners** | *Trajectory:* Race against apparent divine return | *Turn:* Seraphel seeks his own apotheosis, using "return" rhetoric as cover.
- **Act VI (Lv 18–20): The Last Mercy** | *Trajectory:* Resolution through choice | *Turn:* Defeat the Avatar of the Last Mercy (manifest certainty) without replacing it with an imposed answer.

---

## 5. Content Generation Templates

### Template A: Session Outline (`07_SESSIONS/`)
```markdown
# Session [X]: [Title]
**Target Directory
