# Natural Resource Sampling (ESPM 102b)

Hello!

## Note on linear regression

I want to offer feedback on interpreting linear regression in hopes that it will help: 

#### Assumptions

Remember, when you are applying linear regression on data you are assuming a bunch of things about the data. E.g. normality, homoscedasticity, no autocorrelation, etc. And linear regression is very sensitive to outliers. 

#### Question the model

Does the point all the way to the right follow the same trend as the others? What would happen to the trendline if that data point was removed?

#### Case: Tree height vs DBH from lab 1

To prove my points above: 

I created a polynomial (non-linear) "trend of best fit" of order 6 and has an R^2 value of 0.69. Linear regression has an R^2 value of 0.64. Thus, a non-linear model out-performs the linear regression model. So a non-linear and curved trend is a better fit for this relationship (i.e. height of trees and diameter).
