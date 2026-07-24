# Walmart Weekly Sales Prediction: EDA & Linear Regression 

A Data Science project focused on predicting Walmart's weekly sales using Linear Regression, alongside statistical analysis using both `scikit-learn` and `statsmodels`.

##  Overview & Goals
**Objective:** Predict weekly sales across Walmart stores and identify key sales drivers.
**Key Tasks:** 
  * Exploratory Data Analysis (EDA) to find corelation with economic indicators(CPI, fuel price, etc.)
  * Feature engineering & preprocessing (one-hot encoding, scaling)
  * Implementation of Linear Regression via 'statsmodels' (for statistical summary, F-statistic, p-value) and 'scikit-learn' (for prediction and evaluation)

## Tech Stack & Tools
* **Language:** Python
* **Data Processing & EDA:** Pandas, Numpy, Matplotlib, Seaborn
* **Modeling:** Statsnodels, Scikit-learn

## Key Results
* **Model Performance:** Achieved R-squared score of **0.929** ('scikit-learn') and **0.961** ('statsmodels'). F-statistic is 2499 which is quite good. 
* **Key Insights:** Identified holiday weeks and store location as the strongest positive contributors to sales volume.

## How to run
1. Clone this repository
