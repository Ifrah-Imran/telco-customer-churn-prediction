# 📊 Telco Customer Churn Prediction (Data Mining)

## 📌 Overview
This project analyzes customer churn in a telecom dataset and builds predictive models to identify customers likely to leave the service. The goal is to apply data mining techniques for classification and extract actionable insights from customer behavior.

---

## 📂 Dataset
- Telco Customer Churn Dataset
- Features include:
  - Demographics (gender, senior citizen)
  - Account information (tenure, contract type)
  - Services (internet, phone, streaming)
  - Billing details (monthly charges, total charges)

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Handled missing values
- Converted categorical variables to numerical (encoding)
- Data cleaning and formatting

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Identified patterns in:
  - Contract types
  - Monthly charges
  - Tenure
- Visualized trends using plots

### 3. Feature Engineering
- Selected relevant variables impacting churn
- Prepared dataset for model training

### 4. Model Building
Implemented classification models:
- Logistic Regression
- Decision Tree (or any you used)
- (Add others if applicable)

### 5. Evaluation
- Accuracy score
- Confusion matrix
- Model comparison

---

## 🧠 Key Insights
- Customers with month-to-month contracts showed higher churn
- Higher monthly charges correlated with increased churn probability
- Longer tenure customers were less likely to churn

---

## 🛠 Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## ▶️ How to Run

1. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
