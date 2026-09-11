---
name: prioritize-roadmap
description: Evaluates feature candidates, customer requests, and backlogs using RICE scoring to build a ruthless, value-driven product roadmap and a Will-NOT-Build list. Triggers on /prioritize-roadmap.
---

# /prioritize-roadmap

> **CPO Principle**: Product management is the art of saying NO to good ideas so you can execute great ones.  
> *"Every feature you build adds permanent maintenance overhead and cognitive burden to your users. Defend your product surface area."*

## Purpose & Objective
`/prioritize-roadmap` eliminates roadmap guesswork and subjective opinions. It ingests feature requests, user feedback, and internal ideas, scoring each candidate with the **RICE Framework** adapted for high-velocity software:
$$\text{RICE Score} = \frac{\text{Reach} \times \text{Impact} \times \text{Confidence}}{\text{Effort}}$$

It outputs a ranked backlog and an explicit **"Will NOT Build"** list to safeguard team focus.

## When to Reach for It
- Backlog is overwhelming and the team is unsure what to build next.
- Evaluating a major customer feature request or partnership integration.
- Planning the next development sprint.
- Triggered by typing `/prioritize-roadmap [list of candidate features or path to issue backlog]`.

---

## The RICE Scoring Parameters

1. **Reach (1 - 100%)**: What percentage of your core ICP will actively use this feature within 90 days?
2. **Impact (0.25 - 3.0)**:
   - 3.0 = Massive (Directly converts free users to paid or prevents churn)
   - 2.0 = High (Significantly improves core activation)
   - 1.0 = Medium (Nice-to-have improvement)
   - 0.5 = Low (Minor convenience)
   - 0.25 = Minimal (Cosmetic tweak)
3. **Confidence (50% - 100%)**:
   - 100% = Backed by direct customer data and behavior
   - 80% = Backed by qualitative feedback or competitor benchmark
   - 50% = Educated hunch
4. **Effort (1 - 5)**:
   - 1 = Autonomous D-Level sprint (< 48 hrs)
   - 2 = Moderate complexity (1 week)
   - 3 = Heavy backend / schema changes (2 weeks)
   - 5 = High risk / multi-system re-architecture

---

## Output Deliverable
Generated at `c-suite/roadmap.md` using `templates/roadmap-prioritization.md.template`:
- Ranked Roadmap Matrix with full RICE breakdown.
- Top #1 initiative flagged for immediate handoff via `/order-feature`.
- Explicit "Will NOT Build" list with documented strategic reasons.
