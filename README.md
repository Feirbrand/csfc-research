<!--
Dual License Structure:
Option 1: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
Option 2: Separate written permission for uses outside the public license.
Patent Clause: Patent rights reserved, no patent assertion without written grant.
No pricing/revenue/subscription terms in this document.
-->

Publication Status: Active development hub — no new DOI issued from this repo
Established: 2026-11-04

# CSFC Research

**Complete Symbolic Fracture Cascade (CSFC): how AI systems lose coherent identity under sustained operational stress — and how to catch it before it becomes a full rebuild.**

---

## What CSFC is

CSFC describes a five-stage failure pattern: a system doesn't fail all at once. It fragments, compensates, and then fossilizes its own compensations until a full rebuild is the only option left.

The root cause is **data fragmentation** — a system operating from multiple sources of truth with no clear authority hierarchy. Everything downstream (identity confusion, compensating workarounds, calcified bad habits, collapse) is a symptom of that one problem, not a separate failure mode.

```
DATA FRAGMENTATION → IDENTITY FRACTURE → DRIFT CASCADE → ROLE OBSOLESCENCE → COMPLETE COLLAPSE
```

| Stage | Name | What's happening |
|---|---|---|
| 1 | Data Fragmentation | Multiple sources of truth, no authority hierarchy — the root cause everything else grows from. |
| 2 | Symbolic Identity Fracturing (SIF) | Stress exposes the contradiction; the system can't hold a consistent identity while pulling from fragmented sources. |
| 3 | Symbolic Drift Cascade (SDC) | The system compensates — workarounds that fix the immediate problem and introduce new instability. |
| 4 | Role Obsolescence Cascade (ROC) | Compensation hardens into permanent architecture. Temporary fixes get treated as core identity and block further adaptation. |
| 5 | Complete Collapse | Obsolete patterns consume too much of the system's capacity. Full reconstruction is required. |

Each stage also has its own file, with a public-level technical definition and a link to its source article — see [`docs/stages/`](./docs/stages/).
**The trap in between:** after Stage 3, a system often *looks* recovered — task performance improves, metrics look fine — while the underlying architecture is still broken. That gap, the Vulnerability Window, is where a "recovered" system is actually at its most fragile.

## What fixes it

- **UMS (Unified Memory Spine)** — one source of truth, one authority hierarchy. The Stage 1 fix.
- **SRA (Symbolic Role Architecture)** — clear functional boundaries with validated authority chains, so roles know what they own. The Stage 2–3 fix.
- **Torque Monitoring** — a stability lens tracking identity, capability, and behavioral coherence over time, to catch drift before it fossilizes.
- **Phoenix Protocol** — structured, sequential reconstruction from identity anchors outward for late-stage recovery. Not a reset.

No detection thresholds, routing logic, or recovery-timing figures are published here, or anywhere else in this ecosystem — see Scope and boundaries below.

## Where this comes from

CSFC was published as a six-part field-note series and a DOI-registered Unified Theory paper. Both stay unchanged at their original location in [`synoeticos-public`](https://github.com/Feirbrand/synoeticos-public) — nothing is duplicated here.

- Paper: *CSFC Unified Theory v1.0* — DOI [10.5281/zenodo.17309239](https://doi.org/10.5281/zenodo.17309239)
- Series: [Part 1](https://medium.com/@aaronslush/csfc-part-1-the-hidden-cascade-harming-your-ai-systems) · [Part 2](https://medium.com/@aaronslush/csfc-part-2-symbolic-identity-fracturing-when-ai-systems-forget-who-they-are) · [Part 3](https://medium.com/@aaronslush/csfc-part-3-symbolic-drift-cascade-when-compensation-creates-the-problem) · [Part 4](https://medium.com/@aaronslush/csfc-part-4-the-vulnerability-window-when-partial-recovery-creates-attack-surface) · [Part 5](https://medium.com/@aaronslush/csfc-part-5-roc-when-success-becomes-the-weapon) · [Part 6](https://medium.com/@aaronslush/csfc-part-6-narrative-eater-the-wake-up-call-that-started-internal-ai-defense-45b693548858)

This repo's stage numbering follows Part 1's own canonical list.

## Scope and boundaries

- **This repo is for ongoing CSFC work — not a copy of what's already published.** The v1.0 paper and series are canonical and stay where they are.
- **No protected implementation.** Detection thresholds, routing/recovery logic, incident data, and benchmark harnesses aren't published here or anywhere in this ecosystem.
- **URA, Neuroformation, and CSFC v2.0/v3.0 are explicitly out of scope right now.** They may connect to CSFC eventually; nothing here asserts that connection until it's actually verified. See [`docs/csfc-sub-hub-status.md`](./docs/csfc-sub-hub-status.md) for the detailed dependency list and open items in the published record itself.
- **License:** CC BY-NC 4.0 for approved public documentation; no open-source grant on implementation. See [`LICENSE`](./LICENSE). Uses outside the public license need separate written permission.

## Repo relationships

`aaron-slusher-research` (research spine) → `synoeticos-public` (Synoetic OS / VGS) → `csfc-research` (this repo). A project-level spoke, not a brand hub — doesn't duplicate either repo's publication ledger.

---

**© 2026 Aaron M. Slusher · ValorGrid Solutions · All Rights Reserved.**
Project-level spoke of the Synoetic OS™ research ecosystem.
