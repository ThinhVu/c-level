---
name: retention-audit
description: Audits user onboarding friction, Time-to-Value (TTV), churn risks, and designs habit-forming retention loops to boost user stickiness. Triggers on /retention-audit.
---

# /retention-audit

> **CPO / Head of UX Principle**: Acquisition fills the bucket, but retention keeps the water in.  
> *"A product with a 10% monthly churn rate must replace its entire customer base every 10 months just to stay flat."*

## Purpose & Objective
`/retention-audit` analyzes the user journey from initial signup to daily/weekly active usage. It pinpoints:
1. **Friction Hotspots**: Unnecessary form fields, mandatory credit cards, complex setup steps that cause drop-off before the "Aha!" moment.
2. **Time-to-Value (TTV)**: How many seconds or clicks elapse before a new user experiences the core payoff of the software? (Target: < 90 seconds).
3. **Churn Drivers**: Why do users abandon the product after day 3?
4. **Engagement Triggers**: Designing automated re-engagement nudges (email digests, desktop alerts, webhook status reports).

## When to Reach for It
- Signups are increasing but Day-7 / Day-30 active users are declining.
- Users drop off during initial workspace configuration or onboarding.
- Evaluating churn survey feedback or cancellation requests.
- Triggered by typing `/retention-audit`.

---

## Output Deliverable
Generated at `.c-level/retention-audit.md`:
- Onboarding friction teardown with click-by-click analysis.
- Concrete recommendations to compress Time-to-Value to under 90 seconds.
- Habit loop blueprint (Trigger -> Action -> Variable Reward -> Investment).
- 3 high-impact retention quick wins ready for delegation to D-Level.
