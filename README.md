# Bank Term Deposit Marketing Strategy with Automatic Machine Learning H2OAutoML

## Blog

[Medium Blog]()

## Introduction

## Data Source

<img src = '../main/Data & Images/df.png'>

<img src = '../main/Data & Images/df_info.png'>

## Exploratory Data Analysis

## Leaderboard

<img src = '../main/Data & Images/leaderboard.png'>

**ModelMetricsBinomialGLM: stackedensemble**

**Reported on train data.**

* MSE: 0.0352567959965488
* RMSE: 0.18776793122508648
* LogLoss: 0.12265871556826867
* Null degrees of freedom: 10064
* Residual degrees of freedom: 10039
* Null deviance: 7250.489028251507
* Residual deviance: 2469.1199443892483
* AIC: 2521.1199443892483
* AUC: 0.9838151034955434
* AUCPR: 0.9060464714993279
* Gini: 0.9676302069910867

<img src = '../main/Data & Images/cm.png'>

### Correlation Between Models

<img src = '../main/Data & Images/model_correlation_heatmap.png'>

## Variable Importance

The variable importance plot shows the relative importance of the most important variables in the model.

<img src = '../main/Data & Images/varimp_plot.png'>

<img src = '../main/Data & Images/varimp_heatmap.png'>

## SHAP Summary

SHAP summary plot shows the contribution of the features for each instance (row of data). The sum of the feature contributions and the bias term is equal to the raw prediction of the model, i.e., prediction before applying inverse link function.

<img src = '../main/Data & Images/shap_summary.png'>

## Partial Dependence Plots

Partial dependence plot (PDP) gives a graphical depiction of the marginal effect of a variable on the response. The effect of a variable is measured in change in the mean response. PDP assumes independence between the feature for which is the PDP computed and the rest.

<img src = '../main/Data & Images/stacked_pdp_age.png'>

<img src = '../main/Data & Images/stacked_pdp_balance.png'>

<img src = '../main/Data & Images/stacked_pdp_campaign.png'>

<img src = '../main/Data & Images/stacked_pdp_contact.png'>

<img src = '../main/Data & Images/stacked_pdp_day.png'>

<img src = '../main/Data & Images/stacked_pdp_default.png'>

<img src = '../main/Data & Images/stacked_pdp_duration.png'>

<img src = '../main/Data & Images/stacked_pdp_education.png'>

<img src = '../main/Data & Images/stacked_pdp_housing.png'>

<img src = '../main/Data & Images/stacked_pdp_job.png'>

<img src = '../main/Data & Images/stacked_pdp_loan.png'>

<img src = '../main/Data & Images/stacked_pdp_marital.png'>

<img src = '../main/Data & Images/stacked_pdp_month.png'>

<img src = '../main/Data & Images/stacked_pdp_pdays.png'>

<img src = '../main/Data & Images/stacked_pdp_poutcome.png'>

<img src = '../main/Data & Images/stacked_pdp_previous.png'>

## Summary of Finding

* Customers over 60 are more likely to invest in term deposit.

## Reference

Brownlee, J. (2021, April 26). Stacking Ensemble Machine Learning with Python. Machine Learning Mastery. Retrieved October 1, 2021, from https://machinelearningmastery.com/stacking-ensemble-machine-learning-with-python/.

Chen, J. (2021, April 29). Term deposit definition. Investopedia. Retrieved October 2, 2021, from https://www.investopedia.com/terms/t/termdeposit.asp#:~:text=A%20term%20deposit%20is%20a,levels%20of%20required%20minimum%20deposits.

Kekre, S. (n.d.) Automatic Machine Learning with H2O AutoML and Python [MOOC]. Coursera. https://www.coursera.org/projects/automatic-machine-learning-h2o-automl-python.

Molnar, C. (2020). 8.1 Partial Dependence Plot (PDP). In Interpretable machine learning: A guide for making Black Box models explainable. Leanpub. 2019.
