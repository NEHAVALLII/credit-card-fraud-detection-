Credit Card Fraud Detection
 



Project Description

This project implements a credit card fraud detection system using machine learning and deep learning techniques. The goal is to accurately identify fraudulent transactions in a highly imbalanced dataset by applying data preprocessing, feature selection, class balancing, and model optimization.

 

Dataset Information

•	Dataset: Credit Card Transactions (creditcard.csv)
•	Target Variable: Class
o	0 → Non-Fraud
o	1 → Fraud
•	Features:
o	V1–V28: PCA-transformed features
o	Time: Seconds since first transaction
o	Amount: Transaction amount
•	Challenge: Extreme class imbalance between fraud and non-fraud transactions
 


Methodology

1. Exploratory Data Analysis (EDA)
           Dataset inspection and summary statistics
            Class distribution visualization
             Correlation analysis and heatmaps
             Transaction time and amount distribution analysis
2. Feature Selection
              Correlation-based feature elimination
                Removal of low-impact PCA components
3. Handling Class Imbalance
                  Random undersampling
                    SMOTE (Synthetic Minority Oversampling Technique)
                    Performance comparison between imbalanced and balanced datasets
 




Models Implemented

•	Deep Learning
•	Artificial Neural Network (ANN)
o	SGD optimizer (baseline)
o	Adam optimizer
o	Dropout regularization
•	Machine Learning
•	Random Forest (GridSearchCV tuning)
•	Logistic Regression (SMOTE + hyperparameter tuning)
•	Support Vector Machine (SVM with GridSearchCV)

 Evaluation Metrics

Models are evaluated using:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
These metrics are chosen to emphasize fraud detection performance, particularly recall and F1-score.

Results & Comparison

All models are compared using a unified evaluation framework.A final visualization highlights performance differences across:
•	Neural Network (Adam)
•	Random Forest
•	Logistic Regression
•	Support Vector Machine

 How to Run

1.	Open the script/notebook in Google Colab or a local Python environment.
2.	Upload the creditcard.csv dataset when prompted.
3.	Run all cells sequentially.
4.	Review printed metrics and generated visualizations.
Repository Structure

•	├── creditcard.csv 
•	├── 23099463.py 
•	└── README.md 

 Key Learning Outcomes

•	Fraud detection in imbalanced datasets
•	Practical use of SMOTE
•	Comparison of ML vs deep learning models
•	Hyperparameter tuning with GridSearchCV
•	Model evaluation beyond accuracy

Author

Student ID: 23099463

 License

This project is for academic and educational purposes only.

