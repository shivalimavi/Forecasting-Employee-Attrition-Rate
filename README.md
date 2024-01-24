# Forecasting-Employee-Attrition-Rate



## Abstract
This project aims to develop a predictive model to identify factors contributing to employee attrition in a company. The team employs exploratory data analysis, regression models (e.g., logistic regression, random forest), and showcases skills in data wrangling, visualization, and machine learning. The outcome can assist organizations in identifying attrition risks and retaining key employees.

## Introduction
The project predicts employee attrition using regression analysis on a dataset with 14,999 records and 10 features. Exploratory data analysis explores the impact of factors like work accidents, satisfaction levels, and salary on attrition. Logistic regression and classification algorithms are used for binary classification.

## Dataset Description
The dataset, sourced from Kaggle, contains information on employees in CSV format. Features include satisfaction level, last evaluation, number of projects, average monthly hours, time spent in the company, work accidents, promotion in the last 5 years, department, and salary. The binary target variable 'left' indicates employee departure.

## Data Preprocessing
Data preparation involves treating null values, encoding categorical variables, and splitting the dataset into training and testing sets (80-20 split). Feature engineering includes drawing correlation matrices and using a Random Forest Classifier to identify important features.

## Exploratory Data Analysis
Visualizations reveal key factors contributing to attrition risks, such as overworked employees and those completing a 5-year term. Attrition rates are influenced by salary, number of projects, time spent in the company, and average monthly hours.

## Models
Various models, including logistic regression, random forest, KNN, Gaussian Naive Bayes, and Support Vector Machine, are employed. Models are assessed based on accuracy, precision, recall, F1-score, and ROC-AUC. The Random Forest Classifier performs best with 99.2% accuracy.

## Model Evaluation
Models are evaluated on all features, important features, and grid CV variations. Random Forest Classifier and K-nearest neighbor achieve over 94% accuracy. Gaussian Naive Bayes performs well, while logistic regression underperforms.

## Limitations and Conclusion
Acknowledging potential bias in the target variable, the study suggests using additional metrics like AUC ROC score, sensitivity, specificity, and f-1 score. The report concludes by emphasizing the importance of identifying attrition risks for strategic employee retention.
