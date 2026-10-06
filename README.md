# Pritzker grant dashboard

This repository now contains a static-export Next.js dashboard that tracks PolicyEngine's progress against the Pritzker Children's Initiative policy analysis expansion grant.

## What it includes

- A rebuilt dashboard surface for grant progress across model coverage, live tools, and partner connections
- The original grant source materials in `responses/`, `financials/`, `impact_plan/`, and `supporting_documents/`
- Builder-style metadata files for the PolicyEngine Claude dashboard workflow: `plan.yaml`, `.claude/settings.json`, and `CLAUDE.md`

## Development

```bash
bun install
make dev
```

## Checks

```bash
make test
make build
```

## Deployment

GitHub Pages now builds the Next.js app and publishes the exported `out/` directory instead of the legacy `docs/` page.
