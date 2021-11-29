# Supervised_learning

## Overview:

In this project, Python is used to build and evaluate machine learning models to predict credit risk. 

The following procedure is adopted:
1. Preprossessing is performed by converting all the categorical data into numeric using lable encoding methods. 
1. Logistic regression model is created. The data is fitted in the model and the model score is obtained. 
2. Random forests classifier model is created and obtained the model score after fitting the data to the model. 
3. The unscaled data is then scaled using standard scaler to both the training and testing set and fitted the above models to see any difference in the model scores.



## Results:

### Unscaled data:

#### Logistic Regression models:
UnScaled Training Data Score : 0.6522988505747126

Un Scaled Testing Data Score : 0.5108464483198639

#### Randon Forest Classifier:
Unscaled Training Score: 1.0

Unscaled Testing Score : 0.638664398128456


### Scaled data:

#### Logistic Regression models:
Scaled Training Data Score  : 0.710919540229885

Scaled Testing Data Score   : 0.7598894087622289

#### Random Forest Classifier:

Scaled Training Score  : 1.0

Scaled Testing Score   : 0.6378136962994471


## Summary:
1. Looking at the model scores before scaling, random forests classifier model shows better score than the logistic regression model.  
2. On the scaled data, the logistic regression model score improved much better compared to random forest classifier.
