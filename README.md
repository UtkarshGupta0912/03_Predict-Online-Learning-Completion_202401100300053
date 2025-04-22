# 03_Predict-Online-Learning-Completion_202401100300053
# 🎓 Predict Online Learning Completion

This project uses machine learning techniques to predict whether a student will complete an online course based on their learning behaviors and activity data.

## 📌 Problem Statement

With the rise of online education, understanding student engagement and predicting course completion has become essential. This project aims to build a classification model that can accurately predict whether a student will complete an online course or not.

---

## 📊 Dataset

- **File:** `online_learning.csv`
- **Description:** Contains learner data such as time spent on the platform, number of logins, quizzes attempted, etc.
- **Target Column:** `completed` (1 = Completed, 0 = Not Completed)

---

## 🧠 Methodology

1. **Data Exploration & Visualization**
   - Checked nulls, distributions, and target balance
   - Visualized course completion rates

2. **Preprocessing**
   - Handled missing values
   - Encoded categorical variables
   - Standardized numerical features

3. **Model Training**
   - Trained a **Random Forest Classifier**
   - Evaluated using accuracy, confusion matrix, and classification report

4. **Evaluation**
   - Visualized confusion matrix and feature importance
   - Measured accuracy and performance metrics

---

## 🧪 How to Run

### ⚙️ Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install requirements using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
