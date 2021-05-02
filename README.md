# Credit_Risk_Analysis
## Overview
In this project we use Python to build various machine learning models to evaluate and predict credit risk. 
Following are the various models we used to compare the accuracy scores the evalute the right model for this kind of data.
* Oversampling the data using **RandomOverSampler** and SMOTE algorithm
* Undersampling the data using **ClusterCentroids** algorithm
* Over & Undersampling using **SMOTEENN** algorithm
* Camparing 2 models that reduce bias, **BalancedRandomForestClassifier** and **EasyEnsembleClassifier**

We will also review the performance of each model and make a recommendation on which model would best fit for predicting credit risk analysis

## Resources
* CSV data file - LoanStats_2019Q1.csv
* Python 3.7.9, mlenv Virtual python environment using Anoconda
* Jupyter Notebook as the IDE

## Results

### *RandomOverSampler Model*

This model shows very low precision on **High Risk** accuracy score with a 75% **Sensitivity** and 100% **Low Risk** precision, hence this model is not a recommended and would need to evaluate other models to reach default accuracy rate.

![ModelUsed](images/RandonOverSampler1.png)
![RandomOverSampler-Output](images/RandonOverSampler2.png)


### *SMOTE Model*

This model shows very low precision on **High Risk** accuracy score with a 62% **Sensitivity** and 100% **Low Risk** precision, hence this model is not a recommended and would need to evaluate other models to reach default accuracy rate.

![SMOTEModel](images/SMOTE1.png)
![SMOTE-Output](images/SMOTE2.png)

### *ClusterCentroid Model*

### *SMOTEENN Model*

### *BalncedRandomForestClassfier Model*

### *EasyEnsembleClassifier Model*



## Summary
