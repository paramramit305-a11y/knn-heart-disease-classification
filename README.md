#  KNN Classification - Heart Disease Prediction

## 📌 Project Overview
This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm using **scikit-learn** to predict heart disease.

The objective of this project is to understand distance-based classification, feature scaling, hyperparameter tuning, and building a clean machine learning pipeline.

---

## 📊 Dataset Information
- Dataset: Heart Disease Dataset
- Problem Type: Binary Classification

Target Variable:
- 0 → No Heart Disease
- 1 → Heart Disease

Features include medical attributes such as:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Maximum Heart Rate
- and other clinical parameters

⚠️ Note: This dataset is also used in my Logistic Regression and Naive Bayes projects to compare different ML algorithms on the same problem.

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn

---

## ⚙️ Project Workflow

1. Data Loading
2. Feature & Target Separation
3. Train-Test Split
4. Feature Scaling using StandardScaler
5. KNN Model Training
6. Testing multiple values of K
7. Hyperparameter tuning using GridSearchCV
8. Pipeline implementation
9. Model Evaluation

---

## 🤖 Model Used
- K-Nearest Neighbors (KNN)
- Distance Metric: Euclidean Distance

---

## 🔎 Hyperparameter Tuning
GridSearchCV is used to find the best value of **n_neighbors**.

Best Parameter:
- n_neighbors = 7

---

## 📈 Evaluation Metrics
- Recall Score
- Accuracy Score
- Precision Score

Sample Results:
- Recall: 0.906
- Accuracy: 0.918
- Precision: 0.935

---

---

## 👨‍💻 Author
**Parmar Amit**  
Aspiring AI/ML Engineer

