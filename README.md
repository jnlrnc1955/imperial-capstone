# Predicting corporations’ compliance outcomes in the Peruvian governance market

## Summary

### Explanation of project

I aim to use machine learning to predict the compliance behaviour of listed corporations in Peru when confronted by a new voluntary corporate governance code introduced there in 2014. Corporations that are listed on the  _Bolsa de Valores de Lima_  (BVL) are required to submit annual returns to the  _Superintendencia del Mercado de Valores_  (SMV). The reason for this exercise is that there is a wide spread of compliance behaviour, and this analysis is part of a wider study to understand why corporations either do or do not comply with the code.

### Data

As outcome data, I use aggregated records of corporate compliance submitted to the regulator, the SMV, on an annual basis. These data were obtained from the regulator’s website  [www.smv.gov.pe](http://www.smv.gov.pe/).

As feature data, I collected data on the 208 listed corporations in 2017 covering 10 aspects of their activities and engagement with financial partner and client markets. This data was collected from a wide range of sources.

Both sets are in accompanying excel.

### Model

The model I use is a logistic classifier chosen from a list of 6 classifiers offered by scilearn for its stability of results.

### Hyperparametric tuning and feature engineering.

The data were tuned by reducing the range of features using Lasso regression.

The classifier threshold was set to 0.39 to balance sensitivity and specificity scores.

The model was tuned using penalties and regularization.

### Results

The model achieved a true positive prediction of 84% true positive for a single rule comprising the code. This methodology can be extended to other rules in due course.

The results are statistically significantly better than random selection.

To read the full report open [Capstone Project JL README Predicting outcomes in the governance market.docx](./Capstone_Project_JL_README_Predicting_outcomes_in_the_governance_market.docx)

