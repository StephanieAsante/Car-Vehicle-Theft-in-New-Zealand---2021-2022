
# Vehicle Theft Analysis in New Zealand (2021–2022)

This project analyzes vehicle theft incidents reported across New Zealand between 2021 and 2022, using interactive Power BI dashboards to identify trends in theft activity by time, location, and vehicle characteristics.

---

## Overview

Vehicle theft is a significant public safety and economic issue, affecting individuals, insurers, and law enforcement agencies. This project analyzes vehicle theft data from **Maven Analytics** covering reported incidents in New Zealand between 2021 and 2022. Using **Microsoft Power BI**, the data was cleaned, modeled, and visualized to examine theft patterns across regions, vehicle types, manufacturers, model years, and time periods. The analysis identifies theft hotspots, vulnerable vehicle categories, and temporal trends, providing insights that can support crime prevention strategies, insurance risk assessment, and evidence-based policymaking.

---

## Repository Structure

```text
├── data/
│   ├── Stolen Vehicle Data.csv
│   ├── Car theft locations - Lookup.csv
│   ├── Make details - Lookup.csv
│   └── stolen_vehicles_db_data_dictionary.csv
├── dashboard/
│   └── Car Theft Dashboard.pbix          # Interactive Power BI dashboard
├── report/
│   └── New Zealand Car Theft (2021-2022) - REPORT.pdf
├── README.md                            # Project documentation
```

### Tools & Technologies

* **Visualization Tool:** Microsoft Power BI
* **Data Source:** Maven Analytics
* **Analysis:** Data Cleaning, Data Modeling, DAX Measures, Geographic Analysis, Time Series Analysis, Interactive Dashboards

### Dataset

The analysis uses a **Maven Analytics** dataset containing reported vehicle theft incidents in New Zealand between **2021 and 2022**. The repository includes supporting lookup tables and a data dictionary to facilitate analysis.

The datasets include information on:

* Vehicle make and type
* Model year
* Vehicle color
* Theft date
* Geographic location
* Regional population data
* Lookup tables for vehicle makes and theft locations

The data was prepared by cleaning missing values, standardizing variables, creating calculated measures, and establishing relationships between multiple tables within Power BI.

### Key Findings

* Vehicle theft increased by **53.46%** between 2021 and 2022.
* **March 2022** recorded the highest number of reported vehicle thefts.
* More than half of all theft incidents occurred during the first quarter of 2022.
* **Auckland** recorded the highest number of vehicle thefts, while **Gisborne** had the highest theft rate relative to its population.
* **Station wagons** were the most frequently stolen vehicle type.
* **Toyota** was the most commonly stolen vehicle manufacturer.
* Standard vehicles accounted for the overwhelming majority of theft incidents, while luxury vehicles represented only a small proportion.
* Older vehicle models, particularly the **2006 saloon**, were more susceptible to theft, suggesting vulnerabilities associated with ageing vehicle security systems.

### Dashboard

The interactive Power BI dashboard enables users to explore:

* Vehicle theft trends over time
* Regional theft distribution and theft rates
* Vehicle type and manufacturer analysis
* Model year and vehicle color trends
* Geographic hotspot identification
* Interactive filtering by region, vehicle type, make, model year, and date

### Report

A comprehensive PDF report is included in the repository, detailing the project's methodology, dashboard design, key findings, interpretations, and recommendations for law enforcement, insurers, and policymakers.

### Files

* **Power BI Dashboard (.pbix):** Interactive dashboard for exploring vehicle theft patterns.
* **PDF Report:** Complete project documentation and analysis.
* **CSV Files:** Source datasets, lookup tables, and data dictionary used in the analysis.



# Overview of Vehicle Theft 
The Executive Dashboard provides a high-level summary of vehicle theft activity across New Zealand during the study period. 

<img width="730" height="404" alt="image" src="https://github.com/user-attachments/assets/ab04b92d-fee2-4997-9bcd-a294505a0eac" />

# Time Based Trends
Analysis of vehicle theft incidents over time indicates a substantial increase in theft activity in 2022 compared to 2021.
<img width="716" height="409" alt="image" src="https://github.com/user-attachments/assets/6e10ad01-09c8-4d45-ab05-cd7a81b539b8" />


# Geographic and Location Risk Analysis
<img width="705" height="406" alt="image" src="https://github.com/user-attachments/assets/89efff2f-c3e5-4494-92f8-d8c854851773" />


# Make and Model Performance Insights
<img width="715" height="410" alt="image" src="https://github.com/user-attachments/assets/d12c2907-9c0e-4444-9ca9-3987b1c1be65" />


