# MultiAffiliations
In this work, we investigate the effects of multi-affiliated authorship on citation counts. Several interesting results are obtained.

## Notebooks

The regression analysis are included in the following notebooks：

- LM: linear regression model on C
- GLM_log: generalized linear model with a continuous lognormal distribution for the error terms on C+1
- NBGLM: Negative binomial regression model
- LM_log: linear regression model on the log of C+1

The comparison.ipynb contains the comparison of these regression models. For goodness-of-fit, we compared
the AIC, BIC and R^2. We found that NBGLM and LM_log perform better than the other two models. In addition,
the results obtained from NBGLM and LM_log show similar patterns.

## regression results
The regression results are stored in result.zip for the above regression models.

.\regression\
    - NBGLM
    - GLM_log
    - LM
    - LM_log
