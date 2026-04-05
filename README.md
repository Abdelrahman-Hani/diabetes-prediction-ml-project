# 🩺 Diabetes Prediction System using Machine Learning

## 📌 Overview
This project is a Machine Learning system designed to predict whether a patient has diabetes or not based on medical data.  
It uses multiple ML models and compares their performance to choose the best one.

The system helps in early detection of diabetes and supports medical decision-making using data-driven predictions.

---

## 🎯 Problem Statement
Diabetes is one of the most common chronic diseases worldwide.  
Early detection is difficult and usually requires medical tests.

This project aims to:
- Predict diabetes early using patient data
- Improve diagnosis support using AI
- Reduce time and human error in diagnosis

---

## 📊 Dataset
**PIMA Diabetes Dataset**

### Features:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target:
- 0 → Non-Diabetic
- 1 → Diabetic

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib

---

## 🧹 Data Preprocessing
- Handled missing values using Median
- Replaced invalid zero values
- Cleaned dataset for better performance
- Applied feature scaling using StandardScaler

---

## 🤖 Machine Learning Models

Three models were trained and compared:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

## 📈 Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 🔧 Model Optimization
- GridSearchCV for hyperparameter tuning
- Cross-validation for stable evaluation

---

## 🧪 Prediction Example

The system can predict diabetes risk for new patients based on input features.

Example output:
- 0 → No diabetes detected
- 1 → High risk of diabetes

---

## 🏁 Results
The models were evaluated and compared to select the best performing model based on F1-score and accuracy.

Random Forest and XGBoost showed strong performance.

---

## 🚀 Future Improvements
- Deploy as a web app using Streamlit
- Add AI explanation for predictions
- Improve dataset size and quality
- Integrate with healthcare systems

---

## 👨‍💻 Author
Abdo Hani

---

## 📌 Note
This project is developed for educational purposes and demonstrates how machine learning can be applied in healthcare for early disease detection.
