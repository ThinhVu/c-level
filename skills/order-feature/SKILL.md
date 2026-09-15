---
name: order-feature
description: Translates an executive product decision or prioritized roadmap feature into an unambiguous Intent Spec and Acceptance Criteria ready for ThinhVu/d-level. Triggers on /order-feature.
---

# /order-feature

> **The Sovereign Handoff**: The C-Suite defines WHAT and WHY; D-Level executes HOW.  
> *"Never hand off loose ideas to an autonomous coding squad. Hand off mathematically precise acceptance criteria and invariant boundaries."*

## Purpose & Objective
`/order-feature` is the formal bridge between **C-Level** strategic leadership and **D-Level (`ThinhVu/d-level`)** autonomous engineering delivery. It converts a strategic roadmap item (from `.c-level/roadmap.md`) into a production-grade Executive Intent Specification (`.c-level/specs/[feature-slug]-intent.md`).

Once finalized, the founder or agent runs:
```bash
/write-intent .c-level/specs/[feature-slug]-intent.md
```
D-Level then autonomously locks boundary contract tests, generates the code, and verifies acceptance invariants via `/let-it-cook`.

## When to Reach for It
- Transitioning a high-priority feature from the C-Level roadmap into autonomous engineering implementation.
- Commissioning a major new capability without ambiguity or scope creep.
- Triggered by typing `/order-feature <feature-slug or description>`.

---

## The Handoff Contract

The generated spec at `.c-level/specs/[feature-slug]-intent.md` contains:
1. **Executive Intent & Problem Statement**: What problem this solves and for whom.
2. **Acceptance Invariants (Definition of Done)**: Exact binary assertions that must pass.
3. **Anti-Creep Boundaries (What NOT to Build)**: Explicit scope constraints.
4. **Target Architectural Seams**: Suggested files, models, and endpoints for D-Level.
5. **Telemetry & Verification Plan**: Metrics to prove the feature achieved its goal.

---

## Output Confirmation

```text
✅ Executive Intent Spec created: .c-level/specs/[feature-slug]-intent.md

Ready for D-Level autonomous engineering! Run:
/write-intent .c-level/specs/[feature-slug]-intent.md
/let-it-cook
```
