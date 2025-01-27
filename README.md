
# BoomBikes Demand Prediction

## Introduction
This project involves building a multiple linear regression model to predict the demand for shared bikes provided by BoomBikes, a US bike-sharing provider. The motivation for this analysis stems from the significant revenue dips the company experienced due to the COVID-19 pandemic, prompting a strategic plan to boost business post-lockdown.

## Problem Statement
BoomBikes aims to understand the demand for shared bikes as the nation recovers from the COVID-19 quarantine. Identifying the factors affecting bike demand is crucial for planning and executing business strategies that cater to emerging consumer needs, ensuring profitability and market competitiveness.

## Business Goal
The objective is to model bike demand using available independent variables, allowing the company's management to understand how demands vary with different features. This understanding will enable strategic manipulations to align supply with anticipated demand levels, optimizing customer satisfaction and business performance.

## Dataset Overview
The provided dataset includes daily records of bike rentals along with weather and seasonal information:
- `day.csv`: Contains detailed records including bike demand ('cnt'), weather conditions, and seasonal indicators.
- Variables include date, temperature, atemp (feels-like temperature), humidity, windspeed, casual users, registered users, and total count of bikes rented.

## Methodology
- Data Preprocessing: Convert categorical features with misleading numeric encoding to string values for accurate analysis.
- Model Building: Employ multiple linear regression to forecast bike demand based on a comprehensive set of features.
- Evaluation: Use R-squared score to measure the model's performance on the test dataset.

## Results
The analysis will provide insights into which variables significantly predict bike demand, aiding management in strategic decision-making.

## Technologies Used
- Python for data manipulation and analysis.
- Pandas, NumPy for data operations; Matplotlib, Seaborn for visualization; Scikit-learn for model building and evaluation.

## Files
1. `Linear_Regression_Assignment.ipynb`: Jupyter notebook containing the regression analysis and model evaluation.
2. `Data Dictionary.pdf`: Describes the dataset fields and their meanings.
3. `Linear Regression Assignment Q&A.pdf`: Contains answers to subjective questions related to linear regression.
