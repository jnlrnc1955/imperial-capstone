
# Model Card J Lawrence 02/24

### Inputs

There are two inputs, both contained in accompanying excel spreadsheet

•  Digitized data representing features of 204 listed corporations in Peru for the year 2017

•  Digitized compliance of corporations with the 2014 corporate governance code, for 24 of the 88 rules contained in the governance code.


Outputs: Predictions

### Outputs

Outputs are predictions for corporate compliance with rule 41 relating to the present=ce of 3 or more independent directors on the corporations’ main board.

### Model

Scilearn logistic regression

### Hyperparameter tuning

•  Data tuning: reduction in the features list using Lasso regression.

•  Threshold tuning: determination of the optimal threshold through modelling of metrics – maximizing Sensitivity + Specificity: 0.39 was used throughout

•  Model tuning using GridSearchCV to adjust model,

•  Solver: I used liblinear and newton-cg with no difference in effect

•  Penalty: set to l2

•  C, the regularization strength: set to 0.2682695795279725

### Results

The logistic classifier yielded a true positive prediction of 84% true positive for a single rule selected from the 88 rues comprising the code. This rule had a compliance rate (P) of 47%, relatively high for thie category of rule of most interest. This is initially promising, however, the quality of the prediction was not so high with a precision of 61%.

Prediction rates for other rules with lower compliance will be lower than this initial trial.

This methodology can be extended to other rules in due course, and those  which have higher compliance rates would yield higher prediction scores.

The results are statistically significantly better than random selection.
