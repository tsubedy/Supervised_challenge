Supervised_learning

Analysis Overview

In this project, Python is used to build and evaluate machine learning models to predict credit risk. 

The following procedure is adopted:
1. Logistic regression model is created. The data is fitted in the model and the model score is obtained. 
2. Random forests classifier model is created and obtained the model score after fitting the data to the model. 
3. The unscaled data is then scaled using standard scaler to both the training and testing set and fitted the above models to see any difference in the model scores.

Results:

Unscaled data:
Logistic Regression models:
UnScaled Training Data Score : 0.50312744331509
Un Scaled Testing Data Score : 0.5138987883107626

Randon Forest Classifier:
Unscaled Training Score: 0.5003909304143862
Unscaled Testing Score : 0.49097172725112853

Scaled data:
Logistic Regression models:
Scaled Training Data Score   : 0.7007036747458952
Scaled Testing Data Score    : 0.7198859586600143

Randon Forest Classifier:
Scaled Training Score  : 1.0
Scaled Testing Score   : 0.6571632216678546


Summary:
1. Looking at the model scores before using standard scaling, both the models showed very similar models scores on both the training and testing set. 
2. On the scaled data, the testing score on logistic regression model seems to be better performing than the random forests classifier. 


        
