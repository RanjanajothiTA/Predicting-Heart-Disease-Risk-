#Predicting Heart Disease Risk Using Machine Learning

#Overview

This project aims to build a machine learning model to predict the likelihood of heart disease based on medical attributes such as age, cholesterol levels, and blood pressure. Using the Heart Disease Dataset, the model classifies patients as either having or not having heart disease. It employs Logistic Regression for classification, with performance evaluation through accuracy, precision, recall, and F1-score metrics.

#Dataset

Source: Heart Disease Dataset on Kaggle

Description:

Rows: 303

Columns: 14 (Features + Target)

#Key Features:

Age: Patient age in years

Sex: Gender (1 = male; 0 = female)

cp (Chest Pain Type): Categorized as 0–3

trestbps (Resting Blood Pressure): Measured in mm Hg

chol (Cholesterol): Serum cholesterol in mg/dl

fbs (Fasting Blood Sugar): > 120 mg/dl (1 = True; 0 = False)

thalach (Maximum Heart Rate Achieved): Numeric value

target: (Dependent Variable) 1 = Disease, 0 = No Disease

#Tools and Libraries

Programming Language: Python

Libraries Used:

Pandas, NumPy: Data handling and preprocessing

Scikit-learn: Model training, evaluation, and scaling

Matplotlib, Seaborn: Visualization

#Project Workflow

#Data Loading:

Load the dataset directly from a URL or local CSV file.

#Data Preprocessing:

Handle missing values, standardize features, and split the dataset into training and testing sets.

#Model Training:

Train a Logistic Regression model.

#Model Evaluation:

Evaluate performance using accuracy, precision, recall, F1-score, and confusion matrix.

Visualization:

Generate visualizations such as feature importance bar plots and confusion matrices.

#Results

Accuracy Achieved: ~85% (may vary based on training and testing splits)

Important Features: Age, Cholesterol, Chest Pain Type, and Maximum Heart Rate.


#Requirements

To run this project, install the dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn


#References

Kaggle Dataset
