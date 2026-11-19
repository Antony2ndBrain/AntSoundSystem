# IEM System Design — GPdI Victory Metro Permata

One-page site that documents the In-Ear Monitor (IEM) system for the church sound team and musicians. English + Bahasa Indonesia.

**Live site:** https://antony2ndbrain.github.io/AntSoundSystem/

## What's here

- `index.html` — the whole site (HTML, CSS and JS in one file, no build step). Open it by double-clicking, or host it anywhere static.
- `.github/workflows/pages.yml` — publishes `index.html` to GitHub Pages on every push to `main`.

## Editing the design

All content lives in two objects at the top of the `<script>` in `index.html`:

- `SYSTEM` — devices, connections, musicians, pitfalls, checklist items and diagram layouts. Every text has `en` and `id`.
- `UI` — interface text in both languages.

Diagrams, cards, the detail panel and the checklist all render from these, so edit the data, commit, and the site updates.

## Deploying (one-time setup)

1. On GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
2. Push to `main` (or run the workflow from the **Actions** tab).
3. The site appears at the URL above after about a minute.

---
Antony2ndBrain · Presented by Antony Laurence Cornelis
