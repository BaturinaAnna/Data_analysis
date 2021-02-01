# Classification 2

Dataset - https://archive.ics.uci.edu/ml/datasets/Adult

1. Conduct standard data preprocessing:
 - Check for missing values / outliers
 - Standardize data as needed
 - Parse categorical / numeric attributes
 - Describe data based on statistics / trait information 
2. Build classification models with target variable> 50K, <= 50K (binary classification)
 - Use cross-validation / split into training and test sets
 - Use appropriate metrics to measure quality
 - For each model, select the optimal hyperparameters to obtain the best metrics on the test sample
 - Ensemble of decision trees 
   - Random Forest and / or Extra Trees
   - Draw a graph of the importance of the features, mark the features that turned out to be important, give an interpretation of why they are important 
 - Any Boosting algorithm (sklearn.ensemle.AdaBoostClassifier, GradientBoostingClassifier / xgboost, catboost or lightgbm - +2 points)
   - Determine the importance of features, compare with the importance in the ensemble of trees - has anything changed 