# Sales Prediction

## Overview
- The dataset has advertising data sales (in thousands of units) for a particular product advertising budgets (in thousands of dollars) for TV, radio, and newspaper media.
- On the basis of this data, we need to suggest a marketing plan for future sales that will result in high product sales.
- We have to create various regression models with a focus on robust performance
- Utilized the best regression model by using the advertising dataset given in the task and analysed the predicted sales based on the given advertising expenditures 
- Implemented the project using Python with Pandas, NumPy, Scikit-learn, and Seaborn for analysis and model development.

## Project Details
- Objective: Predicting sales based on the given advertising expenditures
- Model Used: KNN Regression, Decision Tree Regression, ElasticNet Regression, Lasso Regression, Linear Regression, Ridge Regression, XGBoost Regression, Random Forest Regression and Gradient Boosting from Scikit-learn
- Best Model: Gradient Boosting Regression
- Accuracy Achieved: 96%
- MSE achieved:  1.245

## Key Features
- Analyzed the Sales Prediction Dataset, navigated through data visualization, preprocessing, and machine learning model selection.
- The characteristics of the dataset, including the nature of relationships and noise, influence model performance. 
- Observed outliers in the Newspapers category, while the other categories have no outliers. 
- Among the models evaluated, Gradient Boosting Regression model performed the best with around 96% accuracy and lowest Mean Squared Error (MSE) of 1.245, followed by Random Forest Regression model with 95% accuracy and Mean Squared Error (MSE) of 1.496 and XGBoost Regression model with 93.9% accuracy and Mean Squared Error (MSE) of 1.880.
- Saved the output file with Gradient Boosting Regression model's sales predictions for deployment
