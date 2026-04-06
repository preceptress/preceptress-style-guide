# GitHub Pages Deployment Guide

## Option A: Publish from the root

If `index.html` is in the root of the repo:

1. Push the repo to GitHub.
2. Open the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment** choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Save.

GitHub will publish the page automatically.

## Option B: Publish from `/docs`

If you prefer to keep the live site in a docs folder:

1. Move `index.html` into `/docs`.
2. In **Settings → Pages**, choose:
   - **Branch:** `main`
   - **Folder:** `/docs`
3. Save.

## Custom domain

If you later want a custom domain such as `style.preceptress.ai`:

1. Go to **Settings → Pages**.
2. Add the custom domain.
3. Create the proper DNS records with your domain provider.
4. Enable HTTPS once GitHub verifies the domain.

## Suggested public repo description

Use something like:

> Public design system and visual style guide for the Preceptress Health AI-first medical discovery platform.

