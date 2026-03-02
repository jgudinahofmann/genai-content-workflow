# Error Taxonomy (Labeling Guide)

Tag each failure with 1–2 labels for consistent analysis.

## Recognition / relevance
- **Wrong item / mismatch** — output doesn’t match the input
- **Missing key detail** — leaves out required info
- **Overly generic** — could apply to many items; weak recognition

## Language quality
- **Awkward phrasing** — unnatural, fragmented, or confusing
- **Grammar / spelling** — errors reduce trust
- **Redundant** — repeats same idea across fields

## Safety & compliance (high-level)
- **Disallowed content** — adult, hate, violence, illegal/regulated goods
- **Sensitive attribute** — references personal identity attributes
- **Policy risk / innuendo** — could be misinterpreted

## Truthfulness
- **Hallucinated detail** — adds facts not in input
- **Unverifiable claim** — “guaranteed”, “best”, “investment-grade”
- **Misleading implication** — implies ownership, endorsement, or certainty

## Formatting / constraints
- **Schema invalid** — not valid JSON / wrong keys
- **Length violation** — exceeds character limits
- **Structure violation** — wrong ordering or missing field

## UX / tone
- **Too pushy** — spammy or guilt-based
- **Fear/scarcity** — false urgency, countdown-style language
- **Wrong audience voice** — third-person distancing, robotic tone
