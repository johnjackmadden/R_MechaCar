# Statistics in R
## Linear Regression to predict potential MPG
### 1) The variables and coefficients that provided a non-random amount of variance to the miles per gallon output value were vehicle weight, spoiler angle, and all wheel drive. The other variables (ground clearence and vehcile length provided random variance
### 2) Since the P-value listed below in image one is less than zero, the slope is not equal to 0
### 3) The R squared value calculated in image one is equal to 71.49% so theres about a 71-72% chance that the predictions will be accurate based on this linear model
![viz 1](/Resources/image1.png)
## Summary Statistics of the Suspension Coils
### After the Suspension coil CSV was converted into a dataframe, I converted it into two different tables: Total Summary and Lot Summary. The total summary table is looking at the total PSI accross all lots while the Lot Summary shows the statistics of each individual lot. As listed in the tables below, the main outlier in this lot data set is Lot 3, with a much larger standard deviation
![viz2](/Resources/totalsum.png)
![viz3](/Resources/lotsum.png)
## T-Test on Suspension Coils
### Comparing all 3 lots against the standard 1500 PSI baseline, we can see some level of varience for this group of coils
### - Lot 1: 1 PSI
### - Lot 2: 0.6072 PSI
### - Lot 3: 0.0417 PSI
### - All PSI: 0.0603 PSI
### Assuming we are looking for a statistically significant result with the standard measure (p >.05), only lot 3 stands out as an outlier with the given criteria. This could lead us to believe there is some issue with lot 3 underpreforming, and could potentially be a safety issue as well. All the other lots lie within the statistically significant margins set by the standard P-value
![viz4](/Resources/t1.png)
![viz5](/Resources/t2.png)
