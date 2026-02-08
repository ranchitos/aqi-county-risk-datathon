# County-Level Air Quality Risk Analysis

## Decision Problem
Which U.S. counties should be prioritized for targeted air quality interventions given limited monitoring and mitigation resources?

## Dataset
EPA Air Quality Index (AQI) by County dataset.
Includes annual county-level counts of AQI categories and pollutant-specific exposure.

## Methodology
- Computed the percentage of days classified as:
  - Unhealthy for Sensitive Groups
  - Unhealthy
  - Very Unhealthy
  - Hazardous
- Created a composite **risk score** based on the frequency of unhealthy AQI days.
- Ranked counties by risk score to identify high-priority areas.
- Identified the **dominant pollutant** in high-risk counties using pollutant-specific day counts.

## Key Findings
- A small subset of counties accounts for the highest long-term air quality risk.
- Ozone dominates exposure in most high-risk counties.
- Risk is driven more by **frequency of unhealthy exposure** than isolated AQI peaks.

## Outputs
- Ranked list of counties by air quality risk
- Priority categories for intervention
- Pollutant-specific exposure profiles

## Tools
- Python
- Jupyter Notebook
- Canva

## Notes
This project was completed during the 7th DubsTech Datathon.
