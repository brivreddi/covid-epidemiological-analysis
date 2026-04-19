# COVID-19 Epidemiological Analysis: Geographic Variation Across Indian States

## Overview
Analyzed COVID-19 surveillance data across Indian states to assess geographic variation in health outcomes and identify potential disparities in healthcare capacity and public health response.

## Key Insights
- Identified a **4-fold variation in Case Fatality Rate (0.5%–2.1%)** across states  
- Found significant differences in recovery rates and active case burden  
- Observed clustering of case burden, with top 3 states accounting for ~40% of total cases  
- Results suggest healthcare infrastructure, testing strategies, and public health interventions influenced outcomes beyond the disease itself  

## Dataset
- Source: COVID-19 India dataset (Kaggle)  
- Time period: Jan 2020 – Aug 2021  
- Coverage: 36 states and Union Territories  
- Size: ~18,000 records  

## Methods
- Cleaned and standardized inconsistent state names and removed non-geographic entries  
- Handled cumulative time-series data using groupby-max aggregation  
- Calculated epidemiological metrics:
  - Case Fatality Rate (CFR)  
  - Recovery Rate  
  - Active Case Rate  
- Performed comparative analysis across states and national aggregates  

## Tools Used
- Python (pandas, matplotlib)  
- Jupyter Notebook  

## Files
- `covid_analysis.ipynb` → main analysis  
- `analysis_report.txt/pdf` → detailed report  

## Notes
This project demonstrates the ability to work with real-world healthcare datasets, apply epidemiological methods, and derive actionable insights from population-level data.
