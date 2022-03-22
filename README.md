# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![](https://github.com/aaronwolfeaaron/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-03-21%20at%202.22.05%20PM.png)

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Two variables provided a non-random amount of variance and are deemed to be statistically significant: vehicle length and ground clearance.

### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not considered to be zero because the p=value is 5.35e-11, far smaller than the commonly held threshold of 0.05.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This linear model predicts MPG effectively with a relative degree of certainty. The R-squared value of 0.7149 suggests that this linear model is ~71% accurate.

## Summary Statistics on Suspension Coils
![](https://github.com/aaronwolfeaaron/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-03-21%20at%202.43.12%20PM.png)
![](https://github.com/aaronwolfeaaron/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-03-21%20at%202.43.28%20PM.png)

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
No, the current manufacturing data do not meet the given design specification, as evidenced by the variance of 170.8 in Lot 3, well over the 100 PSI threshold.

## T-Tests on Suspension Coils
![](https://github.com/aaronwolfeaaron/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-03-21%20at%202.55.22%20PM.png)
![](https://github.com/aaronwolfeaaron/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-03-21%20at%202.55.35%20PM.png)
![](https://github.com/aaronwolfeaaron/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-03-21%20at%202.55.45%20PM.png)
![](https://github.com/aaronwolfeaaron/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-03-21%20at%202.55.53%20PM.png)

### Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
The overall T-test results and the three lot T-tests (all shown above) do not present statistically significant findings. The only T-test finding that *may* show a statistical significance is that of Lot 3, although it is still technically within the commonly held threshold of 0.05 with a p-value at 0.04168.

## Study Design: MechaCar vs Competition

### Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

### What metric or metrics are you going to test?
For a further study of MechaCar's comparison to competitors, I am going to study the average lifetime maintenance cost.

### What is the null hypothesis or alternative hypothesis?
My null hypothesis is that there will be a highly significant positive statistical difference in the lifetime maintenance cost of MechaCar.

### What statistical test would you use to test the hypothesis? And why?
The statistical test I will use to test my hypothesis is a Two-sample T-test. I've selected this test because it compares the difference in two dichotomous samples to show whether there is a statistical difference. 

### What data is needed to run the statistical test?
In order to run this test, I will need to gather a large sample of data from MechaCar, as well as from a competitor and aggregate the totals of average cost of maintenance over a multi-year period. To ensure only inclusion of accurate data, I will gather the data from the dealerships where cars are serviced and have longstanding records, rather than from independent service shops.
