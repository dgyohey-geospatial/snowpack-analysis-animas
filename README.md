# snowpack-analysis-animas
# Snowpack Analysis – Animas River Watershed

This project develops a reproducible geospatial workflow using Python (ArcPy) to analyze snow water equivalent (SWE) across the Animas River watershed.

---

## Study Area

- HU-8 Animas River Watershed  
- Southwestern Colorado / Northwestern New Mexico  

---

## Data

- DAYMET SWE (monthly means, 1 km resolution)  
- Time range: 2015–2025 water years  
- Source: ClimateEngine.org  

---

## Workflow

1. Validate raster datasets using ArcPy `Describe()`  
2. Project rasters to watershed coordinate system  
3. Clip rasters to AOI boundary  
4. Iterate through monthly datasets using Python  
5. Generate outputs for seasonal comparison  

---

## Tools Used

- ArcGIS Pro  
- ArcPy (Python)  
- Jupyter Notebook  

---

## Purpose

This project demonstrates:
- Raster data processing workflows  
- Automation using Python in GIS  
- Hydrologic pattern analysis using remote sensing data  

---

## Future Improvements

- Automate full pipeline  
- Add visualization outputs  
- Integrate with web mapping or dashboards  

---

## Author

Daniel Yohey  
Geospatial Analysis & Consulting
