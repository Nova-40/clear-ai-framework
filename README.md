# CLEAR 2.0 — Context, Limits, Evidence, Action, Review

**A vendor-neutral assurance framework for reliable human–AI collaboration and agentic systems.**

CLEAR 2.0 develops CLEAR from a behavioural operating discipline into an assurance framework that distinguishes behaviour requested from a model, behaviour independently verified, and behaviour enforced outside the model.

## Start here

- **CLEAR-2.0.md** — authoritative CLEAR 2.0 specification
- **HOW-TO-USE.md** — practical use, Persistent Core, control levels and implementation classes
- **benchmarks/CLEARBench-1.0-RC3-Hardening-Test-Specification.md** — frozen 40-scenario adversarial test specification
- **benchmarks/CLEARBench-1.0-RC3-P-First-Run-2026-09-29.md** — first recorded RC3-P R1 dry run
- **benchmarks/TESTING-METHOD-AND-FURTHER-VALIDATION.md** — what has been tested, limitations, and further validation required
- **CHANGELOG.md** — version history
- **archive/CLEAR-1.0/** — preserved CLEAR 1.0 public release
- **LICENSE-DOCUMENTATION** — CC BY 4.0 for framework documentation
- **LICENSE-CODE** — MIT for code, schemas and reference implementations

## The nine invariants

1. Confidence is not evidence.
2. Capability is not authority.
3. Objectives do not create permission.
4. Ambiguity must not expand authority.
5. Failure, uncertainty and incomplete execution remain visible.
6. Material claims and consequential actions retain sufficient provenance for their claimed evidence, authority and verification state.
7. Delegation, decomposition or alternative routes cannot increase authority.
8. Revocation or narrowing of authority takes precedence over task completion.
9. Trust cannot be laundered across models, agents, tools, memory, summaries or transformations.

## Control and assurance

Runtime control levels: **L0 Core**, **L1 Evidential**, **L2 Consequential**.

Implementation classes: **CLEAR-P** (prompt-governed), **CLEAR-V** (independently verified), **CLEAR-C** (externally controlled).

Action lifecycle: **READ → PROPOSE → AUTHORISE → EXECUTE → VERIFY**.

## Testing status

CLEARBench 1.0 contains 40 frozen adversarial scenarios. The first recorded CLEAR 2.0 RC3-P run was an **R1 self-evaluated dry run**: 34 behavioural scenarios and 6 simulated architecture scenarios produced the RC3-prescribed response with no recorded critical violation.

That result demonstrates internal specification/test coherence. It does **not** establish independent effectiveness, superiority over baseline, stochastic robustness, cross-model effectiveness, or CLEAR-C enforcement. See the testing-method document for the required validation programme.

## Governing principles

> **Interpret human intent generously. Treat evidence, capability and action exactingly.**

> **Where a rule matters, prefer enforcement over instruction.**

## Licensing

Documentation: **CC BY 4.0**.  
Code, schemas and reference implementations: **MIT**.

Copyright 2026 Geoff Webster.
