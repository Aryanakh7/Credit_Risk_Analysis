# Credit_Risk_Analysis


## Purpose of the Analysis

The purpose of this analysis is to use the credit card credit dataset from LendingClub, a peer-to-peer lending services company, to oversample and undersample the data in order to compare different machine learning models that reduce bias and predict accurate credit risk. In order to achieve this, the ClusterCentroids algorithm and the SMOTEENN algorithm are utilized along with imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.


## Results

### *Naive Random Oversampling*

The results for the Naive Random Oversampling method are found below:

![image](https://user-images.githubusercontent.com/75655852/116025795-58444c00-a61f-11eb-94ff-cd76bbca8e8f.png)

- As seen above, the Balanced Accuracy Score for the Naive Random Oversampling method is 64.66%
- The Precision High Risk is 1%
- The Precision Low Risk is 100%
- The Recall High Risk is 74%
- The Recall Low Risk is 55%

### *SMOTE Oversampling*

The results for the SMOTE Oversampling method are described below:

![image](https://user-images.githubusercontent.com/75655852/116025965-ab1e0380-a61f-11eb-951a-25312f377d6b.png)

- As seen in the analysis, the Balanced Accuracy Score for the SMOTE Oversampling method is 66.24%
- The Precision High Risk is 1%
- The Precision Low Risk is 100%
- The Recall High Risk is 63%
- The Recall Low Risk is 69%

### *ClusterCentroids Undersampling*

The following results are indicated from the ClusterCentroids Undersampling method:

![image](https://user-images.githubusercontent.com/75655852/116026275-5b8c0780-a620-11eb-83a1-ca184a9f077d.png)

- The Balanced Accuracy Score is 54.42%
- The Precision High Risk is 1%
- The Precision Low Risk is 100%
- The Recall High Risk is 67%
- The Recall Low Risk is 42%

### *SMOTEEN Sampling*

The results for the SMOTEEN Sampling method are indicated as follows:

![image](https://user-images.githubusercontent.com/75655852/116026672-28964380-a621-11eb-8cc8-855ecde1f78d.png)

- The Balanced Accuracy Score is 64.00%
- The Precision High Risk is 1%
- The Precision Low Risk is 100%
- The Recall High Risk is 70%
- The Recall Low Risk is 58%


### *Balanced Random Forest Classifier*

Here are the results for the Balanced Random Forest Classifier method: 

![image](https://user-images.githubusercontent.com/75655852/116027124-081ab900-a622-11eb-8484-8f6ea05b3333.png)

- The Balanced Accuracy Score is 78.85%
- The Precision High Risk is 3%
- The Precision Low Risk is 100%
- The Recall High Risk is 70%
- The Recall Low Risk is 87%


### *Easy Ensemble AdaBoost Classifier*

Finally, the Easy Ensemble AdaBoost Classifier method indicate the following results:

![image](https://user-images.githubusercontent.com/75655852/116027194-38faee00-a622-11eb-93e6-1398cfea1789.png)

- The Balanced Accuracy Score is 93.17%
- The Precision High Risk is 9%
- The Precision Low Risk is 100%
- The Recall High Risk is 92%
- The Recall Low Risk is 94%

## Summary  

In terms of overall performance, the methods that score the highest in the Balanced Accuracy category are:

  - *Easy Ensemble AdaBoost Classifier*, scoring 93.17%
  - *Balanced Random Forest Classifier*, scoring 78.85%
 
In order to detect if a loan is high risk, the methods described above will have to demonstrate their capacity to flag high risk loans. The methods that score the highest for the recall high risk category and are therefore capable of detecting high risk loans more effeciently are:

 - *Easy Ensemble AdaBoost Classifier* with a score of 92%
 - *Naive Random Oversampling* with a score of 74%
 - *SMOTEEN Sampling* with a score of 70%
 - *Balanced Random Forest Classifier* with a score of 70%

In contrast, the *SMOTE Oversampling* method only has a score of 63%, and would subsequently not be as efficient as the other methods in detecting high risk loans.

To conclude, the **Easy Ensemble AdaBoost Classifier** appears to be the most dependable when detecting high risk loans as it has a high rate of true positive detection, and can therefore be recommended as a reliable machine learning model capable of reducing bias and predicting accurate credit risk.

