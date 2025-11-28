# 🏡 California Housing Price Prediction

A machine learning project based on the **"Hands-On Machine Learning (HOML-3)"** book by Aurélien Géron.  
The goal is to predict **median house values in California districts** using the 1990 Census dataset.

---

## 🚀 Project Overview

This project walks through a complete ML workflow:

1. **Data Loading & Exploration**
2. **Train/Test Splits**
3. **Feature Engineering**
   - Ratio features (rooms per household, etc.)
   - Log transforms
   - Cluster similarity (KMeans + RBF kernel)
   - Handling missing values
   - One-Hot Encoding for categorical features
4. **Preprocessing Pipelines** using `ColumnTransformer` & `Pipeline`
5. **Model Training & Evaluation**
   - Linear Regression
   - Decision Tree
   - Random Forest Regressor
6. **Cross-Validation**
7. **Hyperparameter Tuning**
   - `GridSearchCV`
   - `RandomizedSearchCV`

---

## 🧠 Models & Performance

| Model | Training RMSE | Validation RMSE | Comments |
|------|---------------|----------------|----------|
| Linear Regression | High | High | ❌ Underfitting |
| Decision Tree | Very low | High | ❌ Severe Overfitting |
| Random Forest | Low | Much lower | ⭐ Best model so far |

Next steps: Try SVM, Gradient Boosting, Neural Networks, and further tuning.

---

## 🛠️ Tech Stack

- Python 3.x
- NumPy, Pandas
- Scikit-Learn
- Matplotlib / Seaborn (optional for visuals)

---

## 📂 Project Structure (example)


├── notebooks/
│ └── housing.ipynb
├── data/
│ └── housing.csv
├── README.md
└── requirements.txt


---

## 📌 References

- “Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow (3rd Edition)” — Aurélien Géron
- California Housing dataset (Scikit-Learn)

---

## ✍️ Author

This repository is a **learning and practice** project created while studying machine learning fundamentals.

