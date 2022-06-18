# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
Coefficients:

![image](https://user-images.githubusercontent.com/100812515/174448143-452f1657-d639-4b37-a93f-e72dd6f6dc5f.png)

In this distribution of data, we can see that the dataset is within normal limits. The p-value is above the assumed significance level, so there is not enough evidence to reject the null hypothesis.

![image](https://user-images.githubusercontent.com/100812515/174448472-c854ca32-d72b-425f-a9c5-c2009b09491d.png)

 - Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset? Vehicle weight, spoiler angle and AWD provided non-random amount of variance.
 - Is the slope of the linear model considered to be zero? Why or why not? It is not considered to be zero because the p-value is less than 0.05.
 - Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not? the r-squared value is 0.71, which means 71% of the predictions with be correct, showing us that this is an effective dataset.

## Summary Statistics on Suspension Coils

After running the dataset, we are able to see two tables. The first one shows the summary statistics of all manufacturing lots, and shows the mean is 1498.78 and population median 1500. The second table is a more specific look at lots, and shows they are similar numbers.

![image](https://user-images.githubusercontent.com/100812515/174450797-6ced7198-5848-4be5-b0a2-4cdd1ddeb69f.png)

![image](https://user-images.githubusercontent.com/100812515/174450810-2789d475-68d5-45aa-a8bc-a179323cd79f.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not? 
The variance of the total lot is 62.29 PS1, which is less than 100 PSI, staying below the requirement. From the second table we can see lot 1 & 2 are consistent with the numbers, but lot 3 shows a variance of 170.29, which does not meet the specifications.

## T-Tests on Suspension Coils

![image](https://user-images.githubusercontent.com/100812515/174450040-4000551e-35e2-447f-9533-284d593d0cf5.png)

These are the sample tests that were ran. We can see that for all of the manufacturing lots, there is not a statistical significance from normal distribution, so there is not enough evidence to reject the null hypothesis. The mean falls within 95% of the confidence interval.

For Lots 1 & 2, they are both similar, and are not statistically significant from normal distribution, so there is not enough evidence to reject the null hypothesis. The mean falls within 95% confidence interval for the both of them.

For Lot 3, there is statistical significance from the normal distribution.

## Study Design: MechaCar vs Competition

A statistical study that can quantify how the MechaCar performs against competition can use metrics for consumers such as cost, fuel efficiency, safety rating, horse power and mantinenance cost. 

- What metric or metrics are you going to test? I am going to test fuel efficiency, with regards to recent increase in gas prices.
- What is the null hypothesis or alternative hypothesis? The null hypothesis is that the fuel efficiency is zero, and alternative hypothesis is that the fuel efficiency is not zero.
- What statistical test would you use to test the hypothesis? And why? A mulitple linear regression statistical summary can show how variables impact fiel efficiency in MechaCar vs competitors. 
- What data is needed to run the statistical test? A sample of cars from MechaCar and competitors would be needed, and we would have to test their fuel efficiency at different speeds and distances. 

