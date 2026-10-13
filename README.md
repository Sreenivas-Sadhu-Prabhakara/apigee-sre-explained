# apigee-sre-explained

A single-page, self-contained explainer for the **SRE observability ladder** built on
Google Cloud Monitoring for the Apigee X proxies in project `apigee-neg-psc` (env `eval`):
a RED + p90/p95/p99 dashboard, availability and latency SLOs, an error budget, and
multi-window burn-rate alerts — plus the latency tail the SLO caught that the dashboard hid.

**Live:** https://sreenivas-sadhu-prabhakara.github.io/apigee-sre-explained/

The page is downloadable as a single HTML file (the "Download this page" button, or
`apigee-sre-observability-explained.html`). No build step, no dependencies beyond two web
fonts; works offline once saved.

Figures were read live from the Monitoring API on 2026-10-13, not estimated. The page
publishes no secrets or personal addresses. The monitoring toolkit itself (the JSON
objects, `apply.sh`/`rollback.sh`, the test suite) lives alongside the proxy bundles and is
applied via the REST API.
