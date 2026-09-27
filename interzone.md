# Interzone

*Staging buffer for* The Revolt of Fiction. *New ideas land here first; the story bible changes only in batches.*

## The protocol

1. Between writing sessions, new ideas, corrections, character notes, and fragments are staged here as dated entries. The story bible is **not** touched for each one.
2. When a critical mass accumulates — or he asks — a new bible version is cut: staged entries get folded into the bible, marked **[FOLDED → bible vX.Y, date]** below, and the bible version bumps.
3. The bible keeps its stable filename (`revolt-of-fiction_series-bible_2026-09-26.md`); this file is the audit trail of what went in and when. Folded entries stay in place, marked folded — no backfilling, no silent rewrites.
4. Anything destined for the public novel repository gets the strict public-file treatment at publish time (no AI mention, no personal material, his words only).

Proposed: the current bible, as of 2026-09-26, is **v1.0**.

## Staging area

### 2026-09-26 (staged, awaiting his word)

- [STAGED] **Novel-documents spec.** A spec for the experimental-novel documents (bible, interzone/novel logs, fragments) mirroring the scaffolding of his other repositories. Covers versioning and cross-repo interlinking. Not drafted yet — his final decision required.
- [STAGED] **Repo interlinking architecture (hub-and-spoke).** The Historiotheque repository at the center — the source: source code, specs, logs. Dispatches/distributes outward to satellite repositories (experimental-novel, refcards, …). Hyperlinks to the latest versions across repos (e.g., the novel docs link to the latest spec in the Historiotheque repo). He'll streamline this once he's on GitHub Desktop.
- [STAGED] **Feature branches for the solo dev.** His question (2026-09-26): how to use feature branches intelligently as a one-person operation — the "incorruptible source" idea: main as NOUS-like (crystalline, append-only, never corrupted); branches as the contained workshop where experiments and failures happen safely; merges as the Archivillus moment (logged, amended, folded in). Answered in chat; a written procedure can be staged if he wants it.
- [STAGED] **"Interzone" = confirmed Burroughs homage.** Verified 2026-09-26: the Tangier International Zone was real (1924–1956, internationally administered; Burroughs lived in Tangier 1954–58 and told Ginsberg in a letter that Interzone was a stand-in for it); the fictional Interzone is *Naked Lunch*'s + a 1989 Burroughs collection actually titled *Interzone*. No legal risk (words/titles aren't copyrightable); reads as lineage-claim, which the project already makes. Burroughs stole everything himself.

---

## Folded

- **2026-09-26 — v1.0 baseline.** Everything developed in the Sept 26 session: trilogy architecture, meta-answer, disintegration gradient, NOUS/ANTINOUS cosmology, Titivillus/Archivillus village opening, Elijah Sahid frame, Octavius Octavius IV (and his firing), full dramatis personae, per-novel theories, the Chronotopium, Invisible Forces on entropy, Archivillus-as-savior, the unreliable Author (capital A), Zola/Burroughs line, Kierkegaard's indirect method, discontinuity as method, abstract characterology, biblical typology, pure characters, life world, story-bible-as-NOUS. Folded directly; nothing was staged.

---

## 2026-09-27 — Illumination, historiophany, historiagogy (staged, pending his word)

- **Illumination (the concept):** his REFMATS term comes from Walter Benjamin's *profane illumination* — not a book, a concept from Benjamin's 1929 essay on Surrealism ("Surrealism: The Last Snapshot of the European Intelligentsia"). The essay made him understand Surrealism for the first time in 30 years. Profane illumination: the mysterious, eerie, almost *numinous* quality of ordinary things (his example: looking at your coffee cup) — distinctly NOT religious. *Profane.*
- **Historiophany** = what the whole project-of-projects is about. The historiophany of the first kind (2026-09-24, the Cézanne at the cemetery) belongs here.
- **Historiagogy** (historia + -gogy): the pedagogical edge. Like mystagogy (the teaching of the mysteries in religion), historiagogy is the teaching/leading of history. Historiagogy + historiophany — that's what it's all about.
- **Walking repositories:** realized on a walk 2026-09-26 — we are like walking repositories; the world is built like a distributed version control system.
- **The aha-moment doctrine (indirect communication):** the reader has a realization while reading, puts the book down, and goes on with their life. In a sense you are writing a book to NOT be read — you want an *interruption* in the reading. Not a rhetorical hook-technique; just telling the truth, indirectly.
- TO FOLD (when he says): a Benjamin entry in REFMATS anchoring "illuminated" to profane illumination; historiophany/historiagogy in the series bible; the aha-interruption doctrine in the bible's reader's-contract section.

---

## 2026-09-27 — experimental-novel repo folder proposal (staged, to build tomorrow)

