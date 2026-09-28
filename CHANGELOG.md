# Changelog

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
