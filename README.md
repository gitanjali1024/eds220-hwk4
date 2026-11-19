# Visualizing fire scars through false color

## About

This repository houses information on the Palisades and Eaton fires in 2025. Using landsat satellite data and fire perimeter scars, true and false color imagery was used to visualize how those fires impacted the region, and how remaining burn scars compare to the inital burned area.

## Repository Structure

eds220-hwk4                                 
│--  .gitignore                                
│--  hwk4-task2-false-color-SHARMA.ipynb     
│--  README.md  

## Data

This notebook uses two datasets:

1) Landsat 8 reflectance bands
The first is a simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmospherically corrected surface reflectance data, collected by the Landsat 8 satellite. The data was retrieved from the Microsoft Planetary Computer data catalog and clipped to an area surrounding the fire perimeters. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2


2) Fire perimeters for Eaton and Palisades fires
The second dataset will be fire perimeters for the Eaton and Palisades fires. This data is from the CAL FIRE Historical fire perimeter dataset, and is housed on the LA county ArcGIS hub. It was downlaoded as a shapefile, with one file for each fire. https://egis-lacounty.hub.arcgis.com/datasets/lacounty::palisades-and-eaton-dissolved-fire-perimeters-2025

This data is not housed in the repository. Access it from the sources listed above.

### References

Los Angeles County. (2025). Palisades and Eaton dissolved fire perimeters (2025) [GIS dataset]. Los Angeles County Enterprise GIS. https://egis-lacounty.hub.arcgis.com/datasets/lacounty::palisades-and-eaton-dissolved-fire-perimeters-2025

Microsoft. (n.d.). Landsat Collection 2 Level-2. Microsoft Planetary Computer. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2


