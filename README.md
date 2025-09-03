# Project - Streaming Service Churn Prediction
A machine learning project that predicts user churn for a streaming platform using XGBoost and Random Forest models. Includes data preprocessing, model evaluation, and explainability with SHAP to uncover key drivers of churn — helping businesses improve user retention and revenue.

## Overview
This project focuses on predicting customer churn for a streaming service using machine learning techniques.  
Churn prediction enables the company to identify users at risk of leaving, allowing targeted retention strategies that improve customer loyalty and revenue.

---

## Dataset
The dataset simulates streaming user behavior and includes features such as:
- Subscription plan type
- Monthly fee and tenure
- Average daily watch time
- Preferred genre
- Days since last login
- Number of devices used
- Number of customer complaints
- Family plan and auto-pay indicators

---

## Approach
- Performed exploratory data analysis (EDA) and data preprocessing.
- Encoded categorical variables and scaled numerical features using `ColumnTransformer`.
- Built predictive models using:
  - Random Forest Classifier
  - XGBoost Classifier with hyperparameter tuning.
- Evaluated models with ROC AUC, precision, recall, and F1-score.
- Applied SHAP (SHapley Additive exPlanations) for model explainability to identify key churn drivers.

---

## Results
- XGBoost achieved an ROC AUC score of **~0.85** on the test set.
- Top features influencing churn predictions included:
  - Days since last login
  - Number of complaints
  - Average watch time per day
- SHAP visualizations provided actionable insights to guide marketing and customer success teams.

---

# Contact

- LinkedIn: [linkedin.com/in/anubhav-dogra](https://www.linkedin.com/in/anubhav-dogra/)
- Website: [My Portfolio](https://fuschia-yak-f61.notion.site/Anubhav-Dogra-211d6dc537bf8027bfe3ebdf322032ec)

