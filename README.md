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
The models were compared by their balanced accuracy score, precision, and recall. See results below.

### Oversampling with RandomOverSampling
* Balanced accuracy score:
* Precision:
* Recall:

### Oversampling with SMOTE
* Balanced accuracy score:
* Precision:
* Recall:

### Undersampling with ClusterCentroids
* Balanced accuracy score:
* Precision:
* Recall:

### Combination Sampling with SMOTEEN
* Balanced accuracy score:
* Precision:
* Recall:

### Reduce Bias with BalancedRandomForestClassifier
* Balanced accuracy score:
* Precision:
* Recall:

### Reduce Bias with EasyEnsembleClassifier
* Balanced accuracy score:
* Precision:
* Recall:

## Summary
