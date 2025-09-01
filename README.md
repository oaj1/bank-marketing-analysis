# bank-marketing-analysis

## 📌 Project Overview
This project analyzes the **Portuguese Bank Marketing dataset** (UCI Machine Learning Repository) to predict whether a customer will subscribe to a term deposit after a marketing campaign.  

The goal is to build an **interpretable logistic regression model** that helps the bank identify the types of customers most likely to convert, improving resource allocation and marketing efficiency.  

---

## ⚙️ Key Steps

### 1. Data Preparation
- Load and clean the dataset  
- Handle categorical and numeric features  
- Perform feature selection for interpretability  

### 2. Exploratory Data Analysis (EDA)
- Examine key variables and their relationship with conversion (`y`)  
- Identify trends in employment, age, previous contact, and campaign-related variables  

### 3. Modeling
- Logistic Regression with selected features  
- Train-test split for validation  
- Threshold adjustment to optimize recall vs. precision  
- Evaluate using metrics: Accuracy, Precision, Recall, F1-score, and ROC-AUC  

### 4. Interpretation
- Emphasis on **recall**: capturing as many true subscribers as possible  
- Business implications of **false positives vs. false negatives**  
- Feature insights: which customer characteristics increase or decrease likelihood of subscription  

---

## 📊 Results
The logistic regression model provides:  
- Conversion likelihood per customer  
- Key drivers of subscription  
- Balanced evaluation using cross-validation and threshold tuning  
- Practical recommendations for improving marketing outreach efficiency  

---

## 🛠️ Tech Stack
- **Python**: pandas, numpy, scikit-learn, matplotlib, seaborn  
- **Jupyter Notebook**: interactive analysis and reporting  

