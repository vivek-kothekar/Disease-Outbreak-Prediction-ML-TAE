![Python](https://img.shields.io/badge/Python-ML-blue)

# Disease Outbreak Prediction using Diabetes Dataset

This project is developed as part of Machine Learning TAE-1 (Project Based Learning). The primary objective is to predict the occurrence of diabetes using multiple supervised machine learning algorithms and perform a comparative analysis to identify the most effective model.

---

## 📌 Introduction

This project focuses on predicting diabetes using machine learning techniques based on medical and diagnostic data. Early prediction of diabetes is important to prevent serious health complications such as heart disease, kidney failure, and vision loss. The system uses patient health attributes to determine whether a person is diabetic or not.

---

## 📊 Dataset

The dataset used in this project is the **Pima Indians Diabetes Dataset**, which contains medical information of patients.

### **Features Include:**

* Glucose Level
* Blood Pressure
* Skin Thickness
* Insulin
* BMI (Body Mass Index)
* Diabetes Pedigree Function
* Age
* Pregnancies

### **Target Variable:**

* **0 → Non-Diabetic**
* **1 → Diabetic**

---

## 🤖 Models Implemented (Supervised Learning)

### ✅ 01: Logistic Regression

* Used for binary classification
* Applied feature scaling
* Provides baseline performance

### ✅ 02: Decision Tree

* Tree-based classification model
* Easy to interpret
* Higher recall but may overfit

### ✅ 03: Random Forest

* Ensemble learning method
* Combines multiple decision trees
* Achieved best performance

### ✅ 04: K-Nearest Neighbors (KNN)

* Distance-based classification
* Sensitive to feature scaling

### ✅ 05: Naive Bayes

* Probabilistic classifier
* Fast and efficient

### ✅ 06: Linear Regression

* Used with thresholding for classification
* Simple model for comparison

---

## ⚙️ Methodology

The project follows a complete machine learning pipeline:

1. Data Collection
2. Data Preprocessing (handling missing values)
3. Feature Scaling (StandardScaler)
4. Train-Test Split (70:30 and 80:20)
5. Model Training
6. Model Evaluation
7. Performance Comparison

---

## 📊 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📈 Results

* **Random Forest** performed best in 70-30 split
* **Naive Bayes** performed best in 80-20 split
* **Decision Tree** achieved highest recall
* **Linear Regression** showed lowest performance

Graphs and confusion matrices are used for better comparison of models.

---

## 🧠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 📁 Repository Structure

```
Disease-Outbreak-Prediction
│
├── README.md
├── datasets
├── logs
├── models
```

---

## 🚀 Objective

* To implement multiple supervised machine learning models
* To compare model performance using different metrics
* To analyze model behavior using different data splits
* To identify the best model for diabetes prediction

---

## ✨ Highlights

* Implemented **6 supervised ML models**
* Compared models using multiple evaluation metrics
* Used **two train-test splits (70-30 and 80-20)**
* Visualized results using graphs and confusion matrix
* Maintained structured project workflow

---

## 🏆 Best Model

**Random Forest** performed best overall due to:

* Higher accuracy
* Better generalization
* Reduced overfitting using ensemble learning

---

## ⚠️ Limitations

* Limited dataset size
* Basic feature engineering
* No advanced hyperparameter tuning
* Linear Regression not ideal for classification

---

## 🔮 Future Improvements

* Apply advanced models (XGBoost, Deep Learning)
* Perform hyperparameter tuning
* Use larger datasets
* Deploy as web or mobile application
* Improve feature engineering

---

## 📌 Conclusion

This project demonstrates that machine learning can effectively predict diabetes using medical data. Comparative analysis helps in selecting the most suitable model for healthcare applications.

---
