# Global HIV Trends and Treatment Effectiveness Analysis

## Project Overview

This Power BI healthcare analytics project examines global HIV trends, treatment access and health outcomes across countries and regions.

The analysis focuses on new HIV infections, HIV-related deaths, people living with HIV, Antiretroviral Therapy (ART) coverage, mortality rates and regional disparities.

## Business Problem

Public health stakeholders require a unified analytical framework to evaluate HIV trends, measure the effectiveness of treatment programs and identify countries requiring urgent intervention.

Without a centralized reporting solution, it is difficult to understand the relationship between HIV infections, mortality and ART coverage or to allocate public health resources effectively.

## Project Objectives

- Analyze HIV infection trends over time.
- Measure global and regional HIV-related mortality.
- Evaluate ART treatment coverage.
- Identify countries with high HIV burden and low treatment access.
- Assess whether higher ART coverage is associated with lower mortality.
- Provide actionable public health recommendations.

## Business Questions

1. How have new HIV infections changed over time?
2. What is the total number of HIV-related deaths?
3. How many people are living with HIV?
4. What is the average ART coverage across countries?
5. Which regions have the highest HIV burden?
6. Which countries have the highest mortality rates?
7. Which countries record the most deaths per 1,000 new infections?
8. Does higher ART coverage correspond with lower mortality?
9. Which high-infection countries have inadequate ART coverage?
10. Which countries should be prioritized for intervention?

## Dataset

The dataset contains annual HIV indicators by country and region.

### Main Fields

- Country
- Region
- Region Code
- Year
- Indicator
- Value

### Indicators

- New HIV infections
- HIV-related deaths
- People living with HIV
- ART coverage percentage

## Tools Used

- Microsoft Excel
- Power Query
- Power BI
- DAX
- Data Modeling
- GitHub

## Data Model

The report uses a star schema containing:

- Fact_HIV
- Dim_Country
- Dim_Year
- Dim_Indicator

## Key Measures

- Total New Infections
- Total HIV Deaths
- People Living with HIV
- ART Coverage %
- Mortality Rate
- Survival Rate
- Deaths per 1,000 New Infections
- Year-over-Year Infection Growth

## Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of HIV infections, deaths, ART coverage, mortality and disease burden.

![Executive Overview](Images/Executive_Overview.png)

### 2. Treatment Effectiveness

Examines the relationship between ART coverage and mortality and identifies countries with limited treatment access.

![Treatment Effectiveness](Images/Treatment_Effectiveness.png)

### 3. Regional Analysis

Compares HIV indicators across regions and highlights high-risk countries.

![Regional Analysis](Images/Regional_Analysis.png)

### 4. Recommendations

Summarizes the principal findings and recommended public health actions.

![Recommendations](Images/Recommendations.png)

## Key Insights

- HIV burden differs substantially across countries and regions.
- ART coverage has improved, but access remains uneven.
- Some countries continue to experience high mortality relative to new infections.
- Countries with low ART coverage and high HIV burden require prioritized intervention.
- Monitoring treatment access alongside mortality provides better evidence for resource allocation.

## Recommendations

- Expand ART access in countries with low treatment coverage.
- Prioritize funding for high-burden and high-mortality regions.
- Strengthen HIV prevention, testing and awareness programs.
- Improve consistency in country-level health reporting.
- Use regularly updated dashboards to monitor intervention performance.

## Skills Demonstrated

- Data cleaning and transformation
- Star-schema data modeling
- DAX measure development
- KPI design
- Time-series analysis
- Geographic analysis
- Healthcare analytics
- Dashboard development
- Data storytelling
- Business recommendations

## Project Files

- `Data/HIV_dataset.xlsx`
- `Dashboard/Global_HIV_Dashboard.pbix`
- `Presentation/Global_HIV_Analysis_Presentation.pdf`
- `Documentation/Power_BI_Capstone_Project_Brief.pdf`

## Author

**Aderonke**  
Healthcare and Data Analytics Professional
