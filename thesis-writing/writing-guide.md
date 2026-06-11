# Practical writing guide

Use this file when drafting or revising actual thesis prose, not just planning the structure.

## Core principle

Every paragraph should do one job in the argument. Avoid paragraphs that merely collect facts. A useful academic paragraph usually has:

1. **Topic sentence**: the point the paragraph advances.
2. **Evidence or development**: data, source-based evidence, methodological detail, or reasoning.
3. **Interpretation**: what the evidence means for the research question.
4. **Local closure**: a sentence that links to the next paragraph or subsection.

If a paragraph has no point, split, move, or cut it.

## Claim -> evidence -> interpretation

For factual or analytical claims, use this order:

- **Claim**: what you want the reader to accept.
- **Evidence**: citation, result, table, figure, excerpt, or local artifact.
- **Interpretation**: why that evidence matters and how strongly it supports the claim.

Weak pattern:

> Several studies have examined fatigue. Study A found X. Study B found Y. Study C found Z.

Stronger pattern:

> Prior work converges on the idea that fatigue has both acute and cumulative components. Evidence for the acute component comes from..., whereas longitudinal studies suggest... However, these studies leave unresolved whether...

## Literature review writing

Organize by ideas, mechanisms, methods, or debates, not by author. A good literature review subsection should answer:

- What is the shared finding or theory?
- Where do studies disagree?
- What methods or populations dominate the evidence?
- What limitation, blind spot, or unresolved question remains?
- How does that gap justify the thesis question or hypothesis?

Use authors as evidence for an idea, not as the structure of the section.

## Methods writing

Methods should be reproducible and justified. For each design choice, include:

- what was done;
- why it was appropriate for the research question;
- what assumptions it introduces;
- what limitation follows from that choice;
- which methodological source or institutional protocol supports it, when relevant.

Avoid a methods chapter that only describes steps. The reader needs to see why those steps are defensible.

## Results writing

Results are factual. Do not compare with the literature or explain broader meaning here.

Recommended order:

1. Remind the reader which question or hypothesis is being tested.
2. State the analysis performed.
3. Report the result with the necessary statistic, table, or figure.
4. State the direct result only.

Example pattern:

> To test H1, [analysis] compared [variables/groups]. The result showed [direction/magnitude/statistic], as reported in Table X. Therefore, H1 was [supported/not supported/partially supported].

Move sentences such as "this suggests", "this may explain", or "consistent with prior work" to the Discussion.

## Discussion writing

Discussion interprets the findings. A strong discussion subsection usually does this:

1. Restate the finding briefly, without re-reporting all numbers.
2. Explain what it means for the research question.
3. Compare with the theoretical framework and prior literature.
4. Explain practical or applied implications.
5. Name limitations and alternative explanations.
6. End with what the reader should now understand differently.

Do not use the Discussion as a second Results chapter.

## Hedging and strength of claims

Match wording to evidence strength.

- Strong evidence: "demonstrates", "shows", "supports".
- Moderate evidence: "suggests", "is consistent with", "indicates".
- Weak or indirect evidence: "may suggest", "could be interpreted as", "raises the possibility".

Avoid overclaiming novelty or impact. Prefer precise claims over impressive claims.

## Citation integration

Use citations to support specific claims, not entire paragraphs. The sentence should make clear what the cited source supports.

Better:

> This instrument has shown acceptable test-retest reliability in healthy adults (Author, Year).

Weaker:

> This instrument is widely used. It is reliable and valid. It has many applications (Author, Year).

If the citation only supports part of the sentence, rewrite the sentence.

## Transitions

Use transitions to show argument movement:

- Addition: "In addition", "A related line of work..."
- Contrast: "However", "By contrast", "This evidence is less clear for..."
- Gap: "Despite this convergence", "What remains unresolved is..."
- Consequence: "This matters because", "As a result..."
- Scope: "For the purposes of this thesis..."

Transitions should describe logical relationships, not merely decorate the prose.

## LaTeX drafting

Use LaTeX only when it is the chosen project format.

For section drafts, prefer fragments like:

```latex
\section{Discussion}
\label{sec:discussion}

The present results suggest...
```

Do not invent a preamble, bibliography system, package list, or document class unless asked. If citation keys are missing, use explicit placeholders:

```latex
Prior work has treated fatigue as a multidimensional construct \cite{key_needed_fatigue_definition}.
```

At the end of the draft, list unresolved placeholders and the evidence needed to replace them.

## Revision pass

Before polishing sentences, check:

- Does each section answer the question it is supposed to answer?
- Does each paragraph advance one point?
- Is every important claim supported?
- Are results and interpretation kept in the correct chapters?
- Are limitations visible rather than hidden?

Only then edit style, grammar, terminology, and citation formatting.
