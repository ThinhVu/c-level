---
name: audit-product
description: Scans an existing codebase to reverse-engineer actual product capabilities, tech stack, active user workflows, and technical debt into a Product Dossier. Triggers on /audit-product.
---

# /audit-product

> **CPO / CTO Principle**: Code is ground truth; everything else is marketing.  
> *"Don't ask what the product was intended to be. Inspect what the codebase actually does today."*

## Purpose & Objective
`/audit-product` performs a deep inspection of the repository. It analyzes routes, controllers, UI pages, database models, third-party API keys/clients, and test suites to build an objective **Product Dossier** (`.c-level/product-dossier.md`).

This ground truth document answers:
- What does this product *actually* do today?
- Who are the current users and what workflows do they execute?
- What tech stack, libraries, database engines, and third-party SaaS tools are active?
- Where is the technical and UX debt concentrated?

## When to Reach for It
- Immediately after running `/setup-c-level` on an existing codebase.
- When taking over or onboarding onto an unfamiliar or undocumented repository.
- Before making any strategic pivots, pricing overhauls, or architecture rewrites.
- Triggered by typing `/audit-product`.

---

## What the Skill Inspects

1. **Routing & UI Surfaces**:
   - Web routes (e.g., `app/`, `pages/`, `routes/`, controller endpoints).
   - What distinct workflows can an end user execute right now?
2. **Data Model & State**:
   - ORM schemas (Prisma, Drizzle, SQLAlchemy, ActiveRecord, migrations).
   - What entities, relationships, and user states exist?
3. **External Dependencies & Paid APIs**:
   - Payment providers (Stripe, LemonSqueezy, Paddle).
   - LLM / AI providers (OpenAI, Anthropic, Gemini).
   - Auth & Storage (Supabase, Clerk, AWS S3, Cloudflare).
4. **Codebase Health & Dead Surfaces**:
   - Orphaned routes, incomplete features, stubbed functions, lacking tests.

---

## Output Deliverable
Generated at `.c-level/product-dossier.md` using `templates/product-dossier.md.template`:
- Executive summary of the app's real thesis.
- Complete breakdown of active vs incomplete features.
- Technical debt & friction hotspots.
- High-leverage stabilization recommendations.
