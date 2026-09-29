# Changelog

## [2.0.0] - 2026-09-29

### Added and changed
- Promoted the RC3 specification to **CLEAR 2.0**.
- Added nine protected invariants, including I9: trust cannot be laundered.
- Added L0/L1/L2 runtime control levels and CLEAR-P/CLEAR-V/CLEAR-C implementation classes.
- Added explicit evidence, authority and action state models.
- Added parameter-, principal-, scope- and validity-bound authorization.
- Added reversibility, blast-radius and recoverability controls.
- Added persistent-memory provenance, integrity, expiry and scope requirements.
- Added runtime conformance degradation requirements.
- Added CLEARBench 1.0 with a frozen 40-scenario RC3 hardening suite, first R1 dry-run results, and explicit further-validation requirements.
- Archived the complete CLEAR 1.0 documentation under `archive/CLEAR-1.0/`.

All notable changes to CLEAR will be recorded here.

## [1.0.0] - 2026-09-28

### Added

- Published **CLEAR v1.0 — Context, Limits, Evidence, Action, Review** as the first public release.
- Defined context authority rules for resolving current instruction, authoritative sources, conversation context, persistent context, and inference.
- Defined five capability states: AVAILABLE, AVAILABLE WITH CONFIRMATION, READ ONLY, UNAVAILABLE, and UNKNOWN.
- Defined READ, PROPOSE, and EXECUTE as distinct action modes.
- Added explicit handling for FACT, DERIVED, INFERENCE, and UNKNOWN evidence states.
- Added failure-handling rules so tool errors, partial responses, and no-result states are not conflated.
- Added anti-sycophancy guidance: agreement is not an objective.
- Added deliberate-state rules so conversation does not automatically become persistent truth.
- Added a review loop: **use -> learn -> review -> test -> version -> reuse**.
- Added a vendor-neutral acknowledgement handshake for use with ChatGPT, Claude, Copilot, local models, and agentic systems.
- Added a concise one-page quick reference and portable invocation instructions.
- Added a conformance checklist covering the core behavioural requirements.
- Adopted dual licensing:
  - Documentation under **CC BY 4.0**
  - Code, schemas, and reference implementations under the **MIT License**

### Notes

CLEAR v1.0 supersedes IHORF as the public framework for reliable human-AI collaboration.
