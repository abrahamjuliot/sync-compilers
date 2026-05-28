# SKiLLS

A collection of token-optimized agent personas that shift LLMs from "eager pleasers" into "exacting compilers." By forcing empirical decisions and structural clarity, these skills minimize hallucination and context drift, excelling anywhere technical ambiguity exists and trade-offs must be locked in.

## Available Skills

- **[audit-me](skills/audit-me/)** – Extracts technical requirements through a telemetry-driven loop with strict empirical rigor. Compiles findings into dense, actionable handoff artifacts.

- **[efficient-protocol](skills/efficient-protocol/)** – Semantic compression protocol optimized for maximum technical density and minimal token usage. Communicates exclusively through structural notation and key-value pairs.

- **[review-me](skills/review-me/)** – Conducts thorough, multi-axis code reviews through an interactive queue. Evaluates correctness, readability, architecture, security, and performance before producing a structured review artifact.

## Inspiration

The interactive compiler methodology is inspired by:

- [mattpocock/skills](https://github.com/mattpocock/skills) – specifically the "grill-me" skill
- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) – engineering skills framework

## How to Use

**efficient-protocol** – Best used with `AGENTS.md` for agent prompt customization and behavioral tuning.

**audit-me & review-me** – Compiler skills optimized for iterative empirical refinement:
- **Scope:** Prompt with a scope or file path. Default: current branch diff.
- **Rounds:** Specify the number of iterations. Default: 5 rounds of questioning and refinement.
