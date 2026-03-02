# Launch Checklist (AI-Generated Content)

## 1) Requirements & alignment
- [ ] PRD includes content requirements + acceptance criteria
- [ ] Disallowed content categories documented (high-level)
- [ ] Output format + length constraints defined
- [ ] Stakeholders aligned on quality bar and risks

## 2) Evaluation readiness
- [ ] Human rubric defined and reviewers trained
- [ ] Error taxonomy in place for labeling
- [ ] Sample sets include representative and edge cases
- [ ] Clear go/no-go thresholds (quality + safety)

## 3) Implementation guardrails
- [ ] Schema validation (strict JSON if needed)
- [ ] Length checks
- [ ] Banned phrase / unsafe content filters (where applicable)
- [ ] Logging plan (privacy-safe; no personal data)

## 4) Experimentation (if applicable)
- [ ] Success metrics defined
- [ ] Monitoring metrics defined (quality proxy, CTR/open rate, complaints)
- [ ] A/B test plan and ramp schedule
- [ ] Alert thresholds and on-call ownership

## 5) Rollback plan (non-negotiable)
- [ ] Explicit rollback trigger conditions
- [ ] Rollback mechanism tested
- [ ] “Safe default” behavior defined if generation fails

## 6) Post-launch operations
- [ ] Dashboard or reporting cadence established
- [ ] Feedback loop: top errors → prompt/data fixes
- [ ] Versioning: track prompt/model versions + change log
