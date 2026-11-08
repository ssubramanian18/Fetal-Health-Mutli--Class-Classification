# Fetal Health Multi-Class Classification

## 📌 Project Overview

This project develops a **multi-class classification model** to predict fetal health conditions using cardiotocogram data.

The goal is to support **early detection of fetal distress** and help reduce risks associated with maternal and child mortality by providing a data-driven approach for identifying high-risk pregnancies.

---

# 🎯 Objectives & Goals

- Develop a machine learning model to classify fetal health conditions
- Compare multiple classification algorithms
- Optimize model performance using machine learning techniques
- Evaluate model effectiveness using classification metrics

---

### Target Classes

| Class | Description |
|---|---|
| 1 | Normal fetal health |
| 2 | Suspected fetal health condition |
| 3 | Pathological fetal health condition |

---

# 🛠️ Methodology

## 1. Data Preprocessing/EDA
- Data cleaning
- Feature inspection
- Preparing data for model training

## 2. Model Development

Multiple Scikit-Learn classification models were trained and compared:

- SVM
- KNN
- Decision Tree
- Random Forest
- Logisitc Regression

## 3. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

# 🤖 Model Results

## Best Performing Model: Random Forest Classifier

| Metric | Performance |
|---|---|
| Precision | ~95% |
| Recall | ~95% |

The Random Forest model provided strong classification performance, making it effective for identifying fetal health conditions from CTG data.

---

# 📈 Key Findings

- Machine learning models can successfully classify fetal health states using cardiotocogram data.
- Random Forest outperformed other tested models.
- High precision and recall indicate reliable identification of fetal health risks.
- Data-driven classification can assist healthcare professionals with early risk detection.



