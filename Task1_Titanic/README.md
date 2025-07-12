# Task 1 - Titanic Survival Prediction 🚢

This project is part of the **CodSoft Data Science Internship (July 2025 Batch B38)**. The objective is to build a machine learning model that predicts whether a passenger survived the Titanic disaster based on features such as age, gender, ticket class, fare, and more.

---

## 📁 Dataset
- **File used**: `Titanic-Dataset.csv`
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

---

## 🔍 Problem Statement
Predict whether a passenger survived or not using historical passenger data. This is a binary classification problem.

---

## 🛠️ Tools & Libraries Used
- **Language**: Python
- **Platform**: Google Colab
- **Libraries**:
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
  - LabelEncoder, RandomForestClassifier

---

## 📊 Workflow

1. **Data Loading**
   - Read CSV into Pandas DataFrame

2. **Exploratory Data Analysis (EDA)**
   - `.info()`, `.describe()`, `.isnull().sum()`
   - Visualized survival by sex, class, age

3. **Data Preprocessing**
   - Handled missing values (e.g., Age, Embarked)
   - Dropped unnecessary columns (Cabin, Name, Ticket)
   - Encoded categorical features (`Sex`, `Embarked`)

4. **Model Building**
   - Used `RandomForestClassifier`
   - Split data using `train_test_split`

5. **Model Evaluation**
   - Accuracy: **84.35%**
   - Classification Report & Confusion Matrix
   - Output includes actual vs predicted survival

---

## ✅ Results
- **Model Accuracy**: `0.8435`
- Output saved in `titanic_predictions_output.csv`  
  Includes actual labels and whether the model predicted "Survived" or "Not Survived".

---

## 📷 Screenshots (Optional)
- Confusion matrix and model output screenshots added as `output_sample.png`

---

## ✨ Conclusion
This beginner-level ML project helped explore:
- Data cleaning and transformation
- Exploratory Data Analysis (EDA)
- Model training and evaluation
- Interpretation of binary classification output

---

## 🔗 Connect with Me
- GitHub: [Vijaybattula26](https://github.com/Vijaybattula26)
- LinkedIn: [Vijay Battula](https://www.linkedin.com/in/vijay-battula-29a131336/)

