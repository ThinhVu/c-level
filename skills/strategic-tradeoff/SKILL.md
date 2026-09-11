---
name: strategic-tradeoff
description: Acts as an executive sounding board to evaluate high-stakes dilemmas like rewrite vs refactor, build vs buy, pivot vs persevere, or open-source vs commercial. Triggers on /strategic-tradeoff.
---

# /strategic-tradeoff

> **CEO Principle**: Strategy is choosing what NOT to do and accepting the second-order consequences.  
> *"Every strategic choice has a hidden bill attached. Great executives choose which bill they are willing to pay."*

## Purpose & Objective
`/strategic-tradeoff` provides rigorous executive deliberation for difficult, high-stakes decisions facing an existing product. It models the decision through the lenses of CEO (Vision & Focus), CPO (Customer Experience), CTO (Technical Feasibility & Velocity), and CRO (Revenue & Margins).

## High-Stakes Dilemmas Evaluated
- **Rewrite vs Refactor**: Should we rewrite the core backend in Go/Rust or incrementally refactor the existing Node/Python service?
- **Build vs Buy**: Should we build custom in-house authentication/billing/search or integrate Clerk/Stripe/Algolia?
- **Monetize Now vs Accumulate Users**: Should we turn on paywalls today or optimize for user acquisition and mindshare first?
- **Open Source (OSS) vs Proprietary**: Should we open-source the core utility and monetize hosted enterprise features, or keep the entire IP proprietary?
- **Feature Pivot vs Double Down**: Is this feature underperforming due to poor distribution or lack of product-market fit?

## When to Reach for It
- Facing an architectural or business crossroads with strong arguments on both sides.
- Preventing hasty, emotional decisions or premature rewrites.
- Triggered by typing `/strategic-tradeoff <decision description or dilemma>`.

---

## Output Deliverable
Generated at `c-suite/decisions/YYYY-MM-[topic].md`:
- Multi-perspective C-Suite matrix (CEO, CPO, CTO, CRO views).
- Second-order consequence mapping (1 month, 6 months, 2 years out).
- Executive Recommendation with explicit fallback conditions.
