# Project 4 — Gas Processing Plant Site Suitability Analysis

**Location:** Delta State, Nigeria  
**Software:** QGIS 4.0.3 | **CRS:** EPSG:32631 | **Resolution:** 10 m

## Overview
This project uses GIS-based multi-criteria decision analysis to identify potential locations for a gas processing plant in Delta State, Nigeria. Seven spatial criteria were combined using the Analytical Hierarchy Process (AHP) and weighted overlay to identify candidate zones for further investigation.

## Tools & Data
QGIS, GDAL, QuickOSM, Python, Raster Calculator, OpenStreetMap, SRTM elevation and Esri/Impact Observatory land cover.

## Methodology
Spatial datasets were prepared and reclassified to a suitability scale of 1–5. AHP was used to calculate criterion weights, which were combined through weighted overlay. Areas scoring 4 or higher were retained, areas within 1 km of settlements were excluded, and patches smaller than 10 hectares were removed.

**AHP consistency ratio:** 0.098.

## Criteria Weights
- Pipelines: 42.1%
- Land cover: 20.6%
- Roads: 15.7%
- Slope: 8.2%
- Waterways: 5.5%
- Power plants: 4.1%
- Settlements: 3.8%

## Key Results
- **531** candidate zones identified.
- **1,180.86 km²** of candidate land.
- **6.9%** of Delta State covered by the identified zones.
- **101.99 km²** — area of the largest candidate zone.

## Map
![Gas Processing Plant Site Suitability Map](map.jpg)

## Limitations
These results represent preliminary GIS screening, not confirmed construction sites. Data completeness, land ownership, flood risk, environmental restrictions, regulatory requirements, and field verification must be assessed before selecting a site.
