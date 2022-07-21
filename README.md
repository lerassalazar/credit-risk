# credit-risk

#### This analysis explores supervised learning to evaluate and predict credit risk for LendingClub.

# Results
#### We used loan status to determine risk, and then categorized them as low or high risk. We then used the RandomOverSampler Model to ensure classifications were equal. Then SMOTE was used to rebalanced the minority class. Then ClusterCentroids were used to identify clusters of the majority class to generate data points that were representative. then we combined oversampling and undersampling with the SMOTEENN model. Then we predicted credit risk using randomforest and easyensemleclassifier. 

# Summary 
#### the easyensenbleclassifier model was the most accurate one, with an accuracy rate at 92% for high risk, and sensitivity rates at 91 for high risk and 100 for low risk. 
