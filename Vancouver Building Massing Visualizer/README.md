# Vancouver Building Massing Visualizer

Three self-contained HTML tools for testing building massing against the City of Vancouver's Broadway Plan. Each file runs directly in a browser (no build step); 3D views use three.js from a CDN.

| File | What it does |
| --- | --- |
| `broadway-massing-tool.html` | Enter an address (Vine St to Clark Dr, 1st to 16th Ave) or click the plan map; finds the Broadway Plan sub-area, applies provincial transit-oriented-area minimums, and sketches an indicative podium/tower envelope. |
| `broadway-massing-tool-v3.html` | Slider-driven massing study: pick a policy area, shape podium and tower, and see FSR, height, floor plate, tower separation and tenure checks against Plan limits. |
| `vancouver-massing-tool.html` | Looks up any Vancouver lot via City open data (parcels, 2015 building footprints, parks, zoning) and draws a test massing with its surrounding context, plan view and equinox shadow. |

Indicative screening only — sub-area boundaries and limits are simplified from the Broadway Plan (2022) and its 2024 amendments. Confirm against the current Plan text at vancouver.ca before relying on any number.
