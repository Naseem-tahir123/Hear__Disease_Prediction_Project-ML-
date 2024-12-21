# Heart Disease Prediction Project

This project aims to predict whether a patient has heart disease based on various medical attributes. The dataset used contains information such as age, sex, chest pain type, cholesterol levels, and more. The model evaluates whether a patient has heart disease based on these features.

## Problem Definition

The task is to predict if a patient has heart disease or not based on provided features.

## Data

The dataset contains the following features:

- **Age**: Age of the patient.
- **Sex**: Sex of the patient (1 = male, 0 = female).
- **Chest Pain Type**: Type of chest pain.
- **Resting Blood Pressure**: Resting blood pressure of the patient.
- **Cholesterol**: Serum cholesterol in mg/dl.
- **Fasting Blood Sugar**: Whether fasting blood sugar > 120 mg/dl (1 = true, 0 = false).
- **Resting Electrocardiographic Results**: Electrocardiographic results.
- **Maximum Heart Rate**: Maximum heart rate achieved during exercise.
- **Exercise Induced Angina**: Whether the patient experienced exercise-induced angina (1 = yes, 0 = no).
- **Oldpeak**: ST depression induced by exercise relative to rest.
- **Slope**: The slope of the peak exercise ST segment.
- **Number of Major Vessels**: Number of major vessels colored by fluoroscopy.
- **Thalassemia**: Blood disorder (1 = normal, 2 = fixed defect, 3 = reversible defect).
- **Target**: Whether the patient has heart disease (1 = disease, 0 = no disease).

## Models Used

- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- Logistic Regression

## Tools

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Accuracy

The models were evaluated and their accuracy was determined using cross-validation. The final model achieved an accuracy above 95%.
 
