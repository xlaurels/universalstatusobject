# Universal Status Object (USO)

**Universal Status Object (USO)** is an open, rail-agnostic data model for representing, normalizing, validating, and explaining financial transaction status across payment networks, banks, clearing systems, and digital asset rails.


USO aims to give diverse financial systems a shared status language while preserving source-specific evidence, identifiers, timestamps, and lifecycle context.

## Vision

One status language for global money movement.

## Objectives

- Normalize payment and transaction lifecycle states into a consistent model.
- Preserve native rail status, source evidence, and provenance.
- Distinguish acknowledgements, processing states, settlement, finality, reversals, and exceptions.
- Enable interoperability across traditional payment rails and digital asset networks.
- Support reliable APIs, reconciliation, analytics, and policy-aware automation.

## Core principles

- **Rail-agnostic:** designed to span systems and networks.
- **Evidence-preserving:** retain the source context behind normalized status.
- **Explicit semantics:** avoid treating similar status codes as equivalent when their meaning or finality differs.
- **Versioned and extensible:** evolve schemas with documented compatibility.
- **Open interoperability:** encourage implementation, feedback, and conformance testing.

## Status

This repository is an evolving specification and development workspace. Definitions, schema, mappings, and implementation guidance are subject to change as the project develops.


## Contributing

Issues, proposals, implementation feedback, and mapping contributions are welcome. Please document the source network, source status code, interpretation, and relevant lifecycle or finality caveats when proposing a mapping.


## Disclaimer

USO is an independent initiative. It is not affiliated with, endorsed by, or operated by any bank, payment network, standards body, or blockchain protocol unless expressly stated.
