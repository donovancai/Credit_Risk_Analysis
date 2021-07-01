# Credit Risk Analysis

## Overview

The purpose of this analysis is to utilize various machine learning methods to assess the dataset for LendingClub to identify factors contributing to credit risk. We used Random Over Sampler and SMOTE algorithms to oversample the dataset, then we used Cluster Centroids to under sample the algorithrm. We also used Balanced Random Forest Classifier and Easy Ensemble Classifier to predict the credit risk, both of which methods reduce bias in calculating the results. 

### Results

#### Naive Random Oversampling

![Naive Rnadom Oversampling](https://github.com/donovancai/Credit_Risk_Analysis/blob/main/Resources/Naive%20Rnadom%20Oversampling.png)

* Balanced Accuracy Score
  * This algorithrm is roughly 65% accurate.

* Precision Score
  * The precision is very low at an estimated 1%.

* Recall Score
  * The recall (sensitivity) of this algorithrm is modest at roughly 66%.

#### SMOTE Oversampling

![SMOTE](https://github.com/donovancai/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)

* Balanced Accuracy Score
  * This algorithrm is roughly 65% accurate.

* Precision Score
  * The precision is very low at an estimated 1%.

* Recall Score
  * The recall (sensitivity) of this algorithrm is modest at roughly 61%.

#### Undersampling

![Naive Rnadom Oversampling](https://github.com/donovancai/Credit_Risk_Analysis/blob/main/Resources/Naive%20Rnadom%20Oversampling.png)

* Balanced Accuracy Score
  * This algorithrm is roughly 54% accurate.

* Precision Score
  * The precision is very low at an estimated 1%.

* Recall Score
  * The recall (sensitivity) of this algorithrm is roughly 69%.

#### Combination Sampling (Over and Under)

![SMOTEENN](https://github.com/donovancai/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png)

* Balanced Accuracy Score
  * This algorithrm is roughly 66% accurate.

* Precision Score
  * The precision is very low at an estimated 1%.

* Recall Score
  * The recall (sensitivity) of this algorithrm is modest at roughly 79%.

#### Balanced Random Forest Classifier

![Naive Rnadom Oversampling](https://github.com/donovancai/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier.png)

* Balanced Accuracy Score
  * This algorithrm is roughly 78% accurate.

* Precision Score
  * The precision is very low at an estimated 3%.

* Recall Score
  * The recall (sensitivity) of this algorithrm is modest at roughly 70%.

#### Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://github.com/donovancai/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png)

* Balanced Accuracy Score
  * This algorithrm is highly accurate at roughly 93%.

* Precision Score
  * The precision is relatively low at an estimated 9%.

* Recall Score
  * The recall (sensitivity) of this algorithrm is high at roughly 92%.

### Summary

All six models have relatively low precision rate, but this is not a bad thing necessarily. Low precision only means that more thorough and in-depth analysis will have to be conducted on more loans to determine whether they are high risk. 

Based on the outcomes of the models, Easy Ensemble AdaBoost Classifier produced the best results with an accuracy of 93% and a recall of 92%. This model produced the least amount of false-positives. 
