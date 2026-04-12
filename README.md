# NRR Series Hub

Last updated: 2026-04-11 (JST)

Repository: https://github.com/kei-saito-research/nrr-series-hub
Maintainer profile: https://github.com/kei-saito-research

## What This Page Is
This page is a public-facing index for the Non-Resolution Reasoning (NRR) series.
It is designed to help readers quickly find paper/code repositories and reproducibility entry points.

## Core Position
NRR is not an anti-LLM framework.
NRR does not replace standard LLM use.
NRR optimizes when to commit and when to defer, under explicit conditions.

## Naming Note
- Public naming follows repository and manuscript titles rather than older internal labels.
- Some current public artifacts still retain historical filename stems for continuity; read the repository title and README as the current public naming.
- Where older `paper*` labels remain inside fixed filenames or cited snapshots, treat them as historical snapshot identifiers only, not as current public numbering.

## Current Public Spine
- NRR-Core
- NRR-Phi
- NRR-IME (currently on hold)
- Hidden-State Interface Reuse (`reuse`; current submission handling is on hold)
- NRR-Coupled
- NRR-Patterns
- NRR-Energy
- NRR-Guarantee
- NRR-Hout (planned/deferred)

## Companion And Adjacent Public Lines
- NRR-Projection
- Post-Acceptance Gap (PAG)

## Papers and Repositories
### NRR-Core
- Paper: https://arxiv.org/abs/2512.13478
- Code: https://github.com/kei-saito-research/nrr-core

### NRR-Phi
- Paper: https://arxiv.org/abs/2601.19933
- Code: https://github.com/kei-saito-research/nrr-phi

### NRR-IME
- Publication: currently on hold after arXiv rejection
- Code: https://github.com/kei-saito-research/nrr-ime

### Hidden-State Interface Reuse (`reuse`)
- Title: Cross-Task Parser/Update Reuse of a Fixed Hidden-State Operator-Target Interface on Stateless LLM APIs
- Publication: reconstructed standalone submission line; current submission handling is on hold
- Manuscript: available in repository (`manuscript/current`)
  https://github.com/kei-saito-research/hidden-state-interface-reuse/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/hidden-state-interface-reuse
- Historical continuity repository: https://github.com/kei-saito-research/nrr-transfer

### NRR-Coupled
- Publication: pre-submission supporting line
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-coupled/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-coupled

### NRR-Patterns
- Publication: public repository (pre-submission authority line for the former standalone `Principles` / `Boundary` zone)
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-patterns/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-patterns
- Public archive repositories:
  - https://github.com/kei-saito-research/nrr-principles
  - https://github.com/kei-saito-research/nrr-boundary

### NRR-Energy
- Publication: public pre-submission calibration / operational-control line
- Manuscript: available in repository (`manuscript/current`)
  https://github.com/kei-saito-research/nrr-energy/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-energy

### NRR-Guarantee
- Publication: public pre-submission bounded verification / assurance line
- Manuscript: available in repository (`manuscript/current`)
  https://github.com/kei-saito-research/nrr-guarantee/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-guarantee

### NRR-Projection
- Publication: public repository (pre-submission companion theory line; not a numbered main-series paper)
- Manuscript: available in repository (`manuscript/current`)
  https://github.com/kei-saito-research/nrr-projection/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-projection

### Post-Acceptance Gap (PAG)
- Publication: public repository (bounded explicit-state-carrying release surface)
- Manuscript: available in repository (`manuscript/current`)
  https://github.com/kei-saito-research/post-acceptance-gap/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/post-acceptance-gap

### NRR-Hout
- Paper: planned/deferred
- Code: https://github.com/kei-saito-research/nrr-hout

## One-Line Scope
- Core: introduces NRR and non-resolution as an operational principle.
- Phi: defines text-to-state mapping and non-collapsing operator conditions.
- IME: implementation pattern under stateless API constraints; currently held rather than being accelerated as the next standalone public line.
- Hidden-State Interface Reuse: cross-task parser/update reuse of a fixed hidden-state operator-target interface under shared protocol conditions.
- Coupled: dependency-consistency under coupled state updates.
- NRR-Patterns: delayed-commitment pattern comparison with explicit provider-sensitive boundary-honesty reporting.
- Energy: downstream calibration and operating-regime line.
- Guarantee: closure and assurance line for commitment-control behavior.
- Projection: Phi companion theory line linking the Phi state ontology to `NRR-Patterns` and downstream `Energy` / `Guarantee` surfaces through a condition-bounded interpretive reading.
- PAG: bounded explicit-state-carrying line centered on the post-acceptance gap under a public release surface.
- Hout: output-side ambiguity diagnostic layer.

## Cross-Series Implementation Note (Phase 1.5)
Phase 1.5 is the stateless API execution pattern stabilized in IME and then reused as the practical execution contract across the standalone `reuse` line, Coupled, and the `NRR-Patterns` line.

## Current Handling Note
- The current authoritative standalone `reuse` line is `hidden-state-interface-reuse`, not the older public `nrr-transfer` repository label.
- The current standalone `reuse` submission handling is on hold while that line remains the active authority surface for that paper family.
- If the standalone `reuse` line is later accepted, `IME` content is expected to be reconsidered there rather than accelerated first as a separate current submission line.
- If the line instead moves to TechRxiv, whether `IME` stays separate or is merged remains intentionally unresolved.
- `NRR-Patterns` is the current public authority for the former standalone `Principles` / `Boundary` zone.
- `nrr-principles` and `nrr-boundary` should be read as public archive repos for that older zone, not as competing current authorities.
- `NRR-Projection` is now public as its own pre-submission companion repo.
- `post-acceptance-gap` is now public as its own bounded release-surface repo.
- `Energy` is now public as its own pre-submission authority repo.
- `Guarantee` is now public as its own pre-submission authority repo.

## Reproducibility Entry
For each line, see the repository `README.md` and `reproducibility.md` as first entry points.

## DOI / Archive
For citation-ready archived versions, use the DOI/Zenodo links listed in each paper repository README.

## Notes on Claims
- Claims are condition-bounded.
- Gains and regressions are both reported.
- Boundary/failure regions are part of the result, not excluded exceptions.

## Contact
Kei Saito  
Email: kei.saito.research@gmail.com
