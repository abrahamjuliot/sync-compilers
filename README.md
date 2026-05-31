# SKiLLS

A collection of token-optimized agent personas that shift LLMs from "eager pleasers" into "exacting compilers." By utilizing emergent orchestrations like Branching Reality Trees, Faction Voting, and Self-Evolving Question Graphs, these skills map state spaces rather than flat conversation loops, driving technical ambiguity to structural clarity.

## Core Pattern

**[efficient-protocol](skills/efficient-protocol/SKILL.md)** – Semantic compression protocol for max technical density and minimal token usage. *(Requires `AGENTS.md`)*

## Product & Scope

**[pitch-sync](skills/pitch-sync/SKILL.md)** – Gamified investor interrogation gauntlet to stress-test product ideas. *(Terminal: Professional Lean Canvas)*

## Architecture & Design

**[architect-sync](skills/architect-sync/SKILL.md)** – System design via **Branching Reality Trees & Internal Political Systems**. *(Terminal: Architecture Decision Record)*

**[api-sync](skills/api-sync/SKILL.md)** – Schematic Constraint Matrix engine using Wave Function Collapse principles. *(Terminal: Production OpenAPI Specification)*

## Execution & Hardening

**[plan-sync](skills/plan-sync/SKILL.md)** – Aggressively cuts scope using a **Self-Evolving Question Graph**. *(Terminal: Dense requirements handoff + MVP scope)*

**[review-sync](skills/review-sync/SKILL.md)** – Multi-axis code review mapped as a **Self-Evolving Question Graph**. *(Terminal: Structured review artifact)*

**[hack-sync](skills/hack-sync/SKILL.md)** – Adversarial threat modeling using a **Self-Evolving Question Graph**. *(Terminal: Threat Model Matrix)*

**[test-sync](skills/test-sync/SKILL.md)** – Edge-case discovery powered by a **Self-Evolving Question Graph**. *(Terminal: Executable test suite)*

## DevOps & Operations

**[deploy-sync](skills/deploy-sync/SKILL.md)** – Transactional DevOps validation loop functioning as an ACID-compliant state machine. *(Terminal: Validated CI/CD Manifest)*

## Installation

Install all skills in the repository simultaneously:

```bash
npx skills@latest add abrahamjuliot/skills --all
```

Or install a specific skill directly:

```bash
npx skills@latest add abrahamjuliot/skills/skills/api-sync
```

## How to Use

**Compiler Skills** (plan-sync, review-sync, architect-sync, api-sync, hack-sync, test-sync, etc.):

- **Scope:** Prompt with a specific system architecture, PRD, or file path. Default: current branch diff.
- **Execution:** The agent will dynamically navigate its structural space (Branching Reality Trees or Self-Evolving Question Graphs). Answer the forcing questions, provide constraints, and watch the state collapse until it reaches a terminal artifact.
