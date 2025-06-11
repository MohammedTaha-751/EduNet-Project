# EduNet-Project
# 💼 Employee Performance & Attrition Prediction System

A Machine Learning system that predicts employee performance scores and attrition risk using structured HR data. Built with Python, Scikit-learn, SHAP, and Matplotlib for analytics and visualization.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [System Requirements](#system-requirements)
- [Setup Instructions](#setup-instructions)
- [Code Walkthrough](#code-walkthrough)
- [Results](#results)
- [Future Scope](#future-scope)
- [GitHub Link](#github-link)
- [License](#license)

---

## 📖 Overview

This project simulates a workplace scenario where employee performance is evaluated and attrition is predicted based on features like stress level, focus, work hours, and training. It supports HR analytics by:

- Predicting performance scores using **Linear Regression**
- Classifying attrition risk using **Random Forest Classifier**
- Visualizing feature importance with **SHAP**

---

## ✨ Features

- Generate realistic synthetic HR data
- Dual modeling (Regression + Classification)
- Clear performance reports with metrics
- Explainable AI using SHAP visualizations
- Ready for deployment in dashboards

---

## ⚙️ Tech Stack

- Python 3.10+
- Libraries:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`
  - `shap`

---

## 📂 Dataset

The synthetic dataset includes:

| Feature              | Type        | Description                          |
|----------------------|-------------|--------------------------------------|
| Attendance (%)       | Numeric     | Weekly attendance percentage         |
| Project Delivery Score | Numeric   | Average score on recent projects     |
| Work Hours/Week      | Numeric     | Average work hours per week          |
| Previous Rating      | Numeric     | Past performance rating (1–5 scale)  |
| Stress Level         | Numeric     | Reported stress level (1–10)         |
| Focus Level          | Numeric     | Measured focus level (1–10)          |
| Sleep Hours          | Numeric     | Average sleep per night              |
| Gender, Education    | Categorical | Demographic details                  |
| Training Completed   | Categorical | Whether employee completed training  |
| Remote Work          | Categorical | Working remotely or not              |

**Target Variables**:
- `Performance Score`: A calculated performance metric
- `Attrition Risk`: Binary value (0 = No, 1 = Yes)

---

## 💻 System Requirements

- Python ≥ 3.8
- Jupyter Notebook or any Python IDE
- Libraries: Install via `pip install -r requirements.txt`  
  (or install manually: pandas, numpy, sklearn, seaborn, matplotlib, shap)

---

## 🔧 Setup Instructions

```bash
git clone https://github.com/MohammedTaha-751/EduNet-Project.git
cd EduNet-Project
pip install -r requirements.txt
python employee_prediction.py
