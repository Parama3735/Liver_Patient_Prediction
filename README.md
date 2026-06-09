# Liver Disease Prediction Using Machine Learning

## Project Overview

This project aims to predict whether a patient is suffering from liver disease using machine learning techniques. The model is trained on the Indian Liver Patient Dataset (ILPD), which contains various clinical and demographic attributes related to liver health. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and comparison of multiple classification algorithms.

## Problem Statement

Liver disease is a major health concern worldwide. Early detection can significantly improve treatment outcomes and reduce healthcare burdens. The objective of this project is to develop a machine learning model that can accurately classify patients as having liver disease or not based on medical test results and patient information.

## Dataset Information

* Dataset Name: Indian Liver Patient Dataset (ILPD)
* Total Records: 583
* Liver Disease Patients: 416
* Non-Liver Disease Patients: 167

### Features

* Age
* Gender
* Total Bilirubin
* Direct Bilirubin
* Alkaline Phosphotase
* Alamine Aminotransferase (ALT)
* Aspartate Aminotransferase (AST)
* Total Proteins
* Albumin
* Albumin and Globulin Ratio

### Target Variable

* 1 → Liver Disease Patient
* 2 → Non-Liver Disease Patient

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Feature Selection
6. Data Scaling
7. Handling Class Imbalance
8. Model Building
9. Hyperparameter Tuning
10. Model Evaluation
11. Model Comparison

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Imbalanced-Learn (SMOTE)

## Machine Learning Models

### Logistic Regression

A baseline classification model used for binary prediction and performance comparison.

### Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

### XGBoost Classifier

A gradient boosting algorithm known for high predictive performance and efficient handling of structured datasets.

## Evaluation Metrics

The following metrics were used to evaluate model performance:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score

## Feature Importance

Feature importance analysis identified the following attributes as major contributors to liver disease prediction:

* Total Bilirubin
* Direct Bilirubin
* Alkaline Phosphotase
* Aspartate Aminotransferase (AST)
* Alamine Aminotransferase (ALT)
* Albumin
* Albumin and Globulin Ratio

## Results

Multiple machine learning models were trained and compared. The best-performing model was selected based on Accuracy, Recall, F1-Score, and Cross-Validation performance.

## Business Impact

The developed predictive model can assist healthcare professionals in:

* Early detection of liver disease
* Faster clinical decision-making
* Reducing diagnostic workload
* Supporting preventive healthcare measures

## Future Improvements

* Deploy the model using Flask or Streamlit
* Integrate real-time patient data
* Improve performance using advanced ensemble techniques
* Develop a web-based healthcare prediction system

## Author

Parama

Engineering Student | Machine Learning & Data Science Enthusiast
