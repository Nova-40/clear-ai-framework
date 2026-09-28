# CLEAR v1.0 Release Notes

**Release:** v1.0.0  
**Date:** 28 September 2026

CLEAR v1.0 is the first public release of **Context, Limits, Evidence, Action, Review** — a vendor-neutral operating framework for reliable human-AI collaboration.

It is designed to work across ChatGPT, Claude, Copilot, local language models, agentic systems, and future AI platforms without depending on any one provider's memory model, tool architecture, or terminology.

## What v1.0 introduces

CLEAR v1.0 defines five operating disciplines:

- **Context** — use relevant information, respect authority, and make material assumptions visible.
- **Limits** — establish actual capabilities, permissions, and platform constraints before claiming action.
- **Evidence** — keep facts, derived conclusions, inference, and unknowns distinct.
- **Action** — separate READ, PROPOSE, and EXECUTE, with consequential actions guarded.
- **Review** — validate outcomes, expose limitations, preserve state deliberately, and improve through use.

The release also includes:

- a standard acknowledgement handshake;
- a one-page quick reference;
- portable invocation text for different AI systems;
- anti-sycophancy requirements;
- explicit failure-handling rules;
- a conformance model and checklist;
- dual licensing for documentation and implementation assets.

## Why it exists

CLEAR was developed from practical human-AI collaboration and replaces the earlier IHORF framework with a simpler public structure and a more explicit operational contract.

Its governing maxim is:

> **Interpret human intent generously. Treat evidence, capability, and action exactingly.**

## Compatibility

CLEAR is intentionally vendor-neutral. It can be applied to:

- ChatGPT
- Claude
- Microsoft Copilot
- local LLMs
- tool-using agents
- multi-model orchestration systems

Implementation details may vary. The behavioural discipline should remain recognisable.

## Conformance

A system should not claim strict conformance merely because CLEAR appears in its prompt.

Use `CONFORMANCE-CHECKLIST.md` to assess whether a system meaningfully implements the core requirements.

## Licensing

- **Framework documentation:** CC BY 4.0
- **Code, schemas, and reference implementations:** MIT

Copyright 2026 Geoff Webster
