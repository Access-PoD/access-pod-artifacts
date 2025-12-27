# Future Extensions (Version B and beyond)

This directory is reserved for **architecture-specific extensions** that build on the Version A artifacts.

## Purpose

Version A is intentionally:
- model-agnostic,
- execution-independent,
- suitable for standards exploration.

Version B (scheduled release: February) will introduce optional extensions, using Q-Pathformer as a reference implementation. These extensions will include:
- Q-Pathformer governance telemetry mappings
- UGCCMT tagging schemas and provenance fields
- Cryptographic anchoring and audit replay mechanisms
- Additional evidence and integrity artifacts

## Rules

- Do **not** modify Version A schemas/certificates to depend on Version B extensions.
- Version B artifacts should be additive and backward-compatible where feasible.
- New schemas should live under `_future_extensions/qpathformer/` (or similar) and be versioned independently.
- Any cryptographic signing requirements must remain optional unless explicitly stated in a Version B document.
