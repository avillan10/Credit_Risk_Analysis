# Credit_Risk_Analysis / Module 17: Supervised Machine Learning and Credit Risk 

## Overview of the analysis: Explain the purpose of this analysis.
In this module we practiced techniques on how to assess credit risk. We utilized imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, we utilized a combinatorial approach of over/ & undersampling using the SMOTEENN algorithm. Afterwards, we compared two new machine learning models that reduced bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. And finally, we had to evaluate the effectiveness of these models, and write out a report recommending if these models should be used for credit risk prediction. 

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Random Oversampling Model

1<img width="1066" alt="1" src="https://user-images.githubusercontent.com/80291340/125232485-956cc180-e291-11eb-9000-df11b24fd0d7.png">

### SMOTE MODEL

2<img width="1056" alt="2" src="https://user-images.githubusercontent.com/80291340/125232598-cea53180-e291-11eb-99df-18c7b8d95eba.png">

### SMOTEENN Model

3<img width="1083" alt="3" src="https://user-images.githubusercontent.com/80291340/125233001-98b47d00-e292-11eb-9f5a-4911bc2a3e03.png">

### BalancedRandomForestClassifier Model

4<img width="1078" alt="4" src="https://user-images.githubusercontent.com/80291340/125233116-ca2d4880-e292-11eb-8c1c-0eeb40b9fdc5.png">

### EasyEnsembleClassifier model

5<img width="1050" alt="5" src="https://user-images.githubusercontent.com/80291340/125233226-f8ab2380-e292-11eb-997f-22bf66290670.png">

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

The performances of all the models suggests weak precision in determining high risk credit. The Easy Ensemble Classifier model displays the recall category as 92%---denoting that the model detects almost all high credit risk. But with low precision, there are also many low risk credits being falsely noticed as high risk, which in the end would hurt a bank's credibility.
