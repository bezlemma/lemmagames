# Lemma Games — lemmagames.com

Static website for Lemma Games, served via GitHub Pages.

## Games
- **Microscope Builder** — live now, web (https://bezialemma.com/microscope/)
- **SciSwipe** — coming soon, iOS & Android
- **Active Nematic Tennis** — coming soon, Steam (Windows & macOS)

## Structure
- `index.html` — the entire single-page site (HTML + CSS + JS inline)
- `CNAME` — custom domain for GitHub Pages (lemmagames.com)

## Deploy
GitHub Pages is served from the `main` branch (root). The custom domain
`lemmagames.com` is configured via the `CNAME` file and Squarespace DNS:

- `A` records for the apex domain point to GitHub Pages:
  185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `CNAME` record for `www` points to `bezlemma.github.io`

## Design
Warm cream palette inspired by a clean, science-forward aesthetic.
Hero and game thumbnails use generated SVG "director field" art evoking
active-nematic flow — no external image dependencies.
