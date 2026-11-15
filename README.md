# Career Portfolio

A mobile-first professional portfolio and role-specific resume renderer for Fadhil Khalid.

## Architecture

- This repository is the public presentation layer only.
- The private canonical source remains `fadhilkhalid/personal-os`.
- `data/profile.json` contains the curated public profile.
- `data/roles.json` defines resume positioning, capability emphasis and achievement selection.
- `index.html` renders the public profile.
- `resume.html` renders a role-specific resume with print / Save as PDF.
- Static HTML, CSS and vanilla JavaScript. No backend, account login, analytics or third-party tracking.

## Role profiles

- Business Operations Architect
- Enterprise Architect
- Digital Transformation Leader
- Strategy & Transformation

Select a role in the resume page or use a direct URL such as `resume.html?role=enterprise-architect`.

## Deployment

GitHub Actions workflow is configured to deploy the site to GitHub Pages on pushes to `main`. In repository Settings → Pages, choose GitHub Actions as the build and deployment source if it is not already selected.

## Publishing governance

Never copy the private repository or raw evidence records here. Promote only explicitly reviewed public data. Do not add internal system names, internal screenshots, proprietary architecture, private source locators, credentials, personal operational information or unvalidated metrics. Review dates, titles, attribution and employer confidentiality before each public release.
