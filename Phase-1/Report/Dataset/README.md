Machine Learning Based Diabetes Risk Prediction System Using Clinical Data

 Team Details
Mukul Fartiyal (Team Lead) – 2028772
Anubhav Bisht – 2028650
Mehul – 2028765
Problem Statement

Diabetes is a serious health condition affecting millions worldwide. Early detection is important to prevent complications like heart disease, kidney failure, and vision loss.

This project aims to build a Machine Learning-based prediction system that can determine whether a person is diabetic or not using basic clinical data.

 Objective
Predict diabetes using patient health data
Assist in early diagnosis
Provide a simple binary output:
0 → Non-Diabetic
1 → Diabetic
 Dataset Information
Based on Pima Indians Diabetes Dataset
Total Records: 300 patients
Features: 8 input + 1 output
Key Features:
Glucose Level
Blood Pressure
BMI
Insulin
Age
Skin Thickness
Pregnancies
Target Variable:
Outcome (0 or 1)
Data Distribution:
Diabetic → 170 (56.7%)
Non-Diabetic → 130 (43.3%)
 Sample Data
Pregnancies	Glucose	BP	BMI	Outcome
2	120	70	28.5	1
1	95	60	24.1	0
 Project Workflow (Phase 1)

This project follows a structured ML pipeline:

1. Data Collection
Dataset loaded from CSV using Pandas
Initial exploration (shape, columns, preview)
2. Data Preprocessing
Missing values handled using median
Outliers removed using IQR
Data scaled using normalization/standardization
3. Feature Selection
Correlation analysis used
Important features identified:
Glucose
BMI
Age
4. Model Selection

Models used:

Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
5. Model Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
 Expected Output

The system predicts:

0 → Non-Diabetic
1 → Diabetic
 Libraries:
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
 Expected Visualizations
Heatmap (Feature correlation)
ROC Curve
Pair Plot
Confusion Matrix

