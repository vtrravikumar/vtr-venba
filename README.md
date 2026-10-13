# Working Book Project

**Author:** V.T.R. Ravi Kumar  
**Working repository name:** `vtr-venba`  
**Final book title:** Undecided  
**Status:** Architecture approved; manuscript development in progress

## Purpose

This repository holds the manuscript and editorial documentation for an original bilingual literary work in Tamil and English, shaped by the discipline of traditional Tamil **குறள் வெண்பா (Kural Venba)**.

Tamil and English have equal literary standing in this project. Each central insight will be expressed in a Tamil composition and an English companion composition. The English is not merely a subordinate translation of the Tamil, nor is the Tamil merely a translation of English. The two versions should be faithful to a shared insight while using the expressive resources of their own languages.

This is not a translation of the Thirukkural and must not be presented as one. The work will explore human thought and experience across the modern period, with a broad horizon from 1900 to 2027. Its aim is to make the concerns of each chapter recognisable to readers with different lives, choices, relationships, and beliefs.

## Remote-only working agreement

**GitHub is the working environment for this project until the manuscript is final.**

- Work directly against files in this remote repository.
- Keep `manuscript.md` updated in the same change whenever any component manuscript or front/back matter changes; verify the master against the component files after updates.
- Do not create or maintain a local clone or local working copy during manuscript development.
- Create, update, and review project documents and manuscript files through GitHub.
- Commit meaningful changes and verify them by reading the files back from the remote repository.
- Keep the project focused on manuscript, research, and editorial work; do not introduce local build or publishing-engine work during this phase.
- Only consider a local pull/export when the manuscript is ready for final production through the VTR Press workflow, or if the author explicitly changes this agreement.

This is a project-specific exception to the local-repository workflow used for other projects.

## Fixed architecture

- **9 Parts**
- **72 Chapters** (8 per Part)
- **720 paired compositions** (10 pairs per Chapter)
- **720 Tamil verses + 720 English companion verses**

The first eight Parts follow a conceptual progression through eight-year life stages, from ages 0–8 through 57–64. Part IX moves beyond age-based stages into bliss, detachment, death, the unknown, and ultimate truth. These stages are a philosophical organising device, not a claim that every life follows the same path.

The approved chapter list and stage framework are documented in [the architecture](docs/architecture.md). The working scopes and insight seeds for all 72 Chapters are in the [Chapter Scope Register](docs/chapter-scope-register.md).

## Editorial commitments

- Treat Tamil and English as equal literary partners expressing a shared central insight.
- Keep every Chapter's central territory distinct; avoid repeating the same idea under different names.
- Make the work inclusive of varied life paths; marriage, parenthood, conventional careers, and any single worldview must not be assumed.
- Do not draft verses until the chapter territories and verse-level topic tracking are in place.
- Research traditional Tamil prosody and develop a separate, defensible compositional and evaluation method for the English verses. Do not assume a direct one-to-one mapping.
- Validate Tamil verses against the relevant Kural Venba rules, including asai, seer, thalai, line structure, and ending requirements, with specialist review where needed.
- Keep claims about formal compliance honest: unverified examples must never be labelled as metrically validated.

## Repository layout

- `docs/architecture.md` — approved Parts and Chapter structure.
- `docs/chapter-scope-register.md` — working scope statements and provisional insight seeds for all 72 Chapters.
- `docs/editorial-principles.md` — thematic, bilingual, linguistic, and validation principles.
- `manuscript.md` — **master production manuscript at the repository root**, combining metadata, front matter, all Parts, and back matter in reading order. Keep it synchronized with the component files.
- `assets/` — cover artwork and interior images referenced by the manuscript, with usage and production conventions documented in `assets/README.md`.
- `manuscript/front-matter.md` — editable source for metadata, copyright, dedication, prologue, epilogue, and author bio; placeholders remain where decisions are pending.
- `manuscript/front-matter/README.md` — front/back-matter workflow and publication checklist.
- `manuscript/parts/` — manuscript content organised by Part.

## Publishing

The manuscript is intended to follow the author's VTR Press workflow and conventions. PDF is the primary planned output; EPUB is optional. This repository contains book source material and editorial records, not the VTR Press publishing engine.

## Current next steps

1. Establish the front and back matter, leaving explicit placeholders for undecided publication details.
2. Research traditional Tamil Kural Venba and document a defensible, separate approach to English composition and prosodic evaluation.
3. Review the 72-Chapter scope register in batches and resolve any overlapping Chapter territories.
4. Draft and validate paired compositions incrementally, following the VTR Press manuscript syntax from the start.
5. Verify the generated table of contents and final PDF/optional EPUB before publication.

The final title and precise thesis remain open decisions.
