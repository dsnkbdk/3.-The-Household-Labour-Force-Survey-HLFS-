# Household Labour Force Survey (HLFS) Analysis

## Overview

This project involves the analysis of employment data in New Zealand's utility sector, specifically focusing on the `Electricity, Gas, Water and Waste Services` industry. The analysis is performed using various time series techniques to explore data features, build forecasting models, and analyze results.

## Key Features

- **Time Series Analysis**: Comprehensive analysis of employment data using advanced time series techniques.
- **Data Decomposition**: Utilizes X-13ARIMA-SEATS decomposition to check for seasonality.
- **Forecasting Models**: Implements ETS and ARIMA models for accurate forecasting.

## Technologies Used

- **R Programming Language**: The analysis is conducted using R, a powerful language for statistical computing and graphics.
- **Libraries**:
  - `fpp3`: Functions for time series analysis and forecasting.
  - `seasonal`: Tools for seasonal adjustment and decomposition of time series data.
  - `tidyverse`: A collection of R packages for data manipulation, visualization, and analysis.
  - `kableExtra`: Customization of tables in RMarkdown documents.

## Workflow

1. **Data Reading and Preparation**: 
   - Read employment data from CSV.
   - Process data into a time series object (`tsibble`).

2. **Visualization**: 
   - Create initial visualizations to understand data trends and patterns.

3. **Seasonality Check**: 
   - Decompose the time series to check for seasonality using X-13ARIMA-SEATS.

4. **Model Building and Comparison**: 
   - Explore and compare various candidate models (ETS and ARIMA) for performance on the training set.

5. **Result Analysis**: 
   - Analyze the forecasts from the chosen models and discuss the results.

## Conclusion

The project provides a detailed analysis of employment trends in the utility sector of New Zealand, utilizing robust statistical methods and powerful tools provided by R. The insights gained from this analysis can be valuable for understanding employment patterns and making informed decisions.
