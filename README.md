# Sales Data Forecasting Analysis

## Overview

This repository contains an Excel file that analyzes the sales data of an outlet business and forecasts the next 12 months of sales. The analysis employs various forecasting techniques including linear regression, quadratic regression, and exponential regression.

## Contents

- **Outlets-1.xlsx**: Excel file containing the sales data and forecasting analysis.

## Forecasting Techniques

### Linear Regression

Linear regression is a statistical method used to model the relationship between a dependent variable (sales) and one or more independent variables (time). In this analysis, a linear regression model is fitted to the sales data to identify a linear trend.

### Quadratic Regression

Quadratic regression extends linear regression by introducing a squared term for the independent variable. It allows for capturing non-linear relationships between variables. In this analysis, a quadratic regression model is applied to capture any curvature in the sales trend.

### Exponential Regression

Exponential regression is used when the rate of change of the dependent variable (sales) is proportional to its current value. It is suitable for data exhibiting exponential growth or decay. In this analysis, an exponential regression model is utilized to forecast sales based on exponential trends.

### Additional Techniques

- **Dummy Variables**: Dummy variables are used to represent categorical data, such as special events or promotions that may impact sales. These variables are included in the regression models to account for their effects on sales.

- **Deseasonalizing**: Seasonal fluctuations in sales data can obscure underlying trends. Deseasonalizing involves removing seasonal components from the data to better identify long-term patterns. This technique may be applied before fitting regression models to the data.

- **Adjusting for Non-Relevant Dates**: Certain dates may have unusual sales patterns due to external events such as holidays, strikes, or inventory clearance sales. These dates can distort the analysis and should be adjusted for or excluded from the forecasting models.

## Usage

1. Open the `Outlets-1.xlsx` file in Microsoft Excel or any compatible spreadsheet software.
2. Review the existing sales data and analysis results.
3. Experiment with different forecasting techniques or adjust parameters as needed.
4. Use the forecasted sales figures for future planning and decision-making.

## Disclaimer

This analysis provides forecasts based on historical sales data and regression models. While efforts have been made to ensure accuracy, the actual sales figures may vary due to unforeseen factors or changes in market conditions.

## License

This repository is licensed under the HULT Business School License.
