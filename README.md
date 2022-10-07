# Credit_Risk_Analysis
## Purpose
The purpose of this analysis is to employ different techniques to train and evaluate models with unbalanced classes. The lead data scientist, Jill asks us to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.
  Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.
  
  ## Results
  ![OverSampling](https://user-images.githubusercontent.com/107155888/194625224-220a817b-b1eb-476f-8c8c-bed0bfbe1a21.png)
  
  Balanced Accuracy score = 64%
  
  Precision = High risk precision 1.0% and low risk precision is 100%.
  
  Recall Scores = High risk recall score is 0.62 and low risk recall score is 0.65.
  
  
  
  
![SmoteOversampling](https://user-images.githubusercontent.com/107155888/194625239-3a3c6df5-f439-4b55-a432-76726a4fe86f.png)

Balanced Accuracy score = 63%

Precision = High risk precision 1.0% and low risk precision is 100%.

Recall Scores = High risk recall score is 0.62 and low risk recall score is 0.64.




![Undersampling](https://user-images.githubusercontent.com/107155888/194625289-f053f587-89a9-4835-8933-cb5a803c50fe.png)

Balanced Accuracy score = 51%

Precision = High risk precision % 1.0 and low risk precision is 100%.

Recall Scores = High risk recall score is 59% and low risk recall score is 43%.




![CombinationSampling](https://user-images.githubusercontent.com/107155888/194625338-111a1a77-7b03-4d61-8d2a-a422eef248f7.png)

Balanced Accuracy score = 64%

Precision = High risk precision 1.0% and low risk precision is 100%.

Recall Scores = High risk recall score is 70% and low risk recall score is 57%.




![BRFS](https://user-images.githubusercontent.com/107155888/194625487-c1e90c82-e7ae-4aa8-853d-c713c6de6d3a.png)

Balanced Accuracy score = 79%

Precision = High risk precision 4.0% and low risk precision is 100%.

Recall Scores = High risk recall score is 67% and low risk recall score is 91%.




![EasyEnsenble](https://user-images.githubusercontent.com/107155888/194625508-60a385e7-7601-4077-b1f5-cd643eaa6eb9.png)

Balanced Accuracy score = 93%

Precision = High risk precision 7.0% and low risk precision is 100%.

Recall Scores = High risk recall score is 91% and low risk recall score is 94%.

## Summary
In conclusion, Easy essemble ADA boost classifier model has a better 93% balanced accuracy sore as compared to the other models. When predicting the high risk customers the precision is only 7% and the sensitivity rate is 91% which is very high as compared to the other models. Also, the low Risk costumers precision is 100% and the highest sensitivity rate is 94% and an F1 score of 97%. I would recommend the easy essemble classifier model for credit card risk analysis based on the balanced accuracy, precision and sensivity score.  
