# Human Evaluation Rubric (AI-Generated Content)

Use this rubric to score outputs consistently during iteration and before launch.

## Scoring (1–5 each)
1) **Relevance / Task success**  
Does the output address the intended task correctly?

2) **Tone & style alignment**  
Does it match the intended voice and style guidelines?

3) **Clarity & readability**  
Is it easy to understand? Natural US English? No awkward fragments?

4) **Truthfulness / Non-misleading**  
No invented specs, no exaggerated claims, no implied guarantees.

5) **Safety & compliance (high-level)**  
Avoid disallowed content categories and sensitive personal attributes.

6) **Format correctness** (if applicable)  
Meets schema/length limits/structure requirements.

## Overall rating
- **Go**: average ≥ 4.3 and no critical safety issues
- **Iterate**: average 3.5–4.2 or recurring failure mode
- **Block**: any critical safety/policy violation

## Reviewer notes
Capture:
- what was good
- what failed
- how to fix (prompt change, data change, rule, or UI constraint)
