# HIV and Child Mortality Analysis

A comprehensive data science project analyzing HIV trends globally and child mortality patterns in East African Community countries using real WHO and UN datasets.

## Project Overview

This analysis addresses critical public health questions by examining:
- **Global HIV Burden**: Countries contributing to 75% of worldwide HIV cases
- **Regional HIV Trends**: Patterns across WHO regions over time  
- **Child Mortality in East Africa**: Under-5 and neonatal mortality rates in EAC countries
- **Policy Implications**: Data-driven insights for healthcare interventions

## Key Findings

### HIV Analysis
- **14 countries** contribute to 75% of the global HIV burden
- **South Africa** leads with 51.4 million total cases (2000-2023)
- **African region** dominates the global burden with 9 of top 10 countries
- Clear temporal trends showing intervention impacts

### Child Mortality Analysis  
- **Somalia** has the highest under-5 mortality rate (162 per 1,000 births)
- **South Sudan** shows highest neonatal mortality (40.3 per 1,000 births)
- Significant variation across East African Community countries
- Overall declining trends but persistent disparities

## Data Sources

- **WHO Global Observatory**: HIV surveillance data (1,084 observations across 144 countries)
- **UN Inter-agency Group for Child Mortality Estimation**: Child mortality data (2,536 observations)
- **World Bank**: Multidimensional poverty indicators
- **Coverage**: 2000-2023 analysis period

## Technical Highlights

### Data Processing
- Custom parsing of formatted HIV values (e.g., "320 000 [280 000 - 380 000]")
- Smart country name matching for EAC countries including variations
- Robust handling of missing data and inconsistencies
- Advanced data cleaning and validation

### Statistical Methods
- Burden analysis with cumulative proportion calculations
- Trend analysis and visualization
- Descriptive statistics and comparative analysis
- Regional aggregation and country-level insights

### Visualization
- Professional publication-quality plots
- Temporal trend analysis with average lines
- Regional comparison visualizations
- Country ranking and burden distribution charts

## Repository Structure

```
├── data/                          # Processed datasets
│   ├── hiv_clean_fixed.csv       # Cleaned HIV data
│   ├── mortality_clean.csv       # Processed mortality data
│   └── ...                       # Additional processed files
├── plots/                         # All visualizations
│   ├── hiv_global_75_trend_fixed.png
│   ├── hiv_regional_trends_fixed.png
│   ├── under5_mortality_trends.png
│   ├── neonatal_mortality_trends.png
│   └── mortality_comparison.png
├── outputs/                       # Analysis reports
│   └── complete_analysis_report.md
├── HIV data 2000-2023.csv        # Original HIV dataset
├── dataset_datascience.csv       # Child mortality dataset
├── multidimensional_poverty.xlsx # World Bank poverty data
└── README.md                     # Project documentation
```

## Visualizations

### Global HIV Trends
- Countries contributing 75% of global HIV burden over time
- Regional breakdown showing African dominance
- Temporal patterns indicating intervention effects

### Child Mortality Analysis
- Under-5 mortality trends across East African Community
- Neonatal mortality patterns by country
- Comparative analysis of mortality indicators

### Key Charts Generated
1. **HIV Global Burden Trend**: Combined cases from top burden countries
2. **HIV Regional Trends**: WHO region comparison over time  
3. **Under-5 Mortality Trends**: EAC countries with regional average
4. **Neonatal Mortality Trends**: Country-specific patterns
5. **Mortality Comparison**: Side-by-side under-5 vs neonatal rates

## Technologies Used

- **R**: Primary analysis language
- **tidyverse**: Data manipulation and analysis
- **ggplot2**: Advanced data visualization
- **stringr**: Text processing for data cleaning
- **scales**: Professional plot formatting
- **readr/readxl**: Data import capabilities

## Methodology

1. **Data Import & Exploration**: Load and examine multiple datasets
2. **Data Cleaning**: Handle formatted values, missing data, and inconsistencies  
3. **Burden Analysis**: Calculate cumulative proportions for HIV burden
4. **Geographic Focus**: Filter and analyze East African Community countries
5. **Trend Analysis**: Time series analysis and visualization
6. **Reporting**: Comprehensive analysis with policy recommendations

## Key Insights for Public Health Policy

### HIV Prevention Priorities
- Focus resources on 14 countries carrying 75% of global burden
- South Africa, Mozambique, and Nigeria require immediate attention
- Regional approaches needed for sub-Saharan Africa

### Child Health Interventions
- Somalia and South Sudan need urgent child health system strengthening
- Neonatal care improvements critical across EAC region
- Significant progress possible based on observed trends

### Data-Driven Recommendations
1. **Targeted Resource Allocation**: Prioritize high-burden countries and regions
2. **Regional Cooperation**: Strengthen EAC health systems collaboration
3. **Integrated Approaches**: Link HIV prevention with poverty reduction
4. **Enhanced Monitoring**: Improve data collection and surveillance systems

## Technical Challenges Solved

- **Complex Data Parsing**: Successfully handled formatted HIV values with confidence intervals
- **Country Name Variations**: Implemented smart matching for geographic entities
- **Multi-source Integration**: Combined datasets from different international organizations
- **Missing Data Handling**: Robust processing of incomplete observations
- **Scale Differences**: Appropriate visualization of vastly different case numbers

## Skills Demonstrated

- **Data Science Pipeline**: End-to-end analysis from raw data to insights
- **Statistical Analysis**: Burden calculations, trend analysis, descriptive statistics
- **Data Visualization**: Professional plots suitable for policy presentations
- **Domain Knowledge**: Understanding of public health data and policy implications
- **Technical Problem-Solving**: Custom solutions for real-world data challenges
- **Communication**: Clear reporting of complex analytical results

## Future Enhancements

- Interactive dashboards using Shiny
- Integration with poverty indicators for correlation analysis
- Predictive modeling for trend forecasting
- Spatial analysis with geographic mapping
- Time series forecasting models

## Acknowledgments

- World Health Organization for HIV surveillance data
- UN Inter-agency Group for Child Mortality Estimation
- World Bank for multidimensional poverty indicators
- East African Community for regional cooperation framework

---

*This project demonstrates applied data science skills in public health analytics, showcasing the ability to work with real-world international health datasets and generate policy-relevant insights.*
