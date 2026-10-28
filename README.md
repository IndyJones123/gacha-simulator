# Gacha Simulator

Free online gacha / loot-box simulator — build a custom item pool with relative drop
rates, roll manually or auto-roll until your target drops, and watch per-item chance
percentages live.

**Live:** https://gacha.reogsolodev.com/

## Features

- Custom item pool — single add or bulk insert (`name,rate` pairs)
- Manual roll + auto roll with target item and safety limit
- Refine mode for enhancement-style simulations (+1 / -1 / 0 effects)
- Bilingual UI (English / Indonesian)
- Privacy by design — no localStorage, no backend, nothing saved

## Run locally

Open `index.html` in any browser. No build step, no dependencies.

## Tech

Single static page: vanilla JS + inline CSS. SEO assets (`robots.txt` with explicit
AI-crawler allows, `sitemap.xml`, `llms.txt`, Open Graph + JSON-LD) included.

Created by [AlfianDev — reogsolodev.com](https://reogsolodev.com).
