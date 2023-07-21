# Predicting CO2 from smart city perspective
CO2 prediction by new vehicles


In this project, I conducted a supervised learning analysis using regression models to predict a continuous target variable based on a set of input features. The primary objective was to explore the relationships between the predictors and the target variable and develop an accurate predictive model. The dataset used for this analysis is taken from the Government site.

Various Models Used:

Linear Regression:
Linear regression is a base model used in this project. It establishes a linear relationship between the input features and the target variable by fitting a straight line to the data points. The model assumes a constant and additive relationship between the predictors and the target. 

Polynomial Regression:
As linear regression might not capture complex relationships, I explored polynomial regression. This model extends the linear regression by incorporating polynomial terms of the input features. By increasing the polynomial degree, we can capture non-linear patterns in the data. However, it's essential to prevent overfitting by tuning the degree of the polynomial carefully.

Ridge Regression and Lasso Regression:
To deal with potential multicollinearity issues among predictors, I employed ridge regression and lasso regression. Both techniques add regularization terms to the traditional linear regression model, which helps to prevent overfitting and stabilize the coefficient estimates. Ridge regression uses L2 regularization, while Lasso regression uses L1 regularization, resulting in sparse coefficient estimates.

Other models used are :Support Vector Regressor, Decision Trees, Random Forest, Support Vector Regression (SVR),Gradient Boosting Regression, Lazy regressor.


Overall, I compared the performance of these regression models using various evaluation metrics, such as mean squared error, mean absolute error, and R-squared, to identify the most suitable model for our dataset. Through this comprehensive analysis, we gained valuable insights into the relationships between the predictors and the target variable, enabling us to make accurate predictions.
