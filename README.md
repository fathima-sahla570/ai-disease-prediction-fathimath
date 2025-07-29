# 🧠 AI-Powered Early Disease Prediction Using Multiple Health Datasets

**Author**: Fathimath Sahla  
**Repository**: `ai-disease-prediction-fathimath`

---

## 📌 Project Overview

This project uses machine learning to build an AI-powered system for early detection of diseases like **Heart Disease**, **Diabetes**, and **Parkinson’s Disease**.  
By analyzing medical data, the system helps identify at-risk patients and supports faster diagnosis and treatment.

---

## 🎯 Objective

To develop a multi-disease prediction system that uses various health datasets and machine learning models to detect diseases early, improving healthcare decisions and outcomes.

---

## 🛠️ Tools & Technologies

- Python (Jupyter Notebook)
- pandas, numpy, matplotlib, seaborn
- scikit-learn (Logistic Regression, Random Forest, SelectKBest)
- joblib (for saving models)
- Streamlit (optional UI)

---

## 📊 Datasets Used

### 🩺 Heart Disease Dataset
- Features: age, sex, chest pain, cholesterol, blood pressure, etc.
- Target: `target` (1 = Disease, 0 = No Disease)

### 🩸 Diabetes Dataset
- Features: glucose level, BMI, insulin, pregnancies, age, etc.
- Target: `Outcome` (1 = Diabetic, 0 = Non-Diabetic)

### 🗣️ Parkinson’s Disease Dataset
- Features: vocal metrics (Fo, Jitter, Shimmer, NHR, etc.)
- Target: `status` (1 = Parkinson’s, 0 = Healthy)

---

## 🔁 Methodology

1. **Data Preprocessing**
   - Outlier removal, missing value handling
2. **Exploratory Data Analysis (EDA)**
   - Boxplots, correlation heatmaps, distributions
3. **Feature Selection**
   - `SelectKBest` and correlation-based filtering
4. **Model Training**
   - Trained models: Logistic Regression (others optional)
5. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC Curve
6. **Model Saving**
   - Used `joblib` to save models and scalers
7. **Prediction**
   - New data prediction using saved models

---

## ✅ Results

- Trained models separately for each disease
- Achieved high accuracy and AUC scores, especially with Parkinson’s
- Built a consistent pipeline from data to prediction

---

## 🚀 How to Use

1. Clone this repo  
2. Run `capsule_project.ipynb` in Jupyter Notebook  
3. Modify the dataset section to choose heart, diabetes, or Parkinson’s  
4. Follow through preprocessing → modeling → prediction  
5. Predict on new patient data at the end of the notebook

---

## 📌 Project Status

✅ Completed core modeling for 3 diseases  
✅ Saved models and feature sets  
✅ Ready for Streamlit deployment or API integration

---

> 💡 Future enhancements:
> - Add more advanced models (XGBoost, SVM, ensemble)
> - Build a unified prediction UI
> - Improve feature engineering with domain knowledge
