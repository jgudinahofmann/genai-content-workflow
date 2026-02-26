# A Smarter Workflow for AI-Generated Content

A scalable, cross-functional process for producing high-quality AI-generated content with clear ownership, consistency, and measurable outcomes.

## Why this exists
The hard part of AI-generated content isn’t generating text — it’s ensuring outputs consistently align with:
- business goals
- tone and style guidelines
- safety and compliance constraints
- quality standards that scale

This workflow is designed to reduce rework, clarify ownership, and make iteration faster *before* heavier science/engineering work begins.

---

## The Workflow

### 1) PRD includes “AI content requirements”
The Product Owner starts with a PRD that includes:
- target use-case and context
- tone/style requirements
- constraints (length, structure, disallowed content)
- acceptance criteria and quality bar
- evaluation approach (how we’ll judge “good”)

### 2) A universal base prompt is defined and maintained
A central owner (often a Science/ML team) maintains a **base system prompt** that enforces shared constraints:
- safety / brand guidelines
- formatting rules and structural requirements
- consistent tone anchors
- hard constraints (e.g., character limits)

All project prompts build on top of this base prompt so requirements are inherited consistently.

### 3) Cross-functional prompt iteration using an LLM + a small sample set
Product and business partners iterate on a project-specific prompt using:
- the base prompt
- project requirements from the PRD
- a small sample input set (≈20 real-ish examples)

The goal is to converge on tone, structure, and correctness *before* requesting larger-scale dataset work.

### 4) Final prompt + expanded sample set for dataset work
Once the prompt is approved, the owner provides:
- the final prompt
- an expanded input sample set (≈100 items)
- any edge cases to include

### 5) Dataset creation + feedback loop
The Science/ML team uses the sample set to generate a training/evaluation dataset with:
- diversity
- consistency
- guideline adherence

They share results back for final review. If no blockers are found, the work proceeds toward production.

---

## Why this framework works
- **Alignment early:** requirements and ownership are defined up front  
- **Efficiency:** iteration happens cheaply before heavy dataset generation  
- **Consistency:** base prompt ensures shared constraints across projects  
- **Scalability:** repeatable across campaigns/verticals with minimal changes  

---

## Templates 
See `/templates` for:
- Prompt spec
- Dataset request checklist
- Quality rubric
- Launch readiness checklist
