# 🏛️ C-Level: The Embedded AI Executive Suite for Existing Products

> A production-grade, composable AI agent skill set for founders, engineering teams, and AI agents acting as the **C-Suite (CEO, CPO, CMO, CTO, CRO)** embedded inside an **existing software project or codebase**.  
> Reverse-engineers product ground truth, discovers high-margin niche positioning, curates ruthless roadmaps, designs pricing architectures, and delegates verified specifications to developer squads.

[![Skills.sh](https://img.shields.io/badge/skills.sh-ThinhVu%2Fc--level-blue.svg)](https://skills.sh)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📖 Why C-Level?

In modern software development, AI coding agents like **D-Level (`ThinhVu/d-level`)** have made writing code virtually free and lightning fast. 

However, when working on an **existing product**, the hardest challenges are no longer syntax or code generation:

> **The greatest risk to an existing software product is undisciplined execution: building features nobody pays for, diluting the niche, suffocating in tech debt, and drifting away from the core value proposition.**

### The Dual AI Engine: Executive Strategy ⟷ Autonomous Delivery

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                      THE AUTONOMOUS SOFTWARE ENGINE                         │
├─────────────────────────────────────────────────────────────────────────────┤
│  🏛️ C-LEVEL (This Suite - ThinhVu/c-level):                                 │
│  "Existing Product Strategy & C-Suite Governance"                           │
│  • Installs into your CURRENT codebase / repository                         │
│  • Reverse-engineers real product capabilities and technical debt           │
│  • Sharpens niche positioning, defensible moats, and ICP definition         │
│  • Enforces RICE roadmap prioritization: what to build next & what to CANCEL│
│  • Designs high-margin pricing architectures & in-app PLG viral loops       │
│  • Evaluates CTO technical tradeoffs (velocity tax, AI unit costs)          │
│  • Delegates verified intent specs to D-Level (/order-feature)              │
├─────────────────────────────────────────────────────────────────────────────┤
│                                      │ (Hands off specs & Acceptance Invariants)
│                                      ▼
├─────────────────────────────────────────────────────────────────────────────┤
│  ⚡ D-LEVEL (Autonomous Delivery Squad - ThinhVu/d-level):                   │
│  "Autonomous Engineering & Implementation"                                  │
│  • Locks boundary invariants & acceptance criteria (/write-intent)          │
│  • Autonomous long-running implementation loops (/let-it-cook)               │
│  • Correctness verification, property fuzzing, and release shipping         │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Quickstart

Install the suite into any existing software repository:

```bash
npx skills@latest add ThinhVu/c-level
```

Then initialize the executive framework in your codebase:

```bash
/setup-c-level
```

This scaffolds:
- **`STRATEGY.md`**: The executive charter, North Star metric, and decision guardrails tailored to your project.
- **`c-suite/`**: Version-controlled directory storing all product dossiers, niche positioning plans, roadmaps, pricing models, and executive specs.

---

## 🧭 The Executive Skill Catalog

C-Level provides **12 modular skills** representing the core leadership functions:

| Skill | Hat | Description & Deliverable |
| :--- | :--- | :--- |
| **`/setup-c-level`** | System | Initializes the `c-suite/` directory and `STRATEGY.md` charter in your codebase. |
| **`/audit-product`** | CPO / CTO | Scans routes, DB schemas, external APIs, and tests to generate the ground-truth `c-suite/product-dossier.md`. |
| **`/niche-position`** | CEO / CMO | Pins down the sharpest niche market, Ideal Customer Profile (ICP), defensible moat, and anti-personas (`c-suite/niche-positioning.md`). |
| **`/prioritize-roadmap`** | CPO | Scores backlog candidates with RICE; determines what to build next and creates the explicit **Will-NOT-Build** list (`c-suite/roadmap.md`). |
| **`/pricing-model`** | CRO / CEO | Formulates value metrics, packaging tiers, paywall triggers, and unit economics margins (`c-suite/pricing-architecture.md`). |
| **`/growth-vector`** | CMO | Designs in-app PLG loops, programmatic SEO templates, and directory distribution channels (`c-suite/growth-playbook.md`). |
| **`/retention-audit`** | CPO / UX | Analyzes onboarding friction, compresses Time-to-Value (TTV < 90s), and designs habit loops to stop churn. |
| **`/strategic-tradeoff`** | CEO / Board | Evaluates hard dilemmas (e.g. rewrite vs refactor, build vs buy, monetize now vs wait) with second-order impact analysis. |
| **`/tech-roi`** | CTO | Audits engineering velocity tax, cloud costs, and AI token unit economics to ensure high-ROI technical choices. |
| **`/order-feature`** | CPO ⟷ D-Level | Converts a prioritized feature into an unambiguous Intent Spec for D-Level (`c-suite/specs/[slug]-intent.md`). |
| **`/board-review`** | Full C-Suite | Runs a periodic 360° health review across Product, Growth, Tech, and Revenue with a traffic-light scorecard (`c-suite/board-scorecard.md`). |
| **`/ask-c-level`** | All Chiefs | Interactive consultation command to receive consensus advice from CEO, CPO, CMO, CTO, and CRO on any question. |

---

## 🔄 The End-to-End Executive Lifecycle

Here is how a founder or team uses C-Level to steer an existing project:

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ 1. GROUND TRUTH           2. STRATEGIC POSITIONING     3. VALUE CAPTURE     │
│   /setup-c-level     ───>   /niche-position       ───>   /pricing-model     │
│   /audit-product            /prioritize-roadmap          /growth-vector     │
│   (What exists now)         (Where to focus)             (Monetize & Scale) │
└─────────────────────────────────────────────────────────────────────────────┘
                                     │
                                     ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│ 4. AUTONOMOUS EXECUTION HANDOFF                                             │
│   /order-feature [feature-slug]                                             │
│   └── Outputs: c-suite/specs/[feature-slug]-intent.md                       │
│        │                                                                    │
│        ▼ (Hands off to ThinhVu/d-level)                                     │
│   /write-intent c-suite/specs/[feature-slug]-intent.md                      │
│   /let-it-cook                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 📁 The `c-suite/` Artifact Architecture

All strategic artifacts are clean, self-contained Markdown files stored right alongside your code:

```
your-repo/
├── STRATEGY.md                     # Executive Operating Charter & Guardrails
├── c-suite/
│   ├── product-dossier.md          # Ground truth of current codebase features
│   ├── niche-positioning.md        # Target ICP, value prop, and defensible moat
│   ├── roadmap.md                  # RICE-ranked backlog & "Will Not Build" list
│   ├── pricing-architecture.md     # Value metrics, tiers, and paywall hooks
│   ├── growth-playbook.md          # PLG loops, pSEO strategy, and GTM channels
│   ├── board-scorecard.md          # Periodic 360° health scorecard
│   ├── decisions/                  # Strategic & architectural decision records
│   │   └── 2026-09-rewrite-vs-refactor.md
│   └── specs/                      # Commissioned specs for D-Level engineering
│       └── billing-portal-intent.md
├── src/ / app/                     # Your existing product code remains untouched!
└── ...
```

---

## 🤝 Synergy with D-Level

C-Level is architected to be the upstream strategic brain for **`ThinhVu/d-level`**:

1. **Strategic Discovery**: Use `/prioritize-roadmap` to rank what has the highest business impact.
2. **Intent Commissioning**: Run `/order-feature <feature>` to generate acceptance invariants and anti-creep boundaries in `c-suite/specs/[feature]-intent.md`.
3. **Autonomous Execution**: Point D-Level's `/write-intent` and `/let-it-cook` directly at the generated spec. D-Level implements and verifies the code autonomously without human guesswork.

---

## 📄 License & Attribution

- **Author**: Thinh Vu ([@ThinhVu](https://github.com/ThinhVu))
- **License**: [MIT](LICENSE)
- **Repository**: [github.com/ThinhVu/c-level](https://github.com/ThinhVu/c-level)
