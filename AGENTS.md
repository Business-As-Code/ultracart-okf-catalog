# Agent Guidance

This public repository holds the merchant-neutral UltraCart OKF standard
catalog and tooling. See [README.md](README.md) for the workflow.

## Governance

Product direction and work are governed in [BAC Notion](https://app.notion.com/p/3d77d9824d9381748548f479ebc8d312). Before work, follow the [BAC agent instructions](https://app.notion.com/p/3d77d9824d93814ca3dfe2d8d763cf20). Notion Work is the live task record; Linear and old BAC repository references are historical. Keep catalog data and implementation documentation here.

## Boundaries

- Keep this repository metadata-only and merchant-neutral. Never commit
  merchant-specific generated bundles, query results, customer or order
  records, credentials, project identifiers, or runtime configuration.
- Nothing in this repository authorizes running queries against, or making
  changes to, any live BigQuery project or merchant system.
- Validate contributions with the commands in the README (bundle
  validation, standard-catalog self test, agent-usability audit) before
  proposing changes.
