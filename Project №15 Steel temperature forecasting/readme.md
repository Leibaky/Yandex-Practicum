# Steel temperature forecasting

## Task

We need to optimise steel production process by forecasting optimal electricity consumption. 
Three different models will be used - linear regression, random forest and catboost boosting algorithm. 
The metric for choosing the optimal model will be the mean absolute error (MAE).


## Result

The Catboost gradient boosting algorithm turned out to be the best model, slightly outperforming the random forest algorithm. 
After choosing the optimal set of parameters (depth = 3, iterations = 300, l2_leaf_reg = 3, learning_rate = 0.1), the best value of the desired MAE metric was also obtained (6.26).
SHAP method analysis showed that the most important features were the initial temperature, wire materials №1 and №2, bulk material №15.

## Tools used

Python (Pandas, Numpy, Matplotlib, Seaborn)

Catboost

SHAP


## Status

Finished
