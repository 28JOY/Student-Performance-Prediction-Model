# Student Performance and Stress Level Prediction 🎓📊

This **group project** was developed as part of our **Semester 6 coursework for the subject Data Mining and Analytics** 
during B.Tech in Computer Science and Business Systems.

## 📌 Project Overview

The goal of this project is to analyze various psychological and environmental factors affecting **student academic performance** and **stress levels**, 
using a combination of **regression** and **classification** techniques.

## 🧠 Key Objectives

- Predict **academic performance** (Regression)
- Predict **stress levels** (Classification)
- Understand and evaluate the most influential factors using feature selection techniques

---

## 📂 Dataset

The dataset used for this project is publicly available on Kaggle:

📎 [Stress Level Dataset on Kaggle](https://www.kaggle.com/datasets/muhammadasifumar/stressleveldataset)  
**Author**: Muhammad Asif Umar

It contains simulated data on:
- Psychological traits (anxiety, depression, self-esteem)
- Environmental conditions (noise level, living conditions, basic needs)
- Academic and social factors (study load, bullying, extracurriculars)
- Target variables:  
  - `academic_performance` (regression)  
  - `stress_level` (classification)

---

## ⚙️ Techniques Used

### ✅ Feature Engineering
- Added `student_id` field
- Normalized selected columns using `StandardScaler`
- Outlier detection via **IQR method**

### ✅ Feature Selection
- Fisher score (`SelectKBest`) for regression and classification
- Visualized top 16 influential features

### ✅ Machine Learning Models
**Regression Models:**
- Linear Regression (with Ridge tuning)
- Random Forest Regressor

**Classification Models:**
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

### ✅ Model Tuning
- Hyperparameter tuning using `GridSearchCV`
- Separate pipelines for regression and classification

---

## 📈 Evaluation Metrics

**Regression:**
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

**Classification:**
- Accuracy
- Precision
- Recall
- F1 Score

---

## 📊 Visualizations

- Box plots for outlier analysis
- Correlation heatmaps
- Bar charts for top feature scores
- Performance metric comparisons

---

## 🛠️ Tech Stack

- Python (Colab)
- `pandas`, `numpy`
- `scikit-learn`, `matplotlib`, `seaborn`
