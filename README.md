# Loan_Default_Prediction

**Overview**
This project focuses on predicting loan defaults using historical loan application data. The goal is to analyze financial factors, detect patterns in loan repayments, and develop a predictive model that helps financial institutions assess credit risk.
This marks my second hands-on data analytics project, where I further explored data preprocessing, feature engineering, model selection, and evaluation techniques. It was a step forward in improving my skills in machine learning and predictive analytics.
The dataset was sourced from Kaggle: https://www.kaggle.com/datasets/yasserh/loan-default-dataset

**Project Objectives**
Analyze Borrower Trends: Identify key financial and demographic factors influencing loan defaults.
Predict Loan Defaults: Use machine learning techniques to classify whether a loan is likely to default.
Optimize Model Performance: Experiment with different models, address class imbalance, and improve predictions through fine-tuning.

**Technical Approach** 

**Data Cleaning & Preprocessing**
Handled missing values, outliers, and inconsistent data.
Encoded categorical variables and normalized numerical features.

**Exploratory Data Analysis (EDA)**
Analyzed key financial metrics (income, loan amount, interest rates).
Visualized correlations and identified risk factors for defaults.

**Model Training & Evaluation**
Started with Logistic Regression, but it struggled with class imbalance.
Switched to Random Forest, which initially overfitted (100% accuracy).
Applied techniques like class weighting, feature selection, and hyperparameter tuning to balance precision and recall.

**Final Model Performance**
Achieved 97.29% accuracy while maintaining a recall of 1.00 for loan defaults.
The model effectively predicts high-risk loan applicants while minimizing false positives.

**Learning Experience**
Although I had previous experience with Python and machine learning, this project was my first deep dive into handling imbalanced datasets and fine-tuning predictive models.
* Iterative Learning: Faced challenges with model overfitting and bias, requiring multiple adjustments.
* Problem-Solving Mindset: Explored different techniques (SMOTE, class weighting, hyperparameter tuning) to improve performance.
* Hands-On Experience: This project reinforced my ability to clean real-world data, build robust models, and evaluate performance effectively.

**Acknowledgments**
I am grateful for the online resources, tutorials, and open-source datasets that helped guide this project. This has been another milestone in my data analytics journey, and I look forward to refining my skills with more advanced projects.
Feel free to explore the code, check out the project files, and leave any feedback or suggestions! 
