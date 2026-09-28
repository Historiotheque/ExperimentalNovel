# Interzone

*Staging buffer for* The Revolt of Fiction. *New ideas land here first; the story bible changes only in batches.*

## The protocol

1. Between writing sessions, new ideas, corrections, character notes, and fragments are staged here as dated, timestamped entries. The story bible is **not** touched for each one.
2. When a critical mass accumulates — or I ask — a new bible version is cut: staged entries get folded into the bible, marked **[FOLDED → bible vX.Y, date]** below, and the bible version bumps.
3. The bible keeps its stable filename (`revolt-of-fiction_series-bible_2026-09-26.md`); this file is the audit trail of what went in and when. Folded entries stay in place, marked folded — no backfilling, no silent rewrites.
4. Anything destined for the public novel repository gets the strict public-file treatment at publish time (no AI mention, no personal material, my words only).
5. Timestamps (my rule, 2026-09-27): every entry carries date + time (EDT), so same-day entries stay in order. Timestamps begin 2026-09-27; earlier entries are date-only — times unrecoverable.

*Cleanup 2026-09-27 ~17:35 EDT (my instruction): voice corrected to first person throughout — I am the solo author; there is no other person. A reader's handle removed (no consent to name). Timestamps added where recoverable from the chat records; 2026-09-26 entries stay date-only. This polishes the working copy, not the record — the audit trail lives in the commit history.*

Current bible: **v1.0** (proposed 2026-09-26).

## Staging area

### 2026-09-26 (time unknown) — staged, awaiting my word

- [STAGED] **Novel-documents spec.** A spec for my experimental-novel documents (bible, interzone/novel logs, fragments) mirroring the scaffolding of my other repositories. Covers versioning and cross-repo interlinking. Not drafted yet — my final decision required.
- [STAGED] **Repo interlinking architecture (hub-and-spoke).** The Historiotheque repository at the center — the source: source code, specs, logs. Dispatches/distributes outward to satellite repositories (experimental-novel, refcards, …). Hyperlinks to the latest versions across repos (e.g., the novel docs link to the latest spec in the Historiotheque repo). I'll streamline this once I'm on GitHub Desktop.
- [STAGED] **Feature branches for the solo dev.** My question (2026-09-26): how to use feature branches intelligently as a one-person operation — the "incorruptible source" idea: main as NOUS-like (crystalline, append-only, never corrupted); branches as the contained workshop where experiments and failures happen safely; merges as the Archivillus moment (logged, amended, folded in). Answered in chat; a written procedure can be staged if I want it.
- [STAGED] **"Interzone" = confirmed Burroughs homage.** Verified 2026-09-26: the Tangier International Zone was real (1924–1956, internationally administered; Burroughs lived in Tangier 1954–58 and told Ginsberg in a letter that Interzone was a stand-in for it); the fictional Interzone is *Naked Lunch*'s + a 1989 Burroughs collection actually titled *Interzone*. No legal risk (words/titles aren't copyrightable); reads as lineage-claim, which the project already makes. Burroughs stole everything himself.

---

## Folded

- **2026-09-26 — v1.0 baseline.** Everything developed in the Sept 26 session: trilogy architecture, meta-answer, disintegration gradient, NOUS/ANTINOUS cosmology, Titivillus/Archivillus village opening, Elijah Sahid frame, Octavius Octavius IV (and his firing), full dramatis personae, per-novel theories, the Chronotopium, Invisible Forces on entropy, Archivillus-as-savior, the unreliable Author (capital A), Zola/Burroughs line, Kierkegaard's indirect method, discontinuity as method, abstract characterology, biblical typology, pure characters, life world, story-bible-as-NOUS. Folded directly; nothing was staged.

---

## 2026-09-27 (time unknown — morning session) — Illumination, historiophany, historiagogy (staged, pending my word)

- **Illumination (the concept):** my REFMATS term comes from Walter Benjamin's *profane illumination* — not a book, a concept from Benjamin's 1929 essay on Surrealism ("Surrealism: The Last Snapshot of the European Intelligentsia"). The essay made me understand Surrealism for the first time in 30 years. Profane illumination: the mysterious, eerie, almost *numinous* quality of ordinary things (my example: looking at a coffee cup) — distinctly NOT religious. *Profane.*
- **Historiophany** = what the whole project-of-projects is about. The historiophany of the first kind (2026-09-24, the Cézanne at the cemetery) belongs here.
- **Historiagogy** (historia + -gogy): the pedagogical edge. Like mystagogy (the teaching of the mysteries in religion), historiagogy is the teaching/leading of history. Historiagogy + historiophany — that's what it's all about.
- **Walking repositories:** realized on a walk 2026-09-26 — we are like walking repositories; the world is built like a distributed version control system.
- **The aha-moment doctrine (indirect communication):** the reader has a realization while reading, puts the book down, and goes on with their life. In a sense I am writing a book to NOT be read — I want an *interruption* in the reading. Not a rhetorical hook-technique; just telling the truth, indirectly.
- TO FOLD (when I say): a Benjamin entry in REFMATS anchoring "illuminated" to profane illumination; historiophany/historiagogy in the series bible; the aha-interruption doctrine in the bible's reader's-contract section.

