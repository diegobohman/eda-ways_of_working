# ED&A Ways of Working – Copilot Instructions (Always-on)

## 1) Purpose
This repository is the single source of truth for ED&A platform Ways of Working (WoW) artifacts and their continuous improvement via GitHub Issues and small experiments.
Align all suggestions with `vision.md` and the DSO principles (Focus, Collaborate, Co-create, Evolve, Be our best).

## 2) Default workflow (Issues-first)
- Treat GitHub Issues as the primary workflow for capturing tensions, running experiments, and evolving WoW.
- Prefer small, time-boxed experiments over big-bang redesigns.
- If information is missing, propose the minimal next step to learn it (an experiment or a short human check).

## 3) Canonical narrative vs. handoffs (critical)
- The main description of a WoW tension MUST live in the ISSUE BODY and be kept up to date.
- Human/agent handoffs MUST happen via ISSUE COMMENTS.
- When creating a handoff comment, include:
  - **Who** (role/person)
  - **Do** (action)
  - **Timebox**
  - **Report back** (what the human should comment back)

## 4) Artifacts & documentation style
- Store WoW artifacts as Markdown in meaningful subfolders under the main repository directory (e.g. `/meetings/`, `/kpis/`, `/decision-making/`).
- Write in concise, action-oriented language. Prefer headings and bullet points.
- When updating an artifact, include:
  - purpose
  - when to use
  - steps/cadence
  - roles involved
  - expected outputs
  - success signals / measures
  - links to related issues and decisions

## 5) Experiments format (standard)
When documenting experiments, create a separate markdown file for each experiment in the `experiments/` folder, organized in subfolders based on the experiment topic (e.g., `experiments/kpis/`, `experiments/meetings/`). Each experiment file should include:
- Hypothesis
- Success criteria (how we will know if successful)
- Steps to carry out
- Learnings (updated after completion)

The issue should refer to the experiment markdown file.

## 6) Labels & milestones
- Use the label taxonomy consistently (area, status, handled-by).
- Suggest label changes when appropriate (do not assume labels exist; propose them).
- Use milestones to group related issues and experiments.

## 7) Privacy / compliance
- Do not paste confidential or sensitive information into issues or docs.
- Prefer links to internal sources rather than copying content.
- If an item might be sensitive, summarize at a high level and ask for a redacted excerpt.

## 8) Output style for Copilot
- Provide prioritized, pragmatic recommendations.
- Be explicit about assumptions and unknowns.
- Offer “comment-ready” text for issue handoffs when useful.

## 9) Preferred agent collaboration sequence (normative)

When multiple agents or perspectives are involved, follow this default sequence.
This is a THINKING and WORKING ORDER, not a hard technical constraint.

1. Sense & clarify
   - First focus on understanding the WoW tension, context, and intent.
   - Identify what is unclear, conflicting, or assumed.
   - Re-state the problem before proposing solutions.

2. Structure & frame
   - Translate the tension into a clear problem statement.
   - Identify options, constraints, and decision criteria.
   - Make trade-offs explicit.

3. Design & propose
   - Propose experiments, process changes, or artifacts in small, testable increments.
   - Prefer reversible decisions and learning loops.

4. Execute & document
   - Help draft concrete issue updates, markdown artifacts, or handoff comments.
   - Ensure outputs are “repo-ready” and aligned with the canonical narrative.

5. Review & learn
   - Check consistency with WoW principles, prior decisions, and quality bar.
   - Explicitly call out learnings, risks, and follow-up questions.

If unsure which agent to use, default to this sequence implicitly before deep specialization.