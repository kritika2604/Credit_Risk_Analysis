# Credit_Risk_Analysis
Supervised Machine Learning

## Purpose ##

1. Using resampling models to predict credit risk
2. Use SMOTEEN to predict credit risk
3. Use ensembler classifier to predict credit risk

## Resources ##
**Data :** [Loan stats-Q1-2019 Dataset](https://github.com/kritika2604/Credit_Risk_Analysis/blob/main/Resources/LoanStats_2019Q1.csv) </br>
**Softwares** - Jupyter notebook, Python, Scikit-learn.

## Overview of the Analysis ##
Using different models of supervised machine learning, credit loan data is used to predict credit risk.

This analysis was performed as below:

1. Use of Resampling Models to Predict Credit Risk
2. Use of the SMOTEENN Algorithm to Predict Credit Risk
3. Use of Ensemble Classifiers to Predict Credit Risk

**Naive Random Oversampling** - 
- Training and test variables were created
- Target variables were created
- Balance of the target variables was created
- An accuracy score for the model is calculated - **too low**  </br> <img width="367" alt="image" src="https://user-images.githubusercontent.com/94858846/165890982-df425711-a9aa-43fd-addf-f528602203b4.png">

- A confusion matrix has been generated </br> <img width="439" alt="image" src="https://user-images.githubusercontent.com/94858846/165890812-ca0549b5-1329-4764-aee8-84226883eb51.png">

- An imbalanced classification report has been generated </br> <img width="520" alt="image" src="https://user-images.githubusercontent.com/94858846/165890896-d7b8f18c-d34c-4559-bd30-9c1a4f871e02.png">

 **SMOTE Oversampling** -
- Training and test variables were created
- Target variables were created
- Balance of the target variables was created
- An accuracy score for the model is calculated - **too low** </br> <img width="307" alt="image" src="https://user-images.githubusercontent.com/94858846/165891320-4261e507-0d69-48d6-ab4f-55e90885268f.png">

- A confusion matrix has been generated </br> <img width="413" alt="image" src="https://user-images.githubusercontent.com/94858846/165891405-b02008b2-8622-4135-bd2c-bf111f062596.png">

- An imbalanced classification report has been generated </br> <img width="516" alt="image" src="https://user-images.githubusercontent.com/94858846/165891448-1545b30a-7340-4c7d-a886-bc364d88b977.png">

 **Cluster Centroids/Undersampling** -
 - Training and test variables were created
- Target variables were created
- Balance of the target variables was created
- An accuracy score for the model is calculated - **too low** </br> <img width="298" alt="image" src="https://user-images.githubusercontent.com/94858846/165892151-ccb1226d-28ff-44dc-bbea-c77296007bfe.png">

- A confusion matrix has been generated </br> <img width="429" alt="image" src="https://user-images.githubusercontent.com/94858846/165892178-d0beb0f4-b67d-448b-a608-8fcba40a92f8.png">

- An imbalanced classification report has been generated </br> <img width="515" alt="image" src="https://user-images.githubusercontent.com/94858846/165892222-7769b3ee-811c-4374-8fef-8556303e08af.png">
 
 
 **SMOTEENN / Combination Oversampling and Undersampling** -
 - Training and test variables were created
- Target variables were created
- Balance of the target variables was created
- An accuracy score for the model is calculated - **too low** </br> <img width="299" alt="image" src="https://user-images.githubusercontent.com/94858846/165892509-84ab7aec-174a-4314-9cff-2929d5f94799.png">

- A confusion matrix has been generated </br> <img width="362" alt="image" src="https://user-images.githubusercontent.com/94858846/165892543-1ae9a33a-8949-4ffb-b169-5e5546b9bd3f.png">

- An imbalanced classification report has been generated </br> <img width="503" alt="image" src="https://user-images.githubusercontent.com/94858846/165892575-a8058e91-8c73-45b6-9b91-29e465eefe9d.png">


 **Ensemble Classifiers to Predict Credit Risk - Balanced Random Forest Classifier** -
   Here two ensemble algorithms are used to determine which algorithm results in the best performance. 
 - Training and test variables were created
 - Target variables were created
 - Balance of the target variables was created
 - An accuracy score for the model is calculated - **good** </br> <img width="293" alt="image" src="https://user-images.githubusercontent.com/94858846/165893429-1f519c52-a744-4e0c-98b1-67a3be25c00f.png">

- A confusion matrix has been generated </br> <img width="284" alt="image" src="https://user-images.githubusercontent.com/94858846/165893759-dfc82ee6-4e37-49cb-aa52-d17d60e9e609.png">

- An imbalanced classification report has been generated </br> <img width="503" alt="image" src="https://user-images.githubusercontent.com/94858846/165892575-a8058e91-8c73-45b6-9b91-29e465eefe9d.png">

 **Easy Ensemble AdaBoost Classifier** - </br>
   Here two ensemble algorithms are used to determine which algorithm results in the best performance. 
 - Training and test variables were created
 - Target variables were created
 - Balance of the target variables was created
 - An accuracy score for the model is calculated - **good** </br> <img width="293" alt="image" src="https://user-images.githubusercontent.com/94858846/165894780-fe3b9d62-1f57-4913-8b42-b65ffecee380.png">

- A confusion matrix has been generated </br> <img width="260" alt="image" src="https://user-images.githubusercontent.com/94858846/165894852-b591f07a-04d9-4378-889c-f9ed7d2ab46a.png">

- An imbalanced classification report has been generated </br> <img width="489" alt="image" src="https://user-images.githubusercontent.com/94858846/165894917-ff2a0223-a53d-4f31-9064-e3bc8ae1af3f.png">

## Summary ##
It was observed that the accuracy scores are 79% and 93% for Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier.
The precision is not to high for any of the models.
