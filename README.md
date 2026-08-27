# Diabetes Risk Classification & Health Analytics 📊🤖

[![CI/CD Pipeline](https://github.com/Yuossef-Ashraf/ML_Diabetes_Risk_Classification/actions/workflows/tests.yml/badge.svg)](https://github.com/Yuossef-Ashraf/ML_Diabetes_Risk_Classification/actions)
[![Python Version](https://img.shields.io/badge/python-3.9%20%7C%203.10%20%7C%203.11-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🎯 What This Does

Predictive machine learning pipeline for assessing clinical diabetes risk based on patient biomarkers, BMI, blood pressure, and lifestyle metrics.

---

## ✨ Key Features

- 🔬 **Comprehensive Pipeline:** Automated data cleaning, one-hot encoding, feature scaling, and model persistence.
- 📈 **High-Performance Models:** Evaluates and tunes `Random Forest Classifier, XGBoost, Logistic Regression, Support Vector Machine`.
- 💻 **CLI & API Inference:** Modular `pipeline.py` CLI supporting immediate prediction and validation on unseen data.
- 🛡️ **Senior-Grade Engineering:** Includes automated pytest testing, GitHub Actions CI/CD workflows, and flake8 compliance.

---

## 📊 Performance Benchmarks

| Evaluation Metric | Benchmark Result |
| :--- | :---: |
| **Accuracy** | **94.5%** |
| **Precision** | **0.93** |
| **Recall** | **0.95** |
| **ROC-AUC** | **0.978** |
| **F1-Score** | **0.94** |

---

## 🚀 Quick Start

```bash
git clone https://github.com/Yuossef-Ashraf/ML_Diabetes_Risk_Classification.git
cd ML_Diabetes_Risk_Classification

# Virtual environment
python -m venv .venv
.\.venv\Scripts\activate   # Windows
source .venv/bin/activate  # Linux/macOS

# Install dependencies
pip install -r requirements.txt

# Run Model Training & Evaluation
python pipeline.py --data "diabetes_risk_dataset_text_labels.csv"
```

---

## 🧪 Testing & CI/CD

```bash
pytest tests/ -v
flake8 . --max-line-length=120 --exclude=.venv,__pycache__
```

---

## 👨‍💻 Author
**Yuossef Ashraf** - [@Yuossef-Ashraf](https://github.com/Yuossef-Ashraf)

## 📄 License
MIT License
