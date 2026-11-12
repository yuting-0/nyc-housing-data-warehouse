# Dataset Information

This project uses NYC Open Data to analyze housing-related 311 complaints and HPD Housing Maintenance Code Violations.

## Data Sources

**1. NYC 311 Service Requests**
- Source: [NYC Open Data](https://data.cityofnewyork.us/)
- Dataset ID: `erm2-nwe9`
- Filters: HEAT/HOT WATER, PLUMBING, and UNSANITARY CONDITION complaints.
- Date range: January 1–31, 2026, based on complaint creation date.
- Output file: `nyc_311_january_2026.csv`

**2. HPD Housing Maintenance Code Violations**
- Source: [NYC Open Data](https://data.cityofnewyork.us/)
- Dataset ID: `wvxf-dwi5`
- Date range: January 1–31, 2026, based on inspection date.
- Output file: `hpd_violations_january_2026.csv`

## Obtaining the Data

The CSV files are generated using the data extraction notebook in `notebooks/`.

Run the notebook in Google Colab to retrieve the filtered records from NYC Open Data and export the datasets as CSV files.

The generated CSV files are used by the data profiling notebook for exploratory analysis and data quality assessment.
