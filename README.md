# SKiLLS

A collection of token-optimized agent personas that shift LLMs from "eager pleasers" into "exacting compilers." By forcing empirical decisions and structural clarity, these skills minimize hallucination and context drift, excelling anywhere technical ambiguity exists and trade-offs must be locked in.

## Core Pattern

**[efficient-protocol](skills/efficient-protocol/)** – Semantic compression protocol optimized for maximum technical density and minimal token usage. Use with `AGENTS.md` for agent customization.

---

## Product & Scope

**[pitch-sync](skills/pitch-sync/)** – Plays devil's advocate on product ideas. Tests feasibility, market fit, and competitive moat. *(Terminal: Lean Canvas or one-page PRD)*

---

## Architecture & Design

**[architect-sync](skills/architect-sync/)** – Interrogates system design proposals and forces decisions on concrete trade-offs (Eventual vs. Strong Consistency, Monolith vs. Microservices, etc.). *(Terminal: Architecture Decision Record)*

**[api-sync](skills/api-sync/)** – Contract-driven design. Iterates over payload structures, idempotency, pagination, and error handling before code. *(Terminal: Valid OpenAPI/Swagger YAML)*

---

## Execution & Hardening

**[plan-sync](skills/plan-sync/)** – Aggressively cuts scope to define a lean MVP, then extracts technical requirements through a telemetry-driven loop with strict empirical rigor. *(Terminal: Dense requirements handoff + MVP scope)*

**[review-sync](skills/review-sync/)** – Multi-axis code review (correctness, readability, architecture, security, performance). Targets overly clever code and forces decisions between complex logic and flatter, procedural alternatives. *(Terminal: Structured review artifact)*

**[hack-sync](skills/hack-sync/)** – Adversarial threat modeling. Presents attack vectors (SSRF, IDOR, race conditions) one at a time and co-develops mitigations. *(Terminal: Security matrix + unified code patches)*

**[test-sync](skills/test-sync/)** – Edge-case discovery. Generates extreme, malicious, or unlikely scenarios. User accepts/dismisses whether the system needs to handle them. *(Terminal: Executable test suite)*

---

## DevOps & Operations

**[deploy-sync](skills/deploy-sync/)** – Pipeline engineering. Forces decisions on caching, secrets, build times, matrix testing, and deployment triggers. *(Terminal: Configured CI/CD YAML)*

---

## How to Use

**Compiler Skills** (plan-sync, review-sync, architect-sync, api-sync, hack-sync, test-sync, etc.):
- **Scope:** Prompt with a scope or file path. Default: current branch diff.
- **Rounds:** Specify the number of iterations. Default: 5 rounds of empirical refinement.
