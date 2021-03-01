# Credit_Risk_Analysis
  LendingClub, a peer-to-peer lending services comapny has provided us with a dataset containg information on client's loans and associated credit information. The [data]() includes loan amounts. interest rates, annual income, income and home ownership information, as-well as personal credit information. 
  
  This respository uses jupyter notebook, specifically the pandas, imbalanced-learn and scikit-learn libraries to conduct a statistical analysis on these data and make observations about not only the dataset provided, but also the machine-learning tools being used here in the credit_risk_resampling, and credit_risk_ensemble. Models and algorithms such as RandomOverSampler, SMOTE, and ClusterCEntroids etc., will be used. The following questions about machine learning, and our data will be answered through our analysis; Which machine learning model is most accurate? Which, if any, is recommended for this purpose? What other observations can be made?
  
## Which models are best?

[**Native Random Oversampling**](Naive_Random_Oversampling.png) vs [**SMOTE Oversampling**](SMOTE_Oversampling.png) vs [**Undersampling**](Undersampling) vs [**Combination Sampling**](Combination Sampling.png)

  These four methods are similar, but varied greatly in two ways. The first major difference is the output they produced. As seen by the images the first three methods vary in ther output, nut the fourth method varies greatly. This can be seen drastically in the f1 columns of the final report. 
 
 **Balanced_Random_Forest_Classifier** vs **Easy_Ensemble_Adaboost_Classifier**
