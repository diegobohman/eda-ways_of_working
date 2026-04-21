---
title: "Listen-first: Co-created Protocol for Platform Health Check"
owner: "diegobohman"
date: "2026-04-21"
timebox: "2026-04-27 → 2026-05-03"
status: "proposed"
---

# Experiment: Listen-first Platform Health Check (pilot)

- Purpose: Quickly test a lightweight, co-created meeting protocol that increases participant preparation, shared understanding, and constructive discussion in the Platform Health Check.
- Context: The monthly Platform Health Check agenda is documented but participation and preparation are uneven. The meeting often becomes reactive rather than collaborative.

## Hypothesis

If we add a short "listening and co-design" step for each agenda item and ask participants to submit one preparatory input, then more participants will come prepared, discussions will be more collaborative, and actions will be clearer.

## Success criteria

- Primary (quantitative): >= 60% of expected participants submit a 2-line pre-read for their agenda item before the meeting.
- Secondary (qualitative): >= 70% of respondents rate the meeting as "useful" or "very useful" in a 2-question post-meeting pulse.

## Measurement plan

- Metrics:
  - Preparation rate: submitted pre-reads / invited participants
  - Meeting usefulness: percent rating "useful" or above
  - Number of actionable follow-ups with clear owners
- Data sources: issue comments (pre-reads), short Google Form pulse, meeting notes
- Frequency: one pilot meeting (within timebox) + immediate post-meeting pulse
- Owner: `owner` (experiment owner) + Data lead

## Experiment steps (high-level)

1. Pre-week (by 2026-04-26) — Announce pilot, share pre-read template, request 2-line inputs (owner).
2. Pre-meeting (day before meeting) — Collect submissions and publish a 1-page consolidated pre-read (facilitator / data lead).
3. Pilot meeting (during scheduled PHC in timebox) — Run shortened agenda where each item begins with a 3-minute read + 10-minute focused discussion using the co-created protocol. Capture actions and owners (facilitator).
4. Post-meeting (within 24h) — Send 2-question pulse and collect metrics; run 30-minute debrief with core participants; record learnings (owner + facilitator).

## Roles & responsibilities

- Owner: diegobohman — overall accountability and coordination
- Facilitator: rotate to a Unit Lead (agree ahead) — run meeting with the protocol
- Data lead: volunteer (or owner) — consolidate pre-reads, collect pulse
- Participants: Unit leads + invited stakeholders — submit pre-reads and attend prepared

## Facilitation checklist

- Before start: announce pilot in issue #1; post pre-read template; set deadline for inputs.
- During: enforce timeboxed read+discuss pattern; capture actions with clear owners and due dates.
- After: publish consolidated notes, pulse results, and a 15-minute debrief summary.

## Artefacts to produce

- Experiment doc: experiments/platform-health-check-listening-experiment.md
- Consolidated pre-read: meetings/platform-health-check-YYYYMMDD-pre-read.md
- Facilitation notes & actions: meetings/platform-health-check-YYYYMMDD-notes.md
- Measurement sheet / pulse results: (link or path to Google Sheet)

## Comment-ready handoff (copy this into the issue comment)

Who: Platform Unit Leads + diegobohman (owner)
Do: For the next PHC, submit a 2-line pre-read for your Unit by 2026-04-26; during the meeting we will run a 3-minute read + 10-minute focused discussion per item using a co-created protocol; facilitator will capture actions with owners.
Timebox: 2026-04-27 → 2026-05-03 (pilot week)
Report back: Comment on issue #1 with the consolidated pre-read, pulse results, and a one-paragraph recommendation by 2026-05-04.

---

## Data collection template

| Date | Metric | Value | Notes | Reporter |
|------|--------:|------:|-------|---------|
| 2026-04-27 | Preparation rate |  | % of participants | <name> |
| 2026-04-27 | Meeting usefulness |  | % rating useful/very useful | <name> |

## Risks & mitigations

- Risk: Low submission rate → Mitigation: personal reminders to Unit Leads and short deadline.
- Risk: Protocol feels forced → Mitigation: keep protocol minimal (3m read + 10m discuss) and solicit quick feedback in debrief.

## Learnings (to be filled after experiment)

- Summary:
- What worked:
- What didn’t work:
- Recommendation: stop / iterate / adopt
