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
- Purchase profile (Doug, updated 2026-07-12 evening — **the Class C pivot**):
  USED **gas Class C**, budget **$60–90k financed**. **Class A is ELIMINATED**
  (national/state-park camping is the primary mission and park length limits
  penalize big rigs; all Class-A-only docs live in `docs/archive/`). Size is THE
  open question: 25' toured felt too small, but park limits favor shorter — the
  parks-fit data (docs 25/26) drives the sweet spot. Mission includes cross-country
  reach (Sequoia, Canyonlands). Window late 2026–2028. Kids born **March 2022**
  (one bigger-, one smaller-than-average) and are **HOMESCHOOLED — no school
  calendar tether** (school-year considerations archived). Abroad travel must
  survive the purchase (Doug's work is HQ'd in Munich — family travel may fold
  into business trips; never name the employer in public docs). Mostly hookups +
  real boondocking, WFH with dual monitors, ~6 conventional bikes (no e-bikes).
  Sara more likely comfortable driving a Class C. Rent-before-buy stands. Buyer in
  **Brick, NJ**. Tow cars: 2017 RAV4 Limited AWD, 2022 Tucson (E-450 tow ratings
  re-open the trailer question). Docket must include an honest anti-hype
  cost-benefit ("how much must we use it to be worth it") and Sara's
  trips-while-waiting concern; tone carries gratitude/perspective without
  condescension.
- Doc standards (Doug, 2026-07-12): every factual claim carries an inline source
  citation + per-doc Sources section; law vs. guidance must be clearly separated
  wherever rules are discussed. Applies to all future docs too.
- Archive convention: superseded docs move to `docs/archive/` (rendered on the
  site under an "Archive" section, clearly bannered, not maintained). Never
  delete research; archive it.
- Docs in `docs/` need Jekyll front matter (`---\ntitle: ...\n---`) to render styled.

## Guardrails

- Repo is PUBLIC: no personal data beyond first names of the adults, town-level
  location, kids' ages/birth month. **Kids' names never appear in the public docs**
  (say "the kids" / "one child"). Never commit addresses, plates, VINs, prices Doug
  has been quoted privately, or family financial specifics beyond the stated
  $100–150k financing target (Doug approved publishing that band).
- Model policy (Doug, 2026-07-12 evening — current): **Sonnet** research/writing
  agents, **Opus** adversarial verification, **Fable** orchestration/advisor only.
  Usage-conscious: don't kill the budget, but don't cut corners on accuracy.
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
