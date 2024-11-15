# Assignment 2

Complete the exercise described in the pdf above and enter your answers in 
the spaces below.

## Running the Script as Given

Run the entire script and compare 
the output from ```summary(lm_full_model)```, 
which includes all variables, 
with that from ```summary(lm_no_damage)```, 
which omits the damage indicator. 
If there are no cars with damage in your simulation, 
run the script again to take another draw.


a. Copy and paste the regression model estimates after the commands
```summary(lm_full_model)``` and ```summary(lm_no_damage)```. 

```
Call:
lm(formula = car_price ~ mileage + accident + damage, data = car_data)

Residuals:
    Min      1Q  Median      3Q     Max 
-9260.1 -2245.5   195.6  2311.5  8335.5 

Coefficients:
              Estimate Std. Error t value Pr(>|t|)    
(Intercept)  4.951e+04  2.000e+03  24.757  < 2e-16 ***
mileage     -1.860e-01  3.801e-02  -4.894 3.99e-06 ***
accident    -5.433e+03  7.587e+02  -7.160 1.62e-10 ***
damage      -1.984e+04  3.757e+03  -5.282 7.96e-07 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 3685 on 96 degrees of freedom
Multiple R-squared:  0.5523,	Adjusted R-squared:  0.5383 
F-statistic: 39.47 on 3 and 96 DF,  p-value: < 2.2e-16

Call:
lm(formula = car_price ~ mileage + accident, data = car_data)

Residuals:
     Min       1Q   Median       3Q      Max 
-19094.7  -2406.8    450.2   2541.0   8253.5 

Coefficients:
              Estimate Std. Error t value Pr(>|t|)    
(Intercept)  5.068e+04  2.246e+03  22.563  < 2e-16 ***
mileage     -2.090e-01  4.268e-02  -4.896 3.90e-06 ***
accident    -5.942e+03  8.505e+02  -6.986 3.57e-10 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 4165 on 97 degrees of freedom
Multiple R-squared:  0.4221,	Adjusted R-squared:  0.4102 
F-statistic: 35.43 on 2 and 97 DF,  p-value: 2.807e-12
```


b. Compare the estimated coefficient for ```ACCIDENT``` 
with and without the damage variable. 
How does this relate to the coefficient for ```DAMAGE```?

```
Type your response here.
```


c. Compare the values of 
```Multiple R-squared``` and ```Adjusted R-squared``` for the two models. 
Which model do you recommend (pretending that you don't know the true model)? 

```
Type your response here.
```




## Running the Script after Modification


d. Copy and paste the new regression model estimates after the commands
```summary(lm_full_model)``` and ```summary(lm_no_damage)```. 

```
Copy your results here.
```


e. For this new set of regressions, compare the estimated coefficient 
for ```ACCIDENT``` with and without the damage variable. 
How does this relate to the new coefficient for ```DAMAGE```?

```
Type your response here.
```


f. Compare the values of 
```Multiple R-squared``` and ```Adjusted R-squared``` for the two models. 
Now which model do you recommend (pretending that you don't know the true model)? 

```
Type your response here.
```

