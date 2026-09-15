---
name: setup-c-level
description: Bootstraps the AI C-Suite executive workspace, creates or enriches AGENTS.md with strategic guidelines, and scaffolds the .c-level/ artifacts directory in any existing codebase. Triggers on /setup-c-level.
---

# /setup-c-level

> **Executive Principle 1**: Ground decisions in reality.  
> *"Before you make a single strategic decision, establish the charter, boundary invariants, and executive record of the product."*

## Purpose & Objective
`/setup-c-level` initializes the embedded C-Suite framework in an existing repository. It inspects the current repository environment, configures or enriches the strategic governance guidelines in `AGENTS.md` (using `templates/AGENTS.md.template`), and scaffolds the `.c-level/` directory structure for all strategic artifacts.

## When to Reach for It
- First command to run immediately after installing `ThinhVu/c-level` on an existing project.
- Re-initializing or updating the C-Suite operating structure in a codebase.
- Triggered by typing `/setup-c-level`.

---

## Execution Workflow

### Step 1: Detect Project Context
Scan the current workspace to automatically detect:
1. **Project Name & Package**: From `package.json`, `pyproject.toml`, `Cargo.toml`, `go.mod`, or directory name.
2. **Tech Stack**: Languages, framework (Next.js, FastAPI, Rails, Gin, etc.), databases, and infrastructure configs.
3. **Existing Documentation**: Read existing `README.md`, docs, or specifications to infer product domain.

### Step 2: Scaffold `.c-level/` Directory
Ensure the executive artifacts directory exists:
```bash
.c-level/
├── decisions/
└── specs/
```

### Step 3: Create or Enrich `AGENTS.md`
Create or enrich `AGENTS.md` at the project root using `templates/AGENTS.md.template`, preserving any existing engineering guidelines:
- Populate Project Name, detected Domain, and initial North Star placeholder.
- Establish the 5 Core Decision Guardrails.

### Step 4: Propose Immediate Next Step
Conclude by asking the user:
> *"C-Suite framework initialized. Would you like to run `/audit-product` to reverse-engineer and document the ground truth of your existing codebase?"*
