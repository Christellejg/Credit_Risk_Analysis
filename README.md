# Credit_Risk_Analysis

## Overview:
In this analysis, I applied machine learning techniques and used scikit-learn and imbalanced-learn to train to determine credit card risk. The credit card credit dataset from LendingClub was provided and I oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compare BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk. The purpose is to evaluate the performance of these models and make a  recommendation on whether LendingClub should be used to predict credit risk.

## Results:
### Naive Random Oversampling
![image](https://user-images.githubusercontent.com/78320504/169443700-84326ef5-7bae-4bf9-a539-18fafbc012d3.png)

The balanced accuracy score is about 65%, precision high risk is 1%, precision low risk is 100%, recall high-risk is 62%, and recall low-risk is 68%.

### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/78320504/169444359-3e34733c-2955-4229-bd82-349879c8ed2d.png)

The balanced accuracy score is about 64%, precision high risk is 1%, precision low risk is 100%, recall high-risk is 63%, and recall low-risk is 66%.

### Undersampling
![image](https://user-images.githubusercontent.com/78320504/169444835-fa4aaac4-6678-474b-9987-d4e1e80128e3.png)

The balanced accuracy score is 52%, precision high risk is 1%, precision low risk is 100%, recall high-risk is 60%, and recall low-risk is 43%.

### Combination (Over and Under) Sampling (SMOTEENN)
![image](https://user-images.githubusercontent.com/78320504/169445226-4783ca51-2dd1-42a4-93e2-cebaee3d2ac6.png)

The balanced accuracy score is about 52%, precision high risk is 1%, precision low risk is 100%, recall high-risk is 60%, and recall low-risk is 43%.

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/78320504/169445630-7196a1c8-f7ef-407b-8c61-bf1731f68b67.png)

The balanced accuracy score is about 79%, precision high risk is 4%, precision low risk is 100%, recall high-risk is 67%, and recall low-risk is 91%.

### Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/78320504/169445945-610f6d5a-b6ac-4944-a622-f09278a7cd95.png)

The balanced accuracy score is about 93%, precision high risk is 7%, precision low risk is 100%, recall high-risk is 91%, and recall low-risk is 94%.

## Summary:
After looking at all the results, I can conclude that the best machine learning model to use would be the Easy Ensemble AdaBooost Classifier. It had the highest Balanced Accuracy Score of 93%. It also has a high recall scores for both high and low risk loans. Overall, this would be the model that I would used to assess credit risk.



