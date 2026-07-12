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
- Purchase profile (frozen inputs from Doug, 2026-07-11): USED, GAS Class A, 30–35 ft
  (35 preferred), window late 2026–2028, mostly hookups + real boondocking ability,
  WFH with dual monitors, ~6 bikes (his gravel/road/MTB + wife's + 2 kids'), NJ buyer.
- Docs in `docs/` need Jekyll front matter (`---\ntitle: ...\n---`) to render styled.

## Guardrails

- Repo is PUBLIC: no personal data beyond first name, town-level location, kids' ages.
  Never commit addresses, plates, VINs, prices Doug has been quoted privately, or
  financial specifics of the family.
- Deep-dive research fan-outs run on **Sonnet-tier subagents**, not Fable (Doug's
  standing usage constraint for this project).
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
