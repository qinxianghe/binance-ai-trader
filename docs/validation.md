# Validation record

Date: 2026-10-04. Cleanup baseline commit: `62c95bb5e6dbb94b9b84005547aeeca8ceb0a354`.

## Preservation and structure

- 197 retained blobs are unchanged at their current paths.
- 0 generated build/cache/executable entries are omitted from the current tree; the baseline history remains available.
- New documents and required configuration/path adaptations are recorded in the cleanup pull request. No existing source history is rewritten.
- Current filenames have no case-insensitive collisions. Markdown file links and generated-output ignore rules are checked before publication.

## Checks and limits

- All application, strategy, risk-control, order, broker, configuration, and test source bytes match the original Git blobs.
- Existing documentation was moved to `docs/development-guide.md`, and a concise project entry page and navigation records were added.
- The full test suite was not rerun for this documentation-only change. Existing fake-client test coverage is described in the development guide rather than presented as a new run.
- This change does not affect Live Trading. No exchange connection, Testnet/Live order, AI API request, backtest, or profitability assessment was performed.

