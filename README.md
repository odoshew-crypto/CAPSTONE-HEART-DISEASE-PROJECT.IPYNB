# CAPSTONE-HEART-DISEASE-PROJECT.IPYNB
Heart Disease Prediction Capstone Project
 Project Overview

This project uses Machine Learning to predict whether a patient is at risk of heart disease based on medical data. It is a classification problem where the model predicts:

0 → No Heart Disease
1 → Heart Disease

The goal is to help in early detection and risk assessment using data-driven methods.

 Dataset
Source: Kaggle 
Type: Medical dataset
Target Variable: HeartDisease
Features include:
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
Max Heart Rate
Oldpeak
Exercise Induced Angina
 Technologies Used
Python 
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Machine Learning Models Used
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
 Workflow
1. Data Loading

Loaded dataset using Pandas.

2. Data Cleaning
Checked missing values
Handled categorical data using Label Encoding
3. Exploratory Data Analysis (EDA)
Correlation heatmap
Target distribution plot
4. Feature Engineering
Label Encoding for categorical variables
Feature scaling using StandardScaler
5. Model Training

Split data into:

Training set (80%)
Testing set (20%)

Trained multiple models for comparison.

 Evaluation Metrics

The models were evaluated using:

Accuracy Score
Confusion Matrix
Precision
Recall
F1-Score

These metrics help understand model performance, especially in medical prediction tasks.

Hyperparameter Tuning

Used GridSearchCV to improve Random Forest performance by testing different combinations of:

n_estimators
max_depth
min_samples_split
 Results
Random Forest performed best among all models
Hyperparameter tuning improved accuracy
Confusion matrix showed strong classification performance
 Model Saving

The final trained model was saved using:

joblib.dump(model, 'heart_disease_model.pkl')
 How to Run the Project
Clone the repository

Install dependencies:

pip install -r requirements.txt

Run Jupyter Notebook:

jupyter notebook
Open the project file and run cells step by step
 Key Learnings
Data preprocessing is very important in ML
Feature scaling improves model performance
Recall is critical in medical prediction problems
Hyperparameter tuning improves accuracy significantly
👨‍💻 Author

Kennedy Juma
