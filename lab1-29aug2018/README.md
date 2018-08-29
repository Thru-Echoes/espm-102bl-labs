# Lab 1: 29 August 2018

## Confidence Interval 

Confidence Intervals (CI) contain lower and upper bounds. They are calculated with the mean and the function <code>=confidence.t(alpha, standard_dev, size)</code>.

### Example usage

```
alpha = 0.05 (5% significance level)
standard_deviation = 1
sample_size = 50
=confidence.t(0.05, 1, 50)
```

## Regression model

How much variance is explained by the regression model?

## ANOVA

Tests if two or more means in a group are significantly different.

With only two groups, **t-test** and **ANOVA** produce the same results. 

### F-test

ANOVA produces an F-value and a F-critical value for the alpha value (**e.g. 0.05**).

If F-value > F-critical value for the alpha reject null hypothesis and say *at least one column's / group's mean is significantly different*.

But F-test is only determining if at least one group is different, but not which one or ones are different. What do we do? 

### T-test 

Pairwise test of differences between groups.

## R-squared

Regression model assumes the relationship between variables is linear.

**High R^2 = high correlation**

### Correlation between variables

Correlation explians the strength of the relationship between variables. But! **Does not explain variance of the data**

<code>=correl(column1, column2)</code>

**R^2 is correlation^2**

<code>rsq(column1, column2)</code>

A high value of R^2 shows high correlation but does not assume significance.

*Example: if rsq(column1, column2) = 0.72* then 72% of the variance is explained by model.

But this 

## Misc Tips

- you can prevent Excel from evaluating a function that is incomplete by typing <code>'=incomplete.formala</code>

- you can go into **Formula Builder** to breakdown complex / nested functions and step through
