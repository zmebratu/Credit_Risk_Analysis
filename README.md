# Credit_Risk_Analysis

## Purpose
The purpose of this project was to predict credit risk using machine learning. The credit card dataset obtained for this task, was from a lending services company called LendingClub. The data will be oversampled and undersampled using RandomOverSampler, SMOTE and ClusterCentroids algorithm. From there machine learning models such as, BalancedRandomForestClassifier and EasyEnsembleClassifier will be used to further predict credit risk. The findings should then allow me to evaluate which unbiased model performed the best.

## Results

In total, 6 machine learning models were used 

### 1. Naive Random Oversampling
* The balanced accuracy score was 64%
* The precision score had a high risk of 0.01 and a low risk of 1.00
* The recall score had a high risk of 0.60 and a low risk of 0.68

![plot](Pictures/Naive_Random_Oversampling.png) 


### 2. SMOTE Oversampling
* The balanced accuracy score was 63%
* The precision score also had a high risk of 0.01 and a low risk of 1.00
* The recall score also had a high risk of 0.60 and a low risk of 0.68

![plot](Pictures/SMOTE.png) 


### 3. Cluster Centroids Undersampling
* The balanced accuracy score of 64%
* The precision score with a high risk of 0.01 and a low risk of 1.00
* The recall score with a high risk of 0.60 and a low risk of 0.68

![plot](Pictures/CC.png) 


### 4. Combination (Over and Under) Sampling
* The balanced accuracy score was 63%
* The precision score also had a high risk of 0.01 and a low risk of 1.00
* The recall score also had a high risk of 0.70 and a low risk of 0.57

![plot](Pictures/combination.png) 


### 5. Balanced Random Forest Classifier
* The balanced accuracy score was 67%
* The precision score also had a high risk of 0.90 and a low risk of 1.00
* The recall score also had a high risk of 0.35 and a low risk of 1.00

![plot](Pictures/Forest.png) 


### 6. Easy Ensemble AdaBoost Classifier
* The balanced accuracy score was 92%
* The precision score also had a high risk of 0.90 and a low risk of 1.00
* The recall score also had a high risk of 0.89 and a low risk of 0.94

![plot](Pictures/AdaBoost.png) 


## Summary
After conducting the analysis, the model that performed the best was the Easy Ensemble AdaBoost Classifier. This model had an accuracy score of 92% which beats out all other models(accuracy score of < 70%) conducted in this analysis.