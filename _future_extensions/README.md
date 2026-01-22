# Future Extensions (Version B and beyond)

This directory is reserved for **architecture-specific and forward governance extensions**
that build on the authoritative **Version A** artifacts.

## Purpose

Version A is intentionally:

- model-agnostic,
- execution-independent,
- suitable for standards exploration.

Future extensions exist to demonstrate **execution-level feasibility and forward evolution**
without modifying or redefining the Version A baseline.

## Version B status

Version B (v1b) artifacts have been released as an **early, artifacts-only extension**
to support standards, regulatory, and architectural review.

The Version B paper is under active review and will be released separately once finalized.

All public review papers for Volume 2 — including **Version A, Version B, Version C, and future
editions** — are published on the Policy of Developments website for reading and citation:

https://policyofdevelopments.org/whitepaper/vol2-a-web-of-sharing-trust-responsibility-toward-a-trustless-future

GitHub Releases remain the **canonical source for artifact packs, manifests, and integrity-bound
distributions**. Website publications do not redefine artifact authority or conformance scope.

## Extension principles

- Do not modify Version A schemas, CSC semantics, or conformance rules to depend on extensions.
- Extensions must be additive and must not retroactively alter Version A authority.
- New schemas should live under `_future_extensions/` and be versioned independently.
- Any cryptographic anchoring or signing mechanisms must remain optional unless explicitly
  stated in an extension-specific document.

Adoption or non-adoption of extensions does not affect conformance to Version A.
