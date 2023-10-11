# Disease-Classification-Kaggle

## Description
--------------------------------------------------- 
Machine learning algorithm is used in classifying whether a patient has disease or not based on the records given. 

## Dataset 
------------------------------------------------------
The train set contains 13 columns including its label and test set was given without its label. The training and testing set has already been split and consists of 60k and 10k rows respectively. The dataset can be found through this link [here](https://www.kaggle.com/competitions/disease-classification/data).

## Experiment Results
---------------------------------------------------------------
Correlation Matrix of the Features
![image](https://github.com/eethiing/Disease-Classification-Kaggle/assets/85276977/2b1fba33-f74a-4008-abb1-405dd452ec19)

Out of the 6 models trained (Logistic Regression, Random Forest, Support Vector Machine, K-Nearest Neighbours, Decision Tree, Light Gradient-Boosting Machine), LGBM achieved the highest score which is 0.72720 with the original dataset values. Normalization and standardization was tested as well on all the models but the the score did not improve. 
