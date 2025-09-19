# HIV and Child Mortality Analysis

Data science analysis of global HIV burden and child mortality patterns in East African Community countries using WHO and UN datasets (2000-2023).

## Project Overview

This analysis examines critical public health questions by analyzing:
- **Global HIV Burden**: Countries contributing to 75% of worldwide HIV cases
- **Child Mortality in East Africa**: Under-5 and neonatal mortality rates in EAC countries
- **Policy Implications**: Data-driven insights for healthcare interventions

## Repository Structure

```
├── data/
│   ├── HIV data 2000-2023.csv              # WHO HIV surveillance data
│   ├── dataset_datascience.csv             # UN child mortality data
│   └── multidimensional_poverty.xlsx       # World Bank poverty indicators
├── visualizations/
│   ├── hiv_global_burden.png               # Top 10 countries HIV burden
│   ├── hiv_trends.png                      # HIV trends (top 5 countries)
│   ├── child_mortality_comparison.png      # Latest EAC mortality rates
│   ├── mortality_trends.png                # Under-5 mortality trends
│   └── analysis_summary.png                # Key findings summary
├── reports/
│   └── analysis_report.md                  # Complete analysis report
└── README.md                               # Project documentation
```

## Key Findings

### HIV Analysis
- **14 countries** contribute to 75% of the global HIV burden
- **South Africa** leads with 51.4 million total cases (2000-2023)
- High burden concentration enables targeted prevention strategies

### Child Mortality Analysis
- **Somalia** has the highest under-5 mortality rate (162 per 1,000 births)
- **Significant disparities** exist across East African Community countries
- Regional trends show overall decline but persistent gaps

## Data Sources

- **WHO Global Observatory**: HIV surveillance data (1,084 observations across 144 countries)
- **UN Inter-agency Group for Child Mortality Estimation**: Child mortality data (2,536 observations)
- **World Bank**: Multidimensional poverty indicators
- **Coverage**: 2000-2023 analysis period

## Technical Approach

### Data Processing
- Custom parsing of formatted HIV values with confidence intervals
- Country name standardization for EAC countries
- Robust handling of missing data and inconsistencies

### Statistical Methods
- Burden analysis using cumulative proportion calculations
- Trend analysis and comparative statistics
- Regional aggregation and country-level insights

### Visualization
- Professional, publication-quality charts with consistent design
- Temporal trend analysis with regional averages
- Comparative visualizations highlighting key disparities

## Tools Used

- **R**: Primary analysis language
- **tidyverse**: Data manipulation and analysis
- **ggplot2**: Advanced data visualization
- **readr/readxl**: Data import capabilities

## Key Insights for Public Health Policy

### HIV Prevention Priorities
- Focus resources on 14 countries carrying 75% of global burden
- Prioritize interventions in sub-Saharan Africa
- Develop targeted regional strategies

### Child Health Interventions
- Somalia and South Sudan need urgent child health system strengthening
- Learn from successful strategies in lower-mortality countries
- Strengthen regional cooperation within East African Community

## Methodology

1. **Data Import**: Load WHO HIV and UN child mortality datasets
2. **Data Cleaning**: Parse formatted values, standardize country names, handle missing data
3. **Burden Analysis**: Calculate cumulative distributions to identify high-burden countries
4. **Trend Analysis**: Examine temporal patterns in HIV cases and mortality rates
5. **Visualization**: Create professional charts highlighting key findings
6. **Reporting**: Generate comprehensive analysis with policy implications

## Skills Demonstrated

- **Data Science Pipeline**: End-to-end analysis from raw data to insights
- **Statistical Analysis**: Burden calculations, trend analysis, descriptive statistics
- **Data Visualization**: Professional plots suitable for policy presentations
- **Domain Knowledge**: Understanding of public health data and policy implications
- **Technical Problem-Solving**: Custom solutions for real-world data challenges
- **Communication**: Clear reporting of complex analytical results

This project demonstrates applied data science skills in public health analytics, showcasing the ability to work with real-world international health datasets and generate policy-relevant insights.

---

*Analysis demonstrates proficiency in public health data science, from raw international datasets to actionable policy insights.*
