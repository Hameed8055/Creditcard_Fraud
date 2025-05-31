# 💳 Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, with a small fraction of transactions classified as fraudulent. The primary goal is to build a model that can effectively identify fraudulent transactions while minimizing false positives.

---

## 📌 Project Objectives

- Clean and preprocess the credit card transaction dataset
- Perform Exploratory Data Analysis (EDA) to uncover patterns
- Handle data imbalance using appropriate techniques
- Train multiple machine learning models
- Evaluate and compare model performance
- Identify important features contributing to fraud detection

---

## 📊 Dataset

- **Source:** [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Total Records:** 284,807 transactions
- **Features:** 30 (28 anonymized PCA components + `Time`, `Amount`)
- **Target:** `Class` (0 = non-fraud, 1 = fraud)

---

## 🔧 Technologies Used

- Python (Pandas, NumPy, Scikit-learn)
- Data Visualization: Matplotlib, Seaborn
- Machine Learning Models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost
- Jupyter Notebook

---

## 🧹 Data Preprocessing

- Scaled `Amount` and `Time` using `StandardScaler`
- Handled missing values (none in this dataset)
- Checked class distribution and addressed imbalance
- Created new features for model training

---

## 📈 Exploratory Data Analysis (EDA)

- Distribution of transaction amounts by class
- Boxplots, histograms, and correlation heatmaps
- Identified key differences between fraudulent and non-fraudulent transactions

---

## 🤖 Machine Learning Models

| Model             | Accuracy | Precision | Recall | F1 Score |
|------------------|----------|-----------|--------|----------|
| Logistic Regression | ~       | ~         | ~      | ~        |
| Decision Tree       | ~       | ~         | ~      | ~        |
| Random Forest       | ~       | ~         | ~      | ~        |
| XGBoost             | ~       | ~         | ~      | ~        |

> 📌 Replace ~ with your actual results from classification reports.

---

## 📊 Feature Importance

- Feature importance was visualized using:
  - Random Forest
  - XGBoost
- Most influential features identified for fraud classification

---

## 📁 Folder Structure

```
credit-card-fraud-detection/
│
├── creditcard.csv
├── creditcard_scaled.csv
├── CreditCardFraud.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Use SMOTE or ADASYN for oversampling
- Add deep learning models (e.g., Autoencoders)
- Deploy model via Flask or Streamlit app
- Integrate with real-time detection pipeline

---

## 🙋‍♂️ Author

**Muhammad Hameed Ullah**  
📧 hameedofficial07@gmail.com  
🌐 [GitHub](https://github.com/Hameed8055) | [LinkedIn](https://www.linkedin.com/in/m-hameed-ullah-khan-a95949255)

---
