# 🌍 Master Reference Library — Data Load Dashboard

A live, single-page dashboard that queries [Supabase](https://supabase.com) directly and visualizes the load progress of every dataset in the Master Reference Library.

**Live page:** [GitHub Pages](https://andredavisme.github.io/reference-library-dashboard/)

## What it shows

- Real-time record counts fetched from Supabase on every page load
- Progress bars for each dataset vs. a defined finite target
- Color-coded status: 🟢 Complete · 🟡 In Progress · 🔵 Started · ⬜ Planned
- Summary stat cards (total records, overall % complete, datasets done)
- Rollup chart by group (Geography, North America, Reference Library)

## Datasets Tracked

| Dataset | Target |
|---|---|
| Hemispheres | 4 |
| Continents | 7 |
| Water Bodies | 23 |
| Countries | 195 |
| US States & Territories | 56 |
| Canada Provinces & Territories | 13 |
| Mexico States | 32 |
| All US Counties | 3,143 |
| All US Cities | 30,000 |
| Canada Counties / Districts | 293 |
| Mexico Municipalities | 2,469 |
| Domains | 10 |
| Concepts | 500 |
| Glossary | 300 |
| Tags | 100 |
| Sources | 50 |

## Tech

- Pure HTML/JS — no build step
- [Supabase JS v2](https://supabase.com/docs/reference/javascript) for live data
- [Plotly.js](https://plotly.com/javascript/) for charts
- Hosted via GitHub Pages

## Updating targets

Edit the `TARGETS` array in `index.html` to adjust goals as the library grows.
