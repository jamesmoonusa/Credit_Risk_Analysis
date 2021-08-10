# Credit_Risk_Analysis

## Overview
To predict credit risk we can use several machine learning models.  

## Results
1. Random Oversampling Model - [Result](https://github.com/jamesmoonusa/Credit_Risk_Analysis/blob/main/Random%20Oversampling.PNG)
2. SMOTE Oversampling - [Result](https://github.com/jamesmoonusa/Credit_Risk_Analysis/blob/main/SMOTE%20oversampling.PNG)
3. Undersampling - [Result](https://github.com/jamesmoonusa/Credit_Risk_Analysis/blob/main/Undersampling.PNG)
4. Combination (Over and Under) Sampling - [Result](https://github.com/jamesmoonusa/Credit_Risk_Analysis/blob/main/Combinationsampling.PNG)
5. Balanced Random Forest Classifier - [Result](https://github.com/jamesmoonusa/Credit_Risk_Analysis/blob/main/Balanced%20Random%20Forest.PNG)
6. Easy Ensemble AdaBoost Classifier - [Result](https://github.com/jamesmoonusa/Credit_Risk_Analysis/blob/main/Easy%20Ensemble.PNG)
7. **ALL MODEL Result Comparison** - ![Chart](https://github.com/jamesmoonusa/Credit_Risk_Analysis/blob/main/Total%20chart.PNG)

## Summary
All models show that 100% Precision on Low Risk but low numbers on High Risk Precision. High Risk Sensitivity range is between 59% ~ 69%. Low Risk Sensitivity range is between 45% ~ 91%. Only Low Risk Precision shows 100%. All models have low High Risk F1 score which can refer that imbalance between sensitivity and precision. Sensitivity and Precision are important measure for credit risk prediction, so I do not recommand any of these models to predict credit risk. If one of model must use, then either Balanced Random Forest Classifier or Easy Ensemble AdaBoost Classifier model should use for the prediction since those two model has highest Balanced Accuracy Score and F1 scores.
