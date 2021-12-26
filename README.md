# Credit_Risk_Analysis


## Overview of the loan prediction risk analysis

The objective of this challenge is to use different machine learning algorithms to predict credit card risk . Use differnt techniques like data preprocessing , data transformation, boosting, bagging, oversampling , undersampling etc to find good candidate for loan. 

PySpark was used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next,  using PySpark, I determined if there is any bias toward favorable reviews from Vine members in the dataset so that SellBy stakeholders can assess if membership to the Vine program is going to be beneficial.

## Resources 

*LoanStats_2019Q1.csv

* Technologies Used
  * Jupyter Notebook
  

## Results

The following section shows comparasion for prediction results of oversampling , undersampling and ensembling .

 1. if we talk about accuracy score than out of four oversampling and undersampling algorithms randomoversampling,SMOTE and SMOTEENN have around 65 % accurate.But compare to sampling algorithms ensembling algorithms give more accuracy here balanced random forest classifier give 79 % accuracy and EasyEnsembleClassifier is 93% accurate.
 2. same with recall(sensitivity) that RandomOversampling ,SMOTE and SMOTEENN provide almost same recallAlso ensampling techniques have a good sensitivity value here BalencedRandomforest give 70% recall for low risk and 88% for high risk. EasyEnsembleClassifier give 92% recall for low risk and 94% for high risk.
 3. After comparing accuracy score ,precision and recall we can conculde that EasyEnsembleClassifier algorithm give good prediction among six algorithms.
 
## RandomOversampling
![image](https://github.com/sanjal7137/Credit_Risk_Analysis/blob/a01714530b3a63883c49f0450dc4718527bb9637/images/randomoversampling.png)


## SMOTE

![image](https://github.com/sanjal7137/Credit_Risk_Analysis/blob/a01714530b3a63883c49f0450dc4718527bb9637/images/smotenew.png)

## Undersampling

![image](https://github.com/sanjal7137/Credit_Risk_Analysis/blob/a01714530b3a63883c49f0450dc4718527bb9637/images/undersampling.png)

## SMOTEENN

![image](https://github.com/sanjal7137/Credit_Risk_Analysis/blob/a01714530b3a63883c49f0450dc4718527bb9637/images/smoteen.png)
## BalancedRandomforest
![image](https://github.com/sanjal7137/Credit_Risk_Analysis/blob/7fedf40e28f297dc7c5339874fd1bcf2230f322f/images/balancedrandomforest.png)
## EasyEnsembleClassifier
![image](https://github.com/sanjal7137/Credit_Risk_Analysis/blob/7fedf40e28f297dc7c5339874fd1bcf2230f322f/images/easyadptive.png)

## Summary
