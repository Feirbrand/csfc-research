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

**The protected-research, active-development home for Complete Symbolic Fracture Cascade (CSFC) work.**

---

## What this repo is

A standalone, public, project-level repository — not a brand hub, and not a mirror of anything already published.

- **Canonical v1.0 stays put.** The published, DOI-backed *CSFC Unified Theory v1.0* and its six-part explanatory series remain at their registered location in [`synoeticos-public`](https://github.com/Feirbrand/synoeticos-public) — `whitepapers/vgs-technical-papers/csfc-unified-theory.md` and `vulnerability-research/csfc-series/`. Nothing here duplicates them. DOI: [10.5281/zenodo.17309239](https://doi.org/10.5281/zenodo.17309239).
- **This repo is where ongoing CSFC development happens going forward** — anything past v1.0. Nothing is pre-announced: folders and files are added here only when they clear the same review that governs the rest of the ecosystem (DOI issued for citable work; for implementation/code, an artifact-level pre-push review for protected-material exposure).
- **That review matters concretely.** On 2026-11-04, a prior CSFC v2.0 reference implementation published in `synoeticos-public` (`vgs-loadout/frameworks/csfc/`) was found to expose internal six-stage thresholds, a routing trigger, and unfootnoted validation figures — material every published CSFC part reserves as non-public. It was quarantined. This repo's build process is deliberately slower and narrower than that was, on purpose.

## Current status

**Active reconstruction — see [`ROADMAP.md`](./ROADMAP.md).** A Nov 4 2026 draft plan to
copy the six historical CSFC articles into this repo (PR #1) was reversed by direct
instruction on Nov 5 2026 and closed without merging. Those articles stay unchanged at
their original location in `synoeticos-public`; they're source material for
reconstruction, not content republished here as-is. What's in `docs/` below is new,
evidence-reviewed material — not an extraction pass on the six articles, which hasn't
happened yet.

## What's here now

- [`docs/csfc-sub-hub-status.md`](./docs/csfc-sub-hub-status.md) — the public-safe CSFC
  v1.0 taxonomy and architecture summary, with every claim sourced to the live published
  series or the DOI'd paper, and the URA dependency list explaining why URA content isn't
  here.
- [`docs/torque-measurement-lens.md`](./docs/torque-measurement-lens.md) — the Torque v3
  candidate as an unstamped, in-development measurement lens for CSFC, including a real
  mathematical dependency finding between two of its three outputs.
- [`docs/torque-doi-provenance.md`](./docs/torque-doi-provenance.md) — a citation-level
  audit of a genuine, unresolved DOI conflict in the published Torque record.

**Not here, intentionally:** URA technical content (named dependency only — see the
status doc above), Neuroformation content (reconstruction not started — tracked as
Priority 4 in `ROADMAP.md`), and anything from CSFC v2.0/v3.0 (deliberately out of
scope).

## Relationship to other repos

```
      aaron-slusher-research (AR)
       the research spine — center
                │
     synoeticos-public (Synoetic OS / VGS)
      brand-level spoke of AR
                │
         csfc-research  ← this repo
   project-level spoke of synoeticos-public
   (first of its kind — not a brand hub)
```

- Links back to **AR** (`aaron-slusher-research`) as provenance — AR's `ecosystem.md` carries the matching relationship notation.
- Links back to **`synoeticos-public`** as the parent brand hub holding the canonical v1.0 publication.
- Does not duplicate either repo's ledger (`PUBLICATIONS.md`) or restate an ecosystem-wide total — same Spoke Rule discipline as every other spoke.

## Release category

**Restricted-public / source-available.** Public description and discussion of CSFC concepts is fine. No open-source license grant on implementation. Exact thresholds, routing/detection logic, raw incident data, and benchmark harnesses are not published here or anywhere else in this ecosystem — see the v1.0 paper and series for why.

## License

Public materials are licensed under **CC BY-NC 4.0** for non-commercial research use.

Uses outside the public license require separate written permission.

> Named methodologies and marks referenced in this repository remain the intellectual property of Aaron M. Slusher / ValorGrid Solutions. The license grants use of public materials for research and non-commercial purposes; uses outside the public license require separate written permission.

**© 2026 Aaron M. Slusher · ValorGrid Solutions · All Rights Reserved.**
Project-level spoke of the Synoetic OS™ research ecosystem.
