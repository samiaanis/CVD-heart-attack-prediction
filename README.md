# ❤️ Cardiovascular Disease Analysis & Heart Attack Prediction (Python)

## 📝 Project Overview

Cardiovascular diseases (CVD) remain one of the leading causes of death globally. This project aims to perform a detailed analysis of health-related factors contributing to heart attacks and build a predictive model to help identify patients at risk. The dataset includes medical attributes of over 4,000 individuals.

---

## 📁 Dataset

**File**: `cvd.ipynb`  
**Domain**: Healthcare / Predictive Modeling  
**Source**: Simulated CVD patient dataset  
**Size**: 4,000+ records with 14 attributes  
**Target Variable**: `target` (presence or absence of heart disease)

| Feature         | Description                                     |
|------------------|-------------------------------------------------|
| age             | Age of the patient                              |
| sex             | Gender (0 = Female, 1 = Male)                   |
| cp              | Chest pain type                                 |
| trestbps        | Resting blood pressure                          |
| chol            | Serum cholesterol (mg/dl)                       |
| fbs             | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| restecg         | Resting ECG results                             |
| thalach         | Maximum heart rate achieved                     |
| exang           | Exercise-induced angina (1 = yes; 0 = no)       |
| oldpeak         | ST depression induced by exercise               |
| slope           | Slope of the peak exercise ST segment           |
| ca              | Number of major vessels (0–3) colored by fluoroscopy |
| thal            | Thalassemia (0 = normal; 1 = fixed defect; 2 = reversible defect) |
| target          | Heart disease diagnosis (1 = yes, 0 = no)       |

---

## 🎯 Objectives

- Identify and analyze major factors influencing heart disease
- Detect patterns in the dataset using exploratory data analysis
- Build a predictive model to classify patients at risk of CVD

---

## 🛠 Tools & Technologies

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Plotly (optional for visualizations)

---

## ✅ Key Tasks Performed

### 🔹 Data Preprocessing
- Inspected data for missing values, nulls, and duplicates
- Removed duplicates and handled missing values
- Summarized the data using descriptive statistics

### 🔹 Exploratory Data Analysis (EDA)
- Count plots for categorical variables like gender, thalassemia, chest pain
- Age-wise and gender-wise heart attack trends
- Analyzed the effect of resting blood pressure, cholesterol, and peak heart rate
- Explored the role of thalassemia and other risk factors
- Used pair plots and correlation matrices for multivariate insights

### 🔹 Predictive Modeling
- Built a classification model using **Logistic Regression**
- Trained and tested the model on the cleaned dataset
- Evaluated model performance using accuracy, confusion matrix, and ROC curve

---

## 📈 Key Insights

- Males are more likely to be diagnosed with CVD than females in this dataset  
- Higher **cholesterol** and **resting blood pressure** levels correlate with higher CVD risk  
- **Thalassemia**, **chest pain type**, and **exercise-induced angina** show strong relationships with CVD  
- Peak heart rate and ST depression (`oldpeak`) are useful predictors

---

## 📌 How to Run the Notebook

1. Open `cvd.ipynb` using **Jupyter Notebook** or **VS Code**  
2. Make sure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
