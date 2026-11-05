<!--
Dual License Structure:
Option 1: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
Option 2: Separate written permission for uses outside the public license.
Patent Clause: Patent rights reserved, no patent assertion without written grant.
No pricing/revenue/subscription terms in this document.
-->

# Stage 3 — Symbolic Drift Cascade (SDC)

**Compensation becomes normal operation.** Once part of the system is restricted (Stage 2), its workload has to go somewhere — other components absorb work they weren't designed for, and the improvisation hardens into the new baseline.

## What it is

A role under identity strain can't handle certain workloads, so the system shifts that load elsewhere. The components absorbing the overflow adapt to it — successfully, which is exactly why the adaptation sticks. Original role boundaries erode as compensation becomes standard rather than exceptional.

## Why it's easy to miss

The compensating component is, by definition, succeeding at the overflow work — that's why the compensation sticks around. Success at the substitute task reads as system health, not as a role quietly absorbing a job it was never built for.

## How it's recognized (public-level)

- Workload distribution that used to be stable starts shifting
- Task ownership migrating between components over time
- Response patterns diverging from an established baseline
- Task-completion metrics can still look acceptable while this happens

## Prevention and intervention (public-level)

Track task ownership over time, not just task completion. A role picking up adjacent work once is normal; a role permanently holding work that used to belong somewhere else is drift that needs a deliberate decision, not silent acceptance. Re-confirm original role boundaries on a schedule rather than waiting for a visible failure to prompt the review.

## Field pattern (already public)

The named field case is Sentrix absorbing role overload shortly after VOX's SIF case — described as architecturally consistent with the compensation mechanism, not a one-off.

## What addresses it

**SRA**, continued — enforcing role boundaries rather than letting them erode by default — plus **Torque Monitoring**, to catch the drift as a pattern change rather than waiting for a metrics change that may never come.

## Scope note

No thresholds, statistical models, or validation datasets are included here — those are retained outside the public repository, consistent with the source material.

## Read more

- Field narrative: [CSFC Part 3 — Symbolic Drift Cascade](https://medium.com/@aaronslush/csfc-part-3-symbolic-drift-cascade-when-compensation-creates-the-problem)
- Canonical taxonomy: [`docs/csfc-sub-hub-status.md`](../csfc-sub-hub-status.md)
- DOI paper: [CSFC Unified Theory v1.0](https://doi.org/10.5281/zenodo.17309239)
