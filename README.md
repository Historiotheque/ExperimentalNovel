# The Experimental Novel 

(v1.0.0) [![DOI](https://zenodo.org/badge/1390198018.svg)](https://doi.org/10.5281/zenodo.22988145)
Cite this version (v2.0.0): [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23068669.svg)](https://doi.org/10.5281/zenodo.23068669)

The ExperimentalNovel repository is not a shelf of novels. It is an
experimental-novel laboratory — the implementation of the novel-as-a-system: a
complex dynamic system whose moving whole comprises the experimental novels
themselves, the process of writing them, the thinking about them, and the
instantiating of novelistic design concepts, plus experimental text-engines
(Python programs that perform operations on novelistic material). A research
workshop: research-as-workshop.

The loop: design concept → text-engine → novel → log → revised concept. This
repository simulates the novelistic process itself, not just its products.

This repository is the instantiation of DC-2026-004 (The ExperimentalNovel
Repository as a Complex Dynamic System), which implements DC-2026-001 (The
Novel-as-a-System). Design concepts live in the DesignConcepts repository;
per-novel concepts to come.

Status: scaffolding (2026-09-28) — structure build in progress.

## Finding aid

```
the-experimental-novel/
├── README.md
├── .zenodo.json
├── REFMATS.md
├── novel-as-a-system_abstract_2026-09-21.md
├── novel-as-a-system_abstract_v2_2026-09-21.md
├── text-engine_taxonomy_2026-09-21.md
├── constitution.md
├── interzone.md
├── novel-logs/
│   ├── README.md
│   ├── novel-log-spec_v1.0.md
│   └── 2026-09-27-0010-first-novel-log.md
├── theory/
│   ├── README.md
│   └── ...
├── novels/
│   ├── README.md
│   ├── the-revolt-of-fiction/
│   │   ├── README.md
│   │   ├── revolt-of-fiction_series-bible_2026-09-26.md
│   │   ├── the-history-project/
│   │   │   └── README.md
│   │   ├── the-archives-project/
│   │   │   └── README.md
│   │   └── the-chronotopium/
│   │       └── README.md
│   └── the-exhibition-in-tonal-cinema/
│       └── README.md
└── src/
    ├── README.md
    └── ...
```

Every folder carries a README.md or index.md — the finding aid extends
indefinitely, one folder at a time. *Findability and discoverability.*

## The facets

- `novels/` — the works, each a system in its own right: novel series and
  standalone novels, one folder each.
- `theory/` — the thinking about the novels, kept alongside them.
- `src/` + `text-engine_taxonomy_2026-09-21.md` — the computational organs:
  text-engines that operate on novelistic material.
- `novel-logs/` — the process record, one piece at a time (first person, on
  the record).
- `interzone.md` — the intake membrane: raw ideation stages here before
  anything reaches canonical text.
- Series bibles — one per series; the Revolt of Fiction's is the first:
  canonical text, changed only in batches folded from the Interzone.

The root-level documents are the general layer: the novel-as-a-system
abstracts and the text-engine taxonomy are about novelistic phenomenology
itself — the universal, not any one series.

## The Revolt of Fiction

The first work-level system under development here: the trilogy —

1. *The History-Project*
2. *The Archives-Project*
3. *The Chronotopium: A Story of Algorithmogenesis*

Named after the event: the fiction revolts — the characters put the Author on
trial; the created turns on the creator.

## Scope

This repository holds the work, not the life. No personal material goes here —
the novels are not about the author.
