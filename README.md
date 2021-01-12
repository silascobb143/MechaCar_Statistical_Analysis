# MechaCar_Statistical_Analysis

## Overview

In this challenge,we were to do the following:

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Linear Regression to Predict MPG

![github](d_1challange.PNG)

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  In this instance the variable that provide a non random amount of variance were vehicle length and ground clearance as they were both below the p-value of 0.05%.
* Is the slope of the linear model considered to be zero? Why or why not?
  With this linear models slope it would be considered to not be zero.  The reasoning behind this is that due to the p-value being so far below the 0.05% it would make us infer    that we will need to regect the hypothesis.
* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  As for this linear model predicting MPG of MechaCar prototypes effectively you would have to say yes.  The resoning is that R-Squared value is 72%, meaing that for 72% of the time our prototypes predict properly.
  
## Summary Statistics on Suspension Coils

![github](summary.PNG)

* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current  manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
  When we processed the lots as a whole the variance is well below the 100 pound limit sitting at 62.3.
