# Forecasting-Employee-Attrition-Rate


## Introduction
This project aims to develop a predictive model to identify factors contributing to employee attrition in a company. The team employs exploratory data analysis, regression models (e.g., logistic regression, random forest), and showcases skills in data wrangling, visualization, and machine learning. The outcome can assist organizations in identifying attrition risks and retaining key employees.
The project predicts employee attrition using regression analysis on a dataset with 14,999 records and 10 features. Exploratory data analysis explores the impact of factors like work accidents, satisfaction levels, and salary on attrition. Logistic regression and classification algorithms are used for binary classification. 


## Dataset Description
The dataset, sourced from Kaggle, contains information on employees in CSV format. Features include satisfaction level, last evaluation, number of projects, average monthly hours, time spent in the company, work accidents, promotion in the last 5 years, department, and salary. The target variable is a binary variable, with a value of 1 representing an employee who has left the company and 0 representing an employee who has stayed. It has 14,999 records with 10 features which is suitable for developing a binary classification model to predict employee attrition.

## Data Preprocessing
Data preparation involves treating null values, encoding categorical variables, and splitting the dataset into training and testing sets (80-20 split). As part of the preprocessing process, we also engineer our features to figure out those features that are important for us to determine and predict the attrition rates with the data we have. Feature engineering includes drawing correlation matrices and using a Random Forest Classifier to identify important features.

## Exploratory Data Analysis
Visualizations reveal key factors contributing to attrition risks, such as overworked employees and those completing a 5-year term. Attrition rates are influenced by salary, number of projects, time spent in the company, and average monthly hours.

## Models
Several machine learning methodologies are employed for predictive modeling, including logistic regression, random forest, K-nearest neighbors (KNN), Gaussian Naive Bayes, and Support Vector Machines (SVM). These algorithms analyze correlations between independent and dependent variables to predict employee attrition. Performance evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC are utilized post-training, followed by potential model refinement through hyperparameter adjustment or feature selection.

## Model Evaluation
Performance assessment involves measuring R-squared values on test sets. The Random Forest Classifier demonstrates the highest accuracy at 99.2%. Subsequent phases involve feature engineering, cross-validation, and grid search for hyperparameter tuning. While all models exhibit slight performance improvements with feature selection and cross-validation, significant enhancements, particularly a 20% increase in accuracy, are observed for SVM after grid search.

## Limitations and Conclusion
While our project successfully leverages exploratory and predictive analytics to address HR challenges, it's essential to acknowledge certain limitations. Potential bias in the target variable (employee attrition) and reliance solely on accuracy scores as evaluation metrics might affect the comprehensiveness of our analysis. Alternative metrics like AUC ROC score could provide a more nuanced understanding of model performance.

In conclusion, this project showcases the effective application of machine learning techniques such as logistic regression, random forest, K-nearest neighbors, Gaussian Naive Bayes, and Support Vector Machines in HR analytics. By identifying key factors contributing to employee attrition, our findings offer valuable insights for organizations to strategize employee retention efforts. Despite limitations, our project underscores the significance of data preprocessing, feature engineering, and model evaluation in addressing real-world business challenges.
