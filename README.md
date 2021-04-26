# Credit_Risk_Analysis


## Purpose of the Analysis

The purpose of this analysis is to use the credit card credit dataset from LendingClub, a peer-to-peer lending services company, to oversample and undersample the data in order to compare different machine learning models that reduce bias and predict accurate credit risk. In order to achieve this, the ClusterCentroids algorithm and the SMOTEENN algorithm are utilized along with imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.


## Results

### *Naive Random Oversampling*

The results for the Naive Random Oversampling method are found below:

![image](https://user-images.githubusercontent.com/75655852/116025795-58444c00-a61f-11eb-94ff-cd76bbca8e8f.png)

- As seen above, the Balanced Accuracy Score for the Naive Random Oversampling method is 64.55%
- The Precision High Risk is 1%
- The Precision Low Risk is 100%
- The Recall High Risk is 74%
- The Recall Low Risk is 55%

### *SMOTE Oversampling*

The results for the SMOTE Oversampling method are described below:

![image](https://user-images.githubusercontent.com/75655852/116025965-ab1e0380-a61f-11eb-951a-25312f377d6b.png)

- As seen in the analysis, the Balanced Accuracy Score for the SMOTE Oversampling method is 66.23%
- The Precision High Risk is 1%
- The Precision Low Risk is 100%
- The Recall High Risk is 69%
- The Recall Low Risk is 63%

## *ClusterCentroids Undersampling*

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

- The Balanced Accuracy Score is 54.42%
- The Precision High Risk is 1%
- The Precision Low Risk is 100%
- The Recall High Risk is 70%
- The Recall Low Risk is 58%


### *Balanced Random Forest Classifier*

### *Easy Ensemble AdaBoost Classifier*
