# Customer_Churn
# 📊 Customer Churn Prediction – Telco Dataset

This project focuses on predicting customer churn using the [Telco Customer Churn Dataset from Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). We compare multiple models, including Neural Networks and ensemble methods, to find the most accurate solution for churn prediction.

---

## 🚀 Objective

To accurately predict whether a customer will churn, helping telecom providers take preventive actions.

---

## 📁 Dataset Overview

- **Source**: Kaggle – Telco Customer Churn Dataset  
- **Features**: 21 (demographics, account, service-related info)  
- **Target**: `Churn` (Yes/No)

---

## 🧠 Models Used

| Model                        | Accuracy |
|-----------------------------|----------|
| Random Forest               | **94%**  |
| XGBoost                     | ~90%     |
| Gradient Boosting           | ~82%     |
| Neural Network (Keras/TensorFlow) | 78%  |

Ensemble models outperformed the neural network on this structured dataset.

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**:
  - `pandas`, `numpy` – Data handling  
  - `scikit-learn` – Preprocessing, modeling, evaluation  
  - `xgboost`, `randomforest`, `gradientboosting` – ML models  
  - `tensorflow`, `keras` – Deep learning  
  - `matplotlib`, `seaborn` – Visualization  

---

## 📊 Visualizations

- Correlation heatmaps  
- Churn distribution plots  
- Feature importance bar charts  
- Confusion matrices per model  

---

## 🔍 Key Findings

- `Contract`, `Tenure`, and `MonthlyCharges` are strong churn indicators.  
- Random Forest achieved the highest accuracy.  
- Neural networks underperformed due to tabular data format.

---

