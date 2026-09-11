---
name: tech-roi
description: Evaluates technical debt impact on velocity, cloud infrastructure costs, AI inference unit economics, and architectural scaling ROI. Triggers on /tech-roi.
---

# /tech-roi

> **CTO Principle**: Technical debt is financial debt; if the interest rate exceeds your shipping speed, you go bankrupt.  
> *"Engineers want to refactor everything; founders want to ship everything. The CTO's job is to calculate the ROI of engineering time."*

## Purpose & Objective
`/tech-roi` provides clear-eyed financial and operational analysis of the product's engineering foundation:
1. **Velocity Tax**: How much is legacy architecture slowing down new feature delivery?
2. **Infrastructure Burn**: Auditing cloud bills, database instance sizing, cache hit rates, and third-party API consumption.
3. **AI Inference Unit Economics**: Breaking down token costs per user interaction against subscription revenue to prevent subsidized negative margins.
4. **Refactoring ROI**: Calculating whether spending 2 weeks refactoring will genuinely yield faster cycle times or if it's engineering vanity.

## When to Reach for It
- Development velocity feels sluggish and PR review cycles are dragging.
- Cloud or LLM API invoices are spiking disproportionately to revenue.
- Preparing for a database migration, cache layer addition, or service decoupling.
- Triggered by typing `/tech-roi`.

---

## Output Deliverable
Generated at `c-suite/tech-roi-audit.md`:
- Technical Debt Tax assessment (% of engineering capacity lost to friction).
- Cloud & LLM unit cost breakdown per active customer.
- High-ROI engineering recommendations ranked by payback period.
