# UOR Workflow

UOR Workflow is a developing, reusable engineering workflow for moving software and computational products from definition through execution, evidence collection, qualification, and governed release.

## Design principles

- **Separation of duties:** execution, technical qualification, and release authorization are distinct decisions.
- **Repeatability:** workflows should be reproducible, with declared inputs and recorded outputs.
- **Evidence first:** qualification results should be traceable to a defined workflow and execution records.
- **Multiple product families:** application testing, formal verification, and scientific computation may share execution infrastructure while retaining their own acceptance criteria.
- **Fail closed:** incomplete or unsuccessful qualification must not imply release approval.

## Proposed repository areas

- `docs/architecture/` — public architecture and interface documentation
- `docs/engineering-captures/` — reviewed and approved-for-publication summaries only
- `workflows/` — reusable, reviewed workflow definitions
- `qualification/policies/` — generic acceptance-policy templates
- `templates/` — reusable product onboarding templates

## Status

Early engineering development. This public repository is not a claim of completed certification, independent assurance, or production release authorization.

## Disclosure boundary

Do **not** commit private engineering captures, proprietary research, credentials, local-machine identifiers, unreviewed execution logs, internal infrastructure details, or restricted source materials. These belong in a separately controlled private environment after review.
