# News-Popularity
A xgboost based classifier for prediction viral news based on UCI-News popularity dataset.

## Approach:
The problem is meant to be used as a regression task to predict the number of shares of a news article, but the target variable has been converted to a binary variable based on the mean value of the column `shares` which provides balanced classes to work with, using `xgboost with hyperparameter tuning` the model was trained.

## Dataset:
`UCI-News Popularity Dataset`

## Accuracy:
`67.36% on the test-set.` `SOTA:69%`

## Dependencies:
1. Xgboost
2. numpy
3. pandas
4. scikit-learn.
