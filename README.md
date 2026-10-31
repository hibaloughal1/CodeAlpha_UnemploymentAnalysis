# Unemployment Analysis with Python

## Project Overview

This project analyzes unemployment trends in India using Python and data analysis techniques.

The main objective is to explore unemployment patterns across different regions and periods, investigate changes observed during the COVID-19 pandemic, and identify insights that may support economic and social policy discussions.

The project was developed as part of the **CodeAlpha Data Science Internship**.

## Project Objectives

- Explore and understand unemployment datasets.
- Clean and preprocess the available data.
- Analyze unemployment rates across regions.
- Compare rural and urban unemployment patterns.
- Investigate changes in unemployment during the COVID-19 period.
- Visualize temporal and geographical trends.
- Identify key findings and propose policy recommendations.

## Datasets

The project uses two CSV datasets:

1. `Unemployment in India.csv`
2. `Unemployment_Rate_upto_11_2020.csv`

The datasets contain information about:

- Region
- Date and frequency
- Estimated unemployment rate (%)
- Estimated employed population
- Estimated labour participation rate (%)
- Area or geographical classification

Both datasets were cleaned and exported for further analysis.

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
CodeAlpha_UnemploymentAnalysis/
│
├── data/
│   ├── Unemployment in India.csv
│   ├── Unemployment_Rate_upto_11_2020.csv
│   ├── unemployment_india_cleaned.csv
│   └── unemployment_upto_2020_cleaned.csv
│
├── notebooks/
│   ├── 01_unemployment_analysis.ipynb
│   └── 02_unemployment_impact_and_insights.ipynb
│
│
│
├── .gitignore
├── README.md
└── requirements.txt
```

## Analysis Workflow

### Notebook 1: Exploratory Data Analysis

`01_unemployment_analysis.ipynb`

- Dataset loading and inspection
- Missing values and duplicate handling
- Data cleaning and preprocessing
- Descriptive statistics
- Unemployment rate distribution
- Regional unemployment analysis
- Rural vs urban comparison
- Correlation analysis
- Monthly unemployment trends
- Regional heatmap visualization
- Key findings

### Notebook 2: COVID-19 Impact and Insights

`02_unemployment_impact_and_insights.ipynb`

- Temporal data preparation
- Pre-COVID and COVID-19 period classification
- Comparison of average unemployment rates
- Regional impact analysis
- Identification of the most affected regions
- Monthly unemployment trends during COVID-19
- Rural vs urban impact comparison
- Economic and social policy recommendations

## Key Findings

The exploratory and temporal analyses revealed several important observations:

- Average unemployment rates increased during the observed COVID-19 period in both datasets.
- Dataset 2 recorded its highest monthly average unemployment rate in May 2020, reaching **23.24%**.
- Puducherry recorded the largest regional increase in Dataset 1, with an absolute change of **37.36 percentage points**.
- Tamil Nadu and Jharkhand also experienced substantial increases.
- Both rural and urban areas experienced higher unemployment rates during the observed COVID-19 period.
- The monthly analysis showed a general decline in unemployment rates between June and October 2020 in Dataset 2.

## Important Limitations

- The datasets cover a relatively short period.
- Their temporal coverage and geographical structures differ.
- Average rates are calculated without population-based weighting.
- Missing regional observations may affect comparisons.
- The analysis is descriptive and does not establish causal relationships.
- The available time series is insufficient to establish reliable recurring seasonal patterns.

## Installation and Usage

Clone the repository:

```bash
git clone https://github.com/hibaloughal1/CodeAlpha_UnemploymentAnalysis.git
```

Navigate to the project directory:

```bash
cd CodeAlpha_UnemploymentAnalysis
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks in the `notebooks/` directory and execute the cells sequentially.

## Conclusion

This project demonstrates how Python-based data analysis can be used to explore unemployment trends, identify regional disparities, visualize changes over time, and develop data-driven insights.

The findings provide a descriptive overview of unemployment patterns in India during the period surrounding the COVID-19 pandemic.

---

**Project:** Unemployment Analysis with Python  
**Internship:** CodeAlpha Data Science Internship  
**Author:** Hiba Loughzal