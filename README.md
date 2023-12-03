# Helsinki Energy Consumption Analysis

This project focuses on analyzing energy consumption data of Helsinki using Python, leveraging various libraries such as pandas, numpy, seaborn, plotly, and others. The analysis includes fetching data from the Helsinki OpenAPI, cleaning and preprocessing the data, performing exploratory data analysis (EDA), and conducting statistical tests for further insights.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Code Explanation](#code-explanation)
3. [Results](#results)
4. [Acknowledgments](#acknowledgments)

## Prerequisites

Ensure you have the necessary dependencies installed. You can install them using the following command:

```bash
pip install requests pandas numpy matplotlib seaborn plotly
```

Additionally, you may need to install Jupyter Notebook if you plan to execute the code in a notebook

```bash
pip install jupyter
```
## Code Explanation

The code is structured into sections, each addressing a specific aspect of the energy consumption analysis:

- Data fetching from the Helsinki OpenAPI
- Preprocessing and cleaning of property information
- Fetching hourly electricity data for each property
- Merging and cleaning the data for further analysis
- Exploratory data analysis, including visualizations and statistical tests

## Results

The analysis generates various visualizations, including:

- Total Yearly Consumption for Each Location
- Top 20 Locations by Consumption
- Year-wise Top 20 Locations by Consumption
- Month-wise Consumption for Each Year
- Top Building Types by Average Consumption
- Consumption Heatmap by Day and Hour

Statistical tests are also conducted to analyze:

- Difference in consumption between weekdays and weekends
- Difference in consumption among different building types

## Acknowledgments

The project utilizes data from the Helsinki OpenAPI. Various Python libraries are used for data analysis and visualization.
