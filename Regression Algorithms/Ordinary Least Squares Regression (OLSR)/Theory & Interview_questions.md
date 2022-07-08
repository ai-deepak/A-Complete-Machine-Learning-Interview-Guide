```
1. What is Ordinary Least Squares Regression?
```

* The main idea of Linear Regression is to fit the line to the Data.
* Ordinary Least Squares regression (OLSR) is a common technique for *estimating coefficients* of linear regression equations which describe the relationship between *one or more independent quantitative variables and a dependent variable* (simple or multiple linear regression).
* Least squares stand for the minimum squares error (SSE).
* Maximum likelihood and Generalized method of moments estimator are alternative approaches to OLS.

***Possible follow up Questions:***
```
2. Why do we square those error?
```
* we do not want our positive errors to be compensated by the negative ones, since they are equally penalizing for our model.
```
3. Why do we square the error instead of using absolute value?
                        (or)
Why are we using the squared residuals instead of the absolute residuals in OLS estimation?
```
* Because extra penalty for higher errors. instead of 2 the error will be squared to 4.

```
4. what are the methods similar to OLS?
```
* OLS can also be called as ***L2-norm, Euclidean distance and variance***
```
5. what is absolute Least Absolute Deviations (LAD)? (L1-norm, Manhatten distance, Taxicab norm)
```
* L1-norm is also known as least absolute deviations (LAD), least absolute errors (LAE). 
* It is basically minimizing the sum of the absolute differences (S) between the target value (Yi) and the estimated values (f(xi)).
```
6. When to use LAE & when to use OLS ?
```
* Least absolute deviations is robust in that it is resistant to outliers in the data. This may be helpful in studies where outliers may be safely and effectively ignored. 
* If it is important to pay attention to any and all outliers, the method of least squares is a better choice.

```
NOTE:

Minimizing the squared error ( L2 ) over a set of numbers results in finding its mean, and minimizing the absolute error ( L1 ) results in finding its median
```