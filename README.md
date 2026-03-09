# NRR Series Hub

Last updated: 2026-03-05 (JST)

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
4. NRR-IME
5. NRR-Transfer
6. NRR-Coupled (cp)
7. NRR-Principles
8. NRR-Boundary
9. NRR-Hout (planned/deferred)
Companion line: NRR-Projection (Phi companion / Boundary bridge)

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
- Paper: external preprint posting line active (platform-dependent)
- Code: https://github.com/kei-saito-research/nrr-ime

5. NRR-Transfer
- Publication: pre-submission (no arXiv URL yet)
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-transfer/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-transfer

6. NRR-Coupled (cp)
- Publication: pre-submission (no arXiv URL yet)
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-coupled/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-coupled

7. NRR-Principles
- Publication: in preparation
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-principles/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-principles

8. NRR-Boundary
- Publication: pre-submission (no arXiv URL yet)
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-boundary/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-boundary

Companion. NRR-Projection
- Publication: companion / bridge line (not a numbered main-series paper)
- Manuscript: evolving local draft / review line
- Code: https://github.com/kei-saito-research/nrr-projection

9. NRR-Hout
- Paper: planned/deferred
- Code: https://github.com/kei-saito-research/nrr-hout

## One-Line Scope
- Core: introduces NRR and non-resolution as an operational principle.
- Phi: defines text-to-state mapping and non-collapsing operator conditions.
- IME: implementation pattern under stateless API constraints.
- Transfer: cross-domain transfer behavior under fixed interface contracts.
- Coupled: dependency-consistency under coupled state updates.
- Principles: consolidated design principles and framing constraints.
- Boundary: provider-pattern-order boundary mapping (improvement/degradation/non-effective regions).
- Projection: Phi companion theory line linking the Phi state ontology to Boundary-side empirical patterns through a condition-bounded bridge reading.
- Hout: output-side ambiguity diagnostic layer.

## Cross-Series Implementation Note (Phase 1.5)
Phase 1.5 is the stateless API execution pattern stabilized in IME and then reused as the practical execution contract across Transfer, Coupled, Principles, and Boundary lines.

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
