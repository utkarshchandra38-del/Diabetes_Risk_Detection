# Diabetes Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict whether a patient has diabetes based on medical attributes using machine learning models.

## 📊 Dataset
-The dataset used in this project is the **Pima Indians Diabetes Dataset**. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. It contains medical diagnostic data of **female patients aged 21 years and above**.
- Features include:
  - Pregnancies: Number of pregnancies the patient has had  
  - Glucose: Plasma glucose concentration  
  - BloodPressure: Diastolic blood pressure (mm Hg)  
  - SkinThickness: Triceps skin fold thickness (mm)  
  - Insulin Level: 2-Hour serum insulin (mu U/ml)  
  - BMI: Body Mass Index  
  - DiabetesPedigreeFunction: Indicates genetic predisposition to diabetes  
  - Age: Age of the patient

## ⚙️ Preprocessing
- Handled missing values (replaced zeros with median)
- Outlier handling using IQR-based capping
- Feature scaling using StandardScaler

## 🤖 Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)

## 📈 Results
- Logistic Regression Accuracy: ~70%
- KNN Accuracy: ~73%

KNN performed better in detecting diabetic cases.

## 📌 Conclusion
KNN showed better performance, indicating non-linear relationships in the dataset. However, both models struggled with identifying all diabetic cases.

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🚀 Future Improvements
- Hyperparameter tuning
- Trying advanced models (Random Forest, XGBoost)
- Improving recall for diabetic cases
