                            OLS Regression Results                            
==============================================================================
Dep. Variable:                  Sales   R-squared:                       0.904
Model:                            OLS   Adj. R-squared:                  0.903
Method:                 Least Squares   F-statistic:                     760.4
Date:                Fri, 04 Jul 2025   Prob (F-statistic):          1.82e-282
Time:                        22:14:33   Log-Likelihood:                -2713.4
No. Observations:                 572   AIC:                             5443.
Df Residuals:                     564   BIC:                             5478.
Df Model:                           7                                         
Covariance Type:            nonrobust                                         
============================================================================================
                               coef    std err          t      P>|t|      [0.025      0.975]
--------------------------------------------------------------------------------------------
Intercept                  217.4784      6.584     33.031      0.000     204.546     230.411
TV_Low[T.True]            -154.5736      4.949    -31.231      0.000    -164.295    -144.852
TV_Medium[T.True]          -75.5947      3.647    -20.726      0.000     -82.759     -68.431
Influencer_Mega[T.True]      2.4948      3.462      0.721      0.471      -4.305       9.295
Influencer_Micro[T.True]     2.9391      3.378      0.870      0.385      -3.695       9.574
Influencer_Nano[T.True]      0.8015      3.346      0.240      0.811      -5.770       7.373
Radio                        2.9735      0.235     12.644      0.000       2.512       3.435
Q("Social Media")           -0.1391      0.676     -0.206      0.837      -1.467       1.189
==============================================================================
Omnibus:                       58.711   Durbin-Watson:                   1.874
Prob(Omnibus):                  0.000   Jarque-Bera (JB):               17.802
Skew:                           0.057   Prob(JB):                     0.000136
Kurtosis:                       2.143   Cond. No.                         147.
==============================================================================

Notes:
[1] Standard Errors assume that the covariance matrix of the errors is correctly specified.
