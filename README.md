# MechaCar_Statistical_Analysis
Statistics &amp; R

## Deliverable 1: Linear Regression to Predict MPG

According to our results, vehicle length and ground distance provided a non-random amount of variance to the mgt values which means that they do not have a significant impact of the prototype performance. The intercept is significant which make me assume that the significant features such as vehicle’s length and ground clearance may need scaling or transforming to help predict the prototypes performance 

The slope of the linear model is not zero because the p-value of our linear regression analysis is 5.35e -11 which is much small than our assumed significance level of 0.05%. We can state that there is sufficient evidence to reject our null hypothesis 

Despite the linear model predicted the mpg of MechaCar prototypes effectively, I suggest that move variables should be considered to predict the prototype performance on a higher and more accurate level 

## Deliverable 2: Create Visualizations for the Trip Analysis 

The variance of the coils is 62.29 PSI, which is within the 100 PSI variance requirement. Lot 1 and Lot 2 are also within the 100 PSI variance requirement: with variances of 0.98 and 7.47 respectively. However, Lot 3 showed a much larger variance in performance and consistency, with a variance of 170.29. Lot 3 that is disproportionately causing the variance at the full lot level.

## Deliverable 3: T-Tests on Suspension Coils 

The true mean of the sample is 1498.78. The p-Value of 0.06, is higher than the common significance level of 0.05. there is NOT enough evidence to support rejecting the null hypothesis. The mean of all three of these manufacturing lots is statistically like the presumed population mean of 1500

1.	Lot 1: The true mean of the sample is 1499.71. The p-Value of 1. The null hypothesis must be accepted as there is no statistical difference between the observed sample mean and the presumed population mean(1500) 
2.	Lot 2 had a sample mean of 1499.42 a p-Value of 0.61; the null hypothesis cannot be rejected, and the sample mean and the population mean of 1500 are statistically similar.
3.	In  Lot 3, the sample mean is 1492.43 and the p-Value is 0.04, which is lower than the common significance level of 0.05. All indicating to reject the null hypothesis. the presumed population mean are not statistically different.

## Deliverable 4: Design a Study Comparing the MechaCar to the Competition

This analysis will involve the data collected from all the prototypes that MechaCar manufactures produced for the last 2 years
•	What are the competitions' comparable models?
•	Which factors will look at the study to determine MechaCar selling price in comparison with their competition?
Metrics
•	Safety Feature Rating: Independent Variable
•	Current Price (Selling): Dependent Variable
•	Drive Package : Independent Variable
•	Engine (Electric, Hybrid, Gasoline / Conventional): Independent Variable
•	Resale Value: Independent Variable
•	Average Annual Cost of ownership (Maintenance): Independent Variable
•	MPG (Gasoline Efficiency): Independent Variable
Hypothesis: Null and Alternative
After determining which factors are key for the MechaCar's type:
•	Null Hypothesis (Ho): MechaCar is priced correctly based on its performance of key factors for its models
•	Alternative Hypothesis (Ha): MechaCar is NOT priced correctly based on performance of key factors for its  models.
Statistical Tests
A multiple linear regression would be used to determine the factors that have the highest correlation/predictability with the list selling price (dependent variable); which combination has the greatest impact on price 


