# AI-Assisted Marine Risk Intelligence & Community Reporting Platform

## Internship Details

Name: Ayush Kumar
Roll No.: 25SCS1003003078
Section: 2CSE 21
Batch: 2025–2029
College: School of Computer Science & Engineering, IILM University, Greater Noida
Organization: MARS – Centre for Sustainable Community Development
Duration: 1 June 2026 – 15 July 2026
Role: GIS Engineer

## Project Overview

The project focused on monitoring and visualizing marine heatwaves using satellite-derived sea surface temperature data and coastal community reports.

As the GIS Engineer, I worked on processing, validating, and preparing spatial data for GIS visualization and integration with the project dashboard.

## Key Contributions

* Cleaned and processed satellite-derived spatial datasets.
* Converted longitude values from the 0–360° format to the standard −180°–+180° format.
* Used WGS 84 (EPSG:4326) for spatial data representation.
* Filtered data for the defined study area:

  * Latitude: −20° to +20°
  * Longitude: −60° to +15°
* Filtered heatwave risk records using `Risk_Label >= 1`.
* Created and styled heatwave visualization layers in QGIS.
* Used `SST_Anomaly` to visualize sea surface temperature variations.
* Prepared grid-based map visualizations and QGIS print layouts.
* Addressed WMS, map tiling, and export-resolution issues.
* Exported the processed dataset as `fixed_atlantic_heatwaves.csv`.
* Prepared Plotly and Streamlit components for dashboard integration.

## Technology Stack

QGIS, Python, Pandas, NumPy, PostGIS, Plotly Express, Streamlit, WGS 84 (EPSG:4326), CSV, NetCDF

## Workflow

Raw Satellite Data → Data Cleaning → Longitude Correction → Study Area Filtering → Risk Filtering → QGIS Visualization → SST Anomaly Mapping → Processed Dataset → Dashboard Integration

## Contribution Summary

My primary contribution was developing the GIS and spatial-data processing workflow, transforming raw satellite observations into clean, geographically consistent, and dashboard-ready data for marine heatwave visualization.
