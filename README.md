# Heart_Failure_Prediction

Heart Failure Prediction using Machine Learning
A machine learning project that predicts the likelihood of heart disease using clinical and patient health records. The project includes comprehensive Exploratory Data Analysis (EDA), data preprocessing, feature engineering, and the implementation of multiple classification algorithms including KNN, Logistic Regression, Gaussian Naive Bayes, Decision Trees, Random Forest, SVM, and XGBoost to evaluate predictive performance.

README.md

#Heart Failure Prediction Using Machine Learning

Project Overview:
Cardiovascular diseases are among the leading causes of death worldwide. Early prediction of heart disease can help healthcare professionals take preventive actions and improve patient outcomes.
This project uses machine learning techniques to predict the presence of heart disease based on patient medical records. The workflow includes data preprocessing, exploratory data analysis, feature engineering, model training, and performance evaluation.

Dataset:
The dataset was obtained from Kaggle's Heart Failure Prediction dataset and contains patient health information such as:
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
Resting ECG
Maximum Heart Rate
Exercise-Induced Angina
Oldpeak
ST Slope

Target Variable:
HeartDisease (0 = No Heart Disease, 1 = Heart Disease)
Dataset Statistics
Total Records: 918
Total Features: 11
Target Variable: HeartDisease

Project Objectives:
Analyze patient health data using Exploratory Data Analysis (EDA).
Identify important factors contributing to heart disease.
Build predictive machine learning models.
Compare multiple classification algorithms.
Determine the most effective model for heart disease prediction.

Data Preprocessing:
The following preprocessing techniques were applied:
Missing value detection and handling
Feature scaling using MinMax Scaling
Label Encoding
One-Hot Encoding
Correlation Analysis
Feature Engineering

Exploratory Data Analysis:
Several visualizations were created to understand data patterns:
Correlation Heatmaps
Histograms
Pair Plots
Box Plots
Distribution Analysis
Feature Relationship Analysis

Machine Learning Models Implemented:

Non-Tree Based Models
Logistic Regression
Gaussian Naive Bayes
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)

Tree Based Models
Decision Tree (CART)
Random Forest
XGBoost

Model Performance:
Algorithm	Accuracy
K-Nearest Neighbors (KNN)	92.30%
Gaussian Naive Bayes	88.37%
Logistic Regression	88.00%
SVM	86.90%
Distance Based Model	84.79%
Decision Tree (CART)	76.13%

Technologies Used:
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Scikit-Learn
XGBoost
Jupyter Notebook

Project Workflow:
Data Collection
Data Cleaning
Exploratory Data Analysis
Feature Engineering
Data Encoding
Feature Scaling
Model Training
Model Evaluation
Performance Comparison
Prediction Analysis

Key Findings:
K-Nearest Neighbors achieved the highest prediction accuracy of approximately 92%.
Feature scaling significantly improved the performance of distance-based algorithms.
Age, Chest Pain Type, Maximum Heart Rate, and ST Slope showed strong relationships with heart disease prediction.
Ensemble and distance-based methods produced strong predictive performance.

Future Improvements:
Hyperparameter tuning
Deep Learning implementation
Model deployment using Flask or FastAPI
Real-time patient risk prediction dashboard
Integration with healthcare systems
