<!--
Dual License Structure:
Option 1: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
Option 2: Separate written permission for uses outside the public license.
Patent Clause: Patent rights reserved, no patent assertion without written grant.
No pricing/revenue/subscription terms in this document.
-->

# Torque — DOI / citation provenance audit

**This is a bibliographic-integrity note, not a technical claim about Torque itself.**
It records a real, unresolved conflict in how "Torque" has been cited across published
and companion material, so the conflict is visible and not silently carried forward into
anything new. Nothing here is protected content — DOIs and their public reference lists
are, by definition, public.

## The conflict

At least four distinct DOIs have been associated with "Torque" or an adjacent paper
across the material reviewed, and they do not agree with each other:

| DOI | What it's attached to, where | Formula / content |
|---|---|---|
| `10.5281/zenodo.17309731` | URA v1.5 paper ("Resilience and Recovery"), published Oct 10, 2025. Self-consistent — this paper doesn't claim any other paper's DOI. | Mechanical form: `τ = r·F·sin(θ)`. Threshold table published in-paper (not reproduced here — see note below). |
| `10.5281/zenodo.17373552` | Torque v2.0 paper ("Quantitative Foundation"), priority date Jan 15 2025, published Oct 15 2025. | Form: `τ = √(v²_drift + (1 − cos θ_align)²) · (1 − λ_damp)`. Threshold zones published in-paper. |
| `10.5281/zenodo.17379750` | **Conflicting attribution.** The v2.0 paper's own reference list cites this DOI as belonging to a *different* paper — "Universal Cognitive Architecture (UCA) v3.1." A separate public companion note ("Measuring AI System Stability in Real-Time") instead cites this same DOI as its *own* canonical Torque record, naming `torque-quantitative-foundation-v2.md` as the canonical paper while using this DOI for itself. Those two claims about what `17379750` actually is cannot both be right. |
| `10.5281/zenodo.17297590` | Cited elsewhere (a separate framework's paper, PME) as the DOI for "Torque." | Not independently confirmed against a Torque paper by this review. |

## Why this matters for CSFC

CSFC's own published material withholds Torque's formula and thresholds at the public
level (see `csfc-sub-hub-status.md`). That means CSFC readers who go looking for "the"
Torque paper via DOI have no single, uncontested citation to follow — they'll land on at
least two different formulas depending on which DOI they're handed, with a third DOI's
ownership itself in dispute. This repo is not the place to arbitrate which, if any, of
these DOIs is "correct" — that's a publication-record question for whoever holds the
Zenodo accounts, not something resolved by writing a stronger-sounding paragraph here.

## What this document deliberately does not do

- It does not reproduce either paper's threshold tables, internal formulas-as-authoritative,
  or validation datasets.
- It does not declare a winner between the mechanical form and the v2.0 form.
- It does not fold URA's Torque formula into CSFC content — see
  `csfc-sub-hub-status.md` § URA dependency list for why that stays separate.
- It does not treat the Torque v3 candidate (`torque-measurement-lens.md`) as a
  resolution to this conflict — it's a third, separately unstamped candidate, not an
  arbiter of the first two.

## Status

Open. This conflict has not been resolved by any reviewer to date. Anything published
later that cites a Torque DOI should be checked against this table first.
