# Predict-Loan-Approval

Predicting loan approval refers to the process of using machine learning models to determine whether a loan application should be approved or rejected based on various features.

# Loan Approval Prediction

This project uses machine learning to predict whether a loan application will be approved or not. The dataset contains various attributes of loan applicants, and the goal is to build a model that can predict loan approval or rejection based on these features. The project leverages the *Random Forest Classifier* for prediction.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Libraries and Dependencies](#libraries-and-dependencies)
4. [Steps to Reproduce](#steps-to-reproduce)
5. [Model Evaluation](#model-evaluation)
6. [Feature Importance](#feature-importance)
7. [License](#license)

---

## Project Overview

The objective of this project is to predict loan approval using machine learning. The **Loan Approval Prediction** dataset includes features like applicant income, credit history, marital status, etc., that contribute to the loan approval decision. We perform the following steps:

1. *Data Preprocessing*: Handle missing values, encode categorical variables, and scale numerical features.
2. *Model Development*: Train a *Random Forest Classifier* to predict loan approval status.
3. *Model Evaluation*: Evaluate the model using metrics like accuracy, confusion matrix, and classification report.
4. *Feature Importance*: Visualize which features are most influential in the prediction process.

---

## Libraries and Dependencies

- Pandas: For data manipulation and preprocessing.
- Zipfile: For data reading
- Missingno: For NULL values visualization
- Seaborn & Matplotlib: For data visualization.
- Lazypredict: For the best model
- Scikit-Learn: For machine learning and model evaluation.
