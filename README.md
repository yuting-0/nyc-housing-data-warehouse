# NYC Housing Data Warehouse

A team data engineering project exploring NYC housing conditions by integrating NYC 311 service requests with HPD Housing Maintenance Code Violations data.

## Project Overview

This project examines housing-related complaints across New York City's five boroughs, focusing on heat and hot water, plumbing, and unsanitary conditions.

The goal is to design an analytical data warehouse that integrates 311 complaint records and HPD violation records to support housing trend analysis and KPI reporting.

## Data Sources

- **NYC 311 Service Requests:** Housing complaints filtered to HEAT/HOT WATER, PLUMBING, and UNSANITARY CONDITION.
- **HPD Housing Maintenance Code Violations:** Housing code violation records.

Both datasets are obtained from NYC Open Data.

## Project Work

- Profiled January 2026 samples of both datasets to assess data quality, missing values, duplicates, and field consistency.
- Examined complaint and violation distributions across the five boroughs.
- Evaluated BBL-based geographic overlap between the datasets.
- Designed a dimensional warehouse model with separate complaint and violation fact tables and shared location and date dimensions.
- Identified analytical KPIs for housing complaint and violation reporting.

## Planned Technology

- Python and pandas for data profiling and processing.
- SQL for data transformation.
- Google BigQuery for cloud data warehousing.
- dbt for ELT transformations.
- Tableau for analytical dashboards.

## Repository Structure

- `notebooks/`: Data extraction and profiling notebooks.
- `data/`: Instructions for obtaining source datasets.
- `models/`: Dimensional models and architecture diagrams.
- `dbt/`: dbt project and SQL models.
- `docs/`: Project documentation.

## Project Status

Currently in the data profiling, requirements, dimensional modeling, and architecture planning stages. Warehouse implementation and dashboard development are planned.

## Contributors

| Name | GitHub | Contributions |
|---|---|---|
| Yuting Wu | [@yuting-0](https://github.com/yuting-0) | Data profiling and dimensional modeling |
| Jenna Lopez | [@username](https://github.com/username) | January 2026 data extraction |
| Dia Dulal | [@username](https://github.com/username) | To be updated |
| Amber Segura | [@username](https://github.com/username) | To be updated |
