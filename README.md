# Obesity Level Classification Using Machine Learning
## Overview
This project applies machine learning techniques to classify individuals into different obesity levels based on demographic, dietary, and lifestyle factors. The aim is to compare model performance and identify an accurate and reliable classifier for multi-class obesity prediction.

## Dataset used
Source: UCL Machine Learning Repository Data includes anonymized lifestyle, dietary, and physical attributes

Target variable: Obesity Level (multi-class classification)

## Methods
Exploratory Data Analysis
Data inspection and visualisation
Identification of class distribution
Detection of potential outliers
Data Preprocessing
Encoding categorical variables
Feature scaling
Outlier handling
Feature Selection
SelectKBest used to identify the most relevant predictors.

## Models implemented:
Logistic Regression 
Random Forest Classifier

## Hyperparameter Tuning
GridSearchCV used to optimise model parameters.

## Model Evaluation
Models were evaluated using:
Accuracy
Precision
Recall
F1-score
Confusion Matrix

## Results
Logistic Regression Test Accuracy: ~91% Random Forest Test Accuracy: ~94% 
Random Forest outperforms Logistic Regression across most obesity classes Most misclassifications occur between adjacent obesity levels

## Ethical Considerations
Dataset is publicly available and anonymized No personal or sensitive information is used Models are intended for decision support, not medical diagnosis Bias is assessed using per-class performance metrics

## Technologies
Python Pandas, NumPy Scikit-learn Matplotlib, Seaborn Jupyter Notebook

## Conclusion
The project shows that ensemble models, particularly Random Forest, can effectively classify obesity levels using lifestyle data, offering valuable insights for health-related decision support.
