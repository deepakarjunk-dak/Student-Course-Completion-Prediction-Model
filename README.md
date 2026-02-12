# Student-Course-Completion-Prediction-Model
End-to-end Supervised ML pipeline for student course completion prediction with EDA, feature engineering, model comparison, and confusion-matrix driven evaluation.


## 🚀 Problem Statement  
Online Ed-Tech platforms face challenges in identifying students at risk of dropping out.
This project aims to predict course completion early so that proactive interventions can be implemented.

## 📊 Dataset Overview  

Target Variable:
0 → Not Completed
1 → Completed

Type: Binary Classification

Dataset includes student academic, course information, app activity information and demographic features.

## 🔎 Exploratory Data Analysis (EDA) 
Key observations:
Certain engagement-related features strongly influence completion.
Correlation analysis identified high-impact predictors.
Some features required scaling and missing value treatment.

## 🏗️ ML Pipeline 
Business Problem Understanding -> Data Collection -> Data Cleaning & Preprocessing -> Feature Engineering -> 
 Statistical Test -> Train-Test Split -> Model Training -> Model Comparison -> Threshold Tuning -> Model Evaluation.

## 🤖 Models Used 
Logistic Regression (Baseline Model & Best Performing Model),
K-Nearest Neighbour,
Gaussian Naive Bayes,
Decision Tree,
Random Forest,
AdaBoost Classifier,
XGBoost, 

## 📈 Evaluation Metrics 
Since this is an imbalanced classification problem, accuracy alone was not sufficient.
The following metrics were used:
Confusion Matrix,
Precision,
Recall,
F1-Score,
ROC-AUC.

## 🧮 Confusion Matrix Interpretation  
True Positives → Correctly predicted completed students;
True Negatives → Correctly predicted non-completed students;
False Positives → Incorrect completion prediction;
False Negatives → Missed at-risk students.

## 📌 Business Impact 
By maximizing recall, the model reduces the number of at-risk students that go undetected.
This can help institutions:
Identify dropout risks early
Provide academic counseling
Improve overall completion rate

## 🛠 Tech Stack 
Python, 
Pandas,
NumPy,
Matplotlib,
Seaborn.
