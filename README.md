# Bhote Koshi Flood Assessment

A rapid population, network, and mobility assessment of the 26 August 2026 Nepal glacial-lake-outburst flood (GLOF), cross-read against the Copernicus EMS EMSR927 rapid mapping activation and the ReliefWeb / Data Friendly Space situation overview.

**Live dashboard:** https://ASchroederCR.github.io/bhote-koshi-flood-dashboard/

## What's in this repo

- `index.html` — the self-contained dashboard (single file: HTML, CSS, JS, an offline OpenTopoMap basemap crop, and the processed dataset, all inlined). No build step; open it directly or serve it as-is.

## Data sources

- **Meta Data for Good** — POP (population density), NET (network coverage), and MOV (movement range) crisis-response exports for Nepal, 26 August 2026. Processed and aggregated locally; raw source files are not included in this repo.
- **Copernicus Emergency Management Service** — [EMSR927 situational reporting story map](https://storymaps.arcgis.com/stories/f76baefadfa74d6d9a18265875f48870).
- **ReliefWeb / Data Friendly Space** — [Nepal Flash Floods: Rapid Situation Overview, 27 August 2026](https://reliefweb.int/report/nepal/nepal-flash-floods-rapid-situation-overview-27-august-2026).
- **Basemap** — © OpenTopoMap (CC-BY-SA), map data © OpenStreetMap contributors (ODbL).

## Caveats

This is a same-day analyst triage for situational awareness, not verified ground truth. See the "Methodology & caveats" section inside the dashboard for the full list of limitations (mobile-signal proxies vs. census population, z-score capping, privacy-threshold data suppression, pre-event NET snapshot timing, approximate zone boundaries, and provisional casualty figures).
