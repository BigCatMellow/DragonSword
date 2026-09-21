# DragonSword: Awakening — Research & Field Notes

A structured notebook for understanding **DragonSword: Awakening**: gameplay systems, canon lore, environmental storytelling, middle worldbuilding, and evidence-based theories about Orbis.

This repository uses a lightweight [MAPS_L](https://github.com/BigCatMellow/MAPS_Lean) workflow: inspect reality, separate evidence from inference, preserve unknowns, and keep one durable owner for each concept.

## Start here

1. [Project brief](PROJECT_BRIEF.md) — purpose, DONE condition, boundaries
2. [Roadmap](ROADMAP.md) — current research direction
3. [Lore baseline](lore/BASELINE.md) — what the game clearly establishes
4. [Claim ledger](research/CLAIM-LEDGER.md) — evidence/status for important claims
5. [Middle worldbuilding](worldbuilding/MIDDLE-WORLDBUILDING.md) — how the visible world implies hidden systems
6. [Orbis iceberg](worldbuilding/ICEBERG.md) — layered reconstruction of what sits beneath the visible setting
7. [Organa & Kalagon](theories/ORGANA-KALAGON.md) — focused ancient-history investigation
8. [Open questions](research/OPEN-QUESTIONS.md) — what to investigate next
9. [Beginner cheat sheet](guides/BEGINNER-CHEAT-SHEET.md) — compact gameplay reference
10. [Hint-first walkthrough](walkthrough/README.md) — chapter/problem lookup with progressive hints before direct answers

## Truth labels

Every nontrivial lore claim should be treated as one of:

- **VERIFIED** — directly supported by Hound13/official material or directly observed in-game.
- **REPORTED** — supported by a secondary source describing in-game material, but not yet independently checked.
- **INFERRED** — follows reasonably from verified/reported evidence but is not directly stated.
- **SPECULATIVE** — plausible theory with meaningful missing links.
- **UNKNOWN** — question deliberately left unresolved.

Do not silently promote a theory into canon.

## Spoilers

Lore files may contain story spoilers. Use headings to mark spoiler depth where practical.

## Core lens

Two recurring ideas guide the analysis:

**Middle worldbuilding** — not just what happened, but how ordinary institutions, jobs, customs, infrastructure, economics, religion, and daily behavior function because of it.

**Write the sequel** — treat worldbuilding events as old news to the people living downstream from them. Ask:

> If this has been true for decades or centuries, what would people have already done about it?

That is often where the hidden iceberg becomes visible.


## GitHub Wiki

User-facing reference pages are authored in [`wiki/`](wiki/) and published to the repository's GitHub Wiki by [`.github/workflows/publish-wiki.yml`](.github/workflows/publish-wiki.yml).

Wiki design:

- Home + persistent sidebar
- hint-first chapter walkthrough
- problem/symptom index
- puzzle index
- beginner cheat sheet
- compact lore/worldbuilding/theory pages

GitHub requires the Wiki to have one initial page before its backing `.wiki.git` repository exists. After that one-time initialization, changes under `wiki/` publish automatically.
