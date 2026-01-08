# COVID-19 Mortality Spatial Analysis in England

## Overview
This project investigates the spatial variation of COVID-19 mortality across 296 English local authorities. The analysis explores whether mortality patterns can be explained by socio-economic deprivation, education, age structure, and occupational characteristics.

## Objectives
- Examine spatial inequality in COVID-19 mortality
- Identify key socio-economic predictors
- Reduce dimensionality using Principal Component Analysis (PCA)
- Model relationships using correlation and regression techniques

## Data
- COVID-19 mortality rates (local authority level)
- Socio-economic indicators including deprivation, education, and occupation
- All data are aggregated and publicly available

## Methods
- Exploratory data analysis
- Correlation and partial correlation analysis
- Principal Component Analysis (PCA)
- Multiple linear regression

## Tools
- R (tidyverse, psych, factoextra, sf)
- QGIS / spatial mapping tools

## Key Findings
- COVID-19 mortality is not randomly distributed across England
- Education emerges as the strongest and most consistent predictor
- Clear spatial clustering aligned with socio-economic disadvantage

## Structure
- `data/` – cleaned datasets
- `code/` – analysis scripts
- `figures/` – plots and maps
- `report/` – final academic report

## Author
MSc Data Science – University of East London
