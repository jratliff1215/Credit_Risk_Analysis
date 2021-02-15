# Credit Risk Analysis and Supervised Machine Learning
This repository contains code for machine learning models which are used to assess credit risk across a portfolio of personal loans. Our client, LendingClub, requires an understanding of how the performance of different machine learning models differ. Using this information and multiple models, potential borrowers will have credit risk assessed and lending recommendations can be made. 

### Overview of the Analysis 
Using Jupyter Notebook with the scikit-learn and imbalanced-learn libraries, oversampling, undersampling, and combinatorial techniques were performed to analyze a credit card dataset. An analysis of outputs will enable the evaluation of these performance of completed models and provide our client recommendations. 

## Results

### Naïve Random Oversampling
<img src="https://github.com/jratliff1215/Credit_Risk_Analysis/blob/main/Images/NaiveRandom.PNG" width="750" height="200"> 

- Overall Recall score: 0.64
- High Risk Recall score: 0.65
- Low Risk Recall score: 0.64
- Balanced accuracy score: 0.65
- High Risk Precision score: 0.01
- Low Risk Precision score: 1.00
- Overall Precision score: 0.99

### SMOTE Oversampling
<img src="https://github.com/jratliff1215/Credit_Risk_Analysis/blob/main/Images/SmoteOver.PNG" width="750" height="200"> 

- Overall Recall score: 0.64
- High Risk Recall score: 0.60
- Low Risk Recall score: 0.64
- Balanced accuracy score: 0.62
- High Risk Precision score: 0.01
- Low Risk Precision score: 1.00
- Overall Precision score: 0.99

### Undersampling
<img src="https://github.com/jratliff1215/Credit_Risk_Analysis/blob/main/Images/Undersampling.PNG" width="750" height="200"> 

- Overall Recall score: 0.64
- High Risk Recall score: 0.54
- Low Risk Recall score: 0.51
- Balanced accuracy score: 0.57
- High Risk Precision score: 0.01
- Low Risk Precision score: 1.00
- Overall Precision score: 0.99

### Combination (Over and Under) Sampling
<img src="https://github.com/jratliff1215/Credit_Risk_Analysis/blob/main/Images/Combination.PNG" width="750" height="200"> 

- Overall Recall score: 0.60
- High Risk Recall score: 0.64
- Low Risk Recall score: 0.60
- Balanced accuracy score: 0.62
- High Risk Precision score: 0.01
- Low Risk Precision score: 1.00
- Overall Precision score: 0.99

## Machine Learning models that reduce bias

### BalancedRandomForestClassifier

<img src="https://github.com/jratliff1215/Credit_Risk_Analysis/blob/main/Images/BalancedRandonForest.PNG" width="750" height="200"> 

- Overall Recall score: 0.87
- High Risk Recall score: 0.70
- Low Risk Recall score: 0.87
- Balanced accuracy score: 0.78
- High Risk Precision score: 0.03
- Low Risk Precision score: 1.00
- Overall Precision score: 0.99

### EasyEnsembleClassifier

<img src="https://github.com/jratliff1215/Credit_Risk_Analysis/blob/main/Images/EasyEnsemble.PNG" width="750" height="200"> 

- High Risk Recall score: 0.92
- Low Risk Recall score: 0.94
- Balanced accuracy score: 0.93
- High Risk Precision score: 0.09
- Low Risk Precision score: 1.00
- Overall Precision score: 0.99
