# SaaS Churn Prediction using ML

**Author:** Apoorva Kuchulakanti  
**Tagline:** Machine learning model to predict SaaS customer churn and improve retention.

---

## 🔎 Project Summary
This repository contains an end-to-end machine learning pipeline to predict customer churn for subscription/SaaS businesses. It demonstrates data preprocessing, imbalance handling (SMOTE), model training (Random Forest), evaluation, and visualizations.

---

## 📂 Repo Structure

---

## 🧾 Data
- Synthetic / sample dataset included: `data/saas_churn.csv` (~5000 rows)  
- Target: `Churn` (0 = retained, 1 = churned)

> If you want to use private/real data, place it in `data/` and **do not** commit sensitive files.

---

## ⚙️ How to run

1. Create virtual env and activate:
```bash
python -m venv venv
venv\Scripts\activate    # Windows
