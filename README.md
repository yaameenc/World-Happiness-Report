# World Happiness Report - Multiple Regression and Exploratory Data Analysis

## Overview

This project performs a multiple regression analysis on the World Happiness Report dataset (2019) to understand the factors contributing to the happiness score of different countries. The analysis also includes various data visualization techniques to explore the relationships between variables and their distribution.

## Objective

The primary goal of this analysis is to determine the impact of six predictor variables (GDP per capita, social support, healthy life expectancy, freedom to make life choices, generosity, and perceptions of corruption) on the happiness score of each country. This information can help policymakers and researchers better understand the key factors contributing to a country's happiness and develop strategies to improve the well-being of citizens.

## Methodology

### Data Import

The dataset is imported from Kaggle and loaded into a pandas DataFrame for further processing and analysis.

### Multiple Regression

A multiple regression model is fitted using the six predictor variables and the happiness score as the dependent variable. The model's summary provides insights into the coefficients and statistical significance of each predictor.

### Data Visualization

Various plots are created to better understand the relationships between variables and their distribution, including:

- Coefficient plot: A bar plot showing the coefficients of the predictor variables from the multiple regression model.
- Residual plot: A scatter plot displaying the relationship between fitted values and residuals.
- Correlation matrix heatmap: A heatmap illustrating the Pearson correlation coefficients between each pair of variables.
- Pairplot: A scatterplot matrix showing the relationship between each pair of variables.
- Kernel density plots: Density plots displaying the distribution of each variable with an overlay of the skewness and kurtosis.
- Histograms: Bar plots showing the frequency distribution of each variable.
- Box plots: Plots representing the central tendency, dispersion, and skewness of each variable.


