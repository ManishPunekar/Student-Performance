# **🎓 Student Performance Prediction using Machine Learning**
## **📌 Project Overview**

This project builds an end-to-end Machine Learning pipeline to analyze and predict student academic performance using a large-scale dataset.
The problem is approached in two parts:

**Regression Task:** Predicting total marks

**Classification Task:** Predicting student grade

The project focuses on classical machine learning algorithms and emphasizes interpretability, evaluation, and fundamental ML concepts rather than deep learning.


## **📊 Dataset Information**

**Source:** Kaggle – Student Performance Dataset

**Type:** Structured tabular data

**Size:** Large-scale dataset (hundreds of thousands to 1M+ records)

### **Target Variables**

  - Total Marks → Regression

  - Grade → Classification

### **Features Include**

- Weekly Study hours

- Attendance

- Class Participation

- Total Score

- student_id

## **🎯 Problem Statement**

To develop machine learning models that:

- Predict a student’s total marks using regression techniques

- Predict a student’s grade using classification techniques

and to analyze the factors that most influence student academic outcomes.

## **🧠 Machine Learning Concepts Covered**

- Exploratory Data Analysis (EDA)

- Data cleaning and preprocessing

- Feature scaling and normalization

- Feature engineering

- Train–test split and cross-validation

- Regression and classification modeling

- Bias–variance tradeoff

- Overfitting and regularization

- Model evaluation and comparison

- Model interpretability and feature importance

## **🤖 Models Used**
### **🔹 Regression (Total Marks Prediction)**

- Linear Regression

### **🔹 Classification (Grade Prediction)**

- Logistic Regression

- Decision Tree Classifier

- Random Forest Classifier

- Gradient Boosting Classifier

- XGBoost Classifier

## **📈 Evaluation Metrics**
### **🔹 Regression Metrics**

- Mean Squared Error (MSE)

- Root Mean Squared Error (RMSE)

- R² Score

### **🔹 Classification Metrics**

- Accuracy

- Precision

- Recall

- F1-Score

- Confusion Matrix

- Cross-validation was applied to ensure robust and generalized model performance.

## **🛠️ Tech Stack**

### **1.Language:** 

- Python

### **2.Libraries:**

- NumPy

- Pandas

- Matplotlib

- Seaborn

- scikit-learn

## **🔍 Key Insights**

- Study consistency and prior academic performance strongly influence total marks.

- Logistic Regression provides a strong baseline for grade prediction.

- Tree-based models capture non-linear relationships and improve classification performance.

- Feature importance analysis helps explain model decisions.

## **🚀 Future Enhancements**

- Model deployment using a lightweight web interface
