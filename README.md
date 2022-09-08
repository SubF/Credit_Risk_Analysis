# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

In this analysis the LendingClub, a lending service company, will have it's data reviewed through several machine learning algorithms. Each algorithm will then be evaluated to determine which is recommended to be used to predict credit risk. 

## Results:

### Naive Random Oversampling
![This is an image](https://github.com/SubF/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling.png)

- The Balanced Accuracy Score of 65.7%
- The High Risk Loans have a precision score of 1% and a recall score of 71%
- The Low Risk Loans have a precision score of 100% and a recall score of 60%

### SMOTE Oversampling
![This is an image](https://github.com/SubF/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling.png)

- The Balanced Accuracy Score of 66.2%
- The High Risk Loans have a precision score of 1% and a recall score of 63%
- The Low Risk Loans have a precision score of 100% and a recall score of 69%

### Undersampling
![This is an image](https://github.com/SubF/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)

- The Balanced Accuracy Score of 66.2%
- The High Risk Loans have a precision score of 1% and a recall score of 69%
- The Low Risk Loans have a precision score of 100% and a recall score of 40%

### Combination (Over and Under) Sampling
![This is an image](https://github.com/SubF/Credit_Risk_Analysis/blob/main/Images/Combination%20(Over%20and%20Under)%20Sampling.png)

- The Balanced Accuracy Score of 68.8%
- The High Risk Loans have a precision score of 1% and a recall score of 71%
- The Low Risk Loans have a precision score of 100% and a recall score of 60%

### Balanced Random Forest Classifier
![This is an image](https://github.com/SubF/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier.png)

- The Balanced Accuracy Score of 78.9%
- The High Risk Loans have a precision score of 3% and a recall score of 70%
- The Low Risk Loans have a precision score of 100% and a recall score of 87%

### Easy Ensemble AdaBoost Classifier
![This is an image](https://github.com/SubF/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost%20Classifier.png)

- The Balanced Accuracy Score of 93.2%
- The High Risk Loans have a precision score of 9% and a recall score of 92%
- The Low Risk Loans have a precision score of 100% and a recall score of 94%

## Summary:

### Recommendation

- The Easy Ensemble AdaBooster Classifier is recommended for this Credit Risk Analysis with the highest Balanced Accuracy of 93.2%. This algorithm also had high precision and recall scores compared to the other algorithms. It will also be difficult to improve the high risk loan precision without more data for high risk loans.

### Balanced Accuracy Ranking

1. Easy Ensemble AdaBoost Classifier - 93.2%
2. Balanced Random Forest Classifier - 78.9%
3. Combination (Over and Under) Sampling - 68.8%
4. Naive Random Oversampling - 65.7%
5. Undersampling - 66.2%
5. Smote Oversampling - 66.2%

### Improvements

- A larger number of high risk loans in comparison to low risk in the sample could yield more accurate results since there was less than 1% of the data as high risk. In the orignal data there were 68470 low risk loans and 347 high risk loans.
