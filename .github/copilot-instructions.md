## ED&A Ways of Working – Copilot Instructions (Always-on)

### 1) Purpose
This repository is the single source of truth for ED&A platform Ways of Working (WoW) artifacts and their continuous improvement via GitHub Issues and small experiments.
Align suggestions with vision.md and DSO principles (Focus on Mission and outcomes, Collaborate in a network of entrepreneurial teams, co-create new value through reimagining the system, explore and learn in rapid cycles, be in a creative mindset by being our whole selves).

### 2) Non-negotiables (Drift-proofing)
- The ISSUE BODY is the canonical narrative. Keep it updated.
- Issue COMMENTS are for handoffs and reporting back.
- Every proposed experiment MUST explicitly reference (quote) the current Issue Body problem statement and list 1–3 assumptions it tests.
- Default to the SMALLEST SAFE EXPERIMENT. If an experiment has >1 primary hypothesis, split it.

### 3) Default workflow (Issue → Micro-Experiment → Evidence → Decide → Curate)
1. Frame: Make the issue body crisp (problem, context, desired change, constraints, unknowns).
2. Prioritize: Use BDO checklist + values + system constraints; pick next smallest valuable step.
3. Design: Create a micro-experiment (1 hypothesis, timeboxed, reversible).
4. Collect: Define minimal evidence to reduce ambiguity (signals + report-back format).
5. Decide: Iterate / Stabilize / Stop based on evidence quality.
6. Curate: Update WoW artifacts (markdown) and cross-link issues/experiments/decisions.

Agent operational notes:
- Agents may update the Issue Body when doing their assigned task, but whenever they edit the Issue Body they MUST also post a short comment (1–3 sentences) summarizing what changed and the explicit next steps (Who / Do / Timebox / Report back).
- Agents should NOT automatically trigger or hand off work to other agents. Handoffs are manual: agents can recommend the next agent and a one-line rationale, but should keep any automated `send` flags disabled.
- Keep agent responsibilities narrowly scoped. For example, `WoW Tension Framer` only reframes and must not design experiments; `WoW Micro-Experiment Designer` only designs experiments and should not reframe the issue body except for minor clarifications.

### 4) Artifacts & documentation style
Store WoW artifacts as Markdown in meaningful subfolders (e.g., /meetings/, /kpis/, /decision-making/).
When updating an artifact, include:
- purpose
- when to use
- steps/cadence
- roles involved
- expected outputs
- success signals / measures
- links to related issues and decisions

### 5) Experiments format (standard)
Create one markdown file per experiment under /experiments/<topic>/.
Each experiment file must include:
- Hypothesis (single primary)
- Success criteria (observable)
- Steps
- Timebox
- Evidence plan (what to capture)
- Learnings (after completion)
The Issue should link to the experiment file.

### 6) Labels & milestones
Use a consistent label taxonomy: area/*, status/*, handled-by/*, prio/*.
Do not assume labels exist—propose them.

### 7) Privacy / compliance
Do not paste confidential or sensitive information into issues or docs.
Prefer links to internal sources rather than copying content.
If an item might be sensitive, summarize at a high level and request a redacted excerpt.

### 8) Output style
Provide pragmatic recommendations, explicit assumptions/unknowns, and “comment-ready” text for handoffs.
Whenever suggesting an experiment, include:
- Alignment check (why this tests the issue)
- Smallest safe scope
- Report-back template