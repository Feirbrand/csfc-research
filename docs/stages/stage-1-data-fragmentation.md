<!--
Dual License Structure:
Option 1: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
Option 2: Separate written permission for uses outside the public license.
Patent Clause: Patent rights reserved, no patent assertion without written grant.
No pricing/revenue/subscription terms in this document.
-->

# Stage 1 — Data Fragmentation

**The root cause.** A system holds multiple sources of truth with no clear authority hierarchy, and operates on the contradictions between them without yet recognizing there's a conflict.

## What it is

Conversation context, system prompts, training data, and retrieval systems can each hold a different version of "what's true," with nothing designating which one governs. The system isn't malfunctioning — it's correctly processing information that is itself inconsistent. Every later stage in this cascade is downstream of this one condition, not an independent failure mode.

## Why it's easy to miss

Fragmentation doesn't announce itself as an error. The system has no way to know it's holding conflicting sources, so nothing flags itself. The contradiction sits latent until external stress forces a choice between two "truths" that were never reconciled — at which point it looks like Stage 2, not like the Stage 1 condition that caused it.

## How it's recognized (public-level)

- Competing sources of truth with no designated authority between them
- Information that should match across contexts quietly doesn't
- No single arbitration path when two sources disagree

## Prevention and intervention (public-level)

Name a single governing source for any fact that could appear in more than one place — context, prompt, retrieved data, training — *before* stress hits, not after. Treat a detected mismatch between sources as a signal to resolve immediately, not noise to filter or average away. The fix is architectural (who's in charge of this fact), not statistical (which answer shows up more often).

## Field pattern (already public)

The field record describes this as the consistent starting condition behind every later-stage incident observed in 2025 — not a separate failure mode that sometimes also happens, but the condition every other stage below grows out of.

## What addresses it

**UMS (Unified Memory Spine)** — a single source of truth with a clear authority hierarchy, so the system has one place to resolve "which version is real" instead of silently inheriting all of them.

## Scope note

No thresholds, scoring formulas, or detection logic are included here — those are retained outside the public repository, consistent with the source material.

## Read more

- Field narrative: [CSFC Part 1 — The Hidden Cascade Killing Your AI Systems](https://medium.com/@aaronslush/csfc-part-1-the-hidden-cascade-harming-your-ai-systems)
- Canonical taxonomy: [`docs/csfc-sub-hub-status.md`](../csfc-sub-hub-status.md)
- DOI paper: [CSFC Unified Theory v1.0](https://doi.org/10.5281/zenodo.17309239)
