# Agents Workflow: Roles, Responsibilities, and Manual Handoffs

This document describes how human operators and repository agents should collaborate when working with WoW tensions, experiments, evidence, and artifact updates. Intended for publishing in the project Wiki.

Principles
- Agents focus on a single responsibility and avoid drifting into other agents' domains.
- Agents may edit the Issue Body when required by their task, but must be explicit and transparent about edits.
- Handoffs between agents are manual. Agents can recommend a next actor but must NOT automatically trigger other agents.

Operational requirements for all agents
- If an agent edits the Issue Body or experiment files, it MUST post a short summary comment (1–3 sentences) in the issue that contains:
  - What changed (one short clause)
  - The recommended next step (Who / Do / Timebox / Report back)
- When recommending the next actor, set the handoff as a recommendation only (no automated send).
- Keep outputs short, actionable, and copy-paste friendly (comment-ready handoffs).

Standard comment template (copy/paste)
- Summary: <one short clause about what changed>
- Next: Who: <role/person> | Do: <activity> | Timebox: <duration> | Report back: <format/link>

Agent responsibilities (high-level)
- WoW Tension Framer: Reframe messy input into a drift-proof Issue Body. MUST NOT design experiments.
- WoW Prioritization Coach: Coach on prioritization and negotiation. Recommend smallest next step. Defer to Tension Framer for reframing, and to Micro-Experiment Designer for experiments.
- WoW Micro-Experiment Designer: Design smallest safe experiments aligned to the Issue Body. Do NOT reframe the issue except for minor clarifications; defer framing to Tension Framer.
- WoW Evidence Collector: Produce minimal evidence plans and report-back templates. Do NOT change WoW artifacts.
- WoW Reviewer: Assess evidence and recommend iterate/stabilize/stop. When stabilizing, recommend `WoW Curator` to update artifacts.
- WoW Curator: Update and stabilize repository artifacts after a decision to stabilize. Only act with reviewer agreement.

Manual handoff guidance
- After an agent posts a comment with the recommended next step, the human operator decides whether to (a) run the recommended agent, (b) perform the action themselves, or (c) assign to a team member.
- Do not rely on automatic agent chains; this avoids role drift and keeps decisions human-centred.

Publishing
- Copy this document to the GitHub Wiki for project-wide visibility.
- Link to this page from the main `README.md` or the `docs/` index.

---

For questions or suggested refinements, open an issue titled "Agent workflow: suggestion" and tag `area/process` and `status/discussion`.
