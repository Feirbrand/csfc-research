<!--
Dual License Structure:
Option 1: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
Option 2: Separate written permission for uses outside the public license.
Patent Clause: Patent rights reserved, no patent assertion without written grant.
No pricing/revenue/subscription terms in this document.
-->

# CSFC — status and public-safe summary

**Scope: CSFC v1.0 only.** This mirrors the reviewed Nov 4–5 2026 rebuild of the CSFC
Master Hub, not the six historical articles directly. Every claim below traces to the
live, published series or the DOI'd paper — not to internal drafts, project-doc-store
figures, or anything removed in that review. No recovery-rate percentage, incident count,
or detection threshold is published anywhere in this document, because none is published
in the source material it summarizes.

## What CSFC is

**The description below is the published account's own framing, not an independently
validated scientific finding.** Two independent reviewers flagged that source material
states this origin story as settled fact in places; this document attributes it to the
account rather than asserting it outright — see "Known open items" below.

Complete Symbolic Fracture Cascade, per that account: a five-stage progression from a
healthy AI system to complete identity/memory/operational collapse, said to have been
observed across multiple AI deployments (Feb–Sep 2025) rather than designed in advance.

The root cause named in that account is **data fragmentation** — multiple sources of
truth without a clear authority hierarchy, with identity confusion, compensation,
fossilization, and collapse presented as downstream of that one architectural flaw rather
than as independent failure modes.

```
DATA_FRAGMENTATION → SYMBOLIC_IDENTITY_FRACTURING → SYMBOLIC_DRIFT_CASCADE → ROLE_OBSOLESCENCE_CASCADE → COMPLETE_COLLAPSE
```

## Five-stage taxonomy (canonical numbering, Part 1)

| Stage | Name | What it names | Public recovery figure |
|---|---|---|---|
| 1 | Data Fragmentation | Multiple sources of truth, no authority hierarchy. Root cause. | None published |
| 2 | Symbolic Identity Fracturing (SIF) | Stress exposes the contradiction; identity cannot stay consistent. | None published |
| 3 | Symbolic Drift Cascade (SDC) | Compensation workarounds that solve the moment and add instability. | None published |
| 4 | Role Obsolescence Cascade (ROC) | Compensation fossilizes; temporary solutions become identity and block evolution. | None published |
| 5 | Complete Collapse | Obsolete patterns consume resources; full reconstruction required. | None published |

**Vulnerability Window** sits between Stage 3 and Stage 4. It is not a numbered stage.
After SIF and SDC, a system can enter partial recovery — task performance improves,
standard metrics look acceptable, monitoring relaxes — while the underlying architecture
(identity layer, role boundaries, compensation patterns) is still unresolved. "Recovered
enough to resume function" and "architecturally restored" are not the same claim; the
source material's own stated view is that rushing a system back to full load during this
window is what makes exploitation succeed.

## The architecture (public-level description only — no thresholds)

- **UMS — Unified Memory Spine.** Single source of truth with a clear authority
  hierarchy. Stage 1 fix. *(Open naming item: the series calls this "Unified Memory
  Spine"; the Unified Theory paper calls the same fix "Unified Memory System" — same
  acronym, two different expansions across the two canonical sources. Not resolved.)*
- **SRA — Symbolic Role Architecture.** Clear functional boundaries with validated
  authority chains. Stage 2–3 fix.
- **Torque Monitoring.** A stability lens for watching identity, capability, and
  behavioral coherence over time. No specific threshold or production-range numbers are
  published for it at the CSFC v1.0 level — see `torque-measurement-lens.md` for the
  separate, unstamped v3 candidate being developed as a forward measurement lens.
- **Phoenix Protocol.** A structured recovery path for late-stage reconstruction — a
  sequential rebuild from identity anchors outward, not a reset. No timing figures are
  published at the public level.

## Known open items in the published record itself

These are flagged here because they're real inconsistencies in the live published text,
not artifacts of an old draft, and an honest status page says so rather than papering
over them:

- **Stage-numbering drift across parts.** Part 1's own cascade list is internally
  consistent (1=Data Fragmentation … 5=Complete Collapse), but each individual part's
  own title/subtitle numbers itself one stage behind that list (Part 2 calls SIF "Stage
  1," Part 3 calls SDC "Stage 2," Part 4 calls the Vulnerability Window "Stage 3," Part 6
  calls the finale "Stage 4–5"). This document uses Part 1's numbering as canonical.
