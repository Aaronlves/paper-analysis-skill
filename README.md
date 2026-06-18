# Paper Analysis Skill

A general Codex skill for analyzing academic papers, especially philosophy papers, as arguments rather than neutral summaries.

The skill guides Codex to read papers carefully, reconstruct argument structure, assess support, map objections and replies, extract key distinctions, screen bibliographies, and explain relevance to a user's research project when project context is provided.

## What It Helps With

- Reading and analyzing academic papers or PDFs
- Extracting a paper's central question and thesis
- Reconstructing arguments in premise-conclusion form
- Identifying objections, replies, unsupported premises, and weak inferences
- Assessing evidence, cases, conceptual distinctions, and methodology
- Placing a paper within a debate or literature-review narrative
- Screening references worth following
- Explaining how a paper supports, challenges, or complicates a project

## Install

Clone this repository into your Codex skills folder:

```bash
git clone https://github.com/Aaronlves/paper-analysis-skill.git ~/.codex/skills/paper-analysis
```

If you already have a local copy, update it with:

```bash
cd ~/.codex/skills/paper-analysis
git pull
```

## Usage

Ask Codex to analyze a paper, PDF, abstract, excerpt, or citation. For example:

```text
Read this paper in full, reconstruct its argument, and assess whether the support is sufficient.
```

```text
Analyze this philosophy paper and identify its central thesis, main premises, objections, and replies.
```

```text
Place this article in the debate and explain whether it is an ally, target, complication, or background source for my project.
```

```text
Extract the references worth following from this paper and explain why each one matters.
```

## Skill Contents

```text
SKILL.md              Core skill instructions
agents/openai.yaml    Codex UI metadata
```

## Core Principles

The skill guides Codex to:

- Read the full paper when available
- Distinguish the author's claims from the user's assessment
- Reconstruct the strongest plausible version of the argument before criticizing it
- Use page citations when pagination is available
- Avoid inventing quotations, page numbers, citations, or argumentative steps
- Treat debate placement as relations among claims, not just a list of authors
- Update project files only when the user asks or provides paths

## Repository

GitHub: <https://github.com/Aaronlves/paper-analysis-skill>
