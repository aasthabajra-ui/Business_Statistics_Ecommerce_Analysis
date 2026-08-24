# business_statistics_ecommerce_analysis
Statistical analysis of factors influencing e-commerce customer expenditure using R.

# E-commerce Customer Expenditure Analysis

## Overview

This project was completed as part of my Master's in Business Analytics for the Business Statistics Using R module.

The analysis investigates factors influencing customer expenditure in an e-commerce environment, focusing on understanding spending behaviour through statistical analysis and regression modelling.

## Objectives

The main objectives were to:

- Explore customer purchasing behaviour
- Perform data cleaning and quality checks
- Identify relationships between customer and transaction variables
- Test statistical hypotheses
- Build and compare regression models
- Identify significant predictors of customer expenditure

## Dataset

The dataset contains information about e-commerce customer transactions, including:

- Total expenditure
- Unit price
- Quantity purchased
- Discount amount
- Customer age
- Session duration
- Product category
- Payment method
- Device type
- Returning customer status

## Analysis

The project included:

- Data cleaning and preparation
- Missing value and duplicate checks
- Outlier detection using the IQR method
- Exploratory data analysis
- Descriptive statistics
- Univariate and bivariate analysis
- Correlation analysis
- Hypothesis testing
- Simple and multiple linear regression
- Regression diagnostics
- Log transformation
- Customer retention analysis

## Key Findings

- Order quantity was identified as one of the strongest predictors of total expenditure.
- Unit price, discount amount, and product category were also significant predictors of spending.
- Customer age did not show a meaningful relationship with expenditure.
- Returning and new customers did not show a statistically significant difference in spending per order.
- A log-transformed regression model provided a better fit to the regression assumptions.

## Tools Used

- R
- RStudio
- tidyverse
- ggplot2
- car
- corrplot
- broom
- knitr

## Files

- `business-statistics-ecommerce-analysis.Rmd` — Main R Markdown analysis
- `business-statistics-ecommerce-analysis-report.pdf` — Final report 

## What I Learned

This project helped me become more comfortable using R for statistical analysis and, more importantly, interpreting statistical results in a business context.

Rather than only looking at whether a model worked, I learned to question the assumptions behind the model and consider what the results could actually mean for a business.
