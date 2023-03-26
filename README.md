# MechaCar_Statistical_Analysis
Performing linear regression and T-Testing in R

## Linear Regression to Predict MPG
In the MechaCar data, it was ground_clearance and vehicle_length that had signigicant impact on mpg value variance. By our linear regression model, we can see that the slope is not zero, given our p-value of 5.35e-11, which is well below our significance level of 0.05. Our model fits with an r-squared value of 0.71. This means that approximately 71% of variance in fuel economy can be explained by the model. While this is a reasonable fit, there's likely factors that aren't a part of the model contributing as well. 

## Summary Statistics on Suspension Coils 
![Lot Summary DF](https://raw.githubusercontent.com/Mrob1995/MechaCar_Statistical_Analysis/main/Lot_summary_df.jpg)

Lots 1 and 2 are well within spec with equal median values and a variance well below the prescribed limit of 100PSI. Lot 3, however, has a much higher variance. When looking at all 3 lots as one (as seen below), the total variance falls within spec. 

![Total Summary DF](https://raw.githubusercontent.com/Mrob1995/MechaCar_Statistical_Analysis/main/Total_summary_df.jpg)


## T-Tests on Suspension Coils
![T Testing Lot 1](https://raw.githubusercontent.com/Mrob1995/MechaCar_Statistical_Analysis/main/T_Test_Lot_1.jpg)

![T Testing Lot 2](https://raw.githubusercontent.com/Mrob1995/MechaCar_Statistical_Analysis/main/T_Test_Lot_2.jpg)

![T Testing Lot 3](https://raw.githubusercontent.com/Mrob1995/MechaCar_Statistical_Analysis/main/T_Test_Lot_3.jpg)

As shown in the T Testing images above, the mean of Lots 1 and 2 heave means that fall within our allowable limit. Lot 3 however has a p-value of 0.041 and is statistically different from our population mean. 





## Design a Study Comparing the MechaCar to the Competition
The study fails to account for engine displacement, which would likely be a greater indicator of mpg. Collecting engine displacement information would be relatively quick and easy, and then design a test to see whether or not MechaCar is statistically different from a dataset made up of other vehicles. The null hypothesis would of course be that there is no statistical difference, and the alternative hypothesis would be that there is a statistical difference. We could do so using a single population T Test. 

