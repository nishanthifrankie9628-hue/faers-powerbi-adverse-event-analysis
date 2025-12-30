# FAERS Adverse Event Analysis using Power BI

## Repository Description
End-to-end analysis of FDA FAERS adverse drug event data using Excel and Power BI, including data cleaning, DAX measures, interactive dashboards, and pharmacovigilance insights.

---

## Project Overview
This project analyzes real-world pharmacovigilance data from the FDA Adverse Event Reporting System (FAERS) to identify trends and patterns in adverse drug events.
The project demonstrates a complete analytics workflow from raw data cleaning to interactive Power BI dashboards.

A detailed project report containing screenshots, step-by-step explanations, and insights is included in this repository.

---

## Objectives
- Clean and preprocess raw FAERS data for analysis
- Handle missing, duplicate, and inconsistent values appropriately
- Build an analysis-ready dataset
- Create DAX measures for key metrics
- Develop interactive Power BI dashboards
- Generate descriptive, diagnostic, predictive, and prescriptive insights

---

## Dataset
- Source: FDA Adverse Event Reporting System (FAERS)
- Type: Public pharmacovigilance dataset
- Key Attributes:
  - Case and report identifiers
  - Drug information (primary suspect drugs, dosage, route)
  - Adverse events (Preferred Terms)
  - Patient demographics (age, gender, weight, age group)
  - Manufacturer / sender information
  - Event and report dates

---

## Tools & Technologies
- Microsoft Excel / Power Query – Data cleaning, transformation, and missing value handling
- Power BI Desktop – Data modeling, DAX calculations, and interactive dashboards

---

## Data Preparation Summary
- Removed duplicate case records to avoid double counting
- Standardized date fields by removing time components
- Expanded abbreviated age group values
- Retained only primary suspect drugs for accurate attribution
- Handled missing values logically instead of deleting records
- Filtered “Not Reported” values at the visualization level

---

## Data Modeling & DAX
Key DAX measures created:
- Total Reports
- Average Age
- Average Weight

Measures dynamically respond to filters and slicers for interactive analysis.

---

## Analysis & Visualizations
The Power BI dashboard includes:
- KPI cards (Total Reports, Average Age, Average Weight)
- Top primary suspect drugs
- Top reported adverse events
- Reports by age group
- Route of drug administration
- Adverse event trends over time
- Manufacturer-wise reporting analysis

---

## Key Insights
- Drugs such as XOLAIR, RISPERDAL, and XYREM show higher adverse event reporting
- TAKEDA appears as a leading manufacturer sender
- Adults and elderly populations account for most reported cases
- Oral and intravenous routes dominate administration patterns
- Adverse event reporting has increased significantly in recent years

---



