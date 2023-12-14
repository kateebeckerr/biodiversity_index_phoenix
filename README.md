# Biodiversity Intactness Index Change in Phoenix from 2017 to 2020

### Author: Kate Becker

### Published: 10/13/2023

## About

This repository contains a notebook, phoenix_biodiversity.ipynb, showcasing the effects of land development. In 2021, Maricopa County, which encompasses the Phoenix metropolitan area, was the US county that added the most developed land since 2001. By exploring a biodiversity intactness index (BII) this analysis found changes in the BII around the Phoenix area from 2017 to 2020.

## Visualizations

After examaining geospatial data, a map, using the Matplotlib library in Pytho, was created to visualize the area in Maricopa County with BII>=0.75 in 2017 that was lost by 2020. The areas with a neon yellow hue are those with BII>=0.75 in 2017 that were lost by 2020. This map is located in the images/directory.

## Highlights

- Data wrangling and exploration with geopandas
- Geospatial data wrangling
- Microsoft Planetary Computer Access and Application
  - Catalog search and selection for io-biodiversity collection
- Creating a visualization using Matplotlib
- Data wrangling for spatial datasets using rioxarray
- Metadata and raster access and exploration for STAC items

## Data

Microsoft. (2022, January 1). Biodiversity Collection on the Microsoft Planetary Computer. Microsoft Planetary Computer. https://www.microsoft.com/planetary-computer/biodiversity-collection

U.S. Census Bureau. (2022). TIGER/Line Shapefiles: 2022 County Subdivisions. U.S. Census Bureau. https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions
