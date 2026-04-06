# Preceptress Health Style Guide

A public, polished design-system repository for the Preceptress Health web experience.

This repo packages the current visual language of the site into a clean, shareable foundation that can be used by:

- researchers building public-facing project pages
- funders reviewing the brand and technical maturity of the project
- developers extending the product UI
- collaborators who need a consistent design reference

## What is inside

- `index.html` — the live style guide and visual reference page
- `docs/getting-started.md` — how to run and edit the guide locally
- `docs/customization.md` — how to change colors, typography, spacing, and components
- `docs/github-pages.md` — how to publish the guide on GitHub Pages
- `CONTRIBUTING.md` — contribution workflow and repo standards
- `LICENSE` — open-source license

## Design direction

The system is built around a modern medical-intelligence aesthetic:

- deep navy and black foundation
- luminous cyan, blue, and green accents
- glass panels and terminal-inspired surfaces
- investor-grade polish without feeling corporate or sterile
- a visual language suitable for science, AI, and public trust

## Quick start

Clone the repo:

```bash
git clone https://github.com/YOUR_USERNAME/preceptress-style-guide.git
cd preceptress-style-guide
```

Open the style guide locally:

```bash
open index.html
```

Or on Linux:

```bash
xdg-open index.html
```

## Publish with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Save.

Your live URL will be:

```text
https://YOUR_USERNAME.github.io/preceptress-style-guide/
```

## Recommended next upgrades

- split the embedded CSS into `static/css/design-system.css`
- add component partials for Flask or Jinja templates
- add a small logo pack and favicon set
- add a landing page variant for researchers and foundations
- add a lightweight token file for SwiftUI or React parity

## Suggested positioning copy

> Preceptress Health is building an AI-first interface for medical discovery. This repository documents the visual system behind that mission.

## Contact

- Site: `preceptress.ai`
- Email: `info@preceptress.ai`

