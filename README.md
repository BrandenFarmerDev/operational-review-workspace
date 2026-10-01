# Operational Review Workspace

**Status: Prototype — in development.** This repository currently contains project documentation and a `.gitignore`; application code and a working demo have not been implemented.

A monthly operating review workflow connecting KPI context, decisions, owners, and action history. Its purpose is to keep performance numbers connected to the commentary and commitments needed to act on them.

## Planned scope

- Organize monthly KPI results with definitions, context, and commentary.
- Record review decisions, assigned owners, and follow-up actions.
- Preserve action history across review periods rather than rebuilding it in disconnected spreadsheets and slides.
- Present lightweight charts and review summaries using synthetic operating data.

## Intended stack

React, TypeScript, Cloudflare Workers, Cloudflare D1, and lightweight charts. KPI structures, history rules, and chart implementation will be finalized during development.

## Data boundaries

The public demo will use fictional metrics, commentary, and participants. Do not commit internal operating reports, employee information, customer records, or confidential business measures. Demo metrics are illustrative and do not claim real performance improvements.

This application will have its own Worker and D1 database. Private review records will not be shared with the portfolio database or used as retrieval sources for Ask Branden.

## Getting started

Clone the repository to begin implementation:

```sh
git clone https://github.com/BrandenFarmerDev/operational-review-workspace.git
cd operational-review-workspace
```

There are no install, development, test, or deployment commands yet. Add reproducible setup and quality checks alongside the first application implementation. Keep secrets in local ignored configuration or Worker secrets; `VITE_` variables are public.

## Portfolio

- [Project outline](https://brandenfarmer.com/work#operational-review-workspace)
- [Portfolio source](https://github.com/BrandenFarmerDev/branden-farmer-portfolio)
