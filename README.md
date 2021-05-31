# MechaCar_Statistical_Analysis


## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/78067427/120119594-8d841280-c166-11eb-9c7a-feeee64ac402.png)

 - In the output above, each Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to the results, vehicle lenght and ground clearance (as well as intercept) are statistically unlikely to provide random amounts of variance to the linear model. In other words the vehicle weight and ground clearance have a significant impact to the mpg values.
 - The slope of the linear model is NOT considered to be zero, because the p-value is 5.35e-11, which is more modest than the critical degree of 0.05% and furthermore gives adequate proof to dismiss the invalid speculation.
 - This linear model predicts mpg of MechaCar prototypes effectively becaused its Multiple R-squared is 0.7149, which implies the mpg expectations will be dictated by this model.


## Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/78067427/120133384-1a948f00-c19a-11eb-9e8b-a2fcf891422c.png)

Based on the statistical insight shown above, the MechaCar suspension coils a general variance of 62.29. This doesn't exceed 100 pounds per square inch, which meets the necessities determinations for the MechaCar suspension curls.

However, out of the individual lots statistics, Lot3 exceeds the benchmark by over 70.29 which does not meet the necessary design specification. Lot1 and Lot2 are fine showing its an acceptable variance of 0.99 and 7.50 respectively. The image below shows the individual variances, as well as other statistical results

![image](https://user-images.githubusercontent.com/78067427/120135160-a0660980-c19d-11eb-80be-46145003d794.png)


## T-Tests on Suspension Coils

First, we run the manufacturing lots against the industry standard of 1,500 PSI coils.

![image](https://user-images.githubusercontent.com/78067427/120139569-ba581a00-c1a6-11eb-8c98-0a01ef400d35.png)

The p-value is above 0.05, which means not sufficient to reject the null hypothesis. 

Let's look at the individual lots to see its p-values to the significant level

![image](https://user-images.githubusercontent.com/78067427/120140306-4159c200-c1a8-11eb-985e-175b84720665.png)    
![image](https://user-images.githubusercontent.com/78067427/120140318-4ae32a00-c1a8-11eb-9dd0-b21f46abd0f6.png)

Lot1 and Lot2 are within P-values 1 and 0.6, well within the significant levels but below is Lot3 which has p-value of 0.04 which is below 0.05

![image](https://user-images.githubusercontent.com/78067427/120140727-263b8200-c1a9-11eb-9437-b870d0f43c78.png)

Therefore, there is sufficient statistical evidence that our null hypothesis is not true, and we would reject our null hypothesis.


