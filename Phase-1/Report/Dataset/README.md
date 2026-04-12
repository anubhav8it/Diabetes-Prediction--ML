# Diabetes Prediction System

## 📌 Project Overview
This project aims to predict whether a person is diabetic or not using Machine Learning techniques. The model is trained on clinical data such as glucose level, blood pressure, BMI, insulin, and age.

---

## 🎯 Objective
- To build a predictive model for diabetes detection  
- To analyze health-related parameters  
- To improve early diagnosis  

---

## ⚠️ Problem Description
Diabetes is a serious health condition affecting millions of people worldwide. If not detected early, it can lead to complications like heart disease, kidney failure, and vision loss.

This system uses machine learning to provide early prediction using basic clinical data, reducing dependency on costly medical tests.

---

## 📊 Dataset Information
- Dataset based on **Pima Indians Diabetes Dataset**
- Total Records: 300 patients  
- Features: 8 input features + 1 output (Outcome)

### Target Variable:
- `0` → Non-Diabetic  
- `1` → Diabetic  

### Class Distribution:
- Diabetic: 170 (56.7%)  
- Non-Diabetic: 130 (43.3%)  

---

## 🔍 Key Insights
- Glucose is the most important feature  
- BMI and Age also strongly affect prediction  
- Missing values (~5%) handled using median  
- Dataset is slightly imbalanced  

---

## ⚙️ Steps of Implementation

### 1. Data Collection
- Dataset loaded using Pandas  
- Initial analysis performed  

### 2. Data Preprocessing
- Missing values → Median Imputation  
- Outliers → IQR Method  
- Scaling → Standardization  

### 3. Feature Selection
- Correlation analysis used  
- Important features:
  - Glucose
  - BMI
  - Age  

### 4. Model Training
Models used:
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  

Split: 80% Training / 20% Testing  

---

## 📈 Model Evaluation Metrics

- **Accuracy** = Correct Predictions / Total Predictions  
- **Precision** = TP / (TP + FP)  
- **Recall** = TP / (TP + FN)  
- **F1 Score** = 2 × (Precision × Recall) / (Precision + Recall)  

### Confusion Matrix:
|               | Predicted Positive | Predicted Negative |
|--------------|------------------|------------------|
| Actual Positive | TP | FN |
| Actual Negative | FP | TN |

---

## 🤖 Prediction System
The system takes input values like glucose, BMI, and age and predicts:
- `0` → Non-Diabetic  
- `1` → Diabetic  

---

## 🛠️ Libraries Used
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📊 Visualization
- Heatmap  
- ROC Curve  
- Pair Plot  

---

## 💻 Platform
- Python  
- Jupyter Notebook  
- VS Code  

---

## 📚 References
- https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database  
- https://scikit-learn.org  
- https://pandas.pydata.org  

---

## ✅ Final Output
- `0` → Non-Diabetic  
- `1` → Diabetic  
