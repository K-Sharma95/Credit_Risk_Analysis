# Credit_Risk_Analysis
  LendingClub, a peer-to-peer lending services comapny has provided us with a dataset containg information on client's loans and associated credit information. The [data](https://github.com/K-Sharma95/Credit_Risk_Analysis/blob/main/LoanStats_2019Q1.csv) includes loan amounts. interest rates, annual income, income and home ownership information, as-well as personal credit information. 
  
  This respository uses jupyter notebook, specifically the pandas, imbalanced-learn and scikit-learn libraries to conduct a statistical analysis on these data and make observations about not only the dataset provided, but also the machine-learning tools being used here in the credit_risk_resampling, and credit_risk_ensemble. Models and algorithms such as RandomOverSampler, SMOTE, and ClusterCEntroids etc., will be used. The following questions about machine learning, and our data will be answered through our analysis; Which machine learning model is most accurate? Which, if any, is recommended for this purpose? What other observations can be made?
  
## Which models are best?

### - **Resampling Models**

  [Naive Random Sampling](https://github.com/K-Sharma95/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Sampling.png)
  
  [SMOTE](https://github.com/K-Sharma95/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Method.png)
  
  [UnderSampling](https://github.com/K-Sharma95/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)
  
  [Combination Sampling](https://github.com/K-Sharma95/Credit_Risk_Analysis/blob/main/Images/Combination.png)
  
Among the resampling methods of analysis, I think the combination sampling method is best. 

### - **Ensemble Models**

 **Balanced_Random_Forest_Classifier**
 ![](https://github.com/K-Sharma95/Credit_Risk_Analysis/blob/main/Images/Balanced_Forest_Random_Classifier.png)
 
 **Easy_Ensemble_Adaboost_Classifier**
 ![](https://github.com/K-Sharma95/Credit_Risk_Analysis/blob/main/Images/Adaboost_Classifier.png)

The easy ensemble adaboost method is the best method used in this case. 
