
---

# **ELEVATE LABS AI/ML INTERNSHIP**

## **Task-3: House Price Prediction**

**By:** Harsimran Singh | **Date:** 26 June 2025

---

##  **Objective:**

Predict house prices using Linear Regression, understand model performance, and observe effects of regularization.

---

##  **What We Did:**

 Cleaned and pre-processed Housing Dataset
 Encoded categorical columns (Yes/No → 1/0, One-Hot for furnishing status)
 Scaled features using `StandardScaler`
 Split data into Train/Test (75/25)
 Applied:

* Simple Linear Regression
* Ridge Regression
* Lasso Regression
   Visualized correlations using Heatmap

---

##  **How We Did It:**

* Used `Pandas` for data handling
* `Numpy` for encoding
* `Sklearn` for model building and evaluation
* Visuals via `Matplotlib` & `Seaborn`

**Models Evaluated with:**

* Mean Absolute Error (MAE)
* R² Score
* RMSE

---

##  **Conclusion:**

| Model             | MAE (₹)     | R² Score | RMSE (₹)     | Remarks                        |
| ----------------- | ----------- | -------- | ------------ | ------------------------------ |
| Linear Regression | \~9.15 Lakh | 0.66     | \~12.45 Lakh | Baseline Model                 |
| Ridge Regression  | \~9.14 Lakh | 0.66     | \~12.46 Lakh | Regularization, minimal impact |
| Lasso Regression  | \~9.15 Lakh | 0.66     | \~12.45 Lakh | Sparse feature impact          |

---

##  **Why We Did It:**

* Understand regression techniques
* Explore real-world house price data
* Learn model evaluation with limited dataset

** Limitation:** Only 545 records → Possible underfitting, low complexity learning

---


