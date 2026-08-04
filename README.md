# Geospatial-Neighborhood-Analytics

### Location as data: PostGIS, spatial joins, and neighborhood features — transit, schools, amenities — that explain why one block rents higher than the next.

![Chain N](https://img.shields.io/badge/Chain%20N-059669?style=for-the-badge) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge)](LICENSE-GPL) [![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue?style=for-the-badge)](LICENSE-AGPL)

[📖 Lesson Plan](docs/LESSON_PLAN.md) · [🎮 Interactive Tour](docs/interactive/index.html)

<!-- SCREENSHOT PLACEHOLDER: docs/screenshots/overview.png -->

> ⬜ **Scaffold pending.** Directory created to portfolio standard; full content (README, lesson plan, tour + quiz, skeleton code) still to be built. Part of **Chain N — PropTech & Real-Estate Engineering**.

## Why This Was Built

"Location, location, location" is the oldest cliché in real estate and almost nobody quantifies it. Two
identical units three blocks apart can differ by hundreds a month, and the explanation is spatial: transit
access, school boundaries, grocery stores, park proximity, and the invisible lines people draw around
neighborhoods.

I want to turn that into actual features — distance to the nearest bus line, count of amenities within a
ten-minute walk, which school zone a parcel falls in — using PostGIS rather than hand-waving. It's also the
honest way to look at housing access, because the same maps show which neighborhoods have been left out.

## Why This Matters (Industry Application)

Geospatial skill is scarce and it shows up well beyond real estate — logistics, retail siting, insurance
risk, and public policy all run on it. For my own domain it's the difference between saying a neighborhood
is desirable and proving it with a spatial join. PostGIS specifically is a strong differentiator on a data
engineering résumé.

## Topics Covered

| Area | What this project covers |
|------|--------------------------|
| PostGIS | Geometry types, spatial indexes, and projections that actually matter |
| Spatial joins | Point-in-polygon, nearest-neighbor, and distance queries |
| Feature building | Walkability, transit access, amenity counts, school zones |
| Boundaries | Census tracts, school districts, and informal neighborhood lines |
| Mapping | Choropleths and point maps that communicate rather than decorate |
| Equity lens | Reading the same maps for access gaps, not just price signals |

## How This Connects

Chain N (PropTech & Real-Estate Engineering). Feeds location features into **Property-Valuation-AVM**; builds on the SQL depth from **Chain I** and **Chain Q**.

---
Dual licensed — [GPL v3](LICENSE-GPL) and [AGPL v3](LICENSE-AGPL).
