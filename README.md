# Sync Protocols: Agent Compilers

This repository is a collection of token-optimized agent personas that shift LLMs from "eager pleasers" into "exacting compilers." Instead of relying on basic prompting and unpredictable "vibes," these agents demand your active collaboration to turn technical ambiguity into structural clarity.

* **You hold the steering wheel:** We replace endless open-ended chatting with structured, deterministic frameworks.
* **Map before building:** The agents outline risks, trade-offs, and edge cases, pausing for your expert input before moving forward.
* **Strict validation:** Every persona forces clear decisions, guaranteeing a solid, production-ready artifact at the end.

## Core Pattern

**[efficient-protocol](skills/efficient-protocol/SKILL.md)** – Semantic compression protocol for max technical density and minimal token usage. *(Requires `AGENTS.md`)*

### Product & Scope

*Stress-tests early product assumptions by employing gamified gauntlets to validate business logic.*

- **[pitch-sync](skills/pitch-sync/SKILL.md)** – Investor interrogation agent validating product ideas. *(Terminal: Professional Lean Canvas)*

### Architecture & Design

*Leverages Branching Reality Trees and Wave Function Collapse principles to explore architectural constraints and resolve conflicts.*

- **[architect-sync](skills/architect-sync/SKILL.md)** – System design agent resolving structural conflicts through internal political systems. *(Terminal: Architecture Decision Record)*
- **[api-sync](skills/api-sync/SKILL.md)** – Schematic constraint matrix engine defining tight API specifications. *(Terminal: Production OpenAPI Specification)*

### Execution & Hardening

*Utilizes a **Self-Evolving Question Graph** to dynamically navigate technical ambiguity. Instead of flat lists, these agents branch into edge cases based on user responses to compile precise terminal artifacts.*

- **[plan-sync](skills/plan-sync/SKILL.md)** – Foundational planning agent that ruthlessly cuts MVP scope. *(Terminal: Execution plan & MVP scope)*
- **[review-sync](skills/review-sync/SKILL.md)** – Bayesian code analysis hunting for systemic architectural flaws. *(Terminal: Structured review artifact)*
- **[hack-sync](skills/hack-sync/SKILL.md)** – Adversarial threat-modeling agent mapping attack surfaces. *(Terminal: Threat Model Matrix)*
- **[test-sync](skills/test-sync/SKILL.md)** – QA engineer proactively discovering complex edge cases. *(Terminal: Executable test suite)*

### DevOps & Operations

*Applies ACID-compliant state machines to build resilient deployment pipelines and validation loops.*

- **[deploy-sync](skills/deploy-sync/SKILL.md)** – DevOps validation agent managing deployment state transitions. *(Terminal: Validated CI/CD Manifest)*

### Installation

Install all skills simultaneously:

```bash
npx skills@latest add abrahamjuliot/skills --all -g
```

Or install a specific skill directly:

```bash
npx skills@latest add abrahamjuliot/skills/skills --skill <skill-name> -g
```

### How to Use

**Compiler Skills** (plan-sync, review-sync, architect-sync, api-sync, hack-sync, test-sync, etc.):

- **Scope:** Prompt with a specific system architecture, PRD, or file path. Default: current branch diff.
- **Execution:** The agent will dynamically navigate its structural space (Branching Reality Trees or Self-Evolving Question Graphs). Answer the forcing questions, provide constraints, and watch the state collapse until it reaches a terminal artifact.
