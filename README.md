# Cardiovascular-Disease-Prediction
Cardiovascular Disease Prediction Internship Project (Medical Electronics student) 
This project builds a machine learning pipeline to predict the likelihood of cardiovascular disease using patient health data.
The dataset includes key features such as age, blood pressure, cholesterol, physical activity, and more.

The project covers the full ML workflow:
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Training 5 ML Models
5. Comparing Model Accuracy
6. Patient-Level Predictions
7. Visualization of Risk Levels

Dataset Description

Dataset: cardio.csv
Rows: 70,000 patients
Features:
Feature	Description
id	Patient ID
age	Age in days (converted to years)
gender	1 = Female, 2 = Male
height	Height in cm
weight	Weight in kg
ap_hi	Systolic blood pressure
ap_lo	Diastolic blood pressure
cholesterol	1 = Normal, 2 = Above normal, 3 = High
gluc	Glucose level
smoke	Smoking habit (1/0)
alco	Alcohol intake (1/0)
active	Physical activity (1/0)
cardio	Target (1 = Disease, 0 = No Disease)


# Machine Learning Models Used

The trained and tested the following ML models:
1. Logistic Regression (LR)-- Linear baseline classifier
2. K-Nearest Neighbors (KNN)-- Distance-based classifier
3. Support Vector Machine (SVM)-- Optimal separating hyperplane
4. Decision Tree (DT)-- Rule-based model
5. Random Forest (RF)-- Ensemble of decision trees

# Model Performance Comparison:
A bar plot and accuracy table compare each model.
Model	Accuracy
1. SVM	0.73–0.75
2. Logistic Regression	0.72
3. Random Forest	0.72
4. KNN	0.69
5. Decision Tree	0.63

# Best Model Selected
SVM (Support Vector Machine) gave the highest accuracy.

This model was selected to: Predict patient risk levels, Generate probability scores, Visualize risk distribution

# Patient-Level Prediction
1. Predict for a single new patient
2. Predict for all patients in the dataset
3. Plot disease probability using bar charts
4. Label each patient as Disease or No Disease

Visualizations done in this Project:
1. Confusion matrices
2. Risk probability distribution
3. taken First 50 patients prediction graph
4. High-risk vs low-risk analysis
