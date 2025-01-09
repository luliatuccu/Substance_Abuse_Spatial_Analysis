# Substance Abuse and Mental Illness Across the United States

## Project Overview
This project analyzes the relationship between substance use and mental illness across the United States. Using data from the National Survey of Drug Use and Health (NSDUH), the study investigates opioid and marijuana use and their impact on mental health, identifying trends and regional patterns to uncover meaningful insights.

## Objectives
- Examine how opioid use impacts mental health disorders.
- Explore how marijuana use influences mental health across the U.S.
- Identify regions and states with the highest prevalence of substance use and mental health issues.
- Investigate spatial patterns and correlations of opioid misuse and mental illness.

## Data
- **Source:** National Survey of Drug Use and Health (NSDUH), 2021
- **Focus:** Adults aged 18 and older
- **Key Features:** Mental illness metrics, opioid use, marijuana use, demographic data
- **Visualization Techniques:**
  - Regression models
  - Spatial autocorrelation
  - Cluster analysis (e.g., LISA plots)

## Tools and Technologies
- **Language:** R
- **Libraries:** ggplot2, dplyr, sf, spdep, leaflet
- **Methods:** 
  - Statistical regression
  - Geographic Information Systems (GIS) analysis
  - Spatial data visualization

## Key Findings
1. **Opioid Use and Mental Health:**
   - Opioid use has a significant impact on mental health, more so than marijuana use.
   - States in the South, like Tennessee and Kentucky, exhibit the highest opioid misuse rates.

2. **Mental Illness Distribution:**
   - The Midwest has the highest rates of mental illness, with Nebraska and Oklahoma leading in serious mental health conditions.

3. **Regional Clusters:**
   - Clustering of high opioid misuse rates is evident in states like Tennessee, Mississippi, and Arkansas.
   - Spatial autocorrelation suggests neighboring states influence each other in terms of opioid misuse.

## Outcomes
- **Maps and Visuals:**
  - Heatmaps of opioid and marijuana use by state and region.
  - Spatial autocorrelation plots for clustering and outliers.
  - Regression models comparing mental illness rates to substance use.
- **Actionable Insights:**
  - Identified regions requiring targeted mental health resources and substance abuse interventions.

## Future Work
- Extend the analysis to county-level data for a more granular understanding.
- Include additional variables such as healthcare access, education levels, and socioeconomic factors.
- Examine trends over time to identify changes in substance use and mental health prevalence.

## References
- Substance Abuse and Mental Health Services Administration (SAMHSA), 2021
- National Institutes of Mental Health (NIMH)
- Various state-level resources on marijuana and opioid laws
