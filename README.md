# Credit_Risk_Analysis

## Analysis Overview
The purpose of this analysis is to predict credit risk using different machine learning models. In this analysis we will oversample the data using the Random Over Sample and SMOTE algorithms, undersample using the ClusterCentroids algorithm, a combination approach with over and undersampling using the SMOTEEN algorithm, and then reduce bias with the BalancedRandomForestClassifier and EasyEnsembleClassifier algorithms. We will evaluate the performance of each model and then make a recommendation on which one can be used to predict credit risk.
### Resources
- Dataset: LoanStats_2019Q1.csv
Software: Python 3.7.9, Jupyter Notebook 6.0.3, Anaconda Navigator 1.9.12, Conda 4.8.4
## Results
### Naive Random Oversampling
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/NRO_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/NRO_imbalanced_classification_report.png?raw=true)
### SMOTE Oversampling
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/SMOTE_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/SMOTE_imbalanced_classification_report.png?raw=true)
### Undersampling
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Under_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Under_imbalanced_classification_report.png?raw=true)
### Combination Sampling
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Comb_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Comb_imbalanced_classification_report.png?raw=true)
### Balanced Random Forest Classifier
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/BRFC_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/BRFC_imbalanced_classification_report.png?raw=true)
### Easy Ensemble AdaBoost Classifier
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/EEAC_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/EEAC_imbalanced_classification_report.png?raw=true)
## Summary
