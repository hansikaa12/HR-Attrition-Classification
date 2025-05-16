# 👥 HR Attrition Classification

## 📌 Problem Statement

Employee attrition (or turnover) is a major concern for businesses as it affects productivity, morale, and costs associated with hiring and training new employees. Predicting which employees are likely to leave helps HR teams take proactive steps to retain valuable talent.

This project builds a classification model to predict employee attrition using organizational, demographic, and performance-related features.

---

## 🎯 Objectives

- Understand patterns and trends in employee attrition through exploratory data analysis (EDA).
- Preprocess and prepare HR data for machine learning.
- Train classification models to predict whether an employee is likely to leave.
- Identify key factors driving employee attrition.

---

## 🎯 Aim

To create a predictive model that assists HR departments in identifying employees at risk of attrition and implementing retention strategies accordingly.

---

## 📚 Dataset Description

The dataset includes information on:

- **Demographics**: Age, Gender, Marital Status, etc.
- **Job Role & Environment**: Department, Job Role, Work-Life Balance, OverTime
- **Performance & Compensation**: Salary Hike, Performance Rating, Years at Company
- **Target Variable**: `Attrition` (Yes/No)

---

## 🧪 Exploratory Data Analysis (EDA)

- Count plots to show distribution of attrition across departments, job roles, and overtime status
- Heatmap to explore correlations
- Boxplots for salary, working years, and job satisfaction comparisons
- Class imbalance analysis

---

## 🧼 Data Preprocessing

- Handled missing values (if any)
- Label encoded binary and ordinal categorical variables
- One-hot encoded nominal categorical features
- Feature scaling using StandardScaler or MinMaxScaler
- Split data into training and test sets (typically 80/20)

---

## 🤖 Classification Models Used

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **XGBoost Classifier** *(if implemented)*

---

## ✅ Model Evaluation

Evaluation metrics used:

- **Accuracy**
- **Precision, Recall, F1-score**
- **Confusion Matrix**
- **ROC-AUC Score**

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~83%     |
| Decision Tree       | ~85%     |
| Random Forest       | **~89%** ✅ |
| SVM                 | ~84%     |
| KNN                 | ~82%     |

🏆 **Best Model**: **Random Forest Classifier** with ~89% accuracy

---

## 📈 Visualizations

- ROC Curve comparison
- Confusion matrices for each model
- Feature importance plot (from tree-based models)
- Attrition distribution by feature (e.g., OverTime, Department)

---

## 🔧 Tools & Libraries

- Python (Jupyter Notebook)
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost (if included)

---
