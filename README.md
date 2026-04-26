# Prenatal Pesticide Exposure and Childhood Brain Development Dashboard

## Overview
This interactive Flexdashboard explores associations between prenatal pesticide exposure and neurodevelopmental outcomes in children. It integrates multiple statistical approaches including linear regression and Weighted Quantile Sum (WQS) regression to assess both individual chemical effects and mixture effects.

## Research Focus and Importance
This project investigates whether prenatal exposure to pesticide metabolites is associated with differences in cortical brain structure, including cortical thickness and surface area.Prenatal exposure to pesticides may influence early brain development, with potential long-term impacts on cognitive and neurological health. This dashboard provides an accessible way to explore these associations, supporting research and public health efforts aimed at reducing harmful environmental exposures during critical developmental periods.

## Data Sources
The dataset is derived from a longitudinal birth cohort study. Maternal urine samples were analyzed for pesticide metabolites using laboratory-based mass spectrometry methods. Neuroimaging data were collected using MRI in early childhood.

- Sample size: N = 120
- Study population: Mother–child pairs
- Data collection method: Clinical visits, biospecimen analysis, and neuroimaging

## Dashboard

View the dashboard here:  
[Prenatal Pesticide Exposure Dashboard](https://najiyahwilliamson7.github.io/Thesis-Dashboard/)

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
- `Prenatal-Pesticide-Exposure-and-Childhood-Brain-Development.Rmd`: Flexdashboard source code
- `Prenatal-Pesticide-Exposure-and-Childhood-Brain-Development.html`: actual dashboard 
- `README.md`: Project documentation

## How to Run
```r
rmarkdown::run("Prenatal-Pesticide-Exposure-and-Childhood-Brain-Development.Rmd")