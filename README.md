# Agribusiness Data Analysis Internship

This repository contains my work and reports for the Agribusiness Data Analysis Internship. The project focuses on collecting, cleaning, exploring, and interpreting agricultural data to identify useful patterns and support data-driven decision-making.

## Week 1: Agribusiness Data Analysis Planning

The Week 1 task focused on creating a structured plan for collecting and analyzing publicly available agricultural data.

The report covers:

- Research rationale and objectives
- Public agricultural data sources
- Key agricultural metrics, including crop yield, agricultural prices, and resource utilization
- Data collection process
- Data cleaning process
- Data analysis and interpretation
- Five-week project timeline
- Expected outcomes

### Potential Data Sources

- Open Government Data Platform India
- Directorate of Economics and Statistics
- Agriculture Census
- Food and Agriculture Organization (FAO)
- World Bank Open Data

## Week 2: Data Cleaning and Preprocessing Strategy

The Week 2 task focused on assessing and preparing the FAOSTAT Producer Prices dataset for India.

### Dataset Overview

- **Source:** FAOSTAT
- **Dataset:** Producer Prices
- **Records:** 5,035
- **Columns:** 16
- **Geographic coverage:** India
- **Year range:** 1991–2025
- **Agricultural commodities:** 104

### Work Completed

- Examined the dataset structure and data types.
- Identified and assessed missing values.
- Checked for duplicate records and inconsistencies.
- Standardised column names and removed unnecessary whitespace.
- Validated relevant numeric columns.
- Investigated measurement units and missing values.
- Examined wheat producer-price records.
- Distinguished absolute producer prices from producer price index values.
- Prepared and validated a cleaned dataset for further analysis.

### Key Findings

- The dataset contained 5,035 records and 16 columns.
- A total of 3,640 missing values were identified in the `Unit` column, representing 72.29% of records.
- These missing unit values were associated with Producer Price Index records, for which a currency-per-tonne unit is not applicable.
- No exact duplicate records were found.
- The cleaning process preserved the original dataset dimensions and retained meaningful missing values.

### Tools and Technologies

- Python
- Pandas
- Google Colab
- FAOSTAT

## Week 3: Exploratory Data Analysis (EDA)

The Week 3 task focused on designing an Exploratory Data Analysis report to investigate agricultural producer-price patterns and identify insights relevant to agribusiness decision-making.

### Objectives

- Summarise the distribution and statistical characteristics of agricultural price data.
- Examine historical trends in producer prices and price indices.
- Compare agricultural commodities using consistent measurement types.
- Identify potential statistical outliers for further investigation.
- Explore correlations between years and reported values.
- Develop an organised EDA report structure with findings, limitations, and recommendations.

### Work Completed

- Generated descriptive statistics, including mean, median, standard deviation, minimum, and maximum.
- Analysed missing values and reviewed dataset quality.
- Created histograms to examine value distributions.
- Generated line charts to visualise historical trends.
- Created bar charts to compare selected agricultural commodities.
- Applied the Interquartile Range (IQR) method to identify potential outliers.
- Examined correlations between years and reported values.
- Conducted a focused analysis of wheat producer prices.
- Exported summary tables and potential-outlier records.
- Prepared an EDA report design covering methodology, analysis, business implications, limitations, and recommendations.

### Preliminary Findings

- The exported descriptive-statistics summary contained 465 observations for each of the three producer-price measures and 3,640 observations for the Producer Price Index.
- The Producer Price Index had a reported mean of 72.27 and median of 60.15.
- The missing `Unit` values remained meaningful for index observations and should not be filled with currency units.
- Potential outliers were identified for investigation rather than automatic removal.
- Annual price data can reveal long-term trends, but it cannot independently establish monthly seasonality or the causes of price movements.

### Visualisation Techniques

| Technique | Purpose |
|---|---|
| Histograms | Examine distributions of reported values |
| Line charts | Explore historical price trends |
| Bar charts | Compare commodities within a measurement type |
| Correlation tables and heatmaps | Examine relationships between numeric variables |
| Missing-value charts | Identify incomplete fields |
| IQR-based outlier analysis | Flag unusual observations for review |

### Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- FAOSTAT

### Week 3 Deliverables

- EDA summary tables in CSV format
- Annual and commodity summary datasets
- Correlation summary
- Potential-outlier report
- Data visualisations
- EDA report outline and report document

## Project Goals

The overall goal of this internship project is to develop practical experience in working with real-world agricultural data, identifying data-quality issues, and preparing reliable datasets for analysis.

The project also aims to develop skills in exploratory data analysis, statistical interpretation, data visualisation, and identifying agricultural price trends that may support data-driven decision-making.

## Future Scope

Potential extensions of the project include:

- Analysing state-level and district-level agricultural market prices.
- Investigating seasonal trends using monthly market-price data.
- Comparing agricultural prices with production volumes and market arrivals.
- Exploring relationships between agricultural prices, weather conditions, and input costs.
- Developing predictive models after establishing suitable data coverage and validating the underlying assumptions.

## Repository Structure

The repository may be organised as follows as additional work is added:

```text
agribusiness-data-analysis-internship/
├── README.md
├── week1/
│   └── week1_report.docx
├── week2/
│   ├── week2_report.docx
│   ├── internship.ipynb
│   └── FAOSTAT_cleaned.csv
└── week3/
    ├── week3_eda.ipynb
    ├── week3_eda_report.docx
    └── outputs/
        ├── descriptive_statistics.csv
        ├── annual_summary.csv
        ├── commodity_summary.csv
        ├── correlation_summary.csv
        ├── potential_outliers.csv
        └── charts/
```

*Note: The structure above is a suggested organisation. File names and folders should be adjusted to match the actual files committed to the repository.*

## Author

**Ankit Sen**

GitHub: [ankitXdev](https://github.com/ankitXdev)
