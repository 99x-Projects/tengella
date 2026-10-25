# Tengella CleanFlow — AI agent marketplace prototype

Clickable prototype of an AI agent marketplace inside Tengella's CleanFlow web product, built by 99x.

- **Overview** — agent inbox with human-in-the-loop decisions and a findings feed
- **AI agents → Marketplace** — browse, configure and activate agents
- **AI agents → My agents** — manage activated agent instances, versions and activity log

## Run locally

It's a single static page with no build step. Open `index.html` in a browser, or:

```sh
python3 -m http.server 8000
```

## Deployment

Every push to `main` deploys to GitHub Pages via `.github/workflows/pages.yml`.
In the repo settings, **Pages → Source** must be set to **GitHub Actions** (the workflow tries to enable this on first run).
