# Credit Risk Analysis

## Overview
The purpose of this analysis was to use machine learning techniques to predict credit risk. Specific supervised machine learning techniques were employed due to the imbalanced nature of credit risk; good loans far outnumber bad loans. 

### Resources
- Data: A dataset from LendingClub, a peer-to-peer lending services company, was used for the analysis. 
- Tools: Python, skikit-learn, imbalanced-learn

### Analysis
The following techniques were used and compared:
- Use RandomOverSampler and SMOTE to oversample the data
- Use ClusterCentroids to undersample the data
- Use SMOTEEN for a combination under- and oversampling approach
- Use BalancedRandomForestClassifier and EasyEnsembleClassifier to reduce bias

The above algorithms were employed and results compared. Recommendations were then made based on the performance of the models.

## Results
The models were compared by their balanced accuracy score, precision, and recall. See results below. H represents the high-risk class and L represents the low-risk class. 

### Oversampling with RandomOverSampling
* Balanced accuracy score: 0.6403
* Precision: H = .01, L = 1.00
* Recall: H = .57, L = .71

### Oversampling with SMOTE
* Balanced accuracy score: .6417
* Precision: H = 0.01, L = 1.00
* Recall: H = 0.63, L = 0.65

### Undersampling with ClusterCentroids
* Balanced accuracy score: 0.5103
* Precision: H = 0.01, L = 1.00
* Recall: H = 0.59, L = 0.43

### Combination Sampling with SMOTEEN
* Balanced accuracy score: 0.6618
* Precision: H = 0.01, L = 1.00
* Recall: H = 0.72, L = 0.60

### Reduce Bias with BalancedRandomForestClassifier
* Balanced accuracy score: 0.7876
* Precision: H = 0.04, L = 1.00
* Recall: H = 0.67, L = 0.91

### Reduce Bias with EasyEnsembleClassifier
* Balanced accuracy score: 0.9254
* Precision: H = 0.07, L = 1.00
* Recall: H = 0.91, L = 0.94


## Summary

### All Models
![Screenshot 2023-03-29 at 8 09 14 PM](https://user-images.githubusercontent.com/109118631/228701987-1787f36c-2830-44de-9a93-c9187687ff15.png)


### Sampling Models
Across the four sampling models, the balanced accuracy scores are poor (under 70%). Precision across the models is also very similar. For the high-risk class, precision is 1% and for the low-risk class it is 100%. There is some variation in the recall or sensitivity of the models.  

### Reduced Bias Models

### Recommendation
