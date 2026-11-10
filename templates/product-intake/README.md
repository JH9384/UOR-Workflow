# Product intake template (public)

Use this template to prepare a new product-family workflow without exporting any local engineering evidence.

## Intake fields

| Field | Meaning |
| --- | --- |
| Product family | Application, formal verification, scientific computation, or other |
| Purpose | Observable capability being tested |
| Inputs | Declared inputs, version identities, and classification |
| Environment | Runtime and dependency declarations (sanitized for public use) |
| Execution | Controller step interfaces, limits, and expected outputs |
| Qualification | Separate, product-specific acceptance contract |
| Evidence | Output artifact types and integrity validation |
| Governance | Independent review and release disposition |

## Gates

`REGISTER → REVIEW → AUTHORIZE TEST → EXECUTE → VERIFY EVIDENCE → QUALIFY → REVIEW RELEASE`

Each gate must fail closed. The universal controller handles execution and evidence transport; product-specific policy determines technical qualification; release governance is separate. Store actual run evidence only in the local controlled environment.
