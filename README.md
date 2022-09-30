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
**1. Naive Random Oversampling**
- The balanced accuracy score for Random Oversampling was 0.576. 
- The precision for classifying low risk applicants was perfect, a score of 1. However, the precision for classifying high risk applicants was poor, at .01. 
- The recall (sensitivity) score was .53 for low risk and .62 for high risk.
![image](https://user-images.githubusercontent.com/104038813/193288912-bd967001-8e0f-43b6-9665-e086fa0ab6b1.png)

**2. SMOTE Oversampling**
- The balanced accuracy score for SMOTE Oversampling was 0.607. 
- The precision for classifying low risk applicants was perfect, a score of 1. However, the precision for classifying high risk applicants was poor, at .01. 
- The recall (sensitivity) score was .67 for low risk and .54 for high risk.
![image](https://user-images.githubusercontent.com/104038813/193289246-51328f02-2be1-4154-954e-f974490a7cfc.png)

**3. Cluster Centroids Undersampling**
- The balanced accuracy score for Cluster Centroids Undersampling was 0.580. 
- The precision for classifying low risk applicants was perfect, a score of 1. However, the precision for classifying high risk applicants was poor, at .01. 
- The recall (sensitivity) score was .47 for low risk and .54 for high risk.
![image](https://user-images.githubusercontent.com/104038813/193289726-b6aafd1e-b8e0-4cc1-885d-004ab26919d5.png)

**4. SMOTEENN Combination Sampling**
- The balanced accuracy score for Cluster Centroids Undersampling was 0.504. 
- The precision for classifying low risk applicants was perfect, a score of 1. However, the precision for classifying high risk applicants was poor, at .01. 
- The recall (sensitivity) score was .49 for low risk and .67 for high risk.
![image](https://user-images.githubusercontent.com/104038813/193290080-4de71711-689b-49e7-ad84-b2b330c113d1.png)

**5. Balanced Random Forest Classifier**
- The balanced accuracy score for Cluster Centroids Undersampling was 0.788. 
- The precision for classifying low risk applicants was perfect, a score of 1. However, the precision for classifying high risk applicants was poor, at .04. 
- The recall (sensitivity) score was .91 for low risk and .67 for high risk.
- The priority feautures that were determined using this algorithm were "total_rec_prncp" and "total_rec_int" meaning that the principal and interest on recent loans is valued very high in determining credit risk. 
![image](https://user-images.githubusercontent.com/104038813/193290492-73636928-0e4b-45e7-8814-bc2c214dd5c5.png)







### Resources
- R Version 4.2.1, R Studio
- MSU Bootcamp Module 15: https://courses.bootcampspot.com/courses/2508/assignments/31929?module_item_id=637258
