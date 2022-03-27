
**CREDIT RISK ANALYSIS**
**OVERVIEW**
The purpose of the exercise is to apply machine learning to credit risk - which is an inherently unbalanced classification problem.  We are trying to predict high risk loans using a dataset from LendingClub, a company that provides credit card data.  We looked at 6 different machine learning models in order to accurately sample all of the data.  We first oversampled, then undersampled.  After that, we used a combinational over and under sampling approach - before finally using two machine learning models to most accurately predict credit risk.



NAIVE RANDOM OVERSAMPLING 

 The balanced accuracy score is (64.63%) 
 
 The low risk precision score is (100%) - sensitivity of (58%) 
 
 The high risk precision score is (1%) - sensitivity of 71%
 


![image](https://user-images.githubusercontent.com/91917546/160301393-3d55717b-b98e-4f90-861c-ade8ed11c334.png)


SMOTE OVERSAMPLING

 The balanced accuracy score is (65.86%) 
 
 The low risk precision score is (100%) - sensitivity of (68%) 
 
 The high risk precision score is (1%0 - sensitivity of (63%)
 
 
![image](https://user-images.githubusercontent.com/91917546/160301424-e75725c4-8b51-496a-8c11-bcfba2e5aad8.png)

UNDERSAMPLING
 The balanced accuracy score is (60.19%) 
 
 The low risk precision score is (100%) - sensitivity of (52%) 
 
  The high risk precision score is (1%) - sensitivity of (68%) 
![image](https://user-images.githubusercontent.com/91917546/160301450-23852f27-00c5-45ba-b1af-fc8f19ad03fd.png)

COMBINATION

 The balanced accuracy score is (64.80%) 
 
 The low risk precision score is (100%) - sensitivity of (57%) 
 
 The high risk precision score is (1%) - sensitivity of (72%) 
 
 
![image](https://user-images.githubusercontent.com/91917546/160301561-d8524931-924f-47e7-aa25-530d92214a68.png)


BALANCED RANDOM FOREST CLASSIFIER 

 The balanced accuracy score is (78.85%) 
 
 The low risk precision score is (100%) - sensitivity of (87%) 
 
 The high risk precision score is (3%) - sensitivity of (70%)
 
 
![image](https://user-images.githubusercontent.com/91917546/160301595-bbd7bbb8-482b-4b72-aedf-ed6c22a4cc7b.png)

EASY ENSEMBLE CLASSIFIER

 The balanced accuracy score is (93.17%) 
 
 The low risk precision score is (100%) - sensitivity of (94%) 
 
 The high risk precision score is (9%) - sensitivity of (92%)


![image](https://user-images.githubusercontent.com/91917546/160301626-01ac63c8-8ac9-4b7b-9ae5-bc862da25097.png)




**SUMMARY**
The Easy Ensemble Classifier is significantly more accurate in identifying high risk credit loans then any other machine learning model.  The 92% accuracy in regards to recall of high risk loans outperforms the rest of the field by a wide margin.  It is also more precise in identifying high credit risk loans and ranks as having the highest accuracy.  Although the precision score is only 9%, it still ranks 3 times better then the next closest machine learning model.  