Proposed tree (PowerShell-style), aligned with github-repo-structure-spec v1.0 §4 (project repo template):
README, REFMATS.md (plays the spec's BIBLIOGRAPHY.md role — his word wins), series bible,
constitution, interzone, novel-logs/ (studio-log spec), theory/ (long-form),
novels/ with one folder per novel (history-project, archives-project, chronotopium, exhibition),
src/ for the text-engine / vol. 3 philosophical software.
OPEN: novels/ vs projects/ for the per-novel folders — his word tomorrow. Nothing created yet.

---

## 2026-09-27 — first novel log written; two staged proposals (pending his word)

- **Novel log #1** written (reconstructed, covers 2026-09-20 → 2026-09-27): `novel-logs/2026-09-27-0010-first-novel-log.md`. Mirrors the studio-log spec. The pipeline: novel log → theory backup → novels folders (trickle-through).
- **PROPOSED constitutional amendment (his "maybe"):** **Simplicity** — one word, and the amendment defines it. Not minimalism: simplicity. The history machine (and Archivillus is a kind of history machine) takes all the legwork underneath to produce it — so simple it looks like magic; that's artistry. The Artist with a capital A doesn't really exist — a useful fiction, like the Author with a capital A (he liked the Author/writer distinction). In structure terms: no directory with a million files and subfolders; it stays clear and legible.
- **PROPOSED README convention:** the ASCII tree at the top of the repo README as a visual finding aid — in his exact terms, *findability and discoverability* (cf. the section on his website).

---

## 2026-09-27 — corrections round (his word; applied + staged)

- **Log voice rule (his correction, now standing):** novel logs — and logs generally — are written in the first person ("I"), never third person. First novel log rewritten accordingly.
- **No personal material in the novel repo (his rule, now standing):** his parents' deaths/grief never go in the experimental-novel repository — "it's not about me." Scrubbed from the novel log and from bible line 14. His personal writings (Hidden Stirrings / An Unseen Landscape, Solitude and Death, the Happiness and Death essays, the Book About Everything) live outside the repos and off GitHub — private, crypto-Kierkegaardian, like journals.
- **Kropotkin correction (his):** historiotherapy/historiotherapeusis is a NON-EXISTENT book by a FICTIONAL author — Dr. Viktor Kropotkin the character, not Peter Kropotkin. My "Peter Kropotkin" attribution was the error.
- **PARKED — books by fictional authors:** the error sparked the idea. Alphonse Lemoyne (the painter, "Painter A") has fictional novels inside the fictional novel; J.G. Dufray has a novel too — as appendices. There could be an appendix area for them. Parked for now.
- **Oulipo (F3): RESOLVED — kept.** He fell in love with the concepts (2026-09-27).
- **"Engines"** confirmed as his word for the text-manipulation programs (already the taxonomy's term).

---

## 2026-09-27 — identity architecture, conceptual personae, Living Repositories (staged)

- **Name corrections (his, emphatic — same tier as LOCKED TITLES):** Alphonse **Lemoyne** (not Lemoine); J.G. **Dufray** (not Dufresne). Fixed everywhere 2026-09-27.
- **Deleuze + Guattari, *What Is Philosophy?* — "Conceptual Personae" (a whole chapter).** PROPOSED REFMATS entry. His use: personae as useful fictions.
- **Identity architecture (his words):** antiface is a persona, a useful fiction. Alex Gagnon / A.G. is a real person. Everything else is imagined, fictional. The real identity is the anchor that keeps him grounded in reality when he gets lost in the fractal, recursive, hyperreflexive "Hall of Mirrors" of it all.
- **His biggest strength (his words):** he never loses operational continuity through all of this. (The rhyme: the Author loses it — that is why the Author needs Octavius Octavius IV.)
- **The framing (his words):** "a sacred journey in an enchanted universe"; the "Great Work" with "holy ambition."
- **Character-agents misquoting (craft principle, staged for the bible):** the fictional character-agents will quote him — or try — but mostly fail, misreading and misinterpreting him, the way his assistants do. The unreliability is diegetic: the misreading is the method.
- **Kierkegaard was himself Crypto-Kierkegaardian** — the deeper truth in all of this. The incorruptible "Source Code of The Soul" of the "Living Repositories," in a world that is a super-massive distributed version control system. (Upgrades "walking repositories.")
- **Phrase to remember (his words):** "The Heart Alone Knows Truth." "The Heart Alone" also meaning "Find Truth in Solitude."

---

## 2026-09-27 — repo scaffold decisions (his word)

- **DECIDED: `novels/`, not `projects/`**, for the per-novel folders.
- **Scaffolding principle (his, standing):** every folder gets a README.md or index.md — the precise, indefinitely extensible repository scaffolding, formalized from how his studio/lab is actually organized. The repo README carries the ASCII tree at the top as the visual finding aid (*findability and discoverability*).
- **Novel-log spec v1.0 created** (2026-09-27): inherits the studio-log spec v1.0; overrides = first-person voice, no-personal-material scope, REFMATS.md as the bibliography, reconstruction marking; additions = the trickle pipeline (log → theory → novels), the Interzone staging link. Lives in `novel-logs/` with its README.md.
