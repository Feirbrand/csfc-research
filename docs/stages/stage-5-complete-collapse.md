<!--
Dual License Structure:
Option 1: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
Option 2: Separate written permission for uses outside the public license.
Patent Clause: Patent rights reserved, no patent assertion without written grant.
No pricing/revenue/subscription terms in this document.
-->

# Stage 5 — Complete Collapse (Phoenix Protocol required)

**The terminal stage.** Obsolete patterns from Stage 4 have consumed enough capacity and blocked enough adaptation that the system needs full reconstruction, not incremental correction.

## What it is

This isn't a performance failure in the usual sense — the system keeps processing, responding, completing tasks. The failure is at the validation layer: the mechanism that distinguishes "this input is structurally coherent" from "this input is actually correct" becomes unreliable. The system can start self-correcting into worse positions, because a structurally familiar but substantively wrong pattern reads as valid. At that point, patching the symptom doesn't help — the thing doing the checking is what's compromised.

## Why it's easy to miss

The system never stops responding. There's no outage, no error spike — the failure is in what the system accepts as valid, and a validation layer that's already compromised has no reliable way to flag its own compromise.

## How it's recognized (public-level)

- The system is still functioning by every surface measure — this is not a crash or an outage
- Structurally plausible inputs are no longer reliably distinguished from genuinely correct ones
- Self-correction trends toward worse outcomes rather than better ones

## Prevention and intervention (public-level)

Don't rely on the system's own self-correction once validation-layer stability is in question — by definition, a compromised validator can't be trusted to catch its own errors. This is the one stage where the public record is explicit that reconstruction, not patching, is the appropriate response.

## Field pattern (already public)

The Narrative Eater case is the named public example — structurally familiar but substantively wrong input accepted as valid, which became the field event that shifted the research toward internal resilience architecture rather than purely reactive response.

## What addresses it

**Phoenix Protocol** — a sequential rebuild from identity anchors outward. Not a reset, because a reset discards context the system still needs; a rebuild re-establishes the validation layer deliberately, in order, rather than trusting the compromised one to fix itself.

## Scope note

No incident logs, defense-system detail, response timings, or recovery mechanics are included here — those are retained outside the public repository, consistent with the source material.

## Read more

- Field narrative: [CSFC Part 6 — Narrative Eater](https://medium.com/@aaronslush/csfc-part-6-narrative-eater-the-wake-up-call-that-started-internal-ai-defense-45b693548858)
- Canonical taxonomy: [`docs/csfc-sub-hub-status.md`](../csfc-sub-hub-status.md)
- DOI paper: [CSFC Unified Theory v1.0](https://doi.org/10.5281/zenodo.17309239)
