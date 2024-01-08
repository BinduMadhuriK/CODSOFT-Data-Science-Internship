# Movie Rating Prediction with Python

## Overview
- Develop a predictive model: In this project, we are going to use machine learning models to predict IMDB ratings of any particular movie based on the provided dataset.
- This is essentially a regression problem, where we aim to estimate the numerical movie ratings based on various features.
- Identify influential factors: Analyze the dataset to determine which factors (e.g., genre, director, actors) have the most significant impact on movie ratings.
- Provide actionable insights: Offer insights to the film industry stakeholders to make informed decisions about movie production, casting, and marketing.

## Project Details
- Objective: Movie Rating Prediction with Python
- Model Used: Linear Regression, Random Forest, Decision Tree Regression, Extended Gradient Boosting, Gradient Boosting, Support Vector Regression, K Nearest Neighbors from Scikit-learn.
- Best Model: Random Forest
- R-squared score achieved: 93.5%
- Mean Squared Error (MSE): 0.12

## Key Insights
- Data cleaning was essential, involving the correction of typos and handling missing/duplicated values.
- Explored the temporal dimension of the data, noting the first entry in 1931 and a movie with just 45 minutes of duration.
- Amitabh Bachchan is the most frequently appearing lead actor
- Identified both the best and worst-performing movies in terms of votes and ratings.
- Insights on directors with the most and least movies were gained.
- The distribution of movies over the years is skewed, with a concentration in the 2015-2019 period.
- In 2010, some movies had the highest average votes.
- Short-duration movies tend to receive higher ratings and votes, indicating a potential preference for shorter films.
- Drama is a consistently popular genre, while Comedy and Action genres had their origins in 1953 and 1964, respectively.
- The distribution of ratings and votes follows Gaussian-like patterns, with specific peaks and trends over time.
- Furthermore, the evaluation of machine learning models revealed that Random Forest outperformed other Regression models, with an impressive R-squared score of 93.5% and lowest Mean Squared Error (MSE) of 0.12 on unseen data, highlighting the model's robustness. Followed by XGBoost model with R-squared score of 91.4% and Mean Squared Error (MSE) of 0.16, and then Decision Tree Regression model with R-squared score of 90.7% and Mean Squared Error (MSE) of 0.17.
- Throughout the analysis, I gained a deep understanding of the dataset and its trends. This knowledge can be leveraged to make informed decisions regarding movie production, genres, and more. Future work could involve building more advanced machine learning models or diving deeper into specific genres or time periods to uncover additional insights.
