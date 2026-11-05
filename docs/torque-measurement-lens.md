<!--
Dual License Structure:
Option 1: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
Option 2: Separate written permission for uses outside the public license.
Patent Clause: Patent rights reserved, no patent assertion without written grant.
No pricing/revenue/subscription terms in this document.
-->

# Torque v3 — proposed measurement lens for CSFC (candidate, not canon)

**Status: proposed candidate. Not stamped. No DOI. Not implemented against a validated
dataset.** This document exists so CSFC's connection to Torque is named honestly, not so
a forward-research candidate can be read as an established part of CSFC. Nothing below is
a threshold, a detector, or production-ready code, and nothing here changes CSFC v1.0's
own scope (see `csfc-sub-hub-status.md`).

## Why this is here at all

CSFC's published material names Torque Monitoring as one of its four architectural fixes
(a stability lens for identity/capability/behavioral coherence over time) but publishes
no formula, threshold, or production range for it — that material is explicitly withheld
in the published series. Separately, at least two DOI'd papers define *different*
equations under the name "Torque," with a direct citation conflict between them (see
`torque-doi-provenance.md`). A third, forward-looking candidate — referred to here as
**Torque v3** — is in active multi-reviewer development as the next attempt to get this
right before anything is published or stamped. This document tracks that candidate's
actual state, not its hoped-for state.

## The v3 candidate shape

Three outputs, not one:

- `τ₃(t) = r(t)·F(t)·sin(θ(t))` — instantaneous/active twisting (the original mechanical
  form).
- `D(t) = (1 − cos(θ(t))) / 2` — monotonic alignment deviation. Added specifically to fix
  the mechanical form's blind spot: `sin(θ)` is non-monotonic past 90°, so a system that
  drifts further out of alignment can show a *falling* `τ₃` even though it's getting
  worse. `D` doesn't have that blind spot.
- `C₃(t) = (median(τ₃), MAD(τ₃), trend(τ₃))` over a trailing window — a temporal summary,
  not yet a validated clustering algorithm.

## A real mathematical finding, not a cosmetic one

`τ₃` and `D` are **not independent** — both are functions of the same `θ`. Using the
half-angle identity `D = sin²(θ/2)`:

```
τ₃ = 2·r·F·√(D·(1 − D))
```

This was found independently by one reviewer and re-derived independently a second time
(confirmed algebraically, not taken on trust). It matters because the candidate's design
intent was for `τ₃` and `D` to act as two independent corroborating signals. They can't,
on their own, since one is a deterministic function of the other once `r` and `F` are
fixed. A further implication worth flagging: if `r` and `F` vary slowly relative to `θ`,
their temporal summaries (`C₃`) would likely track each other too, not add independent
information — which would undercut using both in a clustering step without first
re-deriving what, if anything, each one is actually adding.

## Four-gate verification framework

Multiple independent reviewers converged on the same gating structure for any Torque
candidate, mechanical or v3. Passing one gate never auto-satisfies the next:

| Gate | What it requires | v3 candidate status |
|---|---|---|
| 1. Mathematical consistency | The formula is internally coherent and its stated properties actually hold. | Largely satisfied — domain issues (θ must be bounded/declared) identified and addressed. |
| 2. Specification completeness | `r`, `F`, `θ` are defined as actual, measurable observables — not placeholders. | **Not met.** |
| 3. Implementation verification | Tested code matches the specification. | **Not met** — existing code is an unguarded stub, not a tested implementation. |
| 4. Empirical validation | The measure correlates with real failure/recovery outcomes on real data. | **Not established.** |

Nothing in this repo represents gates 2–4 as satisfied. Any future document that claims
otherwise should be checked against this table before being trusted.

## What this is not

- Not a replacement for, or amendment to, anything published under CSFC v1.0.
- Not a source of thresholds, routing logic, or recovery dispatch — none exist yet at a
  reviewed, publishable level.
- Not URA content. URA's own, separately published mechanical Torque formula is a
  different, already-DOI'd object; see `torque-doi-provenance.md` for how it relates (and
  conflicts) with the other published Torque material.
- Not a clustering algorithm — `C₃` is a temporal-summary sketch, not a validated method.
