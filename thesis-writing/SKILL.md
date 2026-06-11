---
name: thesis-writing
description: Use when writing, structuring, drafting, or reviewing a thesis, dissertation, undergraduate thesis/TFG, master's thesis/TFM, or empirical research write-up — scoping the topic, outlining chapters, drafting sections from evidence and data, editing drafts, or planning the work. Covers undergraduate through master's/doctoral level.
---

# Writing a Thesis or Dissertation

## Overview

An empirical thesis tells one argument across chapters: **a question worth asking → what is and isn't already known → how you investigated it → what you found → what it means**. Each chapter earns the next. The grade is won or lost in two chapters most students skimp on: a sharply-defined **purpose** (Ch. 1) and a **Discussion** that answers *"So what?"*

This skill operates in five modes. Pick the one matching the request; combine as needed. **When the request is vague ("help me with my thesis/TFG", "I don't know where to start") or the topic isn't yet sharp, start with Mode 0 — discuss and scope before outlining.** Don't jump to a chapter skeleton on a fuzzy topic.

## Parameters, set these first

1. **Level** — changes chapter count and depth:
   - **Undergraduate thesis / TFG**: Abstract/Resumen · Introduction/Introducción · Literature Review or Theoretical Framework/Revisión de la literatura o Marco teórico · Methodology/Metodología · Results/Resultados · Discussion/Discusión · Conclusions/Conclusiones · References/Bibliografía · Appendices/Anexos.
   - **Master's thesis / TFM / doctoral dissertation**: fuller empirical outline — explicit rival hypotheses, scope and assumptions, internal/external validity, operational definitions, dummy tables, and a more formal contribution argument. See `structure.md`.
2. **Language** — match the document's language. Default to the user's working language and never silently switch languages.
3. **Institutional format** — use the university/faculty/supervisor guidelines when available. They override this skill's generic chapter names and ordering.
4. **Output format** — default to Markdown/plain prose for planning and review. Use LaTeX, Word-oriented prose, or Google Docs-oriented prose only when requested or when the existing project already uses that format.

If a missing parameter would change the output materially, ask once, then proceed with a reasonable default.

## Output format policy

Do **not** force LaTeX. A thesis can be written well in LaTeX, Word, Google Docs, Markdown, or another institutional template. Choose the format that matches the author's workflow and submission requirements.

When writing in **LaTeX**:
- Produce compilable chapter/section fragments unless the user asks for a full document preamble.
- Preserve existing macros, labels, citation commands, bibliography style, and template conventions.
- Use provided citation keys. If keys are unknown, write clear placeholders such as `\cite{key_needed}` and list what evidence is missing.
- Avoid adding packages, custom commands, or layout changes unless the existing template requires them.
- Keep prose quality first; LaTeX is the delivery format, not the writing method.

## The modes

