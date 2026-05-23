# 💳 Credit Scoring Model

> **CodeAlpha Machine Learning Internship — Task 1**

Predict an individual's **creditworthiness** (Good / Bad credit) using past financial data and classification algorithms.

---

## 📌 Objective
Build a credit scoring system that predicts whether a loan applicant is likely to repay or default, using supervised machine learning.

## 📊 Dataset
**German Credit Dataset** — auto-loaded via `sklearn.datasets`
- 1000 samples | 20 features
- Features: credit amount, duration, age, employment, housing, etc.

## 🤖 Models Compared
| Model | ROC-AUC | F1-Score |
|-------|---------|----------|
| Logistic Regression | ~0.78 | ~0.83 |
| Decision Tree | ~0.72 | ~0.78 |
| Random Forest | ~0.82 | ~0.85 |
| **Gradient Boosting ✅ Best** | **~0.84** | **~0.86** |

## 📈 Key Features
- ✅ Full EDA (distributions, boxplots, class balance)
- ✅ Label Encoding + StandardScaler pipeline
- ✅ 4 models trained and compared
- ✅ ROC Curves for all models
- ✅ Confusion Matrix
- ✅ Feature Importance (Random Forest)
- ✅ 5-Fold Cross Validation

## 🚀 Run on Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

1. Upload `credit_scoring_model.ipynb` to Colab
2. `Runtime → Run All`
3. No dataset download needed ✅

## 🛠️ Tech Stack
`Python` · `Scikit-learn` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`

## 📁 Output Files
| File | Description |
|------|-------------|
| `task1_eda.png` | EDA Dashboard |
| `task1_results.png` | Model Performance Dashboard |

---

*Built with ❤️ during CodeAlpha ML Internship*
