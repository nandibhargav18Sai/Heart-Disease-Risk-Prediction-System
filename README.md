# Heart-Disease-Risk-Prediction-System
# 🫀 Heart Disease Risk Prediction System

A complete machine learning classification pipeline built in Python to predict cardiovascular disease risk from patient clinical parameters.

## 📌 Project Overview
Early detection of cardiovascular disease is vital for effective medical intervention. This project implements an end-to-end data science workflow—from data cleaning and outlier management to model training and performance evaluation using an `ExtraTreesClassifier`.

## ⚙️ Key Workflow & Steps
1. **Data Preprocessing & Cleaning:** Handled missing values and managed outliers in numerical features using the Interquartile Range (IQR) method.
2. **Feature Engineering & Scaling:** Standardized key continuous parameters using `StandardScaler`.
3. **Model Training:** Trained a robust machine learning classification pipeline utilizing `ExtraTreesClassifier`.
4. **Model Evaluation:** Evaluated performance comprehensively focusing on Precision, Recall, F1-Score, and ROC-AUC.

## 📊 Performance Metrics
* **Accuracy:** 85%
* **ROC-AUC Score:** 0.9283
* **Classification Report Summary:**
  * Class 0 (Low Risk): Precision: 0.83 | Recall: 0.86 | F1-Score: 0.85
  * Class 1 (High Risk): Precision: 0.87 | Recall: 0.84 | F1-Score: 0.86

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## 🚀 How to Clone and Run

Run these commands in your terminal to set up and execute the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/nandibhargav18Sai/Heart-Disease-Risk-Prediction-System

# 2. Navigate to the project directory
cd Heart-Disease-Risk-Prediction-System

# 3. Open the Jupyter Notebook
jupyter notebook heart_disease.ipynb
