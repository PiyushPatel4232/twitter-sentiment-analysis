# Employee Attrition Prediction Using Random Forest

## Overview  
This project focuses on predicting employee attrition using machine learning techniques, specifically Random Forest. The dataset is preprocessed, feature selection is performed, and a classification model is built to identify key factors influencing attrition.

## Dataset  
- **train.csv** - Contains labeled employee data for training.  
- **test.csv** - Contains unlabeled employee data for testing.  

## Steps Involved  
1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical features using Label Encoding  
   - Standardizing numerical features using StandardScaler  

2. **Feature Selection**  
   - Identifying the top 10 most important features using Random Forest  

3. **Model Training & Evaluation**  
   - Training a Random Forest Classifier  
   - Evaluating performance using Confusion Matrix, Accuracy Score, ROC AUC Score  

## Requirements  
Install the required libraries using:  
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
