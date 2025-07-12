# 🔐 Task 5 – Credit Card Fraud Detection

This project is part of the **CodSoft Data Science Internship – July 2025 (Batch B38)**.  
The goal is to build a machine learning classification model to **detect fraudulent credit card transactions**, a critical real-world use case in financial security.

---

## 📁 Dataset Overview

- Dataset: **creditcard.csv**
- Size: ~285,000 transactions
- Features: Time, Amount, V1 to V28 (anonymized PCA features)
- Target:  
  - `0` = Legitimate transaction  
  - `1` = Fraudulent transaction

⚠️ The dataset is highly **imbalanced** (fraud cases ~0.17%).

---

## 💡 Problem Statement

> Build a classifier that can distinguish **fraudulent** from **genuine** transactions.  
> Address class imbalance and evaluate performance using metrics that matter:  
> **Precision, Recall, and F1-Score**.

---

## 🛠️ Tools & Libraries Used

- Python (Google Colab)
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (LogisticRegression, train_test_split, metrics)
- imbalanced-learn (RandomUnderSampler)

---

## 🔍 Project Steps

### ✅ 1. Data Exploration & Cleaning
- Inspected structure, missing values, class imbalance
- Visualized class distribution and correlations

### ✅ 2. Preprocessing
- Dropped `Time`, normalized `Amount`
- Used `StandardScaler` for feature scaling

### ✅ 3. Train-Test Split
- Used `stratify=y` to preserve class distribution

### ✅ 4. Imbalance Handling
- Applied **RandomUnderSampler** to balance classes
- Ensured equal distribution of 0 and 1 for training

### ✅ 5. Model Building
- Trained a **Logistic Regression** classifier
- (Also tested with Random Forest for comparison)

### ✅ 6. Evaluation
- Accuracy, Confusion Matrix
- **Precision**, **Recall**, **F1-score**

### ✅ 7. Output
- Saved predictions to `fraud_detection_predictions.csv`
- Visualized confusion matrix

---

## 📂 Folder Structure

Task5_FraudDetection/
├── fraud_detection.ipynb ← Notebook (Colab)
├── fraud_detection_predictions.csv ← Output with predictions
├── output_sample.png ← Confusion matrix / plot
└── README.md ← Project overview


> ⚠️ Dataset not included due to GitHub file size limits.  
> 📥 You can download it from: [Kaggle Credit Card Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

## 🧠 Key Learnings

- How to handle **class imbalance** in classification problems  
- Importance of evaluation beyond accuracy: **precision/recall**  
- Preprocessing with scaling and sampling  
- Real-world fraud detection simulation

---

## 👨‍💻 Completed By

**Vijay Battula**  
📧 vijaybattula1426@gmail.com  
🔗 [LinkedIn – Vijay Battula](https://www.linkedin.com/in/vijay-battula-29a131336)  
🎓 CodSoft Data Science Internship – July 2025 (Batch B38)

---

## 🔖 Hashtags

`#CodSoft #DataScienceInternship #CreditCardFraud #MachineLearning #PythonProject #ImbalancedData #ScikitLearn #VijayBattula #LogisticRegression #FraudDetection #CodSoftInternship #GoogleColab #GitHubPortfolio`

