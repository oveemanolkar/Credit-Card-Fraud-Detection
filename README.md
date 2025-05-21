### Credit Card Fraud Detection Project

## 📌 Project Overview

This Jupyter Notebook demonstrates **Credit Card Fraud Detection** using machine learning techniques in Python. It utilizes unsupervised anomaly detection models to identify potentially fraudulent transactions in a highly imbalanced dataset.

The dataset used includes anonymized features derived from PCA transformations, a transaction `Amount` feature, and a binary `Class` label indicating fraud (1) or normal (0).

---

## 📁 Dataset Description

- Number of transactions
- Features: V1–V28 (PCA transformed), `Amount`, `Time`
- Target: `Class` (0 = Normal, 1 = Fraud)

Ensure that `creditcard.csv` is in your working directory before running the notebook.

---

## 🧪 Key Steps Performed

- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Class imbalance visualization
- Outlier detection using:
  - Isolation Forest
  - Local Outlier Factor (LOF)
  - One-Class SVM
- Evaluation of prediction performance
- Confusion matrix and classification report generation

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`, `seaborn`
- `sklearn` (for models and metrics)
- `PyCaret` (for simplified ML workflow)

---

## ▶️ How to Run This Notebook

1. Install the required packages if not already installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn pycaret
   ```

2. Download and place `creditcard.csv` in the same directory as this notebook.

3. Open and run each cell sequentially in your Jupyter Notebook environment.

---

## 📊 Output

The notebook produces:

- Visualizations of class distribution
- Anomaly detection results
- Confusion matrices
- Performance metrics for model evaluation

---

## 📌 Conclusion

This project illustrates the power of unsupervised anomaly detection in identifying fraudulent transactions within large, imbalanced financial datasets. It emphasizes model comparison and interpretability.

---

