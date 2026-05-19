# ZüriWieNeu Urban Report Analysis

Analysis of reported infrastructure issues in Zurich using open data from the 
ZüriWieNeu platform, combined with statistical neighbourhood boundaries.

## Data Sources
- ZüriWieNeu reports: https://data.stadt-zuerich.ch/dataset/geo_zueri_wie_neu
- Statistical neighbourhood boundaries: https://data.stadt-zuerich.ch/dataset/geo_statistische_quartiere

## How to Run

1. Place the data files in the `data/` folder:
   - `zurich_reports.csv`
   - `zurich_quartiere.json`
   - `zurich_quartiere_names.json`

2. Open and run `notebooks/project1_analysis.ipynb` from top to bottom.

## Repository Structure

SDS210/
├── data/               # Input data files (not tracked by Git)
├── notebooks/          # Jupyter notebook with full analysis
├── outputs/            # Generated maps and charts
└── README.md

## Research Questions
- Q1: Which neighbourhoods have the most reports?
- Q2: What are the most common problem categories?
- Q3: How have reports changed over the years?
- Q4: Which categories dominate in the busiest neighbourhoods?
- Q5: What is the resolution rate per neighbourhood?
- Q6: On which day of the week are most reports submitted?
- Q7: Spotlight on Oerlikon neighbourhood