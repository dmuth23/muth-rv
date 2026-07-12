# muth-rv

Session state: .claude/STATE.md (written by /handoff) — read it first when resuming; if absent, no handoff has run here yet.

## What this is

Research project (not code): a family motorhome-purchase docket for Doug + wife +
two 4-year-olds. Deliverable is the doc set in `docs/`, published as a GitHub Pages
site for the family to review together. "Done" for any session = docs committed,
pushed, and rendering on the Pages site.

## Key facts

- Repo: https://github.com/dmuth23/muth-rv (**PUBLIC** — Doug explicitly approved
  publishing this research)
- Pages site: https://dmuth23.github.io/muth-rv/ (served from `main` branch, `/docs`
  folder, Jekyll)
- Purchase profile (Doug, updated 2026-07-12): USED, financing target **$100–150k**
  (flexible down for a deal). Primary: gas Class A 30–35 ft (35 preferred). Also on
  the table: **Class C** (30'+, with a toad) and **diesel** (not excluded anymore —
  Doug wants informed-buyer coverage; a diesel would be shop-serviced, not DIY).
  Window late 2026–2028. Kids born **March 2022** (turn 5 in Mar 2027, 6 in Mar 2028;
  one bigger-, one smaller-than-average — affects car-seat/booster timing). Mostly
  hookups + real boondocking ability, WFH with dual monitors (no employer location
  rules), ~6 conventional bikes (**no e-bikes — ruled out**). Wife likely NOT
  comfortable driving a Class A. Rent-before-buy is the agreed plan. Buyer in
  **Brick, NJ**. Tow-car candidates: 2017 Toyota RAV4 Limited AWD, 2022 Hyundai Tucson.
- Doc standards (Doug, 2026-07-12): every factual claim carries an inline source
  citation + per-doc Sources section; law vs. guidance must be clearly separated
  wherever rules are discussed. Applies to all future docs too.
- Docs in `docs/` need Jekyll front matter (`---\ntitle: ...\n---`) to render styled.

## Guardrails

- Repo is PUBLIC: no personal data beyond first names of the adults, town-level
  location, kids' ages/birth month. **Kids' names never appear in the public docs**
  (say "the kids" / "one child"). Never commit addresses, plates, VINs, prices Doug
  has been quoted privately, or family financial specifics beyond the stated
  $100–150k financing target (Doug approved publishing that band).
- Model policy (Doug, 2026-07-12 — supersedes the earlier Sonnet-only rule):
  research/writing agents run on **Opus**; adversarial verification and
  orchestration run on **Fable**.
- Git identity + workflow policy are box-wide — see `~/projects/CLAUDE.md`
  (noreply commit identity; free-push vs ask-first classes). **This repo's class:
  free-push — personal research repo, Doug pre-approved public publishing.**

## Workflow: Forge
This project uses **Forge** for non-trivial work — the framework at
`~/projects/claude-harness-loop/` (the `/forge` lever). Mid-brainstorm, `/forge`
captures the conversation, frames it into a pieces-board (HAVE/BUILD/UNKNOWN) + a
quantifiable goal, runs an advisor-refined interview, freezes a spec, then builds +
verifies. Efforts land in `efforts/<slug>/` here and mirror to
`~/projects/claude-harness-loop/efforts/`.
