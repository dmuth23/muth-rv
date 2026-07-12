# muth-rv — session state

Last updated: 2026-07-12 ~14:00 ET (revamp session, wrapped at Doug's request near usage cap)

## What this project is
Family motorhome-purchase research docket. Deliverable = `docs/` published at
https://dmuth23.github.io/muth-rv/ for Doug + Sara to review.

## Frozen decisions & standing approvals (do NOT re-ask)
- **Purchase profile (Doug, 2026-07-12 — supersedes 07-11):** USED, financing
  $100–150k (flexible for a deal). Primary: gas Class A 30–35'. Also on the table:
  Class C 30'+ w/ toad, and diesel (informed-buyer coverage; shop-serviced).
  Window late 2026–2028. Kids born March 2022 (one bigger-, one smaller-than-avg;
  names NEVER in public docs). Brick, NJ; likely driveway storage. Tow-car
  candidates: 2017 RAV4 Limited AWD, 2022 Tucson (both ~trailer-only per doc 19).
  ~6 conventional bikes, NO e-bikes. Sara likely won't drive a Class A.
  Rent-before-buy agreed. No model shortlisting — full landscape.
- **Standing approvals:** repo PUBLIC, free-push, Pages site approved; the
  $100–150k band is approved for publication.
- **Doc standards (Doug):** inline citations + per-doc Sources section on every
  doc; law-vs-guidance explicitly separated. Applies to all future docs.
- **Model policy:** Opus writers + Fable adversarial/orchestration when headroom
  allows; drop agents to Sonnet when usage-constrained (Doug called both today).

## State as of session end
- Revamp COMPLETE and pushed: commit `dd58bb1` on main — 24 docs (14 revised/
  citation-retrofitted + 8 new: 17 diesel, 18 Class C, 19 towing/toad, 20 Brick NJ
  storage, 21 school/cadence, 22 one-driver, 23 insurance/toad, 24 out-of-state
  buying), rebuilt index/reading-list/open-questions. Two-pass fact-check applied.
  Pages was rebuilding at wrap; verify site rendering next session.
- **IN-FLIGHT, STOPPED, RESUMABLE:** phase-2 audit workflow (4 Fable auditors:
  legal/money/vehicle/consistency + Opus Sara-lens reader → Opus fixers per file).
  Run `wf_b458ba82-be2`, stopped ~96% usage before findings landed. Resume after
  reset with: Workflow({scriptPath: "~/.claude/projects/-home-dmadmin-projects-muth-rv/2761eb8c-d3d8-4d92-a21e-58a005e4df05/workflows/scripts/muth-rv-final-audit-wf_b458ba82-be2.js",
  resumeFromRunId: "wf_b458ba82-be2"}) — completed audit agents return cached.
- Phase-1 revamp workflow `wf_3fa2cbb9-701` fully complete (54 agents, ~3.2M tok).
  Full result JSON: /tmp/claude-1000/-home-dmadmin-projects-muth-rv/2761eb8c-.../tasks/wbexbs4k7.output
  Known loose end: docs 08 + 10 chains hit a StructuredOutput cap late (files on
  disk are fine/fixed; the stopped audit was their second check — resume covers it).

## Next likely work
1. Resume the phase-2 audit (after 3:00 PM ET reset), apply fixes, commit+push.
2. Verify Pages build + spot-check new pages render.
3. Doug + Sara read the new entry path: docs 05 → 19 → 22 → 13; then 16
   (Decisions & Open Questions) for the next round of decisions.
