# 🚨 Los Angeles Crime Analysis: Data-Driven Insights for Urban Safety

## Executive Summary
This project investigates crime patterns in Los Angeles using LAPD data from January to November 2023. The goal is to uncover actionable insights in where—and what types—crimes occur, helping recommend strategies for public safety improvement.

## Key Results
- Street crimes are the most prevalent—nearly 1.5 times more frequent than single-family dwellings, and over double multi-family dwellings.
- Auto Theft (stolen vehicles) dominates street crimes by a large margin.
- Central LA is the most crime-heavy area, while Foothill is the least affected.
- Many cases remain unresolved: Most have the status "Investigation Continued" (32,000+ out of 37,000 cases).
- Victim gender and age show no strong trends—gender counts are similar; "age 0" victims likely indicate missing data, not infants.

## Methodology
- Cleaned and visualized LAPD open data (37,000 cases).
- Used Python (pandas, numpy, matplotlib, seaborn).
- Analyzed by location, premises, crime type, and status.
- Explored correlations with gender, age, and victim characteristics—no strong links found.
- Documented code and figures in Jupyter Notebook for reproducibility.

## Business Recommendations
- Increase patrols and visibility in Central LA and on major street zones.
- Target public awareness for auto theft prevention.
- Resource more investigators to close pending cases.
- Periodic audit of unresolved or "in progress" cases for trends.

## Limitations & Next Steps
- Data only covers 11 months (Jan–Nov 2023).
- Only reported crimes, no external variables or context.
- Large population of "Victim Age = 0" due to missing/unclear data.
- Recommend future work: incorporate socioeconomic, environmental, and event data for deeper predictive modeling.

## Analysis Files
The detailed analysis can be found in: `LA_Crime_Analysis_2023.ipynb`
