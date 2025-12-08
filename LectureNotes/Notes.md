# Class 1

# Lecture notes

## Markdown files

[Cheate sheet](https://www.markdownguide.org/cheat-sheet/)

## Create a CSV dataset

See `demo.csv`. 

## Open csv file 

- Change variable type: https://www.youtube.com/watch?v=pquU5lsKXcA
- Code missing value(s): https://www.youtube.com/watch?v=QV9OtK2XEdg

## Descriptive statistics

https://www.youtube.com/watch?v=1ISwWsc_7E8



# Class: 2

## Data management

0. How to clean a data collected from the web. Example: autokostencheck.de

1. Open large datasets (ESS and WVS): How to handle it: read codebooks

2. Compute variable

https://www.youtube.com/watch?v=_CqfI3eFqD4

# Class: 3

3. Filtering/Subset variables

https://www.youtube.com/watch?v=pij0KlFhITw
https://www.youtube.com/watch?v=gl8HPmb6SWA
https://www.youtube.com/watch?v=KyWFuADOr04

4. Saving ongoing works
(Introducing the concept: maintainer)

5. Selecting variables

6. Cross tables: absolute vs. relative 
https://www.youtube.com/watch?v=6-vldNpg7As&t=109s


7. Recode
https://blog.jamovi.org/2018/10/23/transforming-variables.html
https://www.youtube.com/watch?v=lBY_lykRxhU


# Class 4

Book data: https://drive.google.com/drive/folders/1loDMI3lwIysVgXDdnhcJV0wjR1jvwAzH
https://www.youtube.com/watch?v=vsrj647Tb3g

# Class 5

## Tasks
- Filter the cntry == "DE"
- Find the variable you want explore and configure the missing values
- Find the variables that are hypothesized to explain the variable in interest and configure the missing values
- Recode variables if necessary
    - Gender (if being female has to do something with other variables)
    - Age (compute or recode to have the contingency table understandable)
- Plot something nice

Future

8. Wide vs long data format

9. Aggregate

9. Merge


# Models
- Dependent variable data is continuous: Linear regression analysis
- Dependent variable data is discrete and binary: Binomial logistic regression
- Dependent variable data is discrete and nominal: Multinomial logistic regression
- Dependent variable data is discrete and ordinal: ordinal logistic regression

# Regression analysis

https://www.youtube.com/watch?v=_5AVGuEzCXc

SPSS example: https://stats.oarc.ucla.edu/spss/output/regression-analysis/

# Binary logistic regression

https://www.youtube.com/watch?v=s7GL0z-3ymA

SPSS example: https://stats.oarc.ucla.edu/spss/output/logistic-regression/

# Multinomial logistic regression

https://www.youtube.com/watch?v=nuyEUEBf-GQ

# Ordinal logistic regression

https://www.youtube.com/watch?v=QnG8Tq80Qwc


Use **hsb2** data

Source (SPSS example): https://stats.oarc.ucla.edu/stata/output/ordered-logistic-regression/

**Log Likelihood** – This is the log likelihood of the fitted model. It is used in the Likelihood Ratio Chi-Square test of whether all predictors’ regression coefficients in the model are simultaneously zero and in tests of nested models.

**Chi-square** -  This is the *Likelihood Ratio (LR) Chi-Square test* that at least one of the predictors’ regression coefficient is not equal to zero in the model. The number in the parenthesis indicates the degrees of freedom of the Chi-Square distribution used to test the LR Chi-Square statistic and is defined by the number of predictors in the model. The LR Chi-Square statistic can be calculated by  $-2*( L(null model) – L(fitted model)) = -2*((-210.583) – (-194.802)) = 31.560$, where L(null model) is from the log likelihood with just the response variable in the model (Iteration 0) and L(fitted model) is the log likelihood from the final iteration (assuming the model converged) with all the parameters.

**Prob > chi2** – This is the probability of getting a LR test statistic as extreme as, or more so, than the observed under the null hypothesis; the null hypothesis is that all of the regression coefficients in the model are equal to zero. In other words, this is the probability of obtaining this chi-square statistic (31.56) if there is in fact no effect of the predictor variables. This p-value is compared to a specified alpha level, our willingness to accept a type I error, which is typically set at 0.05 or 0.01. The small p-value from the LR test,  <0.00001, would lead us to conclude that at least one of the regression coefficients in the model is not equal to zero. The parameter of the Chi-Square distribution used to test the null hypothesis is defined by the degrees of freedom in the prior line, chi2.

**Pseudo R2 McF** – This is McFadden’s pseudo R-squared. Logistic regression does not have an equivalent to the R-squared that is found in OLS regression; however, many people have tried to come up with one.  There are a wide variety of pseudo R-squared statistics which can give contradictory conclusions.  Because this statistic does not mean what R-squared means in OLS regression (the proportion of variance for the response variable explained by the predictors), we suggest interpreting this statistic with great caution.

These are the ordered log-odds (logit) regression coefficients. Standard interpretation of the ordered logit coefficient is that for a one unit increase in the predictor, the response variable level is expected to change by its respective regression coefficient in the ordered log-odds scale while the other variables in the model are held constant. 

**science** – This is the ordered log-odds estimate for a one unit increase in science score on the expected ses level given the other variables are held constant in the model. If a subject were to increase his science score by one point, his ordered log-odds of being in a higher ses category would increase by 0.03 while the other variables in the model are held constant.

**socst** – This is the ordered log-odds estimate for a one unit increase in socst score on the expected ses level given the other variables are held constant in the model. A one unit increase in socst test scores would result in a 0.0532 unit increase in the ordered log-odds of being in a higher ses category while the other variables in the model are held constant.

**female** – This is the ordered log-odds estimate of comparing females to males on expected ses given the other variables are held constant in the model. The ordered logit for females being in a higher ses category is 0.4824 less than males when the other variables in the model are held constant.


# Exam preparation

 * Car price prediction data
 * Descriptive statistics: Fuel price, group it against Fuel type. Graphically and numerically. 
 * Test the hypothesis that the average fuel price is no different than 30000
 * Build a cross table with transmission and fuel type with rowwise/columnwise percentage.
 * Build a correlation table using all the variables and report the correlations that are NOT significant at 5% level. 
 * Run this model: fuel price = f (how old the car is, engine size, mileage, fuel type, transmission). Interpret the output. 

# Important dates
Incourse exam: December 15 (requirement: laptop)
Extra class: January 9 
Presentation: January 12

