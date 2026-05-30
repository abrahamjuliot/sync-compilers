# SKiLLS

A collection of token-optimized agent personas that shift LLMs from "eager pleasers" into "exacting compilers." By utilizing emergent orchestrations like Branching Reality Trees, Faction Voting, and Self-Evolving Question Graphs, these skills map state spaces rather than flat conversation loops, driving technical ambiguity to structural clarity.

## Core Pattern

**[efficient-protocol](skills/efficient-protocol/SKILL.md)** – Semantic compression protocol optimized for maximum technical density and minimal token usage. Use with `AGENTS.md` for agent customization.

---

## Product & Scope

**[pitch-sync](skills/pitch-sync/SKILL.md)** – Gamified investor interrogation gauntlet. Stress-tests product ideas against market realities, unit economics, and competitive moats through a turn-based "Term Sheet" negotiation. *(Terminal: Professional Lean Canvas)*

---

## Architecture & Design

**[architect-sync](skills/architect-sync/SKILL.md)** – System design via **Branching Reality Trees & Internal Political Systems**. Forks proposals into multiple architectural realities, allowing internal factions (Execution, Economist, SRE, Security) to debate and vote on trade-offs based on user constraints. *(Terminal: Architecture Decision Record)*

**[api-sync](skills/api-sync/SKILL.md)** – Contract-driven design. Iterates over payload structures, idempotency, pagination, and error handling before code. *(Terminal: Valid OpenAPI/Swagger YAML)*

---

## Execution & Hardening

**[plan-sync](skills/plan-sync/SKILL.md)** – Aggressively cuts scope using a **Self-Evolving Question Graph**. It spawns Bayesian nodes targeted at the highest areas of uncertainty to define a lean MVP and vertically sliced execution plan. *(Terminal: Dense requirements handoff + MVP scope)*

**[review-sync](skills/review-sync/SKILL.md)** – Multi-axis code review mapped as a **Self-Evolving Question Graph**. Code smells become root nodes that organically grow to hunt systemic architectural flaws across the codebase. *(Terminal: Structured review artifact)*

**[hack-sync](skills/hack-sync/SKILL.md)** – Adversarial threat modeling using a **Self-Evolving Question Graph**. The attack surface expands dynamically; successfully defending a vector instantly mutates the graph to spawn bypasses. *(Terminal: Threat Model matrix + mitigation plan)*

**[test-sync](skills/test-sync/SKILL.md)** – Edge-case discovery powered by a **Self-Evolving Question Graph**. Evaluates how the system handles failures, dynamically branching into deeper tests for recovery mechanisms and error leaks. *(Terminal: Executable test suite)*

---

## DevOps & Operations

**[deploy-sync](skills/deploy-sync/SKILL.md)** – Pipeline engineering. Forces decisions on caching, secrets, build times, matrix testing, and deployment triggers. *(Terminal: Configured CI/CD YAML)*

---

## How to Use

**Compiler Skills** (plan-sync, review-sync, architect-sync, api-sync, hack-sync, test-sync, etc.):
- **Scope:** Prompt with a specific system architecture, PRD, or file path. Default: current branch diff.
- **Execution:** The agent will dynamically navigate its structural space (Branching Reality Trees or Self-Evolving Question Graphs). Answer the forcing questions, provide constraints, and watch the state collapse until it reaches a terminal artifact.
