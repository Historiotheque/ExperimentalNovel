---
date: 2026-09-28
time_start: "09:00"
time_end: "19:00"
timezone: America/Toronto
season: autumn-of-joyful-being
project: [the-experimental-novel]
stream: [text]
session_type: discourse
workspace: historiotheque
tags: [revolt-of-fiction, repo-surgery, readme, versioning-doctrine, test-suite, geology-of-the-workspace, crackland, novelistic-phenomenology, life-problems]
---

# Novel Log — 2026-09-28: the repo surgery, the versioning doctrine, the Geology of the Workspace

*Written 2026-09-28 from the "The Experimental Novel" side-chat record
(2026-09-27 → 2026-09-28). First person, per the log voice rule.*

## What I did

**Repo surgery.** I restructured `novels/` around `the-revolt-of-fiction/`:
the three trilogy novels moved inside, the series bible moved from the repo
root into the series folder — the root stays lean, because more bibles are
coming, one per series. I renamed `the-exhibition/` to
`the-exhibition-in-tonal-cinema/`, the book's actual title ("The Exhibition"
is my colloquial name for it). I rewrote the root README as the laboratory:
the repository as an experimental-novel laboratory implementing the
novel-as-a-system (DC-2026-004) — the loop (design concept → text-engine →
novel → log → revised concept), the facets, series bibles one per series.
Committed and pushed via GitHub Desktop, 2026-09-28.

**The versioning doctrine.** A reader's feedback gave me the release rule I
didn't have: version by reader-visible state, not file volume — my work
exists in states, between states there are deltas (Δ), and a release freezes
a state. My release threshold: no new release until there's a noticeable,
discernible difference in the code base. Staged in the Interzone for the
constitution batch.

**The test-suite concept.** The checklist doctrine turned executable: the
README-tree bug was the first failed test ("the finding aid mirrors reality"
is an executable invariant). Staged in the Interzone as a future design
concept.

**The Geology of the Workspace.** I brought my December 8, 2023 article into
this repo's orbit. The Geological Method: the phenomenal world as sedimentary
layers, geo-grammatical forms, built by accretion — and the true geology
turned out to be the geology of my workspace. The art operator as land
surveyor. Crackland & The Crackland Journals: that was the actual filename of
some 400 pages I wrote on the computer — material that was never in the
physical manuscript of The History-Project — and Crackland is fundamental to
that novel's physical cosmology. The 2001–2004 concept came from my own
workspace methodology first; the fictional world came second.

## Decisions

- `novels/` is organized one folder per novel or series; series bibles live
  inside their series folder, never at the root. (Decided 2026-09-28.)
- The root README presents the repo as a laboratory, not a shelf.
  (Decided 2026-09-28.)
- The logs are the archives: nothing of my personal business goes in the
  logs. This is the records layer — it stays clean. This matters to me more
  than the novels rule. (Clarified 2026-09-28.)
- Novel-log-spec §2 (Scope) gets amended in the next batch to match the
  2026-09-28 Lifespace refinement: the boundary is not a ban — theory about
  subjectivity stays in; the logs carry no personal business.

## Problems and friction

- The README finding-aid tree didn't mirror the repo (three root files
  missing; per-novel READMEs unlisted). Fixed 2026-09-27; the bug became the
  first "failed test" of the test-suite concept.
- I cloned the repo before making deletions on the website, so the local
  clone was behind the remote — resolved by fetching before replacing the
  novels/ folder. Operator lesson, logged.

## Ideas and sketches

- **The repo is a geological formation.** The Geological Method is the deep
  logic of this repository's architecture: the Interzone stages accretions,
  the bible folds them in batches — sedimentary layers, oldest at the
  bottom, never rearranged. The law of superposition is the no-backfill
  rule, stated as geology. (Staged in the Interzone 2026-09-28.)
- **Novelistic phenomenology**, in my own published words: a phenomenology
  of the novel-writing itself — "the novel as it appears in the mind of the
  author." For each new novel I come up with its own physical cosmology:
  unique universes.
- **Personality as a subjective historical system** — the self-reflexive
  system that orders itself around chosen themes, projects itself in
  narrative form, and can suffer narrative failure — is the theoretical
  engine behind the projections. Crackland, St-Elsewhere, the Dream
  Assembly, the Exhibition in Tonal Cinema, NOUS, ANTINOUS, and the rest:
  mental projections of the geo-grammatical forms onto the inward plane.
  What enters the work enters modulated — transformed, never raw.
- **Life problems.** A novel as I conceive it can address life problems —
  addiction, mental illness, poverty are examples of the kind of thing a
  novelistic phenomenology can take on. Judged case by case; when the time
  comes, the reasoning gets published alongside. (My term going forward:
  life problems.) The repo currently holds no novel content.

## Research and references

- My own article, "The Geology of the Workspace" (Medium, Dec 8, 2023): the
  Geological Method, the workspace as 3D material memory / analog database,
  Crackland & The Crackland Journals, the art operator as land surveyor.
  Filed in my context; to be filed in the Workspace Theory side chat.
- REFMATS.md: the *Variants* "still unfolding" article entry remains
  tentative — citation incomplete, still to file.

## Feedback and collaboration

- The reader's rule (Bluesky, 2026-09-27): version by reader-visible state.
  Staged in the Interzone; the constitution gets amended in batches. A short
  reply was drafted; whether I posted it is unconfirmed.

## Reproducibility notes

- Repo surgery procedure (operator checklist): fetch/pull first when the
  website was touched after cloning → delete local `novels/` → extract the
  new folder in its place → replace root README → review the Changes list →
  commit → push.
- Everything changed on my side is enumerated in "What I did" above; the
  workspace master and the goal mirror were synced after.

## Artifacts produced

- `novels/` restructured (the-revolt-of-fiction/ series folder with the
  three novels + the series bible; the-exhibition-in-tonal-cinema/ renamed)
  — committed and pushed 2026-09-28.
- Root README rewritten as the laboratory — committed and pushed 2026-09-28.
- Commit message + summary delivered in chat and as a file backup.

## Next actions

- [ ] Amend novel-log-spec §2 (Scope) per the 2026-09-28 Lifespace
  refinement — batch with the constitution amendments (reader's rule,
  test-suite concept).
- [ ] The Crackland material (filename, ~400 pages, fundamental cosmology)
  is staged in the Interzone for the next series-bible batch — not written
  into the bible now.
- [ ] File the "still unfolding" *Variants* article entry in REFMATS.md when
  the citation is complete.
- [ ] Test-suite concept goes in the next studio log (flagged).
