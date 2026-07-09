# 🏨 Hotel Booking Cancellation Prediction using Machine Learning

## 📖 Overview

This project predicts whether a hotel booking will be cancelled using Machine Learning techniques. It demonstrates the complete machine learning workflow, starting from data preprocessing and feature engineering to model comparison and explainability.

The project was built as an end-to-end case study focusing not only on predictive performance but also on understanding business problems and model interpretability.

---

## 🎯 Problem Statement

Hotel booking cancellations can lead to revenue loss, inefficient room allocation, and poor resource planning. The objective of this project is to build a machine learning model that predicts booking cancellations in advance so hotels can make proactive business decisions.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Create business-driven engineered features
- Train multiple machine learning models
- Compare model performance
- Interpret predictions using SHAP
- Select the best-performing model

---

## 📂 Dataset

**Hotel Booking Demand Dataset**

**Target Variable**

- `is_canceled`
  - **0** → Booking Not Cancelled
  - **1** → Booking Cancelled

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SHAP
- Jupyter Notebook

---

## 🔄 Project Workflow

- Data Loading
- Data Inspection
- Exploratory Data Analysis
- Data Cleaning
- Feature Engineering
- Feature Encoding
- Train-Test Split
- Model Building
- Model Evaluation
- Feature Importance
- SHAP Explainability
- Model Comparison
- Final Conclusion

---

## 🤖 Models Evaluated

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## 📊 Performance Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|----------:|----------:|--------:|----------:|
| Logistic Regression | 79.69% | 68.33% | 48.64% | 56.83% |
| Decision Tree | 79.13% | 61.93% | 63.29% | 62.60% |
| Random Forest | 84.07% | **76.75%** | 60.31% | 67.54% |
| **XGBoost** | **84.20%** | 75.27% | **63.31%** | **68.78%** |

---

## 🏆 Best Performing Model

**XGBoost** achieved the best overall performance by providing the highest Accuracy, Recall, and F1 Score while maintaining strong Precision.

---

## 💡 Feature Engineering

Business-oriented features were created to improve prediction quality, including:

- Total Guests
- Total Nights
- Estimated Booking Value
- Estimated Total Cost
- Cost Per Guest
- Long Stay
- Couple Booking
- Changes Per Night
- Risk Score

Several engineered features were identified as important by the final model.

---

## 🔍 Explainability

Model predictions were interpreted using:

- Feature Importance
- SHAP (SHapley Additive Explanations)

These techniques helped identify the key factors influencing booking cancellations and improved the transparency of the final model.

---

## 📈 Key Findings

- Lead Time is one of the strongest predictors of cancellation.
- Booking channel significantly influences customer behavior.
- Deposit Type and Parking Requirements impact cancellation probability.
- Feature engineering improved model performance.
- XGBoost produced the best overall balance of evaluation metrics.

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Streamlit Dashboard
- Flask/FastAPI Deployment
- Real-time Prediction API

---

## 👨‍💻 Author

**Venkat Jyoshit Potnuru**

B.Tech – Artificial Intelligence & Data Science

Amrita Vishwa Vidyapeetham

---

⭐ If you found this project useful, consider giving it a star!