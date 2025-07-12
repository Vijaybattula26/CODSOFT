# 🌸 Task 3 - Iris Flower Classification

This project is part of the **CodSoft Data Science Internship – July 2025 (Batch B38)**.  
The goal is to build a machine learning model that accurately classifies **Iris flower species** based on their **sepal and petal measurements**.

---

## 📁 Dataset

We use the **Iris dataset**, a classic multivariate dataset that contains:

- **150 samples**
- **3 classes**:  
  - Iris-setosa  
  - Iris-versicolor  
  - Iris-virginica

### 📊 Features:
- `sepal_length` (cm)  
- `sepal_width` (cm)  
- `petal_length` (cm)  
- `petal_width` (cm)  
- `species` (target)

---

## 🧰 Tools & Libraries Used

- Python 🐍  
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
- Google Colab

---

## 🔍 Project Workflow

### ✅ 1. Data Loading & EDA
- Displayed data structure with `.info()`, `.describe()`
- Checked for nulls and class balance
- Visualized data using `pairplot` and `heatmap`

### ✅ 2. Preprocessing
- Label-encoded target (`species`)
- Split data into training and testing sets

### ✅ 3. Model Building
- Trained a **Random Forest Classifier**
- Evaluated using:
  - **Accuracy Score**
  - **Classification Report**
  - **Confusion Matrix**

### ✅ 4. Predictions & Export
- Compared actual vs predicted values
- Exported results to `iris_classification_predictions.csv`

---

## 📈 Results

- Achieved **high accuracy** using Random Forest
- Model accurately classified all three species

---

## 📂 Files in this Folder


