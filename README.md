# bank-marketing-analysis

📌 Project Overview

          -This project analyzes the Portuguese Bank Marketing dataset (UCI Machine Learning Repository) to predict whether a customer will subscribe to a term deposit after a marketing campaign.
          
          -The goal is to build an interpretable logistic regression model that helps the bank identify the types of customers most likely to convert, improving resource allocation and marketing efficiency.

⚙️ Key Steps

          -Data Preparation
          
          -Loading and cleaning the dataset.
          
          -Handling categorical and numeric features.
          
          -Feature selection for more intuitive interpretation.
          
          -Exploratory Data Analysis (EDA)
          
          -Examining key variables and their relationship with conversion (y).
          
          -Identifying trends in employment, age, previous contact, and campaign-related variables.
  
          -Modeling
          
          -Logistic Regression with selected features.
          
          -Train-test split for validation.
          
          -Threshold adjustment to optimize recall vs precision.
          
          -Evaluation using metrics: Accuracy, Precision, Recall, F1-score, and ROC-AUC.
          
          -Interpretation
          
          -Emphasis on recall: capturing as many true subscribers as possible.
          
          -Business implications of false positives vs false negatives.
          
          -Feature insights: which customer characteristics increase or decrease likelihood of subscription.

📊 Results

          -A logistic regression model that provides:
          
          -Conversion likelihood per customer.
          
          -Key drivers of subscription.
          
          -Balanced evaluation using cross-validation and threshold tuning.
          
          -Practical recommendations for improving marketing outreach efficiency.

🛠️ Tech Stack

        -Python: pandas, numpy, scikit-learn, matplotlib, seaborn
        
        -Jupyter Notebook for interactive analysis
