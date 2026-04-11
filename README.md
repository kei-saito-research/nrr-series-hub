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

## Series Numbering Policy
- `paper3` is permanently skipped and never reused.
- Active paper IDs are: `1, 2, 4, 5, 6, 7`.

## Read Order
1. NRR-Core
2. NRR-Phi
3. (intentionally skipped)
4. NRR-IME (currently on hold)
5. standalone `reuse` line (`paper5` slot; current submission line now on hold; historical `paper5-nrr-transfer-*` filenames retained for continuity)
6. NRR-Coupled (cp)
7. NRR-Patterns (integrated paper7 authority; historical `Principles` / `Boundary` continuity retained separately)
8. NRR-Energy (public pre-submission authority line)
9. NRR-Guarantee (public pre-submission authority line)
10. NRR-Hout (planned/deferred)
Companion line: NRR-Projection (public Phi companion / interpretive bridge to `NRR-Patterns` and downstream `Energy` / `Guarantee` surfaces)

## Papers and Repositories
1. NRR-Core
- Paper: https://arxiv.org/abs/2512.13478
- Code: https://github.com/kei-saito-research/nrr-core

2. NRR-Phi
- Paper: https://arxiv.org/abs/2601.19933
- Code: https://github.com/kei-saito-research/nrr-phi

3. (intentionally skipped)
- No paper is assigned to `paper3`.

4. NRR-IME
- Publication: currently on hold after arXiv rejection
- Code: https://github.com/kei-saito-research/nrr-ime

5. standalone `reuse` line (`paper5` slot)
- Title: Cross-Task Parser/Update Reuse of a Fixed Hidden-State Operator-Target Interface on Stateless LLM APIs
- Publication: reconstructed standalone submission line; current submission handling is on hold
- Manuscript: available in repository (`manuscript/current`)
  https://github.com/kei-saito-research/hidden-state-interface-reuse/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/hidden-state-interface-reuse
- Historical continuity repository: https://github.com/kei-saito-research/nrr-transfer

6. NRR-Coupled (cp)
- Publication: pre-submission supporting line
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-coupled/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-coupled

7. NRR-Patterns
- Publication: public repository (pre-submission authority line for the former standalone `Principles` / `Boundary` zone)
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-patterns/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-patterns
- Historical continuity repositories:
  - https://github.com/kei-saito-research/nrr-principles
  - https://github.com/kei-saito-research/nrr-boundary

8. NRR-Energy
- Publication: public pre-submission calibration / operational-control line
- Manuscript: available in repository (`manuscript/current`)
  https://github.com/kei-saito-research/nrr-energy/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-energy

9. NRR-Guarantee
- Publication: public pre-submission bounded verification / assurance line
- Manuscript: available in repository (`manuscript/current`)
  https://github.com/kei-saito-research/nrr-guarantee/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-guarantee

Companion. NRR-Projection
- Publication: public repository (pre-submission companion theory line; not a numbered main-series paper)
- Manuscript: available in repository (`manuscript/current`)
  https://github.com/kei-saito-research/nrr-projection/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-projection

10. NRR-Hout
- Paper: planned/deferred
- Code: https://github.com/kei-saito-research/nrr-hout

## One-Line Scope
- Core: introduces NRR and non-resolution as an operational principle.
- Phi: defines text-to-state mapping and non-collapsing operator conditions.
- IME: implementation pattern under stateless API constraints; currently held rather than being accelerated as the next standalone public line.
- reuse (`paper5` slot): cross-task parser/update reuse of a fixed hidden-state operator-target interface under shared protocol conditions.
- Coupled: dependency-consistency under coupled state updates.
- NRR-Patterns: delayed-commitment pattern comparison with explicit provider-sensitive boundary-honesty reporting.
- Energy: downstream calibration and operating-regime line.
- Guarantee: closure and assurance line for commitment-control behavior.
- Projection: Phi companion theory line linking the Phi state ontology to `NRR-Patterns` and downstream `Energy` / `Guarantee` surfaces through a condition-bounded interpretive reading.
- Hout: output-side ambiguity diagnostic layer.

## Cross-Series Implementation Note (Phase 1.5)
Phase 1.5 is the stateless API execution pattern stabilized in IME and then reused as the practical execution contract across the standalone `reuse` line, Coupled, and the `NRR-Patterns` line.

## Current Handling Note
- The current authoritative `paper5` line is the standalone `reuse` line, not the older public `nrr-transfer` repository label.
- The current standalone `reuse` submission handling is on hold while that line remains the active `paper5` authority surface.
- If the standalone `reuse` line is later accepted, `IME` content is expected to be reconsidered there rather than accelerated first as a separate current submission line.
- If the line instead moves to TechRxiv, whether `IME` stays separate or is merged remains intentionally unresolved.
- `NRR-Patterns` is the current public authority for the former standalone `Principles` / `Boundary` zone.
- `NRR-Projection` is now public as its own pre-submission companion repo.
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
