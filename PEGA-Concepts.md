## PEGA - Concepts

### What are the steps involved in the model preparation? 

1. __Data Preparation__ - Critical step in the model preparation
  - Source Selection: 
      Select data either using the CSV, Database 
  - Sample Construction: 
      Select the appropriate fields - Categorical or Numerical
      Discard the fields that are not useful. For example, customer id etc...
      Select the hold-out sets that include Validation and Test Sets
  - Outcome definition
      Decide the outcome to be predicted - whether it is a scoring model or spectrum model. 
      Scoring Model - Categorical model like true, and false. Like the prediction belongs to which category
      Spectrum Model - Numerical range. Like predicting the house prices
      
2. __Data Analysis__
  - Identification of the potential predictors.
  
3. __Model Development__
  - Predictor grouping
  - Model Creation - By Default, PEGA provides the Regression and DecisionTree-CHAID models
4. __Model Analysis__
5. __Model Selection__
