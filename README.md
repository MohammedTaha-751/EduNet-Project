# 💼 Employee Performance & Attrition Prediction System

A machine learning-based system that predicts employee performance scores (regression) and attrition risk (classification) using synthetic HR data. This project demonstrates model training, evaluation, and SHAP-based interpretability for business insights.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Project Highlights](#project-highlights)
- [Tech Stack](#tech-stack)
- [Dataset Description](#dataset-description)
- [Installation & Setup](#installation--setup)
- [Code Overview](#code-overview)
- [Results & Visualizations](#results--visualizations)
- [Future Scope](#future-scope)
- [GitHub Link](#github-link)
- [License](#license)

---

## 📖 Overview

This project uses synthetic data to:

- Predict employee performance scores using **Linear Regression**
- Predict attrition risk using **Random Forest Classifier**
- Visualize prediction accuracy and model interpretability via **SHAP plots**

It serves as a compact demonstration of regression, classification, preprocessing, evaluation, and explainability in a real-world HR scenario.

---

## ✨ Project Highlights

- 🔧 **Synthetic Dataset** with categorical and numerical features
- 📊 **Dual Prediction**: Performance (regression) & Attrition (classification)
- 🧠 **SHAP Interpretability** for explaining model decisions
- 📈 **Visual Insights** using Seaborn and Matplotlib

---

## 🧰 Tech Stack

- Python 3.8+
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- shap

---

## 📂 Dataset Description

| Feature               | Type        | Description                        |
|-----------------------|-------------|------------------------------------|
| Attendance (%)        | Numeric     | Attendance rate                    |
| Project Delivery Score| Numeric     | Score out of 100                   |
| Work Hours/Week       | Numeric     | Average working hours              |
| Previous Rating       | Numeric     | Rating from previous cycle (2–5)   |
| Stress Level          | Numeric     | 1–10 scale                         |
| Focus Level           | Numeric     | 1–10 scale                         |
| Sleep Hours           | Numeric     | Average daily sleep                |
| Education Level       | Categorical | Diploma/Bachelor/Master            |
| Remote Work           | Categorical | Yes/No                             |
| Gender                | Categorical | Male/Female                        |
| Training Completed    | Categorical | Yes/No                             |

**Targets:**
- `Performance Score`: Regression target
- `Attrition Risk`: Binary classification target (0 = No, 1 = Yes)

---

## 🛠 Installation & Setup

```bash
git clone https://github.com/MohammedTaha-751/EduNet-Project.git
cd EduNet-Project
pip install -r requirements.txt

```

## Code Overview
➤ Data Generation & Preprocessing
Synthetic dataset created using NumPy

Encoding categorical variables via pd.get_dummies

Feature scaling with StandardScaler

Target variables: Performance Score, Attrition Risk 
---

## 📊 Results & Visualizations
✅ Performance Score: R² ≈ 0.87, MSE ≈ 90

✅ Attrition Prediction: Balanced precision, recall

🔍 Important Features: Focus Level, Project Delivery Score, Stress Level

📉 Visual Tools: Scatterplots, Confusion Matrix, SHAP Beeswarm

## 🔮 Future Scope
Integration with HRMS dashboards

Web-based deployment using Streamlit or Flask

Use real HR data for enhanced prediction accuracy

## 📜 License
This project is open-source and available under the MIT License.

---






