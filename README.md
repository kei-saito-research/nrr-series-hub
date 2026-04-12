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
- NRR-IME
- Hidden-State Interface Reuse (`reuse`)
- NRR-Coupled
- NRR-Patterns
- NRR-Energy
- NRR-Guarantee

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
- Publication: currently on hold
- Code: https://github.com/kei-saito-research/nrr-ime

### Hidden-State Interface Reuse (`reuse`)
- Title: Cross-Task Parser/Update Reuse of a Fixed Hidden-State Operator-Target Interface on Stateless LLM APIs
- Publication: public repository
- Manuscript: available in repository (`manuscript/current`)
  https://github.com/kei-saito-research/hidden-state-interface-reuse/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/hidden-state-interface-reuse
- Related historical repository: https://github.com/kei-saito-research/nrr-transfer

### NRR-Coupled
- Publication: pre-submission supporting line
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-coupled/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-coupled

### NRR-Patterns
- Publication: public repository for the former standalone `Principles` / `Boundary` zone
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

## One-Line Scope
- Core: introduces NRR and non-resolution as an operational principle.
- Phi: defines text-to-state mapping and non-collapsing operator conditions.
- IME: implementation pattern under stateless API constraints.
- Hidden-State Interface Reuse: cross-task parser/update reuse of a fixed hidden-state operator-target interface under shared protocol conditions.
- Coupled: dependency-consistency under coupled state updates.
- NRR-Patterns: delayed-commitment pattern comparison with explicit provider-sensitive boundary-honesty reporting.
- Energy: downstream calibration and operating-regime line.
- Guarantee: closure and assurance line for commitment-control behavior.
- Projection: Phi companion theory line linking the Phi state ontology to `NRR-Patterns` and downstream `Energy` / `Guarantee` surfaces through a condition-bounded interpretive reading.
- PAG: bounded explicit-state-carrying line centered on the post-acceptance gap under a public release surface.

## Cross-Series Implementation Note
IME introduced the stateless API execution pattern that later appears again in
the standalone `reuse` line, Coupled, and `NRR-Patterns`.

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
