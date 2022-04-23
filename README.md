# Credit Risk Analysis

## Overview of the analysis
Credit Risk Anaysis project uses Python to build and evaluate serveral machine learning models to predict credit risk. We employ different techniques to train models with unbalanced classes. Through resampling, we use imbalanced-learn and scikit-learn libraries to perform risk analysis. Our goal is to evaluate the performance of machine learning models and predit credit risk.

## Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. 
### Machine Learning Model
#### Oversampling 
- Naive Random Oversampling
   - Balance Accuracy Score
  <img src='Resources/Images/bas_ros.PNG' width=500 height=45 >
- SMOTE Oversampling
   - Balance Accuracy Score
  <img src='Resources/Images/bas_SMOTE.PNG' width=500 height=45 >
#### Undersampling
- ClusterCentroids
   - Balance Accuracy Score
  <img src='Resources/Images/bas_undersampling.PNG' width=500 height=50 >
#### Combination Over & Undersampling
- SMOTEENN 
  - Balance Accuracy Score
  <img src='Resources/Images/bas_combination.PNG' width=700 height=45 >
  
#### Ensamble Learners
- Balanced Random Forest Classifier
   - Balance Accuracy Score
  <img src='Resources/Images/bas_brf.PNG' width=700 height=40 >
- Easy Ensemble AdaBoost
   - Balance Accuracy Score
  <img src='Resources/Images/bas_eec.PNG' width=700 height=40 >
  
## Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
