# How to Run Linear Regression in Python

- Scikit-learn is a powerful Python module for machine learning.
- It contains function for regression, classification, clustering, model selection and dimensionality reduction. 
- If you want to look inside the linear regression object, you can do so by typing LinearRegression. and the press `<tab> `key. This will give a list of functions available inside linear regression object.
- `lm.fit()` -> fits a linear model
- `lm.predict()` -> Predict Y using the linear model with estimated coefficients
- `lm.score()` -> Returns the coefficient of determination (R^2). A measure of how well observed outcomes are replicated by the model, as the proportion of total variation of outcomes explained by the model.
- You can explore the functions inside lm object by pressing `lm.<tab>`
- `.coef_ `gives the coefficients and `.intercept_` gives the estimated intercepts.
- In practice you wont implement linear regression on the entire data set, you will have to split the data sets into training and test data sets.
- You have to divide your data sets randomly. Scikit learn provides a function called `train_test_split` to do this.
- Residual plots are a good way to visualize the errors in your data. If you have done a good job then your data should be randomly scattered around line zero.  

# Resources

- https://bigdata-madesimple.com/how-to-run-linear-regression-in-python-scikit-learn/ 
