# NRR Series Hub

Last updated: 2026-03-04 (JST)

Repository: https://github.com/kei-saito-research/nrr-series-hub

## What This Page Is
This page is a public-facing index for the Non-Resolution Reasoning (NRR) series.
It is designed to help readers quickly find paper/code repositories and reproducibility entry points.

## Core Position
NRR is not an anti-LLM framework.
NRR does not replace standard LLM use.
NRR optimizes when to commit and when to defer, under explicit conditions.

## Read Order
1. NRR-Core
2. NRR-Phi
3. NRR-IME
4. NRR-Transfer
5. NRR-Coupled (cp)
6. NRR-Principles
7. NRR-Boundary
8. NRR-Hout (planned/deferred)

## Papers and Repositories
1. NRR-Core
- Paper: https://arxiv.org/abs/2512.13478
- Code: https://github.com/kei-saito-research/nrr-core

2. NRR-Phi
- Paper: https://arxiv.org/abs/2601.19933
- Code: https://github.com/kei-saito-research/nrr-phi

3. NRR-IME
- Paper: under moderation (submitted 2026-02-10 EST)
- Code: https://github.com/kei-saito-research/nrr-ime

4. NRR-Transfer
- Publication: pre-submission (no arXiv URL yet)
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-transfer/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-transfer

5. NRR-Coupled (cp)
- Publication: pre-submission (no arXiv URL yet)
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-coupled/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-coupled

6. NRR-Principles
- Publication: in preparation
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-principles/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-principles

7. NRR-Boundary
- Publication: pre-submission (no arXiv URL yet)
- Manuscript: available in repository (`manuscript/current`)  
  https://github.com/kei-saito-research/nrr-boundary/tree/main/manuscript/current
- Code: https://github.com/kei-saito-research/nrr-boundary

8. NRR-Hout
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
- Hout: output-side ambiguity diagnostic layer.

## Cross-Series Implementation Note (Phase 1.5)
Phase 1.5 is the stateless API execution pattern stabilized in IME and then reused as the practical execution contract across Transfer, Coupled, Principles, and Boundary lines.

## Reproducibility Entry
For each line, see the repository `README.md` and `reproducibility.md` as first entry points.

## Notes on Claims
- Claims are condition-bounded.
- Gains and regressions are both reported.
- Boundary/failure regions are part of the result, not excluded exceptions.

## Contact
Kei Saito  
Email: kei.saito.research@gmail.com
