---
name: paper-analysis
description: Systematically triage, read, and analyze academic papers, especially philosophy papers. Use when the user provides a paper, PDF, citation, abstract, notes, or text and asks for relevance scoring, paper analysis, argument reconstruction, thesis extraction, concept analysis, objection and reply mapping, evidence assessment, historical placement, literature-review placement, bibliography screening, or project relevance assessment.
---

# Paper Analysis

Analyze papers as arguments and contributions to a knowledge base, not as neutral summaries. Preserve the differences among what the author argues, what the evidence supports, what other sources report, and what the user or project should take from the paper.

Use related skills when available: use `pdf` for PDF extraction and visual checks, `zotero` for citation records, `philosophy-writing` for philosophical standards, and any user-provided project or literature-review skill for local context and output rules.

## Core Commitments

- Survey the whole paper before rating or reporting on it. Do not infer the argument from the abstract or introduction alone.
- Read closely before giving a full analysis when the full text is available.
- Distinguish the author's claims from the analyst's assessment and the user's project commitments.
- Reconstruct the strongest plausible version of an argument before criticizing it.
- Tie major premises to the evidence or argument offered for them.
- Support paper-specific and contested claims with page citations whenever pagination is available.
- Never invent quotations, page numbers, bibliography entries, DOI values, evidence, or argumentative steps.
- You are allowed to say “I don't know” or “I am not sure” if you are uncertain about the relevant information.
- Use the user's requested citation style. If none is specified, use APA 7.
- Preserve source files, notes, and unrelated workspace materials.
- Treat current local files as authoritative when they differ from memory or prior summaries.

If the user provides only an abstract or excerpt, state that the analysis is provisional and limited to the supplied material. Do not apply a full-text reading claim.

## Use Two Reading Passes

### Pass 1: Identify, Survey, and Rate

Record, when available:

- one complete citation in the user's requested style, or APA 7 by default;
- version status: published, accepted manuscript, preprint, draft, or unknown;
- source file or supplied source location;
- whether the file has reliable selectable text, pagination, notes, bibliography, figures, or appendices;
- reading status: coarse survey, thorough reading, or analysis limited to supplied material.

Put the complete citation under the report's Metadata section as `Reference`. Do not repeat bibliographic information already contained in that citation, including record title, authors, year, venue, DOI or stable identifier, page range, or paper type. Record only nonduplicative source and reading information as separate metadata fields.

If extraction is unreliable, use OCR or page rendering and visually verify crucial passages.

Survey the whole paper:

1. Read the abstract, introduction, conclusion, headings, and explicit statements of thesis and structure.
2. Skim every section.
3. Inspect passages containing the principal arguments, objections, evidence, conceptual machinery, and historical framing.
4. Record the central question, thesis, dialectical target, main argumentative route, and likely project use.

When the user has a research project, rate prospective project relevance from 0 to 5 and explain the rating:

- `0`: no identifiable use.
- `1`: remote topical overlap.
- `2`: limited background or bibliographic use.
- `2.5`: borderline; no clear argumentative role yet.
- `3`: clear use for a concept, premise, objection, case, or debate narrative.
- `4`: direct and substantial use in a live argument, chapter, or literature review.
- `5`: central source that materially shapes the thesis, a core premise, or a major objection and reply.

The score measures project usefulness, not philosophical quality. Do not inflate it because a paper shares keywords with the project. A rating above 2.5 requires a specific prospective role.

If no project context exists, omit numerical relevance scoring unless the user requests it and proceed at the depth appropriate to the request.

### Pass 2A: Thorough Analysis Above 2.5

For project-relevance ratings above 2.5, read the full paper closely and produce a full analysis. Identify:

- every central concept and distinction, including definitions and argumentative functions;
- the central question, thesis, and dialectical target;
- positions, arguments, assumptions, or interpretations the author opposes;
- each major argument the author supports;
- the premises, intermediate conclusions, and route to the final conclusion;
- the evidence or argument supporting each major premise;
- the historical narrative used to frame the problem and what it presupposes or omits;
- the strongest objection considered and the author's reply;
- inferential gaps, ambiguous concepts, unsupported premises, evidential weaknesses, and relevant counterevidence;
- relations to earlier positions, allies, targets, competitors, and unresolved questions.

Use premise-conclusion reconstruction when it clarifies the argument. Do not force formalization on interpretive, historical, empirical, or methodological papers whose real structure is better represented another way.

### Pass 2B: Concise Report at 2.5 or Below

For ratings of 2.5 or below, avoid unnecessary line-by-line reconstruction. Produce a concise report containing:

- a complete citation plus nonduplicative source, version, reading-status, and selectable-text information under Metadata;
- rating and rationale;
- reading status as coarse reading and relevance triage;
- central question, thesis, dialectical target, and main argumentative route;
- principal kind of evidence;
- limited possible relevance and recommended disposition;
- only the strongest references worth following;
- one or two open questions when useful.

If source corruption, missing pages, or ambiguity prevents responsible triage, resolve that problem before rating.

## Analyze Concepts and Arguments

For each central concept or distinction, explain:

- what it means in the paper;
- why the author introduces it;
- what argumentative work it performs;
- whether it is exhaustive, exclusive, stable, or contested;
- what nearby concept it should not be confused with;
- whether the author's use differs from standard or neighboring uses.

