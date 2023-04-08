# Credit_Risk_Analysis

## Overview 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. The purpose of this analysis is to employ different techniques to train and evaluate models with unbalanced classes.

## Results

The following results for the balanced accuracy, precision, and recall, were obtained by using six different types of machine learning models.

### #1 Native Random Oversampling 

![Naive_Random_Oversamping](https://user-images.githubusercontent.com/118491043/230700299-f691979c-0633-44e5-b9e4-76b1fd576da9.png)

- Balance Accuracy: 0.6798605056669573
- Precision: Is low for High-risk loans and is high for Low-risk loans
- Recall: High / Low = .59 / .68

## #2 SMOTE Oversampling

![SMOTE_Oversampling](https://user-images.githubusercontent.com/118491043/230700472-c63173ea-49de-4a61-9a3d-13c5e4453712.png)

- Balance Accuracy:0.6443475733798314
- Precision: Is low for High-risk loans and is high for Low-risk loans
- Recall: High / Low = .61 / .64

## #3 Undersampling

![Undersampling](https://user-images.githubusercontent.com/118491043/230700515-675ea368-687e-4a03-8033-c80416c390be.png)

- Balance Accuracy: 0.43016564952048825
- Precision: Is low for High-risk loans and is high for Low-risk loans
- Recall: High / Low = .61 / .43

## #4 Combination Under-Over Sampling

![Combination_Under-Over_Sampling](https://user-images.githubusercontent.com/118491043/230700544-89757f50-4e51-4150-bb61-e634db1d3fdb.png)

- Balance Accuracy: 0.5428654460912525
- Precision: Is low for High-risk loans and is high for Low-risk loans
- Recall: High / Low = .71 / .54

## #5 Balanced Random Forest Classifier

![Balanced_RF_Classifier](https://user-images.githubusercontent.com/118491043/230700558-d487179b-5eb3-4c7b-96d9-4a13dbf00b11.png)

- Balance Accuracy: 0.9076431269979657
- Precision: Is low for High-risk loans and is high for Low-risk loans
- Recall: High / Low = .67 / .91

## #6 Easy Ensemble AdaBoost Classifier

![Easy_EA_Classifier](https://user-images.githubusercontent.com/118491043/230700594-89dbf6f1-8f3e-4e0d-a861-80fb1e6279d1.png)

- Balance Accuracy: 0.9428073234524847
- Precision: Is low for High-risk loans and is high for Low-risk loans
- Recall: High / Low = .90 / .94



