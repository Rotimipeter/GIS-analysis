# NDVI Analysis of Eleyele Basin, Oyo State, Nigeria

## Project Overview

This project presents a **Normalized Difference Vegetation Index (NDVI) analysis of the Eleyele Basin in Oyo State, Nigeria**, using geospatial and remote sensing techniques to assess the spatial distribution and condition of vegetation within the study area.

The analysis demonstrates the application of satellite imagery, GIS, raster processing and spatial analysis techniques to derive and interpret vegetation characteristics across the basin.

The project was undertaken as part of my geospatial/environmental analysis portfolio and demonstrates practical skills relevant to **GIS Analyst, Geospatial Analyst, Remote Sensing and Environmental GIS** roles.

---

## Study Area

**Eleyele Basin, Oyo State, Nigeria**

The Eleyele Basin is located in Oyo State in southwestern Nigeria. The area contains a mixture of built-up areas, vegetation, agricultural land and other land-cover types.

The basin provides a useful study area for demonstrating the application of remote sensing and GIS techniques for vegetation assessment.

---

## Project Objectives

The main objectives of this project were to:

* Calculate NDVI for the Eleyele Basin.
* Assess the spatial distribution of vegetation within the basin.
* Identify areas of relatively high and low vegetation density.
* Produce an NDVI map using GIS and remote sensing techniques.
* Demonstrate the application of satellite imagery for environmental monitoring.
* Develop a reproducible geospatial workflow for vegetation analysis.

---

## Data Used

### Satellite Data

* Satellite imagery: **Landsat 8 **
* Acquisition date: **1984,1989, 1994, 1999,2004, 2009, 2014, and 2019**
* Source: **USGS EarthExplorer**

### Supporting Data

* Eleyele Basin boundary
* Administrative boundary data
* Digital Elevation Model 

## Methodology

The NDVI analysis followed a series of geospatial processing steps:


Satellite Imagery
       ↓
Data Preparation
       ↓
Study Area Delineation
       ↓
Image Clipping
       ↓
Cloud/Quality Filtering
       ↓
Spectral Band Selection
       ↓
NDVI Calculation
       ↓
NDVI Classification
       ↓
Spatial Analysis
       ↓
Map Production
       ↓
Interpretation
```

### NDVI Calculation

The Normalized Difference Vegetation Index was calculated using:

NDVI = \frac{NIR - RED}{NIR + RED}

where:

* **NIR** = Near-Infrared reflectance
* **RED** = Red-band reflectance

Healthy vegetation generally has relatively high NIR reflectance and lower red reflectance, resulting in higher NDVI values.

---

## NDVI Classification

The resulting NDVI values were classified into vegetation-condition categories.

| NDVI Range     | Interpretation                      |
| -------------- | ----------------------------------- |
| Red | Very low vegetation / bare surfaces |
| Orange | Low vegetation                      |
| Yellow] | Moderate vegetation                 |
| Greenish yellow | High vegetation                     |
| Deep Green| Very high vegetation                |


Results

The NDVI analysis revealed spatial variation in vegetation conditions across the Eleyele Basin.

Areas with relatively higher NDVI values represented locations with greater vegetation density. In comparison, lower NDVI values were generally associated with areas such as built-up surfaces, exposed soil, water or sparsely vegetated land.

### Key observations

* Vegetation distribution varied spatially across the basin.
* Higher NDVI values were associated with areas of relatively dense vegetation.
* Lower NDVI values occurred in areas with limited vegetation cover and/or non-vegetated surfaces.
* The NDVI map provides a spatial representation of vegetation conditions that can support environmental monitoring and land-management analysis.

---

## Results Map

### NDVI Map

!Eleyele Basin NDVI Map (images/eleyele_ndvi_map.png)

*Figure 1. NDVI distribution across the Eleyele Basin, Oyo State, Nigeria.*

---

## Additional Outputs

* NDVI raster
* NDVI classified map
* Study-area map
* Satellite imagery
* GIS layers
* Processing workflow
* Statistical summaries
* Charts and visualisations

---

## GIS & Remote Sensing Skills Demonstrated

This project demonstrates experience in:

* Remote sensing
* NDVI analysis
* Raster analysis
* Satellite image processing
* GIS data preparation
* Spatial analysis
* Image classification
* Geospatial visualisation
* Cartographic map production
* Environmental monitoring
* Watershed/basin analysis
* Interpretation of remotely sensed data

---

## Software & Technologies

* **ArcGIS Pro / ArcMap**
* **QGIS**
* **Google Earth Engine**
* Microsoft Excel

## Limitations

The analysis has some limitations, including:

* Satellite imagery may be affected by cloud cover and atmospheric conditions.
* NDVI provides an indicator of vegetation condition but does not directly measure biomass or plant health.
* Different land-cover types can produce similar NDVI values.
* Results are dependent on the spatial and temporal resolution of the satellite imagery.
* The selected NDVI classification thresholds can influence interpretation.

---

## Potential Applications

NDVI analysis can support:

* Vegetation monitoring
* Environmental assessment
* Agricultural monitoring
* Land-cover analysis
* Watershed management
* Deforestation monitoring
* Urban expansion assessment
* Ecosystem monitoring
* Climate and environmental studies

---

## Future Work

Potential extensions of this project include:

1. Performing multi-temporal NDVI analysis to identify vegetation changes over several years.
2. Comparing NDVI with rainfall and climate variables.
3. Investigating the relationship between NDVI and land-use/land-cover change.
4. Integrating NDVI with DEM-derived terrain variables.
5. Performing change-detection analysis.
6. Using Sentinel-2 imagery for higher-resolution vegetation assessment.
7. Developing a time-series vegetation monitoring workflow using Google Earth Engine.
8. Applying machine-learning techniques to classify land cover.

---

## Conclusion

This project demonstrates the use of **GIS and remote sensing techniques to assess vegetation distribution within the Eleyele Basin, Oyo State, Nigeria**.

The analysis provides a spatially explicit representation of vegetation conditions and demonstrates how satellite-derived indices can be integrated with GIS workflows for environmental monitoring and catchment-scale assessment.

The project forms part of my broader interest in **GIS, remote sensing, hydrology, environmental modelling, catchment management and climate-change analysis**.

---

## Author

**ROTIMI PETER OLADELE**

GIS Analyst | Environmental & Hydrological GIS Specialist
rotimipeter6@gmail.com
