# Doctors-Consultation-fee-Prediction
 The doctors consultation fee prediction is formulated as regression problem

## Data cleaning and Processing
   Primarily, as the feature Miscellaneous_Info contains redundant information it can be removed from the dataframe.
   Data preprocessing was performed to features experience and place
   Qualification feature was considered as ordinal categorical feature and  *target encoding* was performed
   Place and Profile features were *one hot encoded*. Frequency encoding was tried to Place feature but it did not give good results
   
   
## Models Trained
  
  1. Regression tree
  2. Linear Regressor
  3. Xgboost tree (Boosting)
  4. Random forest regressor (Bagging)
  
  ### Hyper Parameter Tuning
       Used GridSearchCV and K fold cross validation techhniques for selection of Hyper parameters
  ### Evaluation metrics used
       Mean Squared error
       Mean absolute error
  From the results of evluation metrics, Xgboost tree was concluded as the final model. 
## Improvements
  performing a random search of hyperparametrs before grid search help us to select best hyperparameters which inturn improve a model a lot.
  
  
