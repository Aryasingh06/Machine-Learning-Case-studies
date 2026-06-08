# Newspaper Circulation Prediction Using Simple Linear Regression

## Project Overview
This project uses Simple Linear Regression (SLR) to analyze the relationship between Daily Newspaper Circulation 
and Sunday Newspaper Circulation. The objective is to determine whether daily circulation can be used to predict
Sunday circulation and to understand the strength of their relationship.

## Business Problem
Newspaper publishers need to estimate Sunday circulation for planning and resource allocation.
This project investigates whether daily circulation can serve as a reliable predictor of Sunday circulation.

## Dataset
The dataset contains newspaper circulation information with the following variables:
* Newspaper: Newspaper name
* Daily: Daily newspaper circulation
* Sunday: Sunday newspaper circulation

## Project Workflow
1. Data Loading and Exploration
2. Data Understanding using `info()` and `describe()`
3. Missing Value Analysis
4. Correlation Analysis
5. Data Visualization
6. Simple Linear Regression Model Building
7. Prediction and Evaluation
8. Statistical Significance Testing using OLS Regression
9. Business Insights and Conclusion

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels

## Model Performance
* R² Score: 0.798
* MAE: 89.09
* MSE: 9927.76
* RMSE: 99.64

## Key Findings
* Daily circulation and Sunday circulation have a strong positive relationship.
* The regression model explains approximately 79.8% of the variation in Sunday circulation.
* Statistical testing confirmed that Daily circulation is a significant predictor of Sunday circulation (p < 0.05).
* Newspapers with higher daily circulation generally have higher Sunday circulation.

## Business Insights
* Daily circulation can be used as an indicator of expected Sunday demand.
* Publishers can leverage daily circulation trends for circulation planning and forecasting.
* The strong relationship between the variables suggests that weekday readership patterns influence Sunday readership.

## Conclusion
This project successfully applied Simple Linear Regression to predict Sunday newspaper circulation from Daily 
circulation data. The model demonstrated strong predictive capability and statistical significance, indicating 
that Daily circulation is a reliable predictor of Sunday circulation. The findings highlight how regression analysis
can be used to support forecasting and data-driven decision-making in the newspaper industry.
