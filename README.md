# About-regression

Regression models are highly valuable as they are the most common ways to make inferences and predictions.
In our model we define the dependent variable y that is being predicted and the independent variable x which is the predictor.
The dependent variable y is a function of the independent variables x1 to xk and the regression model is a linear approximation of this function. 
So the simple linear regression is the easiest regression and OLS (Ordinary least squares)is the most common method to estimate the linear regression equation.

## Simple linear regression
Interpretation:
- Based on the coefficients  table, the 'size' and 'year' are significant at the 5% significance level. 
- The p-values are virtually 0 and the coefficients are statistically significant. 
- The F-statistics is relatively high 285.9. Unlike the F-statistics value, we would like the probability to be as small as possible. Looking at the table we can see that the number is close to 0 therefore the overall model is significant. 
- Finally the Model Summary table shows that the R-squared value is 0.745.

Data reference:
real_estate_price_size_year_view dataset from [Kaggle](https://www.kaggle.com/gauravduttakiit/real-estate-priceOnly=true)

## Multiple linear regression 
Interpretation:


Datasource: 
real_estate_price_size_year_view dataset from [Kaggle](https://www.kaggle.com/gauravduttakiit/real-estate-priceOnly=true)

## Dealing with categorical predictors 
Using dummy variables to include categorical variables into a regression model. So we are imitating category with numbers.

Interpretation: 
file [Simple regression with categorical predictors](https://github.com/IwonaV/About-regression/blob/main/Simple%20regression%20with%20categorical%20predictors.ipynb)
