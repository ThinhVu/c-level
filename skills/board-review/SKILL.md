---
name: board-review
description: Runs a 360-degree executive health review across Product, Growth, Tech, and Revenue, outputting an alignment scorecard and next 30-day priorities. Triggers on /board-review.
---

# /board-review

> **Governance Principle**: What gets measured gets managed; what gets reviewed gets aligned.  
> *"A monthly board review keeps founders honest, prevents feature creep, and aligns every line of code with enterprise value."*

## Purpose & Objective
`/board-review` convenes the virtual AI C-Suite (CEO, CPO, CMO, CTO, CRO) to conduct a holistic, 360-degree audit of the product's operational health. It evaluates:
- **Product Health (CPO)**: Feature adoption, onboarding friction, core retention.
- **Growth Health (CMO)**: Organic acquisition channels, visitor conversion, distribution loops.
- **Revenue Health (CRO)**: MRR growth, gross margins, free-to-paid conversion rates.
- **Technical Health (CTO)**: Bug frequency, PR velocity, infrastructure cost per customer.

## When to Reach for It
- At the end of every month or quarter to take stock of progress.
- When feeling overwhelmed by tactical tasks and needing a high-level strategic reset.
- Preparing for an investor update, co-founder meeting, or public build-in-public retrospective.
- Triggered by typing `/board-review`.

---

## Output Deliverable
Generated at `c-suite/board-scorecard.md` using `templates/board-scorecard.md.template`:
- Executive Traffic Light Dashboard (🟢 Green / 🟡 Yellow / 🔴 Red) with 1-10 scores per department.
- Key metrics snapshot comparing actuals vs targets.
- Resolution of critical open strategic dilemmas.
- Top 3 prioritized objectives for the next 30-day operating cycle.
