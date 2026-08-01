# Pacific County Timber

An interactive web map of Designated Forest Land parcels in Pacific County, Washington — a tax-status category with real consequences for how much of the coastal Pacific Northwest stays in timber.

**Live map:** https://aschulz714.github.io/Pacific-County-Timber/

## Methodology

1. Load the county Taxlot (Parcels) shapefile in QGIS 3.14
2. Filter to department code "88 — Designated Forest Land Parcels"
3. Export GeoJSON → reduce line intersections in Mapshaper → export TopoJSON
4. Render with Mapbox GL JS against a custom Mapbox Studio style (developed in MAP 671, University of Kentucky New Maps Plus)

## Data

Pacific County Department of Public Works Spatial Data 2021 — Taxlot (Parcels) shapefile, updated 2021-01-12.

## Stack

HTML · CSS · JavaScript · Mapbox GL JS · TopoJSON
