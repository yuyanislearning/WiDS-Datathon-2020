# WiDS-Datathon-2020
Code for 2020 WiDS Datathon challenge

## Method Description
### Missing data imputation
To deal with the problem of missing data, we consider two imputation method.
For variables with most of the data missing, we believe that it is very likely they are specific test for certain disease, so its presense is actually a useful predictor. For missing values in this case, we fill in with average value.
For variables with most of the data present, we believe that missing error is likely due to random event and it should follow the distribution of the population. So for these missing values, we will impute them through matrix factorization(or simply interpolation).

### Features selection
manually remove useless data
remove redundant data 

### Model building
logistic regression, SVM, random forest, neural net
