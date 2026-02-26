# A Smarter Workflow for AI-Generated Content

A practical, cross-functional workflow for producing high-quality AI-generated content with clear ownership, consistency, and measurable outcomes.

## Why this exists
Generating text is the easy part. The hard part is ensuring every output consistently aligns with:
- product objectives
- tone and style guidelines
- safety/compliance constraints
- quality standards that scale

This workflow reduces rework, clarifies ownership, and accelerates iteration before larger-scale dataset work begins.

---

## The Workflow

### 1) PRD includes AI content requirements
The Product Owner starts with a PRD that captures both business context and technical requirements, including:
- target user intent and context
- tone/style requirements
- constraints (length, structure, disallowed content)
- acceptance criteria and quality bar
- evaluation approach (how “good” is judged)

### 2) A universal base prompt is maintained
A central owner (often an ML/Science team) maintains a **base system prompt** that enforces shared constraints:
- safety and brand guidelines
- formatting rules and structural requirements
- consistent tone anchors
- hard constraints (e.g., character limits)

All project prompts build on top of this base prompt so constraints are inherited consistently.

### 3) Cross-functional iteration with a small sample set
Product + business partners iterate on project-specific prompts using:
- the base prompt
- requirements from the PRD
- a small sample input set (≈20 examples)

The goal is to converge on clarity, tone, and correctness before requesting larger dataset work.

### 4) Final prompt + expanded sample set
Once the prompt is approved, the owner provides:
- the final prompt
- an expanded input set (≈100 items)
- edge cases and exclusions to include

### 5) Dataset creation + feedback loop
The ML/Science team generates a dataset ensuring:
- diversity and coverage
- guideline adherence
- consistency in tone/format

The dataset is shared back for final review. If no blockers are found, the work proceeds toward production.

---

## Why this framework works
- **Alignment early:** requirements and ownership are defined up front
- **Efficiency:** iteration happens cheaply before heavy dataset generation
- **Consistency:** base prompt enforces shared constraints across projects
- **Scalability:** repeatable across campaigns/verticals with minimal changes

---

## What’s in this repo
- `prompts/auction_reminder_copy_prompt.md` — a public-safe prompt example for generating auction reminder copy (title, subject-line piece, preheader)
- `templates/` — reusable templates for prompt specs, quality rubrics, and launch readiness

---

## Disclaimer
This repository contains general process guidance and example prompt patterns. It does not include proprietary policies, internal tools, or confidential data.
