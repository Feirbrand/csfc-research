<!--
Dual License Structure:
Option 1: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
Option 2: Separate written permission for uses outside the public license.
Patent Clause: Patent rights reserved, no patent assertion without written grant.
No pricing/revenue/subscription terms in this document.
-->

# Keeper verification log — data-accuracy audit, Nov 5 2026

**Purpose:** an independent, infrastructure-side check of this repo's own claims and
provenance, run by the Notion-side workspace Keeper (not the Claude Code session that
wrote `docs/csfc-sub-hub-status.md`, `docs/torque-measurement-lens.md`, or
`docs/torque-doi-provenance.md`, and not the one that closed PR #1). This is a second,
independent pass, not a restatement of that session's own audit in `ROADMAP.md` — the
two should agree, and this log records why they do.

## What was checked, and against what

| Claim in this repo | Checked against | Result |
|---|---|---|
| File paths cited for the six published CSFC parts and the DOI'd paper (`whitepapers/vgs-technical-papers/csfc-unified-theory.md`, `vulnerability-research/csfc-series/csfc-part1-v1.1.md` … `csfc-part6-v1.1.md`) | Fresh clone of `Feirbrand/synoeticos-public`, direct `ls` | All six parts and the paper exist at the exact paths cited. |
| "Zero percent-sign claims in any of the six live parts" (`docs/csfc-sub-hub-status.md`, verification note) | `grep -c "%"` against all six live files in the fresh `synoeticos-public` clone | Confirmed — 0 matches in every part. |
| DOI `10.5281/zenodo.17309239` for CSFC Unified Theory v1.0 | `grep` across `synoeticos-public` — found in `README.md`, `PUBLICATIONS.md`, the paper itself, and all six parts' own reference sections | Consistent everywhere it's cited inside that repo. |
| The four-DOI Torque citation conflict (`docs/torque-doi-provenance.md`) | Cross-checked against the live VGS Recovery Notion hub's independently-sourced DOI inventory (same four numbers: `17309731`, `17373552`, `17379750`, `17297590`) | Matches — not a number invented for this repo. |
| Repo-relationship diagram (`aaron-slusher-research` → `synoeticos-public` → `csfc-research`) | `synoeticos-public`'s own `README.md` independently names `aaron-slusher-research` as its parent spine (three separate citations, not written by this repo); confirmed `aaron-slusher-research` resolves as a real repo via `git ls-remote` | Chain is real on both ends, not a one-sided claim. |
| PR #1 closed, not merged, "per Aaron's Nov 5 2026 direction" | GitHub API (`pulls/1`, `issues/1/comments`) — state, merge status, and the actual closing comment's text | `state: closed`, `merged: false`. Closing comment cites the same Workbench priority-1 item ("Stop the outdated six-article reproduction plan") this Keeper independently verified live on the Workbench page earlier the same day, with Aaron's own quoted direction ("this is the path we need to use for csfc... we focus on csfc for now"). Not a self-authorized AI decision dressed up as one — traces to a real instruction already logged on this side. |
| LICENSE's artifact-scope clause | Direct read of `LICENSE` | Present ("No patent, trademark, production deployment, commercial integration, or sublicensing rights are granted..."). This closes a gap flagged earlier the same day (Nov 5 AM Sentrix pass) — at that point the clause was missing. It is in place now. |

## Net finding

Every externally-checkable claim in this repo — file paths, the DOI, the zero-percent
claim, the repo-relationship chain, the PR-closure rationale, the license clause —
checked out against a source outside this repo's own text. No fabricated path, invented
number, or unsupported assertion found.

## What this log does not do

- It does not re-run the content judgment calls already made elsewhere (claim hedging,
  URA exclusion, Torque v3 candidate status) — those are reviewed in `ROADMAP.md`'s own
  Nov 5 audit entry and are sound on inspection, but this log's job is provenance, not a
  second content review.
- It does not resolve the one open item both audits agree on: the live Torque v3
  contract page in Notion still states `τ₃` and `D` as independent outputs, which
  contradicts the twice-derived dependency finding. That stays Notion-side, under active
  multi-reviewer control, and is tracked there — not something this repo can fix by
  itself since the contradiction isn't in this repo's own text.

## Status

This repo has everything it needs for its current, deliberately narrow scope (CSFC v1.0
status + the Torque v3/DOI tracking it depends on). Nothing is missing that is actually
ready to add — Priorities 2–5 in `ROADMAP.md` (source extraction, Neuroformation link,
URA relationship, repository design beyond today) are correctly gated behind work that
hasn't happened yet, not behind anything this repo forgot to do.
