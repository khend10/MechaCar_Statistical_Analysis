# MechaCar_Statistical_Analysis

## Study Design: MechaCar vs Competition
The purpose of this analysis is to perform a statistical study that can quantify how the MechaCar performs against the competition. There are various metrics that could impact the design such as, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating. In this study we will focus on vehicle length, vehicle weight, spoiler angle, ground clearance, and all wheel drive (AWD) to determine miles per gallon (mpg) and comparing pounds per square inch across three lots to measure consistency.

## Linear Regression to Predict MPG
Based on the linear regression run in RStudio, the most impactful variables are vehicle length and ground clearance. Both variables have p-values that are less than 0.05 which makes them more reliable and effect to predict mpg in a linear model. ![image](Resources\linear regression.png)
## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 PSI. Based on the results it looks like most lots meet the expectation. Lot3 shows a variance that is greater than 100 which is skewing the total suspension coil data on an aggregate level.Lot 1 and Lot 2 have a variance that is within 100 PSI, thus meets design specifications.![image](Resources\suspension.png)
## T-Tests on Suspension Coils
Based on the results of the t-tests performed on Lot 1, Lot 2, and Lot 3 from the suspension coil test, Lot 3 is definitely an outlier. For testing purposes the mean used to perform the t-test was 1,500 PSI. When all data was used the results were not as effective as grouping the suspension coil data by Lot number.  ![image](Resources\ttest.png)