For each major argument, distinguish:

- **Reconstruction:** State the premises and conclusion charitably.
- **Premise support:** Identify what supports each premise.
- **Logical check:** Assess validity, inferential gaps, equivocation, suppressed premises, and scope shifts.
- **Content check:** Assess the clarity, plausibility, and independent support of the premises.
- **Evidence check:** Assess whether the evidence supports the premise and whether checked empirical, textual, or argumentative counterevidence exists.

Identify the kinds of support used: thought experiments, cases, conceptual distinctions, textual interpretation, formal models, empirical data, intuitions, linguistic evidence, explanatory virtues, theoretical costs, or burden-shifting.

## Place the Paper Relationally

Identify:

- the earlier position or problem to which the paper responds;
- its allies, targets, and competitors;
- what intervention it makes;
- what changes after that intervention;
- what remains unresolved;
- which broader literature-review or historical narrative it belongs to.

Do not replace relational placement with an author list. Separate the paper's historical narrative from independently verified history. Cite the paper for its own narrative; mark second-hand claims until original sources are checked.

## Assess Project Relevance

When project context exists, state:

- whether the paper is an ally, target, complication, precursor, source of machinery, objection source, background source, or methodological model;
- where it converges with or pressures the project;
- which concept, premise, objection, chapter, or literature-review problem it bears on;
- what the user should incorporate, answer, revise, or set aside;
- its best placement: main text, argument section, objection section, literature review, concept file, footnote, bibliography, or future-reading list;
- key passages with page numbers only when exact wording matters.

Recommend citing the paper only when it does at least one of the following:

1. explicates a concept;
2. supports a premise;
3. exhibits an implication of the project;
4. supplies a vivid case for or against a premise;
5. gives an independent argument for or against a project claim;
6. contributes materially to the background or development of a relevant debate.

Do not recommend citation for mere topical similarity, prestige, name-checking, or bibliography padding. Do not treat project memory or management files as academic evidence.

## Screen the Bibliography

Prioritize references that defend, attack, or clarify the main thesis; supply recurring distinctions or cases; represent major positions; provide foundational sources; or constitute important recent interventions.

For each selected reference, state why it is worth following and what it may contribute. Separate:

- verified sources already read or analyzed;
- follow-up leads identified only through the paper.

Never use an unread bibliography item as independent support. Do not promote its claims into argument maps, historical narratives, or literature reviews until the relevant content is checked.

## Write the Report

Use this full structure for a thorough analysis unless the user's project supplies a more specific template:

```markdown
# Author (Year): Short Title

## 1. Metadata
**Reference:** [Complete citation]
**Version status:**
**Source file:**
**Selectable-text reliability:**
**Reading status:** Thorough reading
## 2. Project Relevance Rating
## 3. Relations to the Project and Previous Literature
## 4. Concepts, Question, Thesis, and Dialectical Target
## 5. Arguments and Checks
## 6. Evidence and Evidence Check
## 7. Strongest Objection and Reply
## 8. Contribution and Historical Placement
## 9. Bibliography Screening
### Verified Sources Worth Using
### Follow-Up Leads Requiring Verification
## 10. Problems and Open Questions
```

Use this structure for a concise triage report:

```markdown
# Author (Year): Short Title

## Metadata
**Reference:** [Complete citation]
**Version status:**
**Source file:**
**Selectable-text reliability:**
**Reading status:** Coarse survey and relevance triage
## Relevance Rating
## Gist
## Limited Project Relevance
## References Worth Following
## Open Questions
```

Adapt headings to the paper's genre without omitting the required substance. Put any additional works actually cited in the report under an `Additional References Used` subsection within Metadata. Do not add a separate References section at the end of the report. Bibliography Screening remains a distinct analytical section for follow-up sources and must not duplicate the analyzed paper's citation. If saving a file, use a descriptive ASCII filename such as `<author-year-keywords>.md` unless the project has an established convention.

## Update Project Files Carefully

Update argument maps, literature-review files, bibliographies, reading lists, historical lineages, or project memory only when the user requests it or supplies a project workflow that calls for it.

Before changing shared research files:

1. Inspect their organization, naming, and citation conventions.
2. Add only claims supported by the analyzed paper or separately verified sources.
3. Preserve distinctions between verified sources, second-hand reports, and follow-up leads.
4. Avoid mechanically changing counts, summaries, or every possible target.
5. Keep speculative relevance separate from confirmed project use.
6. Update stable project memory only when the user accepts a commitment or authoritative project files already entail it.

If no project pipeline exists, produce a standalone analysis instead of creating one without permission.

## Quality Check

Before finishing, verify that:

- the report accurately states coarse or thorough reading status;
- the relevance rating has a concrete project-based rationale;
- the thesis and dialectical target are precise and charitable;
- major arguments are reconstructed rather than merely summarized;
- every major premise is connected to its support;
- logical, content, and evidence checks remain distinct;
- page citations and metadata are accurate where available;
- bibliographic information appears once in the Metadata citation rather than in duplicate fields;
- no separate References section appears at the end of the report;
- the author's claims, other sources' claims, and the analyst's assessment remain separate;
- debate placement is relational, not merely bibliographic;
- bibliography recommendations are screened and unread leads are labeled;
- saved files follow the user's naming and folder conventions.
