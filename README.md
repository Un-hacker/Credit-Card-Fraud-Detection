# Credit-Card-Fraud-Detection
📌 Overview

This project focuses on building a Machine Learning model to detect fraudulent credit card transactions. Fraud detection is a critical task in financial services where the goal is to minimize false negatives (frauds that go undetected) while also keeping false positives low.
We use the Credit Card Fraud dataset, preprocess and normalize the data, handle class imbalance with resampling techniques, and train multiple classification models (Logistic Regression & Random Forest). <br/>

🚀 Features

-Data preprocessing & normalization<br/>
-Handling class imbalance using SMOTE<br/>
-Training models: Logistic Regression & Random Forest<br/>
-Evaluation using Precision, Recall, F1-score & Confusion Matrix<br/>
-Feature importance visualization<br/>

📂 Dataset

The dataset used is the Kaggle Credit Card Fraud Detection Dataset, which contains:<br/>
-Transactions made by European cardholders in September 2013.<br/>
-284,807 transactions in total.<br/>
-Only 492 frauds (0.172%), making it highly imbalanced.<br/>

🛠️ Technologies Used

Python 3<br/>
Libraries:
  pandas, numpy → data preprocessing<br/>
  scikit-learn → model building<br/>
  imbalanced-learn (SMOTE) → handling imbalance<br/>
  matplotlib, seaborn → visualization<br/>

⚙️ Steps in the Project

1.Data Preprocessing<br/>
  Handled missing values<br/>
  Normalized transaction features<br/>
2.Handling Class Imbalance<br/>
  Used SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.<br/>
3.Model Training<br/>
  Logistic Regression<br/>
  Random Forest Classifier<br/>
4.Model Evaluation<br/>
  Confusion Matrix<br/>
  Precision, Recall, F1-score<br/>
  Feature importance visualization<br/>

📊 Results

-Best performing model: Random Forest Classifier<br/>
-Achieved high recall, meaning fewer fraudulent transactions go undetected.<br/>
-Logistic Regression performed decently but was outperformed by Random Forest.<br/>

