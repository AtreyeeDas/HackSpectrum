# HackSpectrum
Diabetes Prediction Using Machine Learning &amp; AI Integration : A machine learning-based diabetes prediction system using ensemble learning (Voting Classifier) trained on the Pima Indian Diabetes Dataset. Integrated with Gemini API for AI-driven medical explanations, enhancing interpretability. Deployed as a FastAPI web service with ngrok tunneling.
# 🏥 Diabetes Prediction using Machine Learning & AI Integration

![Diabetes Prediction](https://img.shields.io/badge/Machine%20Learning-Python-blue) 
![FastAPI](https://img.shields.io/badge/API-FastAPI-green)
![Google Gemini](https://img.shields.io/badge/AI-Gemini-orange)

## 📖 **Project Overview**
This project is an AI-powered **diabetes risk prediction system** that utilizes **Machine Learning (ML) and Generative AI** for both prediction and medical guidance. 

- 🔍 **Predicts diabetes risk** based on health metrics.
- ⚡ **Ensemble ML Model (Voting Classifier)** for high accuracy.
- 🤖 **Gemini API for AI-driven medical explanations**.
- 🌐 **Deployed as a web API using FastAPI & ngrok**.

---

## 📊 **Dataset: Pima Indian Diabetes Dataset**
The **Pima Indian Diabetes Dataset (PIDD)** is widely used for diabetes prediction research. It consists of **768 samples** and **8 health features**:

| Feature | Description |
|---------|------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration (mg/dL) |
| Blood Pressure | Diastolic blood pressure (mm Hg) |
| Skin Thickness | Triceps skinfold thickness (mm) |
| Insulin | 2-hour serum insulin (μU/ml) |
| BMI | Body Mass Index (kg/m²) |
| DPF | Diabetes Pedigree Function (Genetic Risk Score) |
| Age | Age of the individual |

**Target Variable**:  
- `1` = **Diabetic**
- `0` = **Non-Diabetic**

---

## 🔍 **Machine Learning Approach**
### ✅ **ML Models Used**
The following models were trained and evaluated:
- **Logistic Regression**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **Naïve Bayes**
- **Gradient Boosting**
- **K-Nearest Neighbors (KNN)**

### 🏆 **Final Model: Voting Classifier**
An **ensemble model** combining the best-performing classifiers.  
**Final Accuracy**: `~79.3%`

---

## 🧠 **AI Integration**
### 🤖 **Gemini API for Medical Explanation**
After predicting diabetes risk, the **Gemini API** generates **personalized medical advice**:
- 🟢 **Non-Diabetic** → **Preventive health tips**
- 🔴 **Diabetic** → **Lifestyle changes & treatment options**
---

## 🚀 **Deployment: FastAPI + ngrok**
The model is deployed as a **FastAPI web service** with **ngrok** for public access.
