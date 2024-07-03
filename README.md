# Predicting Health Insurance Charges

## Overview
This project is a Data Science and Machine Learning endeavor involving the transformation and analysis of historic health insurance data. The goal is to build, train, and evaluate models that predict insurance charges based on provided biodata.

## Dataset
The dataset used for this project is sourced from Kaggle. It includes the following features:
- Age: Age of the insured individual
- Sex: Gender of the insured (male/female)
- BMI: Body mass index of the insured
- Children: Number of children covered under the policy
- Smoker: Smoking status of the insured (yes/no)
- Claim_Amount: The insured amount
- Past_consultations: Number of health consultations
- Num_of_steps: Number of steps taken
- Hospital_expenditure: Amount spent on hospital bills
- Number_of_past_hospitalizations: Previous hospitalizations
- Annual_Salary: Annual salary earned
- Region: Region of the insured (northeast, northwest, southeast, southwest)

## EDA Tools
- Pandas
- Numpy
- Seaborn
- Matplotlib

## Data Preprocessing and Model Building Tools
- Scikit-learn
- XGBoost

## Models Used
- Linear Regression
- Random Forest
- XGBoost

## Metrics of Performance Evaluation
- R2 Score
- Mean Squared Error (MSE)
- Comparison of individual and ensemble models

## Model Selected
Ensemble of:
- Linear Regression: Basic model to establish a baseline prediction
- XGBoost (Extreme Gradient Boosting): Boosted tree algorithm known for its efficiency and accuracy in complex datasets
