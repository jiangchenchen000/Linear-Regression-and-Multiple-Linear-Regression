# Linear Regression and Multiple Linear Regression
 Perform linear regression and multiple linear regression model with the Boston Housing Dataset, interpret the results and assess the model's performance. 

# Methodology 
With Boston Housing Dataset, using Linear Regression and Multiple Linear Regression model respectively to see how the MEDV (Median value of owner-occupied homes in $1000’s) can be influenced by other factors. Through calculating and comparing their MSE and R2 values respectively to evaluate the model performance.

# Result and Analysis
I tried to use different columns data as the independent variable to fit the Linear Regression model, to see their relationship with MEDV which is dependent variable. The top three parameters fits the model best are: 
TAX (full-value property-tax rate per $10,000), 
AGE(proportion of owner-occupied units built prior to 1940), 
RM (average number of rooms per dwelling).

The MSE and R2 of them are as below: 

	      MSE  	 R2
TAX	  79.46	  -0.19
AGE  	103.27	 -0.55
RM	   121.82	 -0.83
CRIM	 129.36	 -18.39
RAD	  274.60	 -3.12
...	...	...

The values of MSE and R2 for the top three independent variables are close. Take RM for an example, from below figure we can see that RM is positive linear regression to MEDV. 


I tried two parameters with Multiple Linear Regression model, and through below table I realized the bias is smaller than using simple Linear Regression when I chose AGE and TAX as the independent variables. 
	           MSE 	R2
AGE, TAX	 74.05	 -0.11
RM, CRIM	 157.26	-1.36
CRIM, AGE	253.93	-2.81
CRIM, TAX	463.99	-5.97

When trying with three parameters, it’s not better than two ones:

	                 MSE  	R2
CRIM, AGE, TAX	 76.14	  -0.14
RM, AGE, TAX	  101.68	  -0.53
RM, CRIM, TAX 	311.19	  -3.67
RM, CRIM, AGE	 508.16	  -6.63

# Conclusion: 
In this case, the performance of Multiple Linear Regression with AGE and TAX as the independent factors is the best option. 
