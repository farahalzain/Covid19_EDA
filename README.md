# COVID-19 Exploratory Data Analysis (EDA)

## Overview

This project performs an **Exploratory Data Analysis (EDA)** on the **World Health Organization (WHO)** COVID-19 dataset.
It explores global and regional COVID-19 cases, deaths, and trends using **Python, Pandas, Seaborn, and Plotly** for visualization.

The project highlights:

* Time series analysis (cases & deaths over time)
* Country and region-level comparisons
* Seasonal patterns and correlations
* Interactive maps and dashboards

---

## Dataset

* Source: [WHO COVID-19 Dashboard Data](https://data.who.int/dashboards/covid19/data)
* Data includes:

  * `Date_reported`: Date of reporting
  * `Country`: Country/territory name
  * `WHO_region`: WHO region code (e.g., AMRO, EURO, EMRO, etc.)
  * `New_cases`: New confirmed cases
  * `Cumulative_cases`: Total confirmed cases
  * `New_deaths`: New confirmed deaths
  * `Cumulative_deaths`: Total confirmed deaths

---

## How to Run

### Jupyter/Colab Notebook

1. Open **`Self_Covid19_EDA.ipynb`** in Jupyter Notebook or Google Colab.
2. Run all cells to:

   * Load WHO COVID-19 data
   * Perform cleaning & preprocessing
   * Visualize insights

-----

## Key Features

* Data cleaning (missing values, duplicates, date parsing)
* Time series analysis of COVID-19 cases & deaths
* Seasonal trends and regional comparisons
* Top-10 countries analysis (cases & deaths)
* Interactive maps (Plotly Choropleth)
* Dash app for interactive visualization

---

## Insights & Findings

* **Most new cases** were recorded in **winter months**, correlating with higher indoor activity and weaker immunity.
* **Deaths peaked in spring and summer**, following infection surges.
* **Europe and the Americas** were the most impacted regions.
* The **Western Pacific region** managed to reduce deaths despite high case counts, reflecting effective public health measures.

---

## Project Structure

```
covid19-eda/
│── Self_Covid19_EDA.ipynb   # Main analysis notebook
```

---

## Future Work

* Add machine learning models for forecasting cases.
* Automate daily data updates from WHO.
* Extend dashboard with user input filters.

---
