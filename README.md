# 🧠 Disease Predictor (Diabetes & Heart Disease)

A **Machine Learning project** that predicts the likelihood of **Diabetes** and **Heart Disease** using classical ML models.  
This repository contains Jupyter notebooks, datasets, pre-trained models, scalers, and a **Streamlit web app** for user-friendly predictions.  

---

## 📖 About
The project demonstrates how **ML models can predict diseases** based on patient health parameters.  
It covers:
- End-to-end **data preprocessing**,
- **Training** and **evaluation** of models,
- **Model persistence** (saving with Pickle),
- **Scalable prediction** through a **Streamlit UI**.

The project currently supports:
- 🩸 **Diabetes Prediction**
- ❤️ **Heart Disease Prediction**

---

## 🚀 Demo
🔗 **Live App**: [Disease Predictor (Streamlit)](https://disease-predictor-agkhmqewox3wfnbavk9f93.streamlit.app/)  

---

## ✨ Features
- Pre-trained ML models for **Diabetes** and **Heart Disease**.
- Simple **Streamlit-based web interface** for predictions.
- Reproducible **Jupyter Notebooks** for training & evaluation.
- **Pickled `.sav` files** for direct inference without retraining.
- Easy to extend with more diseases & datasets.

---

## 📊 Datasets
1. **Diabetes Dataset (`diabities.csv`)**  
   - Derived from the popular Pima Indians Diabetes Database.  
   - Features include glucose, BMI, insulin, age, etc.  

2. **Heart Disease Dataset (`heart_statlog_cleveland_hungary_final.csv`)**  
   - Combines heart disease records from multiple sources (Cleveland, Hungary).  
   - Features include cholesterol, blood pressure, max heart rate, ST depression, etc.  

Both datasets are included in the repository.

---

## 🔎 Machine Learning Workflow
1. **Data Collection** → Load datasets (`.csv`).  
2. **Data Preprocessing** → Handle missing values, scaling, encoding.  
3. **Feature Scaling** → `StandardScaler` used for normalization.  
4. **Model Training** → ML algorithms applied (Logistic Regression, SVM, Random Forest, etc.).  
5. **Evaluation** → Accuracy, confusion matrix, precision-recall, etc.  
6. **Model Saving** → Store trained models (`.sav`) and scalers.  
7. **Deployment** → Load models into a **Streamlit UI** for predictions.

---

