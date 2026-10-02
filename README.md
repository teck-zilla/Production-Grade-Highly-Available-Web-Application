# HA Web App Portfolio

A simple, responsive two-page static portfolio site based only on the supplied PDF.

## Pages
- `index.html` — project overview, architecture, resources, outcomes
- `project.html` — implementation details, configuration highlights, issues and takeaways

## Run
Open `index.html` directly, or serve this folder with any static web server.

## Intentional safety adjustments
The source PDF contains a literal database password and a fixed SSH source IP. The site does not publish those values. It keeps the relevant architectural/security context and the source document's recommendation to use secret injection/AWS Secrets Manager.
