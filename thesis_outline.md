# **Outlined Plan**

## EDA
- 2007-2020 Q3 data only has information on accepted loans, another Kaggle dataset from 2007-2018 Q4 has information on both accepted and rejected loans
- Basic describes of interesting features, check distributions and plot

## Modeling
- Logistic regression used as baseline
- Imbalanced tree models
- Imbalanced XGBoost
- Basic NN
- TBD

## Survival Analysis
- Given a set of features, try to predict when down the line the loan will default or if it will default at all.
- This analysis can be used to assign some sort of score (A, B, etc.) in conjunction with a predicted probability of default from the models in the previous section.

## Credit Risk Analysis
- Credit risk drift can be done after the loans have been assigned both a probability of default value as well as a score.  Credit risk drift is an indicator of whether or not the given model has fluctuating scores from year to year as new and more loans are added.

## Possible excursion: Relative Value
- Determine relative value of loans to identify loans which have the best returns.
