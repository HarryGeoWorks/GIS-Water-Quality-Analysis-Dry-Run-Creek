# GIS Water Quality Analysis — Dry Run Creek

An ArcPy-based workflow for organizing, analyzing, and mapping multi-year water-quality monitoring data for Dry Run Creek in Cedar Falls, Iowa.

## Project overview

This project develops a reproducible GIS workflow for combining annual water-quality records into a standardized multi-year dataset and examining spatial and temporal patterns across monitoring sites.

The analysis is being developed as part of graduate GIS programming work and is intended to demonstrate practical use of Python and ArcPy for environmental data processing and spatial analysis.

## Objectives

- Standardize annual water-quality monitoring tables.
- Combine records into a consistent master dataset.
- Summarize selected water-quality parameters by site and year.
- Examine spatial and temporal patterns across monitoring locations.
- Explore relationships between water-quality conditions and antecedent rainfall.
- Incorporate land-use/land-cover context into interpretation.
- Develop reusable ArcPy scripts rather than relying only on manual GIS processing.

## Planned workflow

1. Inspect and standardize annual monitoring files.
2. Perform data-quality checks and harmonize field names/types.
3. Combine annual records into a master table or feature class.
4. Create or update monitoring-site point features where coordinates are available.
5. Calculate derived fields and summaries using ArcPy data-access cursors.
6. Summarize selected parameters by monitoring site and year.
7. Integrate rainfall and land-use information.
8. Produce maps, tables, and figures for interpretation.
9. Evaluate whether multivariate analysis such as PCA is useful for the final analysis.

## Python / ArcPy concepts

The project is designed to apply:

- `arcpy.da.SearchCursor`
- `arcpy.da.InsertCursor`
- `arcpy.da.UpdateCursor`
- field creation and calculation
- geoprocessing automation
- attribute and spatial data management
- repeatable GIS workflows

## Repository structure

```text
GIS-Water-Quality-Analysis-Dry-Run-Creek/
├── README.md
├── .gitignore
├── config.example.py
├── scripts/
│   └── README.md
├── figures/
├── docs/
└── notebooks/
```

Large/raw geospatial datasets and generated ArcGIS outputs are intentionally excluded from version control.

## Data

The monitoring data used for this project are not redistributed through this repository. The repository focuses on code, documentation, workflow design, and selected non-sensitive figures/results.

## Status

**In development.** Scripts and documentation will be added as the workflow is built and tested.

## Tools

- ArcGIS Pro
- ArcPy
- Python
- GIS / spatial analysis
- Environmental monitoring data

## Author

**Harriet Morkor Quarshie**  
Graduate student in Geography, University of Northern Iowa  
Interests: GIScience, remote sensing, geospatial programming, UAV mapping, and environmental analysis
