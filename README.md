# GuptaHemphillWilliams_ENV872_FinalProject

# <ENV872_FinalProject>

## Summary

The primary purpose of this repository is to conduct analysis and generate insights related to energy data, particularly focusing on distributed solar capacity generation in California.
It serves as a centralized location for storing code, data, and documentation related to exploratory research project.

The project aims to explore trends, patterns, and relationships within the energy data, as well as understand the spatial distribution and factors influencing distributed solar capacity generation.

Energy Data: The repository contains Excel files containing data related to distributed solar capacity generation in California, spanning 2015-2021. 
Spatial Data: It includes spatial datasets, such as shapefiles and GeoJSON files, representing geographic boundaries and solar footprints.
Code: R Markdown scripts for data wrangling and spatial analysis tasks.
Final Report: A template and output file for the final project report, indicating a structured analysis process.

Understand Energy Trends: This exploratory analysis seeks to understand the trends in distributed solar capacity generation over time to identify patterns and changes.
Spatial Analysis: This exploratory analysis seeks to the spatial distribution of solar capacity across California counties and investigate spatial relationships with environmental factors or policy implications.
Data Wrangling: Clean, preprocess, and format the energy data to make it suitable for analysis.
Report Generation: Compile the findings and insights into a final report to communicate the analysis process and results effectively.


Where: The analysis focuses on energy data, particularly related to distributed solar capacity generation in California.
When: The temporal scope of the analysis spans 2015-2021, as indicated by the range of data provided in the Excel files.
How: Analysis is conducted using R programming language, as evidenced by the presence of R Markdown scripts. Spatial analysis might involve GIS (Geographic Information Systems) techniques and tools for processing and visualizing spatial data.

## Investigators

<Brook Hemphill, brook.hemphill@duke.edu - Spatial Analyst, MF candidate>, 
<Shubhangi Gupta, shubhangi.gupta@duke.edu , MEM candidate - Energy Analyst> 
<Sydney Williams, sydney,williams@duke.edu, MEM candidate - Energy Analyst>

## Keywords

<small-scale pv capacity, capacity, generation, electricity prices>

## Database Information

EnergyData Folder
Form EIA- 861M Detailed Data, Small Scale PV Estimate, accessed April 1, 2024
https://www.eia.gov/electricity/data/eia861m/
Timeframe: 2015 to 2021
Description: The data contain capacity (in AC) and estimated generation from PV solar systems less than 1 megawatt in size. The purpose of this threshold is to include PV capacity and generation that is otherwise not collected on Form EIA-860 and Form EIA-923, which collects data from utility-scale electricity -generation systems. Data are created from net-metering and non-net-metering distributed PV data using formulas and adjustments described in the technical notes of the Electric Power Monthly.

SpatialData Folder
Solar Footprints in California Dataset, accessed April 1, 2024 - https://cecgis-caenergy.opendata.arcgis.com/datasets/9398e39a0424434b9e95ccf8e8938807_0/explore?location=36.209468%2C-119.976002%2C8.96    
2018 Social Vulnerability Index CSV file from Agency for Toxic Substances and Disease Registry, accessed April 1, 2024 - https://www.atsdr.cdc.gov/placeandhealth/svi/data_documentation_download.html 
USA Counties Shapefile filtered for California counties - dataset provided by class


## Folder structure, file formats, and naming conventions 

Coding Folder:
EnergyDataWrangling.Rmd - used for wrangling and pre-processing of the energy data
SpatialAnalysis.Rmd - used for the spatial analysis

EnergyData:
CaliforniaDistributedSolarCapGen2015-21.xlsx - Data regarding distributed solar distributed solar capacity generation in California from 2015 to 2021.
NEMPVPriceData2015-22.xlsx - Data related to NEM (Net Energy Metering) PV (Photovoltaic) price from 2015 to 2022.

FinalReport:
Project_Template.Rmd
Project_Template.html

SpatialData Folder:
California_county.csv - a CSV file containing information about California counties.
Solar_Footprints_V2_-1101629766070969057 (1).geojson - GeoJSON files representing solar footprints. 
Solar_Footprints_V2_-1101629766070969057 (2).geojson - GeoJSON files representing solar footprints. 
cb_2018_us_county_20m.cpg - Shapefile components representing US county boundaries from the 2018 Census Bureau data.
cb_2018_us_county_20m.dbf - Shapefile components representing US county boundaries from the 2018 Census Bureau data.
cb_2018_us_county_20m.prj - Shapefile components representing US county boundaries from the 2018 Census Bureau data.
cb_2018_us_county_20m.shp - Shapefile components representing US county boundaries from the 2018 Census Bureau data.
cb_2018_us_county_20m.shp.ea.iso.xml -Shapefile components representing US county boundaries from the 2018 Census Bureau data.
cb_2018_us_county_20m.shp.iso.xml- Shapefile components representing US county boundaries from the 2018 Census Bureau data.
cb_2018_us_county_20m.shx - Shapefile components representing US county boundaries from the 2018 Census Bureau data.

.gitignore
GuptaHemphillWilliams_ENV872_FinalProject.Rproj
LICENSE
README.md

## Metadata

EnergyData 
CaliforniaDistributedSolarCapGen2015-21.xlsx
1. Year - year, numeric
2. Month - month, numeric
3. State - state name, character
4. Data Status - data status, character
5. Cap-Residential - residential solar PV capacity, numeric, MW
6. Cap-Commercial - commercial solar PV capacity, numeric, MW
7. Cap-Industrial - industrial solar PV capacity, numeric, MW
8. Cap-Total - total solar PV capacity, numeric, MW
9. Gen-Residential - residential solar PV generation, numeric, MWh
10.Gen-Commercial - commercial solar PV generation, numeric, MWh
11.Gen-Industrial - industrial solar PV generation, numeric, MWh
12.Gen-Total - total solar PV generation, numeric, MWh 
   


SpatialData
California_county.csv
1. COUNTY - county name, character  
2. FIPS - county code, factor
3. LOCATION - county name, character
4. E_TOTPOP - estimated total population, integer
5. E_POV - estimated employed population, integer
6. E_MINRTY - estimated minority population, integer



Solar_Footprints_V2_-1101629766070969057 (1).geojson
1. COUNTYNAME - contains names of counties in California, character
2. Type - solar footprint type (rooftop, parking lot, or ground), character
3. Urban_Rural - solar footprint location (urban or rural), character
3. Acres - solar footprint area in acres, number, acres
4. geometry - spatial information, SFC_multipolygon


cb_2018_us_county_20m.shp
1. STATEFP - state code, character
2. COUNTYFP - county code, character 
3. COUNTYYNS, character
4. GEOID, character
5. NAME - name of county, character
6. ALAND - area of land, number
7. AWATER - area of water, number 
8. GEOMETRY - spatial information, SFC_multipolygon



## Scripts and code

<list any software scripts/code contained in the repository and a description of their purpose.>
