# Credit Risk Analysis
Module 17 Challenge

## Project Overview
The purpose of this project is to analyze credit card risk by employing six different techniques to train and evaluate models with unbalanced classes.  The models are evaluated and a recommendation based on the results on which model that best predicts credit card risk  is provided.

### Software & Resources
-	Python
-	Jupyter Notebook
-	Scikit-learn library
-	Imbalance-learn library
-	Dataset: [LoanStats_2019.csv](https://github.com/retroxsky06/Credit_Risk_Analysis/blob/main/LoanStats_2019Q1.csv.zip)

## Results
The following results are the resampling models that have been applied in this project: 

### Resampling Models
#### Oversampling: Naive Random Sampling
In random sampling, 

![fig1](https://github.com/retroxsky06/Credit_Risk_Analysis/blob/main/images/naive_random.png)

  - Balanced Accuracy Score: 63.83%
  - Precision
    - high risk: 0.01
    - low risk: 1.00
  - Recall
    - high risk: 0.66
    - low risk: 0.61

#### Oversampling: SMOTE Oversampling

![fig2](https://github.com/retroxsky06/Credit_Risk_Analysis/blob/main/images/smote_oversampling.png)

  - Balanced Accuracy Score:65.89%
  - Precision
    - high risk: 0.01
    - low risk: 1.00
  - Recall
    - high risk: 0.62
    - low risk: 0.69

#### Undersampling: Cluster Centroids

![fig3](https://github.com/retroxsky06/Credit_Risk_Analysis/blob/main/images/cluster_centroids.png
)
  - Balanced Accuracy Score: 54.42%
  - Precision
    - high risk: 0.01
    - low risk: 1.00
  - Recall
    - high risk: 0.69
    - low risk: 0.40

#### Combination (Over & Under) Sampling

![fig4](https://github.com/retroxsky06/Credit_Risk_Analysis/blob/main/images/combo_sampling.png)

  - Balanced Accuracy Score: 66.68%
  - Precision
    - high risk: 0.01
    - low risk: 1.00
  - Recall
    - high risk: 0.79
    - low risk: 0.54


### SMOTEEN Algorithm
#### Balanced Random Forest Classifier

![fig5](https://github.com/retroxsky06/Credit_Risk_Analysis/blob/main/images/brfc.png)

  - Balanced Accuracy Score: 78.85%
  - Precision
    - high risk: 0.03
    - low risk: 1.00
  - Recall
    - high risk: 0.70
    - low risk: 0.87

### Ensemble Classifiers
#### Easy Ensemble AdaBoost Classifier

![fig6](https://github.com/retroxsky06/Credit_Risk_Analysis/blob/main/images/eea_classifier.png)

  - Balanced Accuracy Score: 93.16%
  - Precision
    - high risk: 0.09
    - low risk: 1.00
  - Recall
    - high risk: 0.92
    - low risk: 0.94


## Summary
There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification
