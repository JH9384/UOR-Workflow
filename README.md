# UOR Workflow

UOR Workflow is a developing, reusable engineering workflow for moving software and computational products from definition through execution, evidence collection, qualification, and governed release.

## Working model

**This repository remains public.** It is for reviewed, shareable workflow definitions, templates, interfaces, and approved technical summaries. **Restricted engineering work remains local** on the UOR development workstation, outside this public repository. Nothing moves from the local environment into this repository without an explicit publication review.

## Design principles

- **Separation of duties:** execution, technical qualification, and release authorization are distinct decisions.
- **Repeatability:** workflows should be reproducible, with declared inputs and recorded outputs.
- **Evidence first:** qualification results should be traceable to defined workflows and execution records.
- **Multiple product families:** application testing, formal verification, and scientific computation may share execution infrastructure while retaining their own acceptance criteria.
- **Fail closed:** incomplete or unsuccessful qualification must not imply release approval.

## Proposed public repository areas

- `docs/architecture/` — reviewed public architecture and interface documentation
- `docs/engineering-captures/` — explicitly approved-for-publication summaries only
- `workflows/` — reusable, reviewed workflow definitions
- `qualification/policies/` — generic acceptance-policy templates, not confidential evaluation records
- `templates/` — reusable product onboarding templates

## Local-only engineering boundary

Keep complete engineering captures, execution logs, controller evidence, raw qualification results, machine-specific configurations, credentials, proprietary research, and restricted source material **on local controlled storage only**. Do not copy these artifacts into the public Git working tree, commit them, attach them to GitHub issues or pull requests, or publish them through CI artifacts. A sanitized public summary may be separately prepared and reviewed when appropriate.

## Status

Early engineering development. This public repository is not a claim of completed certification, independent assurance, or production release authorization.