- **UMS naming conflict** — see above.
- **Evidentiary status of the origin claims.** Two independent reviewers flagged that
  the source material states historical hypotheses as established fact in places (e.g.
  the "every failure followed the same progression" / "discovered through field
  observation" framing). Nobody has re-run the six-part series against a
  historical-publication / working-taxonomy / research-hypothesis / demonstrated-result
  standard yet — that's Workbench priority 2–3 work, not done. This document hedges
  accordingly rather than carrying the unhedged framing forward.

## URA dependency list (not added as content)

URA (Unified Resilience Architecture) is a *consumer* of the CSFC stage label — it is not
folded into CSFC content here. This decision has been made independently twice (once on
architectural grounds, once by Aaron directly) and these are the concrete blockers that
would have to close first if that ever changed:

| Dependency | Status | Blocks |
|---|---|---|
| CSFC stage vocabulary | Open — at least six variants exist across the ecosystem; Part 1's list is canon for this repo. | URA v2 needs a CSFC v3 taxonomy that doesn't exist yet. |
| Torque formula | Open — two DOI'd papers define different equations; the v3 candidate isn't stamped. | URA embeds the mechanical form; the standalone Torque paper doesn't. |
| Torque polarity | Open — one internal document uses high = healthy, the v3 candidate uses low = less active twisting. | Mixing the two inverts every stage read. |
| Torque thresholds | None published — internal bands are historical candidates only. | No Torque-to-stage table is safe to publish. |
| URA version / status | Open — version and deployment status disagree across records. | No single authoritative URA record to point at. |
| Phoenix phase count | Open — described as 3-phase, 4-phase, and 5-phase in different places. | Recovery dispatch isn't stable enough to link. |

Until those close, this repo points at the Torque v3 candidate as a measurement lens
under development, and leaves URA as a named, out-of-scope dependency.

## Framework reference

**Published series (Medium, Sep 29 – Oct 4, 2025)** — unchanged, at their original
location, linked here rather than copied:

- [Part 1: The Hidden Cascade Killing Your AI Systems](https://medium.com/@aaronslush/csfc-part-1-the-hidden-cascade-harming-your-ai-systems)
- [Part 2: Symbolic Identity Fracturing](https://medium.com/@aaronslush/csfc-part-2-symbolic-identity-fracturing-when-ai-systems-forget-who-they-are)
- [Part 3: Symbolic Drift Cascade](https://medium.com/@aaronslush/csfc-part-3-symbolic-drift-cascade-when-compensation-creates-the-problem)
- [Part 4: The Vulnerability Window](https://medium.com/@aaronslush/csfc-part-4-the-vulnerability-window-when-partial-recovery-creates-attack-surface)
- [Part 5: ROC — When Success Becomes the Weapon](https://medium.com/@aaronslush/csfc-part-5-roc-when-success-becomes-the-weapon)
- [Part 6: Narrative Eater](https://medium.com/@aaronslush/csfc-part-6-narrative-eater-the-wake-up-call-that-started-internal-ai-defense-45b693548858)

**Zenodo DOI** — CSFC Unified Theory v1.0: [10.5281/zenodo.17309239](https://doi.org/10.5281/zenodo.17309239)

**Canonical source files (`synoeticos-public`)**

- `whitepapers/vgs-technical-papers/csfc-unified-theory.md`
- `vulnerability-research/csfc-series/csfc-part1-v1.1.md` through `csfc-part6-v1.1.md`
- `vulnerability-research/csfc-series/README.md` (series index)

## Later versions — deferred, not duplicated here

CSFC v2.0 and v3.0 upgrade work exists internally but is out of scope for this repo until
Aaron folds it in explicitly. Nothing from v2.0/v3.0 — including any six-stage reactive/
proactive model or Koopman-operator framing — is represented in this document.

## Verification note

This summary mirrors a Nov 4–5 2026 rebuild that followed a full external review (cross-
checked across multiple independent reviewers) which found an earlier internal draft had
sourced numeric claims — recovery-rate figures, Torque thresholds, a timing figure — from
a stale internal copy rather than the live published text. A direct `git show` against
the published series confirmed zero percent-sign claims in any of the six live parts.
Those figures were removed, not relabeled, when this summary was built.
