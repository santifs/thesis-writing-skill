# Thesis Writing Skill

An AI-agent skill for scoping, structuring, drafting, and reviewing empirical theses, dissertations, undergraduate theses, TFGs, master's theses, and TFMs.

The skill is intentionally format-neutral: it can help with Markdown, Word-oriented prose, Google Docs-oriented prose, or LaTeX. LaTeX is supported when the project uses it, but it is not required.

## What It Helps With

- Define and narrow a thesis topic before outlining.
- Turn a broad subject into research questions, hypotheses, scope, and significance.
- Build chapter and subsection outlines for undergraduate, master's, and doctoral empirical theses.
- Draft sections from evidence, data, figures, and sources.
- Review thesis drafts at macro and micro levels.
- Keep Results factual and Discussion interpretive.
- Write stronger paragraphs using claim, evidence, and interpretation.

## Skill Contents

```text
thesis-writing/
├── SKILL.md
├── structure.md
├── writing-guide.md
└── review-checklist.md
```

Keep the full `thesis-writing/` folder together. `SKILL.md` references the supporting Markdown files by relative path.

## Installation

Copy the `thesis-writing/` folder into your agent's local skills directory.

Examples:

```bash
cp -R thesis-writing ~/.codex/skills/
```

```bash
cp -R thesis-writing ~/.claude/skills/
```

The exact skills directory depends on the agent environment you use.

## Recommended Use

Use this skill when asking an AI coding or writing agent to help with thesis work, for example:

```text
Use the thesis-writing skill to help me define and scope my TFG topic.
```

```text
Use the thesis-writing skill to review my Discussion chapter.
```

```text
Use the thesis-writing skill to draft this Results section in LaTeX from these tables.
```

## License

MIT.
