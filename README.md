# US-Financial-Crime-Analysis-Python

# Analyzing SAR Filing Patterns and MSB Distribution
**Technical Toolkit: Python | Pandas | Matplotlib | Seaborn 

## [📺 Watch the Project Presentation Video] - https://youtu.be/zKYCdiRiDts
## Project Objective
This project examines nationwide patterns in Suspicious Activity Report (SAR) filings and evaluates their relationship with Money Services Business (MSB) density. By integrating multi-source regulatory data, the analysis identifies geographic hotspots and quantifies the correlation between MSB presence and suspicious financial activity.

## Audit & Compliance Relevance
This project demonstrates the ability to use **Python for Regulatory Technology (RegTech)**:
* [cite_start]**Automated Data Integration:** Merged FinCEN SAR statistics, the MSB Registrant Database, and synthetic fraud benchmarks to create a unified analytical view.
* [cite_start]**Statistical Auditing:** Applied a linear regression model to validate the relationship between entity density and filing volume (β₁ = 46.42, R² = 0.44)[cite: 1329].
* [cite_start]**Trend Analysis:** Identified a 3.7% annualized growth rate in SAR filings from 2020 to 2025, reaching nearly 1.25 million annual filings[cite: 1328].

## Key Technical Workflows
1. [cite_start]**Data Cleaning:** Standardized disparate schemas, mapped state abbreviations to full names, and handled missing values across three datasets.
2. [cite_start]**EDA:** Generated visual filing trends by state (CA, NY, TX, FL) and industry category[cite: 1102].
3. [cite_start]**Modeling:** Developed a single-predictor regression model to quantify how each additional MSB correlates with ~46 additional SAR filings[cite: 1329].

## Author
**David Gibbens, CAMS, CPA, MBA**
*Financial Crimes Audit Leader | Data Science Major @ ASU* - www.linkedin.com/in/djogibbens
