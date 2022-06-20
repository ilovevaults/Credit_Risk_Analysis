# Credit_Risk_Analysis
## Overview
The purpose of this analysis is to evaulate the creditcard data from LendingClub using six different types of models where four of them are algorithms and the other two are both machine learning models. By using these six methods we can predict the credit risk of each person from the creditcard data. Then we will compare each method based on accuracy and determine which one will be used to predict credit risk.
## Analysis
### Random Oversampling
Random oversampling is used when the amount of data is insufficient and one method of oversampling is called SMOTE which stands for Synthetic Minority Oversampling Technique. The purpose of SMOTE is to generate synthetic samples for the minority class which helps with the overfitting problem caused by oversampling 
#### Random Oversampling
![Random Oversampling](https://user-images.githubusercontent.com/98357581/174683728-ef67c8f3-30cb-4005-b52c-ec4d1258af49.png)
#### SMOTE Oversampling
![SMOTE Oversampling](https://user-images.githubusercontent.com/98357581/174683821-ee65d75f-0c75-4b84-9ac9-da1f2aef1f02.png)
### Undersampling
This is used when there is enough data that can be used 
![image](https://user-images.githubusercontent.com/98357581/174684050-bb209080-f04b-49e2-8219-73302d4b67eb.png)
### Combination(Oversampling and Undersampling)
![Combination](https://user-images.githubusercontent.com/98357581/174684103-47a91c41-5b97-4242-a0af-173aef964b1f.png)
### Balanced Random Forrest Classifier
![image](https://user-images.githubusercontent.com/98357581/174684210-a2521e86-9bf1-4456-a57a-70ecb33bba0c.png)
### Easy Ensemble AdaBoost Classifier
![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/98357581/174684335-ac839ec5-c908-41f1-aef4-7e6ca8a7036a.png)
## Summary
### Random Oversampling
Accuracy Score: 67%

High-Risk Precision:1%      High-Risk Recall:68%

Low-Risk Precision:100%     Low-Risk Recall:66%
### SMOTE Oversampling
Accuracy Score: 68%
High-Risk Precision:1%       High-Risk Recall:68%
Low-Risk Precision:100%     Low-Risk Recall:69%
### Undersampling
Accuracy Score: 52%
High-Risk Precision:1%      High-Risk Recall:61%
Low-Risk Precision:100%     Low-Risk Recall:43%
### Combination(Oversampling and Undersampling)
Accuracy Score: 68%
High-Risk Precision:1%        High-Risk Recall:78%
Low-Risk Precision:100%       Low-Risk Recall:58%
### Balanced Random Forrest Classifier
Accuracy Score: 67%
High-Risk Precision:1%       High-Risk Recall:34%
Low-Risk Precision:100%       Low-Risk Recall:100%
### Easy Ensemble AdaBoost Classifier
Accuracy Score: 92%
High-Risk Precision:6%      High-Risk Recall:91%
Low-Risk Precision:100%     Low-Risk Recall:91%

Based on all of these results the Easy Ensemble Adaboost Classifier seems to be the ideal model to used because it has the highest percentage in each category compared to the other models. 