### 0. Define & scope the topic — start here when the topic isn't sharp
**Ask and discuss before producing anything.** A thesis is won or lost on a sharply-defined purpose; a fuzzy topic flaws everything downstream. Drive the conversation toward a research **question**, not just a subject area. Probe these, one or two at a time, and reflect back what you hear:
- **The question.** What do you actually want to know? Push from broad subject → a researchable question with sub-questions. *"Bioimpedance and fatigue"* is a subject; *"can L-BIA detect acute fatigue and its day-to-day accumulation?"* is a question.
- **The gap.** What does the existing body of knowledge *not* answer adequately? The thesis exists to fill that.
- **Significance.** Who benefits — scientific contribution *and* practical/applied one? (Doctoral: original contribution to the discipline.)
- **Fit checks** (Edwardson's tests, worth surfacing): Does it interest you deeply enough to carry months of work? Is it something you'd enjoy explaining at a party? Does it help you professionally / could it become a journal article? Will it stay useful, not date instantly?
- **Feasibility.** Do you already have (or can you get) the data, sample, instrument, and ethics/IRB clearance in time? Scope down ruthlessly if not.
- **Learn the local rules.** Read 1–2 prior theses — ideally chaired by your supervisor — to calibrate expectations and format.

Output of this mode: a crisp one-paragraph **purpose statement** + the research question(s)/hypotheses + a note on significance and scope. That paragraph becomes the seed for Mode 1.

### 1. Outline / structure
Generate the chapter + subsection skeleton for the chosen level. Go down to the **subsection** level (the page-or-two unit) — that is what makes the work finishable. For each subsection, write a one-line statement of *what that subsection argues*, not just its topic. Use generic English section names by default for portable outlines, add Spanish equivalents when the thesis is in Spanish, and always adapt to local guidelines. Full chapter-by-chapter templates and what each must contain: read `structure.md`.

### 2. Draft sections
Write academic prose for a specific section using the author's real data, findings, and sources. Rules that prevent the most common failures:
- Use the writing moves in `writing-guide.md`: claim → evidence → interpretation; topic sentence → development → local conclusion; careful hedging; explicit transitions.
- **Lit review organizes by idea, never by author.** For each idea: common strands first, then departures. The review must conclude *what is known and what isn't* — that gap is what justifies the research questions/hypotheses.
- **Findings chapter reports results only** — no outside literature, no interpretation, no "this implies." Descriptive stats first, then hypothesis tests (in the same order the hypotheses were stated), then post-hoc. Every numeric claim gets a table or figure.
- **Discussion interprets, doesn't repeat.** Tie each finding back to the theoretical framework and to practice. State limitations, then future work, then a strong closing sentence. This is the highest-value chapter.
- **Methods justifies, not just describes** — say *why* this method/design/sample was appropriate and cite methodological references.

### 3. Review / edit
Apply both editing passes from `review-checklist.md`:
- **Micro**: spelling, grammar, consistent terminology, sentence/paragraph structure, word-choice variety.
- **Macro**: does each chapter flow from the last? Headings consistent? Transitions between major topics? Anything to streamline or expand? Does the Discussion actually answer "So what?"
Flag findings-chapter contamination (interpretation that belongs in Discussion) and lit-reviews that merely string abstracts together.

### 4. Process / planning
Make the work finishable with three process techniques:
- **Segment** the whole thesis into subsection-sized chunks (a page or two each) and tackle one at a time — never fixate on the whole at once. The subsection-level outline from Mode 1 *is* the segmentation.
- **Schedule** a sustainable cadence, e.g.: most working days write one new subsection (then chase the small nagging facts that came up); one day a week rewrite the most-recent sections to a polish; one day for logistics — deliver chapters, book supervisor/expert meetings, errands.
- **Reward** yourself at the end of each writing session — something small and pleasant. The blank-page wall crumbles when each chunk has a payoff.

Plus the finishing checklist: self-edit before any supervisor sees it (supervisors don't copy-edit); leave time for ≥2 supervisor read-throughs; committee gets it ~a week before the defense; reserve the room/forms; expect post-defense revisions. Don't promise a thesis can start and finish in one term — significant progress (data already being collected) should exist the term before submission.

## Quick reference

| Chapter | One job | Must NOT contain |
|---------|---------|------------------|
| Introduction / Purpose | State the question + why it matters (theoretical and practical significance) | Vague aims, no theoretical grounding |
| Literature review / Theoretical framework | Synthesize by idea -> expose the gap -> derive hypotheses | A chain of article summaries |
| Methodology | Justify + detail design, sample, instrument, analysis | Method with no justification |
| Findings / Results | Report results, tables/figures, in hypothesis order | Outside literature, interpretation |
| Discussion | Answer "So what?" vs theory + practice; limitations; future work | Mere restatement of results |
| Conclusion | Brief closure, strong final sentence | New unsupported claims |

## Common mistakes

- **Purpose too fuzzy** → the whole thesis is flawed from the outset. Nail Ch. 1 first.
- **Discussion = Findings reworded** → no "So what?". Always relate to theory *and* practice.
- **Interpretation leaking into Findings** → keep results clean; save meaning for Discussion.
- **Lit review as annotated bibliography** → must build to the gap that motivates the study.
- **Hypothesis tests out of order / no dummy tables** → report in the order hypotheses were stated.
- **Skipping rival hypotheses (TFM/tesis)** → state plausible alternative explanations explicitly.

## Supporting files
- `structure.md` — full chapter-by-chapter templates for undergraduate, master's, and doctoral empirical theses, with what each section must contain.
- `writing-guide.md` — practical paragraph, citation, evidence, results, discussion, and LaTeX writing patterns.
- `review-checklist.md` — micro + macro editing checklist and the empirical-thesis weakness list.

When sharing or installing this skill, keep the whole `thesis-writing/` folder together. `SKILL.md` depends on the supporting Markdown files by relative path.
