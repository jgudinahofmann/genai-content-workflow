# GenAI Content Workflow (Public-Safe Playbook)

This repository contains **public-safe** artifacts that demonstrate how to design and scale an AI-generated content workflow:
- a cross-functional operating model
- practical evaluation methods (human rubric + error taxonomy)
- launch readiness guardrails (monitoring + rollback)
- a template prompt pattern (generic; not production IP)

> **Disclaimer:** This repo shares generalized process and templates. It does not contain proprietary prompts, internal tools, or confidential policies.

## Contents
- `docs/workflow_ai_generated_content.md` — workflow article (anonymized)
- `evaluation/human_rubric.md` — scoring rubric for reviewers
- `evaluation/error_taxonomy.md` — error categories for consistent labeling
- `launch/launch_checklist.md` — launch readiness checklist (quality, safety, monitoring, rollback)
- `templates/public_prompt_template.md` — a generic prompt template (safe to share)

## How to use
1. Start with the workflow doc and adapt roles/ownership to your org.
2. Use the rubric + taxonomy to build a repeatable evaluation loop.
3. Gate launches with the checklist (and keep the rollback plan explicit).
4. Use the public prompt template as a starting point for non-sensitive projects.
