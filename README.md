# Credit Risk Analysis

In this analysis we are trying to predict the credit risk of applicants. To obtain this information we have used six different machine learning models to obtain the highness performance assessment. 

# Results 
**Oversampling:** this models displays a 65% accuracy score with a 1% precision and 61% recall on high risk applicants. 
<img src="https://github.com/carolinamedina26/Credit_Risk_Analysis/blob/main/Resources/Naive_oversampling.png">

**Oversampling:** this models displays a 62% accuracy score with a 1% precision and 61% recall on high risk applicants. 
<img src="https://github.com/carolinamedina26/Credit_Risk_Analysis/blob/main/Resources/SMOTE_sampling.png">

**Undersampling:** this models displays a 62% accuracy score with a 1% precision and 61% recall on high risk applicants, which is the same performance of the oversampling model. 
<img src="https://github.com/carolinamedina26/Credit_Risk_Analysis/blob/main/Resources/Cluster_Centroids.png">

**SMOTEENN:** this models displays a 62% accuracy score with a 1% precision and 70% recall on high risk applicants.
<img src="https://github.com/carolinamedina26/Credit_Risk_Analysis/blob/main/Resources/SMOTEENIN.png">

**Balance Random Forest:** this models displays a 79% accuracy score with a 3% precision and 70% recall on high risk applicants.
<img src="https://github.com/carolinamedina26/Credit_Risk_Analysis/blob/main/Resources/Radom_forest.png">

**Easy Ensemble:** this models displays a 93% accuracy score with a 9% precision and 92% recall on high risk applicants.
<img src="https://github.com/carolinamedina26/Credit_Risk_Analysis/blob/main/Resources/adaboost.png">

# Summary
After the application of 6 different machine learning model were applied, the results display that the easy ensemple model has the highest score with 93% accuracy and should be the model use for this analysis.Although, we also have to considerate that this model tends to overfit the data points. 
