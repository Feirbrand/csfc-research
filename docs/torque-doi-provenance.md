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

**Canonical DOI authority — November 14, 2026:** The Published Papers Master Ledger assigns DOI 10.5281/zenodo.17379750 to *Torque v2.0: Quantitative Foundation for AI Resilience*. The conflicting attributions documented below are historical citation and provenance discrepancies, not competing canonical DOI ownership. This audit preserves those discrepancies without changing published manuscripts, reassigning other DOIs, or resolving separate formula-provenance and validation questions.

## The conflict

At least three distinct DOIs have been associated with "Torque" or an adjacent paper
within material in scope for this repo, and they do not agree with each other. (A
fourth is tracked in the operating-system repo's publication record instead — see
`synoeticos-public/README.md`'s correction-note stack.)

| DOI | What it's attached to, where | Formula / content |
|---|---|---|
| `10.5281/zenodo.17373552` | Torque v2.0 paper ("Quantitative Foundation"), priority date Jan 15 2025, published Oct 15 2025. | Form: `τ = √(v²_drift + (1 − cos θ_align)²) · (1 − λ_damp)`. Threshold zones published in-paper. |
| `10.5281/zenodo.17379750` | **Conflicting attribution.** The v2.0 paper's own reference list cites this DOI as belonging to a *different* paper — "Universal Cognitive Architecture (UCA) v3.1." A separate public companion note ("Measuring AI System Stability in Real-Time") instead cites this same DOI as its *own* canonical Torque record, naming `torque-quantitative-foundation-v2.md` as the canonical paper while using this DOI for itself. Those two claims about what `17379750` actually is cannot both be right. |
| `10.5281/zenodo.17297590` | Cited elsewhere (a separate framework's paper, PME) as the DOI for "Torque." | Not independently confirmed against a Torque paper by this review. |

## Why this matters for CSFC

CSFC's own published material withholds Torque's formula and thresholds at the public
level (see `csfc-sub-hub-status.md`). CSFC readers should follow the canonical DOI identified above; historical citations point to differing formulas and retain unresolved provenance discrepancies. This repo records historical citation discrepancies without reopening canonical DOI ownership or reassigning other DOIs.

## What this document deliberately does not do

- It does not reproduce either paper's threshold tables, internal formulas-as-authoritative,
  or validation datasets.
- It does not declare a winner between the mechanical form and the v2.0 form.
- It does not fold any out-of-scope paper's Torque formula into CSFC content — each stays in its own publication record.
- It does not treat the Torque v3 candidate (`torque-measurement-lens.md`) as a
  resolution to this conflict — it's a third, separately unstamped candidate, not an
  arbiter of the first two.

## Status

**Canonical DOI assignment:** Resolved in the Published Papers Master Ledger as of the November 14, 2026 Workbench reconciliation. **Historical cross-citation provenance:** Open for evidence reconciliation. Earlier citation conflicts remain documented above and do not reopen canonical ownership. Future explanatory citations follow the authoritative ledger; protected originals remain unchanged.
