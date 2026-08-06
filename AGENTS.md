# Agent Guidance

This public repository holds the merchant-neutral UltraCart OKF standard
catalog and tooling. See [README.md](README.md) for the workflow.

## Governance

Product direction, goals, finite projects, and work orders for this system
are governed outside this repository, in the private Business-As-Code
operating repository (`Business-As-Code/bac`, `systems/ultracart-okf.md`)
with live work tracked in the Scale Lean Linear workspace. This repository
does not carry its own task queue; treat issues and changes here as
implementation-level only.

## Boundaries

- Keep this repository metadata-only and merchant-neutral. Never commit
  merchant-specific generated bundles, query results, customer or order
  records, credentials, project identifiers, or runtime configuration.
- Nothing in this repository authorizes running queries against, or making
  changes to, any live BigQuery project or merchant system.
- Validate contributions with the commands in the README (bundle
  validation, standard-catalog self test, agent-usability audit) before
  proposing changes.
