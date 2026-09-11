---
name: order-feature
description: Translates an executive product decision or prioritized roadmap feature into an unambiguous Intent Spec and Acceptance Criteria ready for ThinhVu/d-level. Triggers on /order-feature.
---

# /order-feature

> **The Sovereign Handoff**: The C-Suite defines WHAT and WHY; D-Level executes HOW.  
> *"Never hand off loose ideas to an autonomous coding squad. Hand off mathematically precise acceptance criteria and invariant boundaries."*

## Purpose & Objective
`/order-feature` is the formal bridge between **C-Level** strategic leadership and **D-Level (`ThinhVu/d-level`)** autonomous engineering delivery. It converts a strategic roadmap item (from `c-suite/roadmap.md`) into a production-grade Executive Intent Specification (`c-suite/specs/[feature-slug]-intent.md`).

Once generated, the spec is ready to be directly fed into D-Level commands:
- `/write-intent` (to lock down implementation invariants)
- `/draft-rfc` (to design system architecture)
- `/let-it-cook` (to autonomously implement and verify the code)

## When to Reach for It
- Moving a prioritized feature from roadmap planning into active software implementation.
- Ensuring developer AI agents do not suffer scope creep, make unauthorized architectural decisions, or dilute the product positioning.
- Triggered by typing `/order-feature <feature-name or description>`.

---

## The Executive Spec Structure

The generated spec at `c-suite/specs/[feature-slug]-intent.md` contains:
1. **Strategic Justification**: Why this feature is being built and its target business metric impact.
2. **Executive Invariants**: Non-negotiable boundary conditions (performance p95, security rules, gross margin unit economics).
3. **Explicit Anti-Scope ("Do NOT Build")**: Strict boundaries to prevent the AI coding agent from over-engineering or adding unnecessary bells and whistles.
4. **Verification Protocol**: Exact commands to verify business correctness before production merge.

## Direct Handoff Command
After running `/order-feature`, the agent prints:
```bash
✅ Executive Intent Spec created: c-suite/specs/[feature-slug]-intent.md

To trigger autonomous implementation with D-Level:
/write-intent c-suite/specs/[feature-slug]-intent.md
/let-it-cook
```
