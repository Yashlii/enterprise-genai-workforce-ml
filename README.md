# Enterprise GenAI Workforce Impact Analysis

## Overview
This project analyzes the impact of Generative AI (GenAI) adoption on enterprise workforce productivity and employee sentiment using machine learning and NLP techniques.

The goal is to predict:
- Productivity impact (Low / Medium / High)
- Employee sentiment polarity (Positive / Neutral / Negative)

---

## Dataset
- 100,000 enterprise records
- Structured + unstructured features
- Source: Kaggle – Enterprise GenAI Adoption & Workforce Impact Dataset
- 10 core features (categorical + numerical + sentiment text)

---

## Problem Statement
How does Generative AI adoption affect enterprise workforce productivity and employee sentiment?

This project builds predictive models to help organizations make data-driven HR and AI adoption decisions.

---

## Data Preprocessing
- Label Encoding (categorical features)
- StandardScaler (numerical features)
- TF-IDF Vectorization (sentiment text)
- Sentiment polarity scoring
- Feature Engineering (ratio + interaction features)

---

## Feature Engineering
- Training Hours per Employee
- New Roles per Employee
- Industry × Country interaction
- Tool × Sentiment interaction

---

## Models Implemented
- Logistic Regression (baseline)
- Random Forest
- XGBoost
- LightGBM (Final Model)

---

## Final Results
Productivity Classification:
- 81% Accuracy
- F1 Score: 0.75

Sentiment Classification:
- 88% Accuracy
- F1 Score: 0.86

---

## Model Explainability
- SHAP analysis used for feature importance
- Key drivers identified:
  - Training Hours per Employee
  - New Roles Created
  - Sentiment Polarity

---

## Tech Stack
Python  
Pandas  
NumPy  
Scikit-learn  
LightGBM  
XGBoost  
SHAP  
NLTK  
Matplotlib  
Seaborn  

---

## Repository Structure
- FINAL_CODE_CAPSTONE_PROJECT.ipynb
- Final_report_project.pdf
- Final_presentation.pptx
- requirements.txt

---

## Future Improvements
- Model deployment using FastAPI
- Containerization using Docker
- Cloud deployment on Azure
- Transformer-based NLP (BERT / GPT)
