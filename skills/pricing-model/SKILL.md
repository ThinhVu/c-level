---
name: pricing-model
description: Designs high-margin pricing architecture, packaging tiers, paywall triggers, and monetization strategies for an existing product. Triggers on /pricing-model.
---

# /pricing-model

> **CRO Principle**: Pricing is not what you charge; it is how you package value.  
> *"If nobody complains about your price, you are too cheap. If users don't hit your paywall, your free tier is too generous."*

## Purpose & Objective
`/pricing-model` formulates a sustainable, high-margin monetization strategy tailored to the existing product's architecture and usage patterns. It identifies the core **Value Metric** (the axis along which customer value grows) and designs pricing tiers, quotas, and conversion triggers.

## When to Reach for It
- Transitioning a free project or open-source tool into a commercial SaaS.
- Current conversion rate from free to paid is under 2%.
- Infrastructure or LLM token costs are eating margins.
- Launching new tiered capabilities or team collaboration features.
- Triggered by typing `/pricing-model`.

---

## 4-Step Pricing Formulation

1. **Identify the Value Metric**:
   - Must scale as the customer gets more value (e.g., number of tracked domains, active team seats, monthly API credits, transactions processed).
2. **Set the Freemium / Trial Boundary**:
   - The free experience must let users experience the "Aha!" moment, but create natural friction when attempting production or recurring team use.
3. **Guard the 75%+ Gross Margin Target**:
   - Factor in database read/write volume, file storage, email delivery (Resend/Sendgrid), and third-party LLM inference.
4. **Place High-Intent Paywall Triggers**:
   - Don't hide buttons behind paywalls; let users click the premium action and present a contextual, 1-click upgrade modal at the moment of highest intent.

---

## Output Deliverable
Generated at `c-suite/pricing-architecture.md` using `templates/pricing-architecture.md.template`:
- Core value metric definition.
- 3-Tier Packaging Structure (Starter, Pro, Team/Business).
- Unit economics & infrastructure margin breakdown.
- Contextual paywall triggers and onboarding email nudge sequence.