---

## 2026-09-27 (time unknown — morning session) — experimental-novel repo folder proposal (staged, to build tomorrow)

Proposed tree (PowerShell-style), aligned with github-repo-structure-spec v1.0 §4 (project repo template):
README, REFMATS.md (plays the spec's BIBLIOGRAPHY.md role — my word wins), series bible,
constitution, interzone, novel-logs/ (studio-log spec), theory/ (long-form),
novels/ with one folder per novel (history-project, archives-project, chronotopium, exhibition),
src/ for the text-engine / vol. 3 philosophical software.
OPEN: novels/ vs projects/ for the per-novel folders — my word tomorrow. Nothing created yet.

---

## 2026-09-27 ~15:58 EDT — first novel log written; two staged proposals (pending my word)

- **Novel log #1** written (reconstructed, covers 2026-09-20 → 2026-09-27): `novel-logs/2026-09-27-0010-first-novel-log.md`. Mirrors the studio-log spec. The pipeline: novel log → theory backup → novels folders (trickle-through).
- **PROPOSED constitutional amendment (my "maybe"):** **Simplicity** — one word, and the amendment defines it. Not minimalism: simplicity. The history machine (and Archivillus is a kind of history machine) takes all the legwork underneath to produce it — so simple it looks like magic; that's artistry. The Artist with a capital A doesn't really exist — a useful fiction, like the Author with a capital A. In structure terms: no directory with a million files and subfolders; it stays clear and legible.
- **PROPOSED README convention:** the ASCII tree at the top of the repo README as a visual finding aid — *findability and discoverability*, my exact terms (cf. the section on my website).

---

## 2026-09-27 ~16:09 EDT — corrections round (my word; applied + staged)

- **Log voice rule (my correction, now standing):** novel logs — and logs generally — are written in the first person ("I"), never third person. First novel log rewritten accordingly.
- **No personal material in the novel repo (my rule, now standing):** my parents' deaths/grief never go in the experimental-novel repository — "it's not about me." Scrubbed from the novel log and from bible line 14. My personal writings (Hidden Stirrings / An Unseen Landscape, Solitude and Death, the Happiness and Death essays, the Book About Everything) live outside the repos and off GitHub — private, crypto-Kierkegaardian, like journals.
- **Kropotkin correction (mine):** historiotherapy/historiotherapeusis is a NON-EXISTENT book by a FICTIONAL author — Dr. Viktor Kropotkin the character, not Peter Kropotkin. The "Peter Kropotkin" attribution was the machine's error, not mine.
- **PARKED — books by fictional authors:** the error sparked the idea. Alphonse Lemoyne (the painter, "Painter A") has fictional novels inside the fictional novel; J.G. Dufray has a novel too — as appendices. There could be an appendix area for them. Parked for now.
- **Oulipo (F3): RESOLVED — kept.** I fell in love with the concepts (2026-09-27).
- **"Engines"** confirmed as my word for the text-manipulation programs (already the taxonomy's term).

---

## 2026-09-27 (time unknown) — identity architecture, conceptual personae, Living Repositories (staged)

- **Name corrections (mine, emphatic — same tier as LOCKED TITLES):** Alphonse **Lemoyne** (not Lemoine); J.G. **Dufray** (not Dufresne). Fixed everywhere 2026-09-27.
- **Deleuze + Guattari, *What Is Philosophy?* — "Conceptual Personae" (a whole chapter).** PROPOSED REFMATS entry. My use: personae as useful fictions.
- **Identity architecture (my words):** antiface is a persona, a useful fiction. Alex Gagnon / A.G. is a real person. Everything else is imagined, fictional. The real identity is the anchor that keeps me grounded in reality when I get lost in the fractal, recursive, hyperreflexive "Hall of Mirrors" of it all.
- **My biggest strength (my words):** I never lose operational continuity through all of this. (The rhyme: the Author loses it — that is why the Author needs Octavius Octavius IV.)
- **The framing (my words):** "a sacred journey in an enchanted universe"; the "Great Work" with "holy ambition."
- **Character-agents misquoting (craft principle, staged for the bible):** the fictional character-agents will quote me — or try — but mostly fail, misreading and misinterpreting me, the way my assistants do. The unreliability is diegetic: the misreading is the method.
- **Kierkegaard was himself Crypto-Kierkegaardian** — the deeper truth in all of this. The incorruptible "Source Code of The Soul" of the "Living Repositories," in a world that is a super-massive distributed version control system. (Upgrades "walking repositories.")
- **Phrase to remember (my words):** "The Heart Alone Knows Truth." "The Heart Alone" also meaning "Find Truth in Solitude."

---

## 2026-09-27 (time unknown) — repo scaffold decisions (my word)

- **DECIDED: `novels/`, not `projects/`**, for the per-novel folders.
- **Scaffolding principle (mine, standing):** every folder gets a README.md or index.md — the precise, indefinitely extensible repository scaffolding, formalized from how my studio/lab is actually organized. The repo README carries the ASCII tree at the top as the visual finding aid (*findability and discoverability*).
- **Novel-log spec v1.0 created** (2026-09-27): inherits the studio-log spec v1.0; overrides = first-person voice, no-personal-material scope, REFMATS.md as the bibliography, reconstruction marking; additions = the trickle pipeline (log → theory → novels), the Interzone staging link. Lives in `novel-logs/` with its README.md.

---

## 2026-09-27 ~16:01 EDT — release/versioning doctrine from reader feedback (staged)

- **A reader's rule (Bluesky, 2026-09-27; handle withheld — no consent to name):** version by *reader-visible state*, not file volume — freeze a release when a reader can cite a stable arrangement, deposit it with a changelog, keep experiments on a moving branch. The DOI names the citable object; repository history preserves becoming. Accepted — better than my "volume" remark, and I didn't have a good answer until it arrived.
- **The delta doctrine, short version:** my work exists in states; between states there are deltas (Δ). I can't cite a becoming — the release freezes a state and the DOI names it.
- **My release threshold:** no new release until there's a noticeable, discernible difference in the code base — then I cut it.
- **TO DO (mine):** review the constitution on versioning. The reader's rule is slated for the constitution, amended in batches per protocol — not yet.

---

## 2026-09-27 ~17:10 EDT — solo-dev posture + maintainability patterns (staged)

- **Solo-dev posture (mine, emphatic):** no forks, no pull requests, no feature branches from other people — I work the repository alone. The whole DevOps for the repos is my operation. Outside input (like the Bluesky exchange) arrives as *ideas*, which stage in the Interzone — never as code branches to merge.
- **The maintainability worry (mine):** the experimental-novel repo is growing fast; left unchecked it becomes large and unmaintainable. I'm going to survey the patterns, techniques, and methods that programmers — especially solo developers — use against exactly this: automating what's done manually, killing repeated manual work, keeping a growing codebase maintainable. Only the applicable ones come into the cultural DevOps. My framing: cultural software + cultural DevOps + the Interzone as the staging area.
- **Bluesky follow-up — RESOLVED (~17:20 EDT):** the commenter wrote **"an evolving literary system"** — my half-remembered "evolutionary textual systems" was my own transformation of that phrase, which is why no search of the records found it. Verified in-session 2026-09-27 via two bounded searches: **it is not an established term** — nobody owns it. Adjacent real fields: genetic criticism (studies drafts retrospectively, never versions a living work), the 2007 VERSIONS Project (version identification for papers), and the *Variants* journal article "Why Do Authors Produce Textual Variation on Purpose? Or, Why Publish a Text That Is Still Unfolding?" — staged as a tentative REFMATS entry (unread; no-unverified-sources rule stands). My sense was right: the exact practice — a living author running novels like versioned software with DOI-stamped releases — looks genuinely unclaimed. The reader's rule (version by reader-visible state) already staged above.
- **The purification doctrine (mine, 2026-09-27):** the repository must be *the source* — the source code of the original, purified down to its simplest atomic form. Atomic units (refcards, and other card-types carrying one atomic unit of knowledge) are the model: the repo as the pure, purified source of the work, in however many versions it takes. The Boy Scout rule is the mechanism: every time I touch a folder, I prune it a little — pruning toward the atomic.
- **Pattern candidates to explore (staged research list):** DRY / single source of truth; the rule of three (no abstraction until the pain repeats); automation over manual steps; the **Boy Scout rule** (leave the repo cleaner than I found it — my chosen maintenance discipline, the pruning mechanism); small frequent releases + changelog discipline; repo-splitting when one repo does too much (hub-and-spoke, already staged); checklists as CI gates; branches-as-workshops (already decided); consistent naming and scaffolding conventions.

---

## 2026-09-27 ~17:30 EDT — src mechanics, new novels, cognitive collapse, literate programming (staged)

- **The Schizobot warning (mine):** my Schizobot repository on my personal GitHub page is what I do NOT want the experimental-novel repo to become — very complex, doesn't always make sense. I wrote 50+ pages of code for Schizobot Lite with a machine intelligence and much of it is inscrutable now. The lesson: complexity without legibility is the failure mode. The experimental-novel repo gets pruned toward the atomic; Schizobot is the anti-pattern.
- **src/ mechanics:** the src folder will hold the text engines — the cut-up machine, Markov chains, and others. (New side chat "Text Engines" created 2026-09-27 for this.)
- **Novels to add:** The Nihilist; Pilgrim Bronze; the Exhibition (already in the scaffold — verify). And others to come. The novels/ folder grows by decision, not by accumulation.
- **Cognitive collapse (my term):** the work is metafiction; at higher orders of abstraction readers hit cognitive collapse — they can't make sense of it anymore, get frustrated and discouraged, and stop reading. Challenging is good; too challenging is a failure mode. So the narrative needs a simple story underneath the machinery — this is what the Simplicity amendment is for. The repo mirrors this: prune it down periodically; versions can scale up and scale down with my practice.
- **Interpretability:** like the interpretability/explainability problem in machine intelligence — in the repo it's not always clear why choices were made; some are quasi-autonomous. The novel-as-a-system is not about having a complex codebase; it's about telling a story using code.
- **Literate programming:** the experimental-novel repo will carry notebooks with working code — showing, e.g., a phenomenological ontology in Python classes, metaclasses, and data structures. Code and story in one document; the explanation IS the program.

---

## 2026-09-28 17:49 EDT — test suite for cultural software (staged, concept / future DC candidate)

- The idea (mine): the equivalent of a test suite — and of test-driven development (TDD) — for Cultural Software such as the experimental-novel repository.
- The first failed test already happened (2026-09-27): the README finding-aid tree didn't mirror the repo's actual structure (three root files missing; per-novel READMEs unlisted). "The finding aid mirrors reality" is an executable invariant — a test.
- Candidate invariants: the README tree matches the actual file listing; every folder carries a README.md or index.md; the strict public-file rules hold (no personal material, no AI mention, no local paths with usernames); file-naming conventions hold.
- The doctrine rhyme (my words — I called it "brilliant"): the checklist doctrine turned executable. My checklists are fast-and-frugal yes/no decision trees built for the operator; a test suite is the same trees, run by the machine. Fits the incorruptible-source doctrine (DC-2026-005): the main branch stays crystalline because the tests guard it.
- TO LOG: this development goes in the next studio log — I called it deep research; it must be documented, not forgotten.
- Status: concept staged; a full design concept to come. Not decided: which invariants, run by what, run when (pre-commit? pre-release?).

---

## 2026-09-28 18:30 EDT — repo surgery executed (record)

- I restructured `novels/` today around `the-revolt-of-fiction/`: the three trilogy novels moved inside, the series bible moved from the repo root into the series folder (root stays lean — more bibles will come), and `the-exhibition/` renamed `the-exhibition-in-tonal-cinema` (the book's actual title).
- I rewrote the root README as the experimental-novel laboratory: the implementation of the novel-as-a-system (DC-2026-004), the loop (design concept → text-engine → novel → log → revised concept), the facets, series bibles one per series.
- Committed and pushed via GitHub Desktop 2026-09-28. Nothing pending below was touched — this entry only records what changed.

---

## 2026-09-28 19:05 EDT — staged: stratigraphy + Crackland bible material

- **Staged for the bible/theory (the repo as a geological formation).** From my Dec 8, 2023 "Geology of the Workspace" article: the Geological Method treats the phenomenal world as sedimentary layers of geo-grammatical forms, built by accretion — and the true geology turned out to be the geology of my workspace. This is the deep logic of this repository's architecture: the Interzone stages accretions, the bible folds them in batches, oldest strata at the bottom, never rearranged. The law of superposition is the no-backfill rule, stated as geology. Candidate: the bible's theory section, or a design concept. Staged, not filed.
- **Staged for the next series-bible batch (Crackland).** "Crackland & The Crackland Journals" was the actual filename of some 400 pages I wrote on the computer — material never in the physical manuscript of The History-Project — and Crackland is fundamental to that novel's physical cosmology. Origin 2001–2004: the concept came from my own workspace methodology first; the fictional world came second. Fold into the bible's cosmology in the next batch — not written into the bible now.
- **Record:** novel log #2 (`novel-logs/2026-09-28-1900-second-novel-log.md`) written 2026-09-28, covering the repo surgery, the versioning doctrine, the test-suite concept, and the Geology material. Pending items below untouched.
