# 📊 Task 4 - Sales Prediction Using Python

This project is part of the **CodSoft Data Science Internship – July 2025 (Batch B38)**.

The aim is to build a **Linear Regression** model that predicts **product sales** based on advertising budgets across **TV**, **Radio**, and **Newspaper**.

---

## 🗂️ Dataset

**File:** `advertising.csv`  
It contains:
- `TV` – Budget spent on TV ads
- `Radio` – Budget spent on radio ads
- `Newspaper` – Budget spent on newspaper ads
- `Sales` – Units sold (target variable)

---

## 🔧 Tools Used

- Python (Google Colab)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (LinearRegression, train_test_split, r2_score)

---

## 🧪 Steps Followed

1. **Exploratory Data Analysis (EDA)**  
   - `.info()`, `.describe()`, `.isnull().sum()`
   - Correlation heatmaps and pairplots

2. **Data Preprocessing**  
   - Verified no missing values
   - No encoding needed (numeric features only)

3. **Model Building**  
   - Used `LinearRegression` from `sklearn`
   - Split data into 80% train, 20% test sets

4. **Model Evaluation**  
   - R² Score
   - Root Mean Squared Error (RMSE)
   - Visual comparison of actual vs predicted sales

5. **Output**  
   - Predictions saved in `sales_predictions.csv`

---

## 📁 Project Files


