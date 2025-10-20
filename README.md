# Life Expectancy Prediction


### Poject Overview

This project predicts life expectancy using socio-economic and health indicators from the Life Expectancy dataset on Kaggle. After data cleaning, imputation, and feature selection, multiple models were tested. The Random Forest Regressor achieved the best performance (R² = 0.96, RMSE = 1.84). 

Future improvements include hyperparameter tuning and using updated datasets for broader policy insights.


### Objectives

- Explore and understand the dataset through exploratory data analysis (EDA).
- Handle missing values using median and regression-based imputation techniques.
- Feature engineering.
- Develop and evaluate multiple machine learning models — Linear Regression, Random Forest Regressor, and Gradient Boosting Regressor.
- Compare model performance using R² score, RMSE, and MAE metrics.

### Data source

https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who

This dataset contains life expectancy data for various countries, along with economic, social, and health-related variables compiled by the World Health Organization (WHO).

### Tools

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

### Key Steps

1. Data Preprocessing: 

Impute missing values using median and regressio-based methods.
Remove irrelevant features and selected features with strong correlation to life expectancy.

2. Model Development:
   
Trained Linear Regression, Random Forest Regressor, and Gradient Boosting Regressor models using the cleaned dataset.
Selected top-performing model based on R², RMSE, and MAE scores.

3. Model Evaluation:
   
Linear Regression: R² = 0.82, RMSE = 4.08, MAE = 3.01
Random Forest Regressor: R² = 0.96, RMSE = 1.84, MAE = 1.14
Gradient Boosting Regressor: R² = 0.95, RMSE = 2.11, MAE = 1.47


### Conclusion

The Random Forest Regressor delivered the best performance, achieving an R² of 0.96, demonstrating strong predictive accuracy. The results indicate that socio-economic and health-related factors, especially schooling, income composition, and adult mortality, significantly influence life expectancy.

Future improvements could include hyperparameter tuning, cross-validation, and using updated datasets for enhanced generalization and policy analysis.


