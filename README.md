# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

Using this regression and summary functions the variables that provided a non-random amount of variance to the mpg values was vehicle length and ground clearance. This is due to the fact that their p value is small giving us a confidence level of 99%. Therefore the slope of linear model is not considered to be zero as our data is correlated with mpg as we are given slopes. I believe this linear model does predict mpg of MechaCar prototypes efectively with our r squared value being over 0.7 we can say that there is a strong correlation between the data and the ability to predict mpg. 

![image](https://github.com/evanbruno617/MechaCar_Statistical_Analysis/blob/main/images/linear_regression.png)
---

## Summary Statistics on Suspension Coils

For all the lots in total the variance of the suspension coils does not eceed 100 pounds per inch and lands in at approximately 62 pounds per inch accounrding to this summary.

![image](https://github.com/evanbruno617/MechaCar_Statistical_Analysis/blob/main/images/total_summary.png)

However, when analyzing each lot individually, lot 3 exceeds this limit with 170 pounds per square inch. There this lot does not meet design specification. 

![image](https://github.com/evanbruno617/MechaCar_Statistical_Analysis/blob/main/images/lot_summary.png)

---

## T-Tests on Suspension Coils

After performing t-tests on the total data and the data of different lots I found that the p-value is 0.5 which does not make the PSI across manufacturing lots statisically different form the population. 

However, when I calculated the t-tests for the individual lots I found that lot one and lot two were statisically different than the population mean with p values less than 0.001. 

The last lot, lot three, was not statistically different with a p-value of 0.15.
