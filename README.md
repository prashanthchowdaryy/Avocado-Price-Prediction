# 🥑 Avocado Price Prediction using Machine Learning

Predicting avocado prices using multiple regression models and comparing their real-world performance on structured data.

This project focuses on **model comparison**, not just accuracy chasing — because in Machine Learning, *the best model depends on the data, not the hype.*

---

##  Project Overview

Avocado prices vary due to multiple factors such as region, volume, and time.  
The goal of this project is to:

- Analyze avocado sales data
- Build multiple regression models
- Compare their performance using standard evaluation metrics
- Understand which models work best for **tabular datasets**

---

##  Models Implemented

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- K-Nearest Neighbors (KNN)  
- Support Vector Regression (SVR)  
- XGBoost Regressor  
- Deep Neural Network (TensorFlow / Keras)

---

##  Evaluation Metrics

All models were evaluated using:

- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **R² Score**

These metrics help measure both prediction accuracy and model reliability.

---

##  Results Summary

| Model                  | MAE   | MSE   | R² Score |
|------------------------|-------|-------|----------|
| Linear Regression      | 0.183 | 0.058 | 0.636    |
| Decision Tree          | 0.132 | 0.040 | 0.748    |
| Random Forest          | 0.094 | 0.018 | 0.889    |
| Support Vector Machine | 0.116 | 0.027 | 0.829    |
| K-Nearest Neighbors    | 0.099 | 0.024 | 0.852    |
| XGBoost                | 0.093 | 0.017 | 0.895    |
| Deep Neural Network    | 0.108 | 0.024 | 0.853    |

 **Key Insight:**  
Tree-based models (XGBoost & Random Forest) outperformed Deep Neural Networks on structured/tabular data — reinforcing a classic ML principle.

---

## 🛠 Tech Stack

- Python  
- Pandas & NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib & Seaborn  
- Jupyter Notebook  

---

## 📂 Project Structure

