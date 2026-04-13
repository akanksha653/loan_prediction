# 💳 Credit Risk Prediction System using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Deployment](https://img.shields.io/badge/Deployed-Streamlit-red)

---

## 📌 Project Overview
This project aims to predict whether a customer is likely to default on a loan using machine learning techniques. It is based on the Home Credit dataset and focuses on improving risk assessment for better financial decision-making.

---

## 📂 Dataset
- Source: https://www.rakamin.com/virtual-internship-experience/data-scientist-home-credit-indonesia

---

## 📑 Table of Contents
- [Business Understanding](#-business-understanding)
- [Workflow](#-workflow)
- [Insight](#-insight)
- [Modeling and Evaluation](#-modeling-and-evaluation)
- [Model Simulation using Streamlit](#-model-simulation-using-streamlit)
- [Recommendations](#-recommendations)

---

## 📂 Business Understanding

### 🧩 Problem Statement
Home Credit provides fast and accessible credit services. However, one major challenge is customers failing to repay loans, which can significantly impact the company financially.

> "Non-payment by consumers can set off a chain reaction of bad debts, lower profits, layoffs, and even bankruptcies."

Identifying high-risk customers helps reduce losses and improve loan approval decisions.

---

### 🎯 Goals
- Reduce losses caused by default customers  
- Improve loan approval decision-making  

---

### 🎯 Objectives
- Build a predictive model for default classification  
- Identify characteristics of high-risk customers  

---

## 📂 Workflow

<p align="center">
  <img src="https://github.com/faizns/HCI-vix-project/assets/115857221/8d64b89f-f0d0-4276-9a51-82a1adb0c9a8.jpg" width="1000">
</p>

---

## 📂 Insight

- Default rate: **9%**
- High-risk customer characteristics:
  - Male  
  - Lower education level  
  - Age: 25–40 years  
  - Work experience: 1–5 years  
  - Cash loan users  

---

## 📂 Modeling and Evaluation

- Train-test split: **80:20**
- Handled imbalance using **RandomUnderSampler**
- Scaling using **RobustScaler**

### Algorithms Used:
- Logistic Regression  
- Random Forest  
- XGBoost  

### 🏆 Best Model:
- Logistic Regression (Tuned)
- Accuracy: **87%**
- AUC Score: **73%**

<p align="center">
  <img src="https://github.com/faizns/HCI-vix-project/assets/115857221/a4daeca8-49f8-4c55-8cdd-3f3ad0486f18" width="800">
</p>

---

## 📂 Model Simulation using Streamlit

<p align="center">
  <img src="https://github.com/faizns/HCI-vix-project/assets/115857221/d7a67ea8-1d82-4ccc-884f-d99e57c335b8" width="1000">
</p>

<p align="center">
  <img src="https://github.com/faizns/HCI-vix-project/assets/115857221/045e4d1f-2b64-4e65-9018-8b6e8142c7cb" width="1000">
</p>

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Streamlit  

---

## ▶️ How to Run

```bash
git clone https://github.com/akanksha653/loan_prediction.git
cd your-repo-name
pip install -r requirements.txt
jupyter notebook
