# Novel Log — Format Specification v1.0

*Inherited from the Historiotheque Studio Log Format Specification v1.0.
Drafted 2026-09-27 for The Experimental Novel.*

*The theory: the novelist documents in the light — continuously, publicly,
reproducibly. The logs are the ground truth; the theory documents and the
novels are built on top of them.*

---

## 1. What this spec is

This spec inherits the studio-log spec v1.0 in full — file conventions
(`§2`: one file per session, `YYYY-MM-DD-HHMM-<slug>.md`, 24h local time),
frontmatter ( `§3`: date, time_start, time_end, timezone, season, project,
stream, session_type, workspace, refcards, tags, related), and the fixed body
section order (`§4`: What I did / Decisions / Problems and friction / Ideas
and sketches / Research and references / Feedback and collaboration /
Reproducibility notes / Artifacts produced / Next actions).

What follows is only what the novel log **overrides or adds**. Where this
spec is silent, the studio-log spec governs.

## 2. Overrides

- **Location:** `novel-logs/` in the experimental-novel repository.
- **Voice:** first person — "I," never "he." The log is the author's own
  record. (Standing rule 2026-09-27.)
- **Scope:** no personal material. The novels are not about the author:
  parents' deaths, grief, and private life never go in this repository. The
  personal writings (Hidden Stirrings / An Unseen Landscape, Solitude and
  Death, the Happiness and Death essays, the Book About Everything) live
  outside the repos and off GitHub — private, crypto-Kierkegaardian.
  (Standing rule 2026-09-27.)
- **References:** cite from the repository's `REFMATS.md` (the illuminated
  bibliography), not a `BIBLIOGRAPHY.md`. The author's word wins over the
  spec's labels.
- **Stream:** almost always `text`. Kept as a field for the exceptions
  (read-aloud sessions, dictation).
- **Reconstruction:** a log reconstructed after the fact — from chat
  transcripts, memory logs, or other records — carries a reconstruction line
  at the top: date reconstructed + sources. Never backfill silently.

## 3. Additions

- **The trickle:** the novel log is the first stage of the pipeline. What the
  log records gets backed up by the theory (`../theory/`) and lands in the
  novels folders (`../novels/`). The log entry should name, in *Next actions*
  or *Ideas and sketches*, where each item is headed.
- **The Interzone:** new ideas may stage in `../interzone.md` as dated
  entries before they are folded into the bible or the theory. The log
  records the staging; it never replaces it.
- **Decisions and Next actions are mandatory** — a session with no decisions
  recorded is a session not yet understood. (Inherited from the studio-log
  spec, restated because it matters twice here.)

## 4. Seeding

1. This spec + the folder README — the map before the territory.
2. The first log (2026-09-27, reconstructed) — the exemplar.
3. Every session after: one file, in the first person, on the record.

---

*Parent spec: Historiotheque Studio Log Format Specification v1.0 ·
Citation standard: Chicago 17th · REFMATS.md is this repo's bibliography.*
