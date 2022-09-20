# Data Science (DS) project 5: Logistic Regression of bank data
Logistic regression with bank data to predict subscription of a term deposit.

# Credit
The dataset and proposal of the exercise is from the Udemy course [The Data Science Course 2022: Complete Data Science Bootcamp](https://www.udemy.com/course/the-data-science-course-complete-data-science-bootcamp/). I highly recommend this course for those learning Python and machine learning.

# A bit of theory
The equation of a logistic regression model is:

$\frac{p(X)}{1-p(X)} = e^{(\beta_{0}+\beta_{1}X_{1}+...+\beta_{k}X_{k})}$

Rearranging, we get the logit regression model equation:

$log\frac{p(X)}{1-p(X)} = \beta_{0}+\beta_{1}X_{1}+...+\beta_{k}X_{k}$

# Interpretation of the regression summary
Let's analyse this table:
<p align="center">
  <img src="https://github.com/MariaGoniIba/DS5-Logistic-Regression/blob/main/SummaryTable.png" width="350">
</p>

The dependent variable is 'duration' (y). The model consists of a Logit regression which employs the Maximum Likelihood Estimation (MLE) method. It has converged after classifying 518 observations. 
The Pseudo R-squared is 0.21 which is within the 'acceptable region' (0.2-0.4). The duration variable is significant, with a coefficient of 0.0051. The constant is also significant with a coefficient of -1.70.
