# Environmental Exposure and Neurodevelopment Dashboard

## Overview
This interactive Flexdashboard explores associations between prenatal pesticide exposure and neurodevelopmental outcomes in children. It integrates multiple statistical approaches including linear regression and Weighted Quantile Sum (WQS) regression to assess both individual chemical effects and mixture effects.

## Research Focus
This project investigates whether prenatal exposure to pesticide metabolites is associated with differences in cortical brain structure, including cortical thickness and surface area.

## Data Sources
The dataset is derived from a longitudinal birth cohort study. Maternal urine samples were analyzed for pesticide metabolites using laboratory-based mass spectrometry methods. Neuroimaging data were collected using MRI in early childhood.

- Sample size: N = [insert N]
- Study population: Mother–child pairs
- Collection period: [insert years]
- Data collection method: Clinical visits, biospecimen analysis, and neuroimaging

## Dashboard Features
- Interactive forest plots with hover tooltips showing effect estimates and confidence intervals
- Exposure distribution plots by pesticide class
- Brain region summaries (thickness and surface area)
- Weighted Quantile Sum (WQS) regression mixture analysis
- Dataset description tab for transparency and reproducibility

## Interactivity
All plots are interactive using Plotly, allowing:
- Hover tooltips with detailed statistical output
- Zooming and panning
- Facet comparisons across brain regions
- Highlighting by statistical significance

## Files Included
- `dashboard.Rmd`: Flexdashboard source code
- `merged_all.csv`: Analysis dataset (not included if confidential)
- `WQS models`: Pre-fitted model objects
- `README.md`: Project documentation

## How to Run
```r
rmarkdown::run("dashboard.Rmd")