# Text-Engine Taxonomy — for The Experimental Novel

*Schema v1.0 — 2026-09-21. Companion to the novel-as-a-system abstract.*

## Design constraints (standing)

- **Language:** Python 3, intermediate level. Only basic functions and the standard library (`random`, `re`, `collections`, `itertools`, `pathlib`, `json`, `textwrap`, `argparse`) — the kind of code any intermediate Python programmer reads at sight.
- **One exception:** `markovify` — the single permitted specialized library, for Markov-chain text generation.
- **One interface:** a single menu-driven program (`novel_engine.py`) that exposes every family below. No scattered scripts; one laboratory, many instruments.
- **Corpora:** plain `.txt` / `.md` files in a `corpora/` folder (his own drafts, public-domain texts, outlines). Every operation reads from and writes to timestamped files in `output/`, and every run appends to a session log — the engine documents itself (cf. the Switchboard Method's self-archiving doctrine).
- **No frameworks, no APIs, no network.** The engine must run on a bare machine, forever.

## The six families

### F1. Fragmentation & Reassembly — the Cut-Up Engine

The founding instrument. Text is treated as physical material: sliced, shuffled, recombined.

- **F1.1 Classic cut-up** — split a source into fragments (by sentence, clause, line, or N-word window), shuffle with a seed, reassemble. Seeded runs are reproducible; unseeded runs are oracles.
- **F1.2 Fold-in** — Burroughs/Gysin's signature move: interleave two texts line-by-line or sentence-by-sentence (page A folded into page B). Two voices occupying one page.
- **F1.3 Collage weaver** — N sources, weighted. The engine draws fragments from each source by weight (e.g. 50% draft, 30% public-domain, 20% outline) and weaves a composite.
- **F1.4 Permuter** — keep every fragment, change only the order: paragraph shuffles, reverse-order, "every third sentence first." Non-linear narrative scaffolding.
- **F1.5 Slot recombination** — Queneau-style: parallel texts with aligned slots (10 sonnets × 14 lines); the engine picks one line per slot. *A Hundred Thousand Billion Poems* as a function.

*Use in the work:* drafting prophetic/strange passages (as in the late-1990s cut-up novel); generating the Nihilist's paradoxical utterances; breaking a stuck chapter.

### F2. Probabilistic Generation — the Markov Atelier

Text that sounds human because it *was* human, recombined probabilistically.

- **F2.1 Markov generator** (`markovify`) — train on a corpus, generate sentences/paragraphs. Controls: state size (1 = dreamlike, 2 = balanced, 3+ = near-quotation), output length, seed.
- **F2.2 Model mixer** — combine two or three trained models with weights (e.g. his draft × Dostoevsky × the outline) and generate from the blend. Voice grafting.
- **F2.3 Seeded oracle** — generate from a starting word/phrase; the engine completes the thought the corpus "would have had."
- **F2.4 Dialogue engine** — two models in conversation, alternating turns (Socrates/Nihilist, Ameinias/Nikēlēs). Each turn seeded by the previous turn's keywords. A dialectic machine.
- **F2.5 Character voice models** — one model per recurring figure; generate "what would X say about Y" by seeding with Y.

*Use in the work:* the Nihilist's sermons, crowd scenes, dreams; testing whether a voice is consistent enough to survive recombination.

### F3. Constraint & Formal Play — the Oulipo Bench

Meaning under artificial pressure. Constraints are treated as *phenomenological reductions*: they strip habit and reveal structure.

- **F3.1 Lipogram** — regenerate/filter text avoiding a given letter (or keeping only sentences that avoid it).
- **F3.2 Univocalism** — keep only words containing a single vowel.
- **F3.3 N+7** — replace each noun with the 7th following noun in a local wordlist (stdlib only: ship a `wordlist.txt`).
- **F3.4 Snowball** — build/grow sentences where each word is one letter longer than the last.
- **F3.5 Acrostic / telestich / mesostic** — select or generate lines whose first/last/middle letters spell a word.
- **F3.6 Palindrome & reversal tools** — reverse words, sentences, whole texts; find accidental palindromes in a corpus.

*Use in the work:* ritual/formal passages; the degrading editor's glitching diction; exercises in "writing against the hand."

### F4. Erosion & Noise — the Decay Lab

Text subjected to time, censorship, and transmission loss. The glitch-bound threshold (cf. the Manifesto of Latent Realism) as a writing instrument.

- **F4.1 Erasure / blackout** — keep a random or rule-based X% of words; redact the rest (█ blocks or removal). Two modes: chance erasure, and "keep only" erasure (nouns only, verbs only, words over 6 letters…).
- **F4.2 Character decay** — simulate manuscript rot: random character swaps, deletions, substitutions at a set rate; multi-pass decay shows a text aging.
- **F4.3 Semantic drift loop** — apply synonym substitution (local thesaurus file) repeatedly; watch meaning walk away from itself over N generations. A telephone game with no players.
- **F4.4 Censorship engine** — redact by pattern: names, numbers, words from a ban-list; produce the "found manuscript with missing passages" effect (cf. The Nihilist's degrading editor).

*Use in the work:* the found-manuscript frame; Part II's degrading agents; poems of attrition.

### F5. Analysis & Measurement — the Observatory

The engine studies texts before (and after) operating on them. Research instruments, not generators.

- **F5.1 Frequency & n-grams** — word counts, bigrams/trigrams, hapax legomena (words used once).
- **F5.2 KWIC concordance** — keyword-in-context: every occurrence of a word with its surrounding line.
- **F5.3 Type-token ratio & length profiles** — vocabulary richness, sentence-length distribution, a "fingerprint" of a voice.
- **F5.4 Overlap comparator** — shared vs. distinctive vocabulary between two texts (draft vs. influence, Part I vs. Part II).
- **F5.5 Repetition finder** — locate unintentional repetitions across a manuscript (continuity bible assistant).

*Use in the work:* checking that the Nihilist's voice stays distinct from the narrator's; mapping an influence's actual (not imagined) footprint.

### F6. Architecture & Scaffolding — the Drafting Table

Large-structure tools: the engine as composition assistant.

- **F6.1 Beat-sheet expander** — take an outline's beats and interleave generated/cut-up filler between them; a chapter skeleton with flesh started.
- **F6.2 Scene shuffler** — reorder scenes by arc, by intensity curve, or by chance; non-linear assembly.
- **F6.3 Anachronism blender** — interleave era-tagged corpora (e.g. 399 BCE diction × contemporary diction) for the historical episodes' double-voiced narration.
- **F6.4 Chapter assembler** — concatenate section files in a chosen order with separators and running headers; builds the manuscript file from parts.

## The single interface — architecture sketch

```
novel_engine/
├── novel_engine.py      # the one program: text menu, routes to families
├── corpora/             # source texts (.txt/.md) — the engine's library
├── output/              # timestamped results, never overwritten
├── lib/
│   ├── f1_cutup.py      # Fragmentation & Reassembly
│   ├── f2_markov.py     # Probabilistic Generation (imports markovify)
│   ├── f3_oulipo.py     # Constraint & Formal Play
│   ├── f4_decay.py      # Erosion & Noise
│   ├── f5_analysis.py   # Analysis & Measurement
│   ├── f6_drafting.py   # Architecture & Scaffolding
│   └── common.py        # corpus loading, seeding, logging, file I/O
└── session.log          # every run recorded: self-archiving engine
```

- `novel_engine.py` prints a numbered menu (families → operations → prompts for corpus, parameters, seed), runs the chosen operation, saves output, logs the run. Pure `input()`/`print()` — no GUI framework, runs anywhere.
- Each `fN_*.py` module exposes functions with plain signatures (`cut_up(text, frag="sentence", seed=None)`), so they are usable both from the menu and interactively.
- `markovify` is imported inside `f2_markov.py` only, guarded by try/except: the rest of the engine runs fine without it.

## Build order (proposed)

1. `common.py` + menu skeleton + `corpora/` conventions (the foundation).
2. F1 cut-up engine (the founding instrument; his 1990s practice, modernized).
3. F2 Markov atelier (the voice work).
4. F5 observatory (so the generators can be measured).
5. F4 decay lab, F3 Oulipo bench, F6 drafting table (in whatever order the work demands).

*Next step: say the word and I build module 1 + the menu skeleton, then we proceed family by family, testing each against real corpora (e.g. The Nihilist drafts) as we go.*
