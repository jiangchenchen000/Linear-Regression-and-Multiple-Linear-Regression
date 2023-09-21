# Linear Regression and Multiple Linear Regression
 Perform linear regression and multiple linear regression model with the Boston Housing Dataset, interpret the results and assess the model's performance. 

## Methodology 
With Boston Housing Dataset, using Linear Regression and Multiple Linear Regression model respectively to see how the MEDV (Median value of owner-occupied homes in $1000’s) can be influenced by other factors. Through calculating and comparing their MSE and R2 values respectively to evaluate the model performance.

## Result and Analysis
I tried to use different columns data as the independent variable to fit the Linear Regression model, to see their relationship with MEDV which is dependent variable. The top three parameters fits the model best are: 
TAX (full-value property-tax rate per $10,000), 
AGE(proportion of owner-occupied units built prior to 1940), 
RM (average number of rooms per dwelling).

...	...	...

The values of MSE and R2 for the top three independent variables are close. Take RM for an example, it is positive linear regression to MEDV. 


I tried two parameters with Multiple Linear Regression model, and through below table I realized the bias is smaller than using simple Linear Regression when I chose AGE and TAX as the independent variables. While when trying with three parameters, it’s not better than two ones:



# Conclusion: 
In this case, the performance of Multiple Linear Regression with AGE and TAX as the independent factors is the best option. 
