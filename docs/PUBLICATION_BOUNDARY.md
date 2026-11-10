# Public publication boundary

This repository is **public**. Restricted UOR engineering and research take place **locally** and are not synchronized to this repository.

## Allowed after review

- Reusable workflow interfaces and generic examples
- Non-sensitive architecture and template documentation
- Deliberately sanitized, approved public summaries

## Do not publish

- Raw controller runs, logs, execution IDs, local workstation paths, identifiers or inventories
- Detailed internal engineering captures or unreviewed qualification evidence
- Credentials, secrets, environment files, research under restriction, proprietary materials
- Machine-specific configuration, internal IP addresses, or data containing third-party information

## Publication checklist

1. Classify content and verify authorization to release it.
2. Review text, files, metadata, commit history and generated artifacts for restricted content.
3. Remove or replace environment-specific paths, IDs and confidential configuration.
4. Check dependencies and licenses; ensure no secret material in examples or CI artifacts.
5. Document what the public material does and **does not** establish.
6. Publish only an explicitly approved, minimal diff.

A successful local test is **not** publication authorization or product release authorization.
