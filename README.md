# Credit Risk Analysis using Supervised Machine Learning

## Purpose
- The purpose of this project is to demonstrate skills using Supervised Machine Learning algorithms such as Logistic Regression, Decision Trees, Ensemble Learning and Bootstrap Aggregation.
- Credit application data was cleaned, normalized, and analyzed to determine applicant credit risk using machine learning models.   

## Project Overview
- A machine learning environment was created to test linear regression and logistic regression models for various datasets, including credit card applicants. 
- Statistical tests were performed to assess machine learning model validation, such as Accuracy, Precision, Sensitivity, and a Confusion Matrix. 


### Challenge Overview
- Credit card applicant data was resampled using Oversampling and Undersampling methods due to the imbalance of high risk to low risk applicants, and then credit risk was predicted using logistic regression models. 
- Ensemble classifiers were executed to predict credit risk, such as the Balanced Random Forest Classifier and the Easy Ensemble Classifier. 

## Results
**1. Naive Random Oversampling ** 
- The balanced accuracy score for Random Oversampling was 0.576. 
- The precision for classifying low risk applicants was perfect, a score of 1. However, the precision for classifying high risk applicants was poor, at .01. 
- The recall (sensitivity) score was .53 for low risk and .62 for high risk.
![image](https://user-images.githubusercontent.com/104038813/193288912-bd967001-8e0f-43b6-9665-e086fa0ab6b1.png)

**2. SMOTE Oversampling **
- 


### Resources
- R Version 4.2.1, R Studio
- MSU Bootcamp Module 15: https://courses.bootcampspot.com/courses/2508/assignments/31929?module_item_id=637258
