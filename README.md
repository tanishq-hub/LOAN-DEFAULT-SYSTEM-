Loan - Default - System 

By Tanishq Sharma
! Project Overview

This project predicts loan approval status based on applicant information such as income, education, credit history, loan amount, and other financial factors.
It uses Machine Learning (Random Forest Classifier) to classify whether a loan will be approved (Y) or not approved (N).

Dataset used: Loan Prediction Dataset (train.csv)

⚙️ Tech Stack
Python 3
Pandas, NumPy → Data handling & preprocessing
Scikit-learn → Model training & evaluation
Matplotlib, Seaborn → Visualization
Google Colab / Jupyter Notebook → Development

🛠️ Steps Implemented
Data Loading & Exploration
Loaded dataset (train.csv)
Checked missing values, data types, distributions
Data Preprocessing
Dropped unnecessary Loan_ID column
Handled missing values (mode for categorical, median for numeric)
Converted categorical columns to numeric using One-Hot Encoding
Feature Selection & Target Variable
Features (X): ApplicantIncome, CoapplicantIncome, LoanAmount, Credit_History, etc.
Target (y): Loan_Status (Y/N → converted to binary)
Model Training
Train-Test Split (80/20)
Standardization with StandardScaler
Trained Random Forest Classifier with 200 trees
Evaluation
Accuracy: ~85%
Confusion Matrix
Classification Report (Precision, Recall, F1-Score)

Visualization
Confusion Matrix Heatmap
Feature Importance Plot

📊 Results
Accuracy: ~85%
Model predicts loan approval with good precision and recall

Most Important Features:
Credit History
Loan Amount
Applicant Income
Education & Employment Status

🚀 How to Run
1. Clone the repository
git clone https://github.com/your-username/loan-prediction.git
cd loan-prediction

2. Install dependencies
pip install -r requirements.txt

3. Run in Jupyter/Colab
jupyter notebook MINOR_PROJECT.ipynb
