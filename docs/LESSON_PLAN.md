# 📖 Lesson Plan — Geospatial-Neighborhood-Analytics

> **Chain N — PropTech & Real-Estate Engineering** | Location as data: PostGIS, spatial joins, and neighborhood features — transit, schools, amenities — that explain why one block rents higher than the next.

## What This Project Is

Turn location into measurable features with PostGIS — spatial joins, distance queries, and neighborhood attributes that explain rent differences block by block.

## Learning Objectives

By the end I can:

1. Store and index geometry correctly in **PostGIS**.
2. Run point-in-polygon and nearest-neighbour **spatial joins**.
3. Compute walkability and amenity-count features within a radius.
4. Assign parcels to census tracts and school zones.
5. Choose an appropriate projection and explain why it matters.
6. Read the same maps for access gaps, not only price signals.

## Software You Will Use

- PostgreSQL + PostGIS.
- Python with GeoPandas.
- QGIS for inspection.
- Open data: census tracts, transit stops, points of interest.

## Build Order

1. Load parcels and points of interest; create spatial indexes.
2. Join parcels to census tracts (point-in-polygon).
3. Compute distance to nearest transit stop.
4. Build amenity counts within a walking radius.
5. Join the features to rent data and look for relationships.
6. Map the results, including an access-gap view.

## Common Mistakes to Avoid

- Mixing projections and silently computing distances in degrees.
- Omitting spatial indexes and waiting minutes for a join.
- Treating a neighborhood name as a precise boundary.
- Assuming correlation between amenities and rent implies causation.
- Building features that encode historical redlining without acknowledging it.

## Check Your Understanding

The quiz covers projections, spatial indexes, point-in-polygon vs nearest-neighbour joins, and interpreting spatial correlation.

## Why This Matters (Industry Application)

Geospatial skill is scarce and it shows up well beyond real estate — logistics, retail siting, insurance
risk, and public policy all run on it. For my own domain it's the difference between saying a neighborhood
is desirable and proving it with a spatial join. PostGIS specifically is a strong differentiator on a data
engineering résumé.

## Reflection Questions

- Which of your location features could act as a proxy for race or income, and what would you do about it?
- What does the access-gap map show that the price map hides?
