# Viz-and-Lasso-Regression-for-Total-Volumes-of-Reports
# Data Analysis and Visualization of Automotive Volumes and Macroeconomic Indicators

This repository contains R scripts and code for analyzing and visualizing automotive volumes, macroeconomic indicators, and the impact of Google AdWords spending on ad revenue. The analysis includes line charts, treemaps, correlation matrices, and a LASSO regression model.

## Project Overview

This project aims to:

- Analyze the trends in automotive volumes over the years.
- Visualize the relationships between different macroeconomic indicators and automotive volumes.
- Explore the impact of Google AdWords spending on ad revenue.
- Investigate the trends in different lease types.
- Apply LASSO regression to predict total automotive volumes based on various predictors.

## Data

The data used in this analysis is from a CSV file named `Comprehensive data for Volumes regression.csv`. This file includes data on automotive volumes, macroeconomic indicators, lease types, and more.

## Key Visualizations

- **Line Charts**: Visualize trends in total volume, insurance volumes, new registration, and other key metrics over time.
- **Macroeconomic Indicators**: Compare GDP, interest rates, and inflation rates over time.
- **AdWords vs. Ad Revenue**: Analyze the relationship between Google AdWords spending and ad revenue.
- **Lease Type Trends**: Visualize the trends in different types of leases over time.
- **Treemap**: Show the square root-transformed average values of different lease types.
- **Correlation Matrix**: Analyze the correlations between selected variables.
- **LASSO Regression**: Perform LASSO regression to predict total volumes and identify the most significant predictors.

## Dependencies

This project requires the following R packages:

- `readr`
- `readxl`
- `dplyr`
- `ggplot2`
- `GGally`
- `car`
- `MASS`
- `glmnet`
- `plotly`
- `corrplot`
- `ggcorrplot`
- `caret`
- `reshape2`
- `knitr`
- `treemapify`
- `data.table`
- `treemap`

You can install the necessary packages using the command:

```R
install.packages(c("readr", "readxl", "dplyr", "ggplot2", "GGally", "car", "MASS", "glmnet", "plotly", "corrplot", "ggcorrplot", "caret", "reshape2", "knitr", "treemapify", "data.table", "treemap"))
