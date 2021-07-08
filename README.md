# Credit_Risk_Analysis
## Overview 
The purpose of this respository is to use python and different machine learning models to analyze and predict credit risk. A sample data set was provided with several parameters and ultimately these variables will be inputed into 6 different ML models and the accuracy will be discussed. 
## Results
### Random Over Sampler Model
![Random Over Sampler Model Accuracy](https://github.com/cchoi22/Credit_Risk_Analysis/blob/main/Random_Sample_acc.PNG)
-Model accuracy score was 64.93%  
-High risk precision was 1% with a sensitivity of 63% and f1 of 2%  
-Low risk precision was 100% with a sensitivity of 67%  
### SMOTE
![SMOTE Model Accuracy](https://github.com/cchoi22/Credit_Risk_Analysis/blob/main/SMOTE_Acc.PNG)
-Model accuracy score was 63.59%  
-High risk precision was 1% with a sensitivity of 61% and f1 of 2%  
-Low risk precision was 100% with a sensitivity of 66%  
### Cluster Centroids Model
![Cluster Centroids Model Accuracy](https://github.com/cchoi22/Credit_Risk_Analysis/blob/main/centroid_acc.png)
-Model accuracy score was 52.40%  
-High risk precision was 1% with a sensitivity of 63% and f1 of 1%  
-Low risk precision was 100% with a sensitivity of 40%  
### SMOTEENN Model
![SMOTEENN Model Accuracy](https://github.com/cchoi22/Credit_Risk_Analysis/blob/main/smoteenn_Acc.png)
-Model accuracy score was 63.76%  
-High risk precision was 1% with a sensitivity of 70% and f1 of 2%    
-Low risk precision was 100% with a sensitivity of 57%    
### Balanced Random Forest Classifier Model
![Balanced Random Forest Model Accuracy](https://github.com/cchoi22/Credit_Risk_Analysis/blob/main/balanced_forest_acc.png)
-Model accuracy score was 92.54%  
-High risk precision was 7% with a sensitivity of 91% and f1 of 14%  
-Low risk precision was 100% with a sensitivity of 94%  
### Easy Ensemble Classifier 
![Easy Ensemble Classifier Model Accuracy](https://github.com/cchoi22/Credit_Risk_Analysis/blob/main/ensemble_acc.png)
-Model accuracy score was 92.54%  
-High risk precision was 7% with a sensitivity of 91% and f1 of 14%  
-Low risk precision was 100% with a sensitivity of 94%  
## Summary 
All the models seem to have trouble in terms of precision when determining high risk items. The most accurate model seems to be the ensemble model however, this model trades off some precision when determining low risk scenarios. This model maybe over fit and to test further more data would need to be run through the ensemble model to see if the model can predict more accurately. 
