# MechaCar Statistical Analysis 

## Linear Regression to Predict MPG

**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**

According to our statistical summary we can conclude that the variables that do not provide a non-random amount of variance to the mpg values in the dataset are the vehicle length and ground clearance. In other words, we can deduce that the ground clearance and the vehicle length have a significant impact in the mpg values.

**Is the slope of the linear model considered to be zero? Why or why not?**

No, the slope of the linear model is not considered 0 because the p-value is smaller than the significance level, which takes us to approve the alternative hypothesis.

**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**

Yes, the linear model predict mpg of MechaCar prototypes effectively because our R-squared value is 0.7149 which represents how well the regression model approximates real-world data points, and can be used as a probability metric to determine the likelihood that future data points will fit the linear model. 

### Linear Model 

![image](https://user-images.githubusercontent.com/108365182/195461199-adce6f14-afd1-4e3e-aa0c-c6ab4099cb84.png)

## Summary Statistics on Suspension Coils

**The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?**

For all manufacturing lots in total, the data meet this design especification, because, according to our total summary dataframe our variance is 62.29 which is under 100 pounds per square inch. However, for each lot individually, only Lot 1 and 2 meet this specification, with a variance of 0.979 and 7.469 respectively, which is far away from 100 pounds per square inch.

### Total Summary

![image](https://user-images.githubusercontent.com/108365182/195616534-a046ec46-4583-4e5f-ac90-8fba2d76829c.png)
### Lot Summary 

![image](https://user-images.githubusercontent.com/108365182/195616705-a8516906-40d7-468d-8231-9f1f2d4c6854.png)

## T-Tests on Suspension Coils

According to our T-test PSI across all manufacturing lots, we can conclude that there is  statistical difference between the mean of the sample and the population mean of 1,500 pounds per square inch, taking us to accept the alternative hypothesis, this, because the value of our p-value=0.06028 is smaller than our significance level. 

Also, based on our T-test PSI for each manufactoring lot, we can conclude that in Lot 3 there is statistical difference between the mean of the sample and the population mean of 1,500 pounds per square inch, taking us to accept the alternative hypothesis, just as the t-test of PSI across all manufacturing lots, this, because our p-value which is 0.04168 is smaller than the significance level. However, in Lot 1 and 2 we can conclude that there is no statistical difference between the mean of the sample and the population mean of 1,500 pounds per square inch to reject our null hypothesis.

### T-test PSI across all manufacturing lots

![image](https://user-images.githubusercontent.com/108365182/195629703-79b4bb1f-59e1-4033-aff8-b3e0dc9eca1a.png)


### T-test PSI for each manufacturing lot

![image](https://user-images.githubusercontent.com/108365182/195627886-72845749-301f-4e9a-9048-34b013a96c4a.png)



