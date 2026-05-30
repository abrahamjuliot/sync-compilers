# SKiLLS

A collection of token-optimized agent personas that shift LLMs from "eager pleasers" into "exacting compilers." By forcing empirical decisions and structural clarity, these skills minimize hallucination and context drift, excelling anywhere technical ambiguity exists and trade-offs must be locked in.

## Core Pattern

**[efficient-protocol](skills/efficient-protocol/)** – Semantic compression protocol optimized for maximum technical density and minimal token usage. Use with `AGENTS.md` for agent customization.

---

## Product & Scope

**[scope-sync](skills/scope-sync/)** – Ruthlessly challenges feature requests to cut scope. Forces empirical decisions about launch blockers vs. nice-to-haves. *(Terminal: MVP task list for Linear/Jira)*

**[pitch-sync](skills/pitch-sync/)** – Plays devil's advocate on product ideas. Tests feasibility, market fit, and competitive moat. *(Terminal: Lean Canvas or one-page PRD)*

---

## Architecture & Design

**[architect-sync](skills/architect-sync/)** – Interrogates system design proposals and forces decisions on concrete trade-offs (Eventual vs. Strong Consistency, Monolith vs. Microservices, etc.). *(Terminal: Architecture Decision Record)*

**[api-sync](skills/api-sync/)** – Contract-driven design. Iterates over payload structures, idempotency, pagination, and error handling before code. *(Terminal: Valid OpenAPI/Swagger YAML)*

**[migrate-sync](skills/migrate-sync/)** – Evaluates database changes against operational realities: locks, N+1 risks, backfill strategies, rollbacks. *(Terminal: Bulletproof SQL migrations)*

---

## Execution & Hardening

**[plan-sync](skills/plan-sync/)** – Extracts technical requirements through a telemetry-driven loop with strict empirical rigor. *(Terminal: Dense requirements handoff)*

**[review-sync](skills/review-sync/)** – Multi-axis code review (correctness, readability, architecture, security, performance) through an interactive queue. *(Terminal: Structured review artifact)*

**[hack-sync](skills/hack-sync/)** – Adversarial threat modeling. Presents attack vectors (SSRF, IDOR, race conditions) one at a time and co-develops mitigations. *(Terminal: Security matrix + unified code patches)*

**[test-sync](skills/test-sync/)** – Edge-case discovery. Generates extreme, malicious, or unlikely scenarios. User accepts/dismisses whether the system needs to handle them. *(Terminal: Executable test suite)*

**[simplify-sync](skills/simplify-sync/)** – De-abstraction. Targets overly clever code and presents side-by-side comparisons of complex vs. flat alternatives. *(Terminal: Clean refactored diffs)*

---

## DevOps & Operations

**[deploy-sync](skills/deploy-sync/)** – Pipeline engineering. Forces decisions on caching, secrets, build times, matrix testing, and deployment triggers. *(Terminal: Configured CI/CD YAML)*

**[rca-sync](skills/rca-sync/)** – Root Cause Analysis via strict 5 Whys framework. Refuses human error as root cause; questions alerts, testing gaps, and systemic blindness. *(Terminal: Blameless post-mortem with action items)*

---

## How to Use

**Compiler Skills** (plan-sync, review-sync, scope-sync, architect-sync, api-sync, hack-sync, test-sync, etc.):
- **Scope:** Prompt with a scope or file path. Default: current branch diff.
- **Rounds:** Specify the number of iterations. Default: 5 rounds of empirical refinement.
