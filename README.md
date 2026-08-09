# 🌍 Global Tuberculosis Epidemiological Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![WHO](https://img.shields.io/badge/Data%20Source-WHO-red)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

Tuberculosis (TB) remains one of the major global public health challenges.

This project presents a comprehensive epidemiological analysis of tuberculosis burden across countries and WHO regions using data from the **World Health Organization (WHO)**.

The analysis combines **epidemiological methods, Python-based data analytics, and Microsoft Power BI** to identify patterns in TB cases, deaths, incidence, mortality, and case fatality rates.

The project transforms raw epidemiological data into a cleaned analytical dataset, statistical insights, visualizations, and an interactive public health dashboard.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze the global burden of tuberculosis.
- Identify countries with the highest TB case burden.
- Identify countries with the highest TB mortality.
- Compare TB burden across WHO regions.
- Analyze temporal trends in TB cases and deaths.
- Examine TB incidence and mortality rates.
- Analyze case fatality rate (CFR).
- Explore relationships between TB incidence and mortality.
- Develop an interactive Power BI dashboard.
- Generate evidence-based public health recommendations.

---

## 📊 Dataset

### Data Source

The dataset was obtained from the:

**World Health Organization (WHO) Global Tuberculosis Programme**

### Dataset Overview

| Characteristic | Description |
|---|---|
| Disease | Tuberculosis (TB) |
| Source | World Health Organization |
| Observations | 5,347 |
| Analytical Variables | 15 |
| Geographic Level | Country |
| Regional Classification | WHO Region |
| Time Period | 2000–2024 |
| Format | CSV |

### Key Variables

- `Country`
- `ISO3`
- `WHO_Region`
- `Year`
- `Population`
- `TB_Cases`
- `TB_Deaths`
- `TB_Incidence_Rate`
- `Mortality_Rate`
- `cfr_pct`

---

# 🔬 Methodology

The project followed a structured epidemiological data analysis workflow:

```text
WHO TB Data
     ↓
Data Loading
     ↓
Initial Data Exploration
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Epidemiological Analysis
     ↓
Data Visualization



Data Cleaning
The following data preparation steps were performed:
Inspection of dataset structure.
Data type validation.
Missing-value assessment.
Duplicate checking.
Country and WHO region validation.
Selection of relevant variables.
Numerical variable preparation.
Preparation of epidemiological indicators.

The final cleaned dataset contains:

5,347 observations and 15 analytical variables.


⚙️ Feature Engineering
Several analytical features were prepared to support epidemiological analysis:
Annual TB cases
Annual TB deaths
Country-level TB burden
Regional TB burden
Average TB incidence rate
Average TB mortality rate
Case Fatality Rate (CFR)
Incidence–mortality relationships

📈 Exploratory Data Analysis
The exploratory analysis examined:
Temporal Trends
Global TB cases over time
Global TB deaths over time
Case fatality rate trends
Geographic Analysis
Top countries by TB cases
Top countries by TB deaths
TB burden by WHO region
Global geographic distribution
Epidemiological Indicators
TB incidence rate
TB mortality rate
Case fatality rate
Incidence vs mortality

📊 Key Findings
The analysis identified several important epidemiological patterns.
Global TB Burden
Approximately:
281.4 million TB cases
49.9 million TB deaths

were recorded across the observations included in the analytical dataset.

These are cumulative values across countries and years in the analyzed dataset and should not be interpreted as a single-year global estimate.

Highest Country-Level Burden

India recorded the highest cumulative TB burden in the analyzed dataset:

TB Cases: 80.32 million
TB Deaths: 14.15 million
Highest Regional Burden

The WHO South-East Asia (SEA) region recorded the highest cumulative TB case burden:

Approximately 100.48 million cases
Temporal Pattern

The highest annual number of TB cases in the analyzed series occurred in:

2005 — approximately 12.05 million cases

Epidemiological Indicators
Indicator	Result
Total TB Cases	281.4M
Total TB Deaths	49.9M
Average Incidence Rate	138.21
Average Mortality Rate	31.41
Average CFR	16.32%


📊 Power BI Dashboard
An interactive Power BI dashboard was developed to communicate the epidemiological findings.
The dashboard contains three pages.

Page 1 — Global TB Overview
The first page provides a global overview of tuberculosis burden.

Key Performance Indicators
Total TB Cases
Total TB Deaths
Average TB Incidence Rate
Average TB Mortality Rate
Case Fatality Rate
Visualizations
Global TB Cases Trend
Global TB Mortality Trend
TB Burden by WHO Region
Dashboard Preview

🌍 Page 2 — Country & Regional TB Burden Analysis
This page focuses on geographic variation in TB burden.
Visualizations
Top 10 Countries by TB Cases
Top 10 Countries by TB Deaths
TB Burden by WHO Region
Global TB Distribution Map
Interactive Filters
Year
Country
WHO Region
Dashboard Preview

🧬 Page 3 — TB Epidemiological Analysis
The third page focuses on epidemiological indicators and comparisons.
Visualizations
Average TB Incidence Rate by WHO Region
Average TB Mortality Rate by WHO Region
Top 10 Countries by Case Fatality Rate
Global Case Fatality Rate Trend
Interactive Filters
Year
Country
WHO Region
Dashboard Preview

🏥 Public Health Recommendations
Based on the epidemiological findings, the following recommendations are proposed:
1. Strengthen Early Detection
Expand TB screening and diagnostic services.
Strengthen active case-finding.
Reduce delays between symptoms, diagnosis, and treatment.
2. Improve Treatment Coverage
Improve access to TB treatment.
Strengthen treatment adherence.
Reduce treatment interruption and loss to follow-up.
3. Prioritize High-Burden Settings

Resources should be prioritized toward countries and regions with:

High numbers of TB cases.
High TB mortality.
High incidence rates.
Relatively high case fatality rates.
4. Strengthen TB Surveillance
Improve data completeness.
Improve reporting timeliness.
Strengthen data quality assurance.
Monitor epidemiological indicators routinely.
5. Use Data Visualization for Decision-Making

Interactive dashboards can support:

Disease surveillance
Resource allocation
Program monitoring
Geographic targeting
Communication with decision-makers
6. Regularly Update TB Data

The analytical workflow can be reused with future WHO TB datasets to maintain an updated epidemiological monitoring system.

🛠️ Tools & Technologies
Tool	Purpose
Python	Data analysis
Pandas	Data manipulation
NumPy	Numerical analysis
Matplotlib	Visualization
Seaborn	Statistical visualization
Jupyter Notebook	Analytical workflow
Power BI	Interactive dashboard
GitHub	Version control and portfolio
CSV	Data storage and exchange
     ↓
Power BI Dashboard
     ↓
Public Health Recommendations
