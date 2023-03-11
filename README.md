# Pipline
End-To-End **SK-Learn pipeline** for predicting survival on the titanic using **logistic regression model**.

In this pipeline, we are using **custom transformers** to preprocess the data and using **LogisticRegression** estimator to train and predict the results.

1- **Feature Imputation**:
   - MeanMedianImputer
   - CategoricalImputer
   - AddMissingIndicator

2- **Feature Encoding**:
   - OneHotEncoder
   - RareLabelEncoder