# lab3_Stat450
To determine whether there is a relationship between bill length and bill depth 
in penguins, we consider a multiple linear regression model as a first attempt:

Bill Depth = beta0 + beta1 * (Bill Length) + beta2 * Species + error.

And for the next step, we need to check the normality assumption (to verify if
the residuals follow a normal distribution), and also the homoscedasticity 
assumption to ensure the residuals for all observations of penguins have the
same variance. 