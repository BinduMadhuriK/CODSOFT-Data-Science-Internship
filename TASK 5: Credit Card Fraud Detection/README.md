# Credit Card Fraud Detection

## Overview
- Developed a Fraudulent transactions detection system to prevent customers from being charged for unauthorized purchases using machine learning on credit card transaction data.
- Data is highly imbalanced, so it needs to be undersampling or oversampling technique. 
- Implemented the project using Python with Pandas, NumPy, Scikit-learn, and Seaborn for analysis and model development.
- Utilized Logistic Regression Model and Random Forest Classifier and achieved more than 94% accuracy on test data for both the models
- Both models (Logistic Regression and Random Forest Classifier) performed exceptionally well, but Random Forest Classifier have achieved high F1-score when compared to Logistic Regression model which makes it the best model.
- Performed both logistic regression and and Random Forest Classifier using scikit-learn, made predictions on a test set, and plotted the confusion matrix for evaluation.
- Evaluate the model's performance using metrics like precision, recall, and F1-score.
- Plotted ROC-AUC curve and Precision-Recall curve to decide the proper threshold values and to explain the model's goodness of fit.

## Project Details
- Objective: Credit Card Fraud Detection using Machine Learning techniques.
- Model Used: Logistic Regression and Random Forest Classifier from Scikit-learn.
- Accuracy Achieved for both models: >94%.
- F1 score for Random Forest Classifier: 95%
- F1 score for Logistic Regression model: 94%

## Key Features
- Utilized Logistic Regression and Random Forest Classifier to predict fraudulent transactions based on transaction features.
- Focused on minimizing false positives and ensuring model interpretability.
- Data is highly imbalanced, so it needs to be undersampling or oversampling technique. I choose to do UnderSampling technique to balance the data.
- The models show balanced performance in correctly identifying instances of both classes (0 and 1), as indicated by the similarity in f1 score and recall values.
- Precision for both classes are also high, suggesting a good balance between and recall. But Precision for Random Forest Classifier is more than compared to Precision of Logistic Regression.
- [Link of the dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)(as dataset was too big to upload) 
