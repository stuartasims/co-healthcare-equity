# co-healthcare-equity

-----

## Purpose

Identifying healthcare provider candidates for Support during COVID-19 pandemic.

## Introduction

COVID-19 is affecting minority communities at disproportionate levels in Colorado. The specific drivers of this inequity in the healthcare system are not the target of this analysis but are investigated by groups such as [The Office of Health Equity in the Colorado Department of Public Health and Environment](https://colorado.gov/pacific/cdphe/ohe) and [The Colorado Health Foundation](https://www.coloradohealth.org/how-we-work/how-we-are-working-achieve-health-equity).
The goal of this project is to identify healthcare providers established in communities that are composed primarily of minority populations that may face health inequities. These providers are especially important during this crisis as they are embedded in communities and serve as subject matter experts in meaningful, community-centric interventions to reduce the spread of disease. We suspect they would also benefit from direct support through corporate and individual giving as well as governmental resource allocation.

## Technologies

### Languages
Python 3.7

### Packages
Jupyter
Geopandas
matplotlib
descartes
folium
seaborn
matplotlib



## Table of contents

### Data 

-Input

    -[Healthcare facilities](https://data-cdphe.opendata.arcgis.com/datasets/cdphe-health-facilities/data?geometry=-123.085%2C35.553%2C-81.271%2C41.560)
        - GeoJSON : https://opendata.arcgis.com/datasets/914bc3a28a644f95b13829128e69ede4_0.geojson
    - [American Community Survey 2018 Blocks](https://data.colorado.gov/Demographics/Census-Block-Groups-in-Colorado-2018/ge9s-ra8y)
        - GeoJSON : https://data.colorado.gov/resource/ge9s-ra8y.geojson
-Output

    -Indexed (among colorado as a whole) race/ethnicity household concentrations at high indexing blocks (top 10% blocks using index values)
    -Clipped point features among blocks with 1.01+ index of black/african american households
    -map html containing the raw html of the folium frame in the notebook

### References

- cdphe-oec
    - Health Equity Fact Sheets
        - These fact sheets highlight measured inequities among health indicators among race/ethnicity groups in Colorado
    
- Figures
    -Images for some context in visualizations notebook 

### Code

- Jupyter notebooks
    -One for ingest and cleaning data
    -One for data visualization


## Project status 

In active development. 4/24/2020 release is first public-facing draft


## Other information

 - [Recent news on Black / African American Inequity exposed by COVID-19](https://www.npr.org/sections/coronavirus-live-updates/2020/04/10/832039813/why-misinformation-and-distrust-is-making-covid-19-more-dangerous-for-black-amer)
 - 
 

 
