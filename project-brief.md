# My project brief

## The question
How far are settlements surrounding Omo Forest Reserve from the nearest health facility?

## The study area
Communities surrounding Omo Forest Reserve, Ijebu East LGA, Ogun State, Nigeria.

## The data I need
- Forest reserve boundary — Protected Planet/WDPA (Omo Strict Natural Reserve, WDPA ID 2089) — https://www.protectedplanet.net/2089 — Shapefile/GeoJSON — small file
- LGA boundary — GRID3 — https://grid3.org/geospatial-data-nigeria — Shapefile — small file
- Settlement extents — GRID3 — https://data.grid3.org/datasets/GRID3::grid3-nga-settlement-extents-v4-1 — GeoPackage/Shapefile — ~40 MB
- Health facilities — GRID3 — https://data.grid3.org/maps/GRID3::grid3-nga-health-facilities-v2-0 — Shapefile — small file
- Roads — OpenStreetMap (Geofabrik Nigeria extract) — https://download.geofabrik.de/africa/nigeria.html — Shapefile/GeoPackage — ~2 GB (national file — clip to Ogun State after download)

## The planned analysis
Health facility points will be buffered at a set distance (e.g. 5 km, or a road-network service area if time allows). Settlements surrounding the reserve will be overlaid on this buffer to identify which fall outside coverage. Proximity to the reserve boundary will also be checked to see if distance from the forest correlates with distance from care.

## Expected output
A map showing settlements around Omo Forest Reserve that are more than 5 km from a health facility, with a summary count/table of underserved settlements.
