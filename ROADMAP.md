<!--
Dual License Structure:
Option 1: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
Option 2: Separate written permission for uses outside the public license.
Patent Clause: Patent rights reserved, no patent assertion without written grant.
No pricing/revenue/subscription terms in this document.
-->

# Roadmap

**Status: active reconstruction. Nothing in this repo is final-form content.**

## November 5, 2026 — CSFC Reconstruction: Revised Workbench Execution Order

On 2026-11-04 a draft PR (`review/six-part-public-series` → `main`, PR #1) proposed copying
the six historical CSFC articles into this repo as full-text content. On 2026-11-05 that
plan was reversed. The six articles are not being ported here — they stay, unchanged, at
their original published location in [`synoeticos-public`](https://github.com/Feirbrand/synoeticos-public).
PR #1 is **closed, not merged**.

The reasoning: those six articles are last year's language. Some of their framing reflects
drift and unverified figures that a later evidence pass (logged across this ecosystem's
Workbench, Nov 3–4 2026) already found and corrected elsewhere. Copying them forward
unchanged would re-import exactly the problem the correction pass existed to fix. They
remain valuable as source material — not as content to republish as-is.

Current execution order (supersedes anything implied by PR #1):

| Priority | Work | Direction | Status |
|---|---|---|---|
| 1 | PR #1 | Stop the outdated six-article reproduction plan | ✅ Done — PR closed 2026-11-05 |
| 2 | Source retrieval | Recover and inspect original CSFC evidence | In progress (ongoing, outside this repo) |
| 3 | Data extraction | Separate supported findings from drift and hallucinations | In progress (ongoing, outside this repo) |
| 4 | Neuroformation | Reconstruct the identity and research-origin relationship | Not started — no verified NF content exists yet to link from here |
| 5 | URA | Determine its actual technical relationship to CSFC | Open — see `docs/csfc-sub-hub-status.md` § URA dependency list |
| 6 | Repository design | Develop corrected, evidence-led documentation | Started 2026-11-05 — `docs/` content below |
| 7 | Governance | Complete review and obtain approval before publication | Ongoing — every doc here carries its own claim-status and open items |

## What's in `docs/` right now and why

What's published here now is content that already cleared an evidence review elsewhere
in this ecosystem (the CSFC Master Hub's Nov 4–5 2026 rebuild, and the independently
re-verified Torque v3 R&D thread) — not a fresh extraction of the six articles, which is
still step 2–3 work and hasn't happened yet. Nothing below carries forward an unsourced
percentage, a protected threshold, detector logic, or recovery-dispatch mechanics.

- `docs/csfc-sub-hub-status.md` — the public-safe CSFC taxonomy and architecture summary,
  mirrored from the reviewed Master Hub (every claim sourced to the live published series
  or the DOI'd paper, not to internal drafts).
- `docs/torque-measurement-lens.md` — the Torque v3 candidate as a proposed, unstamped
  measurement lens for CSFC stage detection. Not implementation. Not thresholds.
- `docs/torque-doi-provenance.md` — a citation-level audit of a real, unresolved DOI
  conflict across the published Torque record. Bibliographic, not protected.

Neuroformation and operating-system cross-links are intentionally left as open items
(Priority 4 above) rather than guessed at. They'll be added once that reconstruction
happens, not before.
