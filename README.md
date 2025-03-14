# Breaking the Myth: A Data-Driven Perspective of Immigration’s Impact on Criminal Activity

## Motivation
Immigration is a key driver of demographic and economic change, yet its relationship with crime rates remains a topic of public debate and policy concern. While some argue that increased immigration contributes to higher crime rates, others suggest that immigrants are less likely to engage in criminal activity than native populations. 

The goal of this project is to analyze whether immigration levels correlate with crime rates on both a global scale (cross-country comparison) and a historical scale (single-country analysis over time). By leveraging statistical and machine learning techniques, this study aims to uncover patterns and test common assumptions regarding immigration and crime.

## Data Source
To conduct this study, publicly available data will be collected from reliable sources:

### Immigration Data:
- **World Bank**: Net migration rates, percentage of immigrants in the population ([Net migration | Data](https://data.worldbank.org/indicator/SM.POP.NETM))
- **Our World in Data**: Total number of immigrants and emigrants ([Migration, Refugees, and Asylum Seekers Data Explorer](https://ourworldindata.org/migration))
- **United Nations Department of Economic and Social Affairs**: International migrant stock as a percentage of the total population by sex and by region, country, or area of destination, 1990-2024 ([International Migrant Stock | Population Division](https://www.un.org/development/desa/pd/content/international-migrant-stock))
- **OECD Migration Data**: World Migration ([World Migration in Figures](https://www.oecd.org/els/mig/World-Migration-in-Figures.pdf))

### Crime Data:
- **United Nations Office on Drugs and Crime (UNODC)**: Country-level crime rates and crime types ([dataUNODC](https://dataunodc.un.org/))
- **World Crime Index Dataset**: Contains country-wise crime index data ([World Crime Index](https://www.numbeo.com/crime/))
- **FBI Uniform Crime Reports**: For U.S.-specific analysis ([Crime Data Explorer](https://crime-data-explorer.app.cloud.gov/))
- **Eurostat Crime Statistics**: For Europe ([Crime and Criminal Justice - Eurostat](https://ec.europa.eu/eurostat/web/crime))

### Additional Data for Enrichment:
- **Economic indicators**: GDP per capita, unemployment rates
- **Global Country Information Dataset**: Contains economic conditions, geographical location, population size, gasoline price, land area, etc. ([Global Country Information Dataset 2023](https://www.kaggle.com/datasets/))

## Data Collection Plan
The dataset will be compiled in CSV format and preprocessed by:
- Handling missing values
- Normalizing immigration and crime data to account for population size
- Aligning timeframes for meaningful comparisons
- Standardizing crime categories across countries for consistency

## Data Analysis
The analysis will be conducted using Python with the following libraries:
- **Pandas**, **NumPy**: Data manipulation and processing
- **Matplotlib**, **Seaborn**: Data visualization
- **Scikit-learn**: Machine learning and statistical analysis

### Key Steps:
1. **Exploratory Data Analysis (EDA):**
   - Summary statistics of crime and immigration trends
   - Correlation heatmaps and scatter plots to visualize relationships
   - Country-wise ranking of crime rates and immigration percentages

2. **Hypothesis Testing:**
   - **Null Hypothesis (H₀):** Immigration levels do not have a significant impact on crime rates.
   - **Alternative Hypothesis (H₁):** There is a statistically significant relationship between immigration and crime rates.
   - Statistical tests including Pearson correlation, t-tests, and ANOVA will be applied.

## Findings
This project will aim to answer:
- Do countries with higher immigration levels experience higher crime rates?
- How does the relationship vary across different economic conditions?
- Does the crime rate in a specific country (e.g., Turkey) change as immigration levels fluctuate over time?

## Limitations and Future Work
- **Crime reporting accuracy** varies across countries, leading to potential biases.
- **Correlation does not imply causation**; external factors such as law enforcement policies must be considered.
- **Future research** could explore regional-level data within countries or consider specific crime categories (violent vs. non-violent).

## Conclusion
This project aims to provide data-driven insights into the relationship between immigration and crime, contributing to informed discussions on immigration policies and public safety strategies.
