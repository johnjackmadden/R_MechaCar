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
### Assuming we are looking for a statistically significant result with the standard measure (p >.05), only lot 3 stands out as an outlier with the given criteria. All the other lots lie within the statistically significant margins set by the standard P-value
![viz4](/Resources/t1.png)
![viz5](/Resources/t2.png)
## Summary
### Based on this analysis, the major components that influence the MPG are the car weight, spoiler angle, and all wheel drive capabilities. This would mean if the goal is to improve the MPG of the car, focusing on these variables would yield the best results. In addition, there is reason to believe there is some issue with lot 3 underpreforming, and could potentially be a safety issue as well if the PSI is not brought back to a more standard deviation.
## Further Study
### Utalizing an ANOVA test for further testing would be a good idea, since that would allow us to see the means from various different samples are statistically significant or not. If the P value is > .05, that would mean that the mecha car is similar with the sample it is being compared against, while if it is P < .05 that would mean it is significantly different to the other variable. That would be a good start to see which other areas of detail would be most beneficial to look at next.  If it ends up being statistically different, then taking a look at the averages would give more context to see which car preforms better in a given area. Some further areas of study could include:
- Emissions Output
- Highway MPG 
- Cost
- Fuel Efficency
- Safety ratings
- Maintenance
- Production length
