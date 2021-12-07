# About linear regression

Regression models are highly valuable as they are the most common ways to make inferences and predictions.
In our model we define the dependent variable y that is being predicted and the independent variable x the predictor.
The dependent variable y is a function of the independent variables x1 to xk and the regression model is a linear approximation of this function. 
So the simple linear regression is the easiest regression and OLS (Ordinary Least Squares)is the most common method to estimate the linear regression equation.

## Simple linear regression
Interpretation:
- We can see the coefficient is statistically significant and p-values is equal to 0.000.
- The F-statistics is relatively high 285.9. Unlike the F-statistics value, we would like the probability to be as small as possible. Looking at the table we can see that the number is close to 0 therefore the overall model is significant. 
- Finally the Model Summary table shows that the R-squared value is 0.745.

Data reference:
real_estate_price_size_year_view dataset from [Kaggle](https://www.kaggle.com/gauravduttakiit/real-estate-price)

## Multiple linear regression 
Interpretation:
- Based on the coefficients table, the 'size' and 'year' are significant at the 5% significance level. 
- The p-values are virtually 0. 
- Adding a second variable slightly improved the model, R-squared increased from 0.745 to 0.776 with adjusted R Square 0.772.
 
Data reference:
real_estate_price_size_year_view dataset from [Kaggle](https://www.kaggle.com/gauravduttakiit/real-estate-price)

## Dealing with categorical predictors 
Using dummy variables to include categorical variables into a regression model. So we are imitating category with numbers.

Interpretation: 
file [Simple regression with categorical predictors](https://github.com/IwonaV/About-regression/blob/main/Simple%20regression%20with%20categorical%20predictors.ipynb)
- Looking at the R-squared and Adj. R-squared we can tell that our model is overall significant. The independent variables explain 89% of variability of the price for our sample.
- The coefficients are significant. 
- The adjusted R-squared for this model is 0.883 which is a an improvement compared to the model without the ‘view’ feature which was 0.772. 

Data reference:
real_estate_price_size_year_view dataset from [Kaggle](https://www.kaggle.com/gauravduttakiit/real-estate-price)
