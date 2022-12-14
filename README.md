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

The balanced accuracy score is 63%. The high_risk precision is about 1% while the recall is at 62% and due to the larger population size the low_risk precision is 100% while the recall is at 68%.

### SMOTE Oversampling 100
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/SMOTE_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/SMOTE_imbalanced_classification_report.png?raw=true)

The balanced accuracy score is 63%. The high_risk precision is about 1% while the recall is at 62% and the low_risk precision is 100% while the recall is at 63%.

### Undersampling
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Under_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Under_imbalanced_classification_report.png?raw=true)

The balanced accuracy score is 51%. The high_risk precision is about 1% while the recall is at 59% and the low_risk precision is 100% while the recall is at 43%.

### Combination Sampling
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Comb_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Comb_imbalanced_classification_report.png?raw=true)

The balanced accuracy score is 62%. The high_risk precision is about 1% while the recall is at 70% and the low_risk precision is 100% while the recall is at 54%.

### Balanced Random Forest Classifier
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/BRFC_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/BRFC_imbalanced_classification_report.png?raw=true)

The balanced accuracy score is 79%. The high_risk precision is about 4% while the recall is at 67% and the low_risk precision is 100% while the recall is at 91%.

### Easy Ensemble AdaBoost Classifier
#### Balanced Accuracy Score
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/EEAC_balanced_accuracy_score.png?raw=true)
#### Imbalanced Classification Report
![image](https://github.com/awill1786/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/EEAC_imbalanced_classification_report.png?raw=true)

The balanced accuracy score is 93%. The high_risk precision is about 7% while the recall is at 91% and the low_risk precision is 100% while the recall is at 94%.

## Summary

In Summary, the Naive Random Oversampling, SMOTE Oversampling, Undersampling, and Combination models have all have relatively low recall scores for the high_risk catagory with the highest being from the Naive Random Oversampling at 68%. The next best model out of the six machine learning models used, was the Balanced Random Forest Classifier model. The high_risk precision rose to 4%, however the recall remained low at 67%. The best out of the models, and earning my recommendation was the Easy Ensemble AdaBooster Classifier with a high_risk precision score of 7% and a recall score of 91%. This model also performed the best out of all of the models when predicting the low_risk catagory as well with a precision of 100% and a recall of 94%.
