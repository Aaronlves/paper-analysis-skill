---
name: paper-analysis
description: Systematically read and analyze academic papers, especially philosophy papers. Use when the user provides a paper, PDF, citation, abstract, notes, or text and asks for paper analysis, argument reconstruction, thesis extraction, objection and reply mapping, literature-review placement, bibliography extraction, source screening, or project relevance assessment.
---

# Paper Analysis

Use this skill to analyze papers as arguments, not as neutral summaries. Preserve the difference between what the author argues, what the evidence supports, and what the user or project should take from the paper.

Use related skills when available: use `pdf` for PDF extraction and visual checks, `zotero` for citation records, `philosophy-writing` for philosophical argument standards, and any user-provided project or literature-review skill for local research context.

## Core Commitments

- Read the full paper before finalizing the analysis when the full text is available. Do not infer the whole argument from the abstract or introduction.
- Distinguish the author's claims from the user's assessment or project use.
- Reconstruct the strongest plausible version of the argument before criticizing it.
- Support paper-specific claims with page citations whenever pagination is available.
- Never invent quotations, page numbers, bibliography entries, DOI values, or argumentative steps.
- Use the user's requested citation style. If none is specified, use APA 7 for references.
- Preserve source PDFs, notes, and unrelated workspace files.
- Treat current local files as authoritative when they differ from memory or prior summaries.

If the user only provides an abstract or excerpt, state that the analysis is provisional and limited to the supplied material.

## Workflow

### 1. Identify the Source

Record, when available:

- Title, author, year, venue, DOI, stable URL, and page range.
- Paper type: article, book chapter, conference paper, preprint, review essay, reply, commentary, or dissertation chapter.
- Version status: published, accepted manuscript, preprint, draft, or unknown.
- Whether the file has reliable selectable text, page numbers, notes, bibliography, figures, or appendices.

If the PDF is scanned or extraction is unreliable, use OCR or page rendering and visually verify crucial passages before relying on them.

### 2. Read for Structure

Identify:

- The central question or problem.
- The paper's thesis in one or two precise sentences.
- The dialectical target: view, argument, distinction, assumption, method, case, or literature gap.
- The main premises or supporting claims.
- Intermediate conclusions.
- The route from premises to the final conclusion.
- The strongest objection considered by the author.
- The author's reply.
- Any premise, inference, case, or interpretation left unsupported.

When useful, provide a numbered premise-conclusion reconstruction. Do not force a formal reconstruction when the paper is primarily interpretive, historical, empirical, or methodological; explain its actual structure instead.

### 3. Assess the Support

Explain what the author relies on:

- Thought experiments or cases.
- Conceptual distinctions.
- Textual interpretation.
- Formal models or proofs.
- Empirical studies or datasets.
- Explanatory virtues, theoretical costs, or burden-shifting.
- Intuitions, common judgments, linguistic data, or practice-based evidence.

For each major piece of support, state what claim it supports and whether the support is sufficient. Mark whether weaknesses concern a false premise, missing evidence, invalid inference, ambiguous concept, unrepresentative case, or unsupported methodological assumption.

### 4. Extract Key Distinctions

Define the paper's central distinctions in plain language. Explain:

- Why the distinction is introduced.
- What argumentative work it performs.
- Whether it is exhaustive, exclusive, stable, or contested.
- What nearby distinction it should not be confused with.
- How the paper's terminology differs from standard or neighboring uses.

Use examples when an abstract distinction could otherwise look merely verbal.

### 5. Place the Paper in the Debate

Identify:

- The earlier position or problem to which the paper responds.
- Its main allies, targets, and competitors.
- What it changes in the debate.
- What remains unresolved after its intervention.
- Which broader literature-review problem narrative it belongs in.

Do not turn debate placement into an author list. Explain relations among claims, problems, methods, or distinctions.

### 6. Assess Project Relevance

When the user has a research project, thesis, chapter, literature review, or argument map, state explicitly:

- Whether the paper is an ally, target, complication, source of machinery, background source, objection source, or methodological model.
- Where it converges with the user's project.
- Where it diverges or creates pressure.
- What the user should answer, revise, incorporate, or set aside.
- The best placement: main text, objection section, literature review, footnote, background section, bibliography, or future-reading list.
- A small set of key passages with page numbers, only when exact wording matters.

Do not treat project memory as evidence. Verify claims against the paper and current project documents.

### 7. Screen the Bibliography

Extract references worth following. Prioritize sources that:

- Defend, attack, or clarify the main thesis.
- Supply recurring distinctions or cases.
- Represent major positions in the debate.
- Are repeatedly cited as foundational or recent interventions.
- Would help the user understand the paper's assumptions or reception.

Exclude purely tangential references unless the user asks for comprehensive bibliography extraction.

### 8. Write the Analysis

Use this default structure unless the user requests another format:

```markdown
# Author (Year): Short Title

## Bibliographic Information

## Central Question

## Thesis

## Argument Structure

## Supporting Evidence

## Key Distinctions

## Objections and Replies

## Position in the Debate

## Relevance to the User's Project

## Key Passages

## References Worth Following

## Open Questions
```

Adapt headings when the paper's genre requires it, but retain the substantive coverage.

If saving a file, use a descriptive ASCII filename such as `<author-year-keywords>.md`, unless the user's project has an existing naming convention.

## Optional Project File Updates

Update argument maps, literature-review files, bibliographies, reading lists, or historical lineage files only when the user asks or provides the relevant paths.

Before changing shared research files:

1. Inspect existing organization and naming conventions.
2. Preserve the file's structure and citation style.
3. Add only claims supported by the paper analysis.
4. Avoid mechanically changing counts or summaries without verifying them.
5. Keep speculative relevance separate from confirmed project use.

If the user has no established project files, offer a concise standalone analysis instead of creating a pipeline.

## Quality Check

Before finishing, verify that:

- The analysis says whether the full paper was read.
- The thesis is precise and charitable.
- The argument is reconstructed rather than merely summarized.
- Major support is tied to specific claims.
- Page citations are accurate where available.
- The author's view and the user's assessment are clearly separated.
- Debate placement is relational, not just bibliographic.
- Project relevance is concrete when project context exists.
- Bibliography recommendations are screened, not dumped.
- Any saved files follow the user's naming and folder conventions.
