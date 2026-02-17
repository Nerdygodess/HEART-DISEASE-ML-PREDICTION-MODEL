# Heart Disease Prediction using Machine Learning

## Project Overview
Heart disease is one of the leading causes of death worldwide. Early prediction can help doctors take preventive measures and improve patient survival chances.

This project uses Machine Learning algorithms to predict whether a patient has heart disease based on medical attributes such as age, chest pain type, cholesterol level, blood pressure, etc.

The model is trained on a publicly available Kaggle dataset and evaluated using accuracy score and confusion matrix.

##  Problem Statement
To build a machine learning model that predicts the presence of heart disease in a patient using medical data.

## Machine Learning Type
**Supervised Learning — Classification**

Output:
- `0` → No Heart Disease
- `1` → Heart Disease Present

## Dataset Information
Dataset Source: Kaggle – Heart Disease Dataset

Features include:
- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Rest ECG (restecg)
- Maximum Heart Rate (thalach)
- Exercise Induced Angina (exang)
- Oldpeak
- Slope
- Number of Major Vessels (ca)
- Thalassemia (thal)

Target:
- `target` → Heart disease presence
- 
## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- 
## Steps Performed

### 1. Data Exploration
- Loaded dataset
- Checked rows and columns
- Checked missing values
- Displayed first five rows

### 2. Data Visualization
- Age distribution graph
- Heart disease count plot
- Chest pain vs disease graph
- Correlation heatmap

### 3. Data Preprocessing
- Feature and target separation
- Train-test split (80% training, 20% testing)

### 4. Model Training
Algorithms used:
- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)

### 5. Model Evaluation
- Accuracy Score
- Confusion Matrix

### 6. Real Time Prediction
Prediction performed for a new patient sample.
## Results
| Algorithm | Accuracy |
|--------|------|
| Logistic Regression | (Your Accuracy) |
| Decision Tree | (Your Accuracy) |
| KNN | (Your Accuracy) |
## 🔍 Confusion Matrix
The confusion matrix shows correct and incorrect predictions made by the model.
## 💡 Conclusion
The machine learning model successfully predicts the presence of heart disease using patient medical data. Logistic Regression provided reliable performance for this classification problem.

This system can help in early detection and assist doctors in decision making.

## 🚀 How to Run the Project

1. Install dependencies:
2. Run Jupyter Notebook:
3. Open: 
4. Run all cells.

## 📁 Project Structure
Heart-Disease-Prediction/
│── heart.csv
│── heart_disease.ipynb
│── README.md

Name: Ujjawala R Singh 
Course: B.E CSE  
Subject: Machine Learning Lab Assignment

