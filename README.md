# LAI Estimation using Sentinel-2 and Landsat 8/9

This repository contains the data processing workflow and analysis used in my dissertation on Leaf Area Index (LAI) estimation in tropical forest and oil palm plantations in Jambi, Sumatra.

## Overview

The study evaluates how well vegetation indices derived from Sentinel-2 and Landsat 8/9 estimate LAI using ground-based measurements.

## Methods

The workflow includes:

- Satellite data extraction using Google Earth Engine  
- Cloud and shadow masking (Sentinel-2 and Landsat QA)  
- Temporal matching to field observations (±15-50 days)  
- Vegetation index calculation (NDVI, NDRE705, CIre705, MTCI)  
- Extraction using:
  - Single-pixel sampling  
  - Area-weighted aggregation  
- Statistical analysis using linear regression and cross-validation  

## Repository structure

- `/code` - scripts and notebooks used for processing and analysis  
- `/data` - processed datasets used for modelling (raw LAI data not included)  
- `/outputs` - figures and model outputs  

## Data availability

The field LAI dataset was provided by Pallavi et al. (2024) and is not included in this repository due to data sharing restrictions.

## Reproducibility

All scripts are provided to reproduce the results presented in the dissertation. Satellite data are accessed through Google Earth Engine.
