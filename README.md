# Urban vs Rural Vegetation Comparison Using NDVI
### A GIS and Remote Sensing Assessment of Kanker Khera and Daurala, Meerut, India

## Overview

This project compares vegetation density between an urban area (Kanker Khera) and a rural area (Daurala) in Meerut, India using Sentinel-2 satellite imagery and the Normalized Difference Vegetation Index (NDVI).

The objective was to investigate how vegetation differs between urban and rural landscapes through GIS and remote sensing techniques while developing practical skills in satellite image processing, raster analysis, and environmental data interpretation.

This is the second project in my self-directed GIS and Remote Sensing learning journey.

---

## Objectives

- Calculate NDVI for both study areas using Sentinel-2 imagery.
- Compare vegetation density between urban and rural environments.
- Analyse NDVI statistics.
- Classify vegetation into density classes.
- Interpret vegetation distribution using GIS.

---

## Study Areas

### Kanker Khera (Urban)

- Residential and commercial area in Meerut
- Dominated by buildings, roads, and small green spaces

### Daurala (Rural)

- Village north of Meerut
- Predominantly agricultural landscape
- Large sugarcane fields and other cultivated land

---

## Data

**Satellite:** Sentinel-2

**Source:** Copernicus Browser

**Spatial Resolution:** 10 m

**Software Used**

- QGIS
- Copernicus Browser

---

## Methodology

1. Download Sentinel-2 imagery.
2. Import Red (Band 4) and Near Infrared (Band 8) bands into QGIS.
3. Calculate NDVI using Raster Calculator.

\[
NDVI=\frac{NIR-Red}{NIR+Red}
\]

4. Calculate descriptive statistics.
5. Reclassify NDVI into vegetation-density classes.
6. Compare vegetation distribution between the two study areas.

---

## NDVI Classification

| NDVI | Vegetation Class |
|------:|------------------|
| -1.00 – 0.20 | Very Low Vegetation |
| 0.20 – 0.40 | Sparse Vegetation |
| 0.40 – 0.60 | Moderate Vegetation |
| 0.60 – 1.00 | Dense Vegetation |

---

## Results

### NDVI Statistics

| Statistic | Kanker Khera | Daurala |
|-----------|-------------:|---------:|
| Mean NDVI | 0.237 | 0.451 |
| Minimum NDVI | 0.053 | 0.182 |
| Maximum NDVI | 0.944 | 0.960 |
| Standard Deviation | 0.187 | 0.269 |

### Vegetation Distribution

| Class | Urban (%) | Rural (%) |
|--------|----------:|----------:|
| Very Low | 55.68 | 24.02 |
| Sparse | 24.59 | 20.99 |
| Moderate | 13.43 | 19.74 |
| Dense | 6.21 | 34.66 |

---

## Key Findings

- Daurala exhibited almost twice the mean NDVI of Kanker Khera.
- More than half of Kanker Khera consisted of very low vegetation.
- Over one-third of Daurala consisted of dense vegetation.
- Agricultural land was the dominant source of vegetation in the rural landscape.
- Urban vegetation was largely limited to scattered trees, gardens, and parks.

---

## Skills Demonstrated

- GIS
- Remote Sensing
- QGIS
- Raster Analysis
- NDVI Calculation
- Sentinel-2 Image Processing
- Land Cover Classification
- Spatial Data Analysis
- Scientific Report Writing
- Environmental Data Interpretation

---

## Future Work

This project serves as a foundation for future GIS and remote sensing studies, including:

- Urban Heat Island Analysis
- Land Surface Temperature Mapping
- Urban Greening Assessment
- Vegetation Change Detection
- Green Corridor Identification

---
