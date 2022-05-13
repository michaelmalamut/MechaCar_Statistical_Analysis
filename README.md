# MechaCar_Statistical_Analysis

The objective of this analysis is to understand the production data.

## Linear Regression to Predict MPG

![summary_lm_mpg](https://user-images.githubusercontent.com/97328622/168376260-c7695196-927d-4818-b5a5-10badd9a45b1.png)

As we can see in the multiple linear regression, the two variables, vehicle_length and ground_clearance have a statistical significance on MPG. Both variables had p-values below the significance level of 0.05%.

The multiple r-suare value is 0.7149 and the p-value is velow the significance level of 0.05%, this is enough sufficient evidence to reject the null hypothesis (The slope of the linear model is not zero).

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

![total_summary](https://user-images.githubusercontent.com/97328622/168377290-a9bc2721-0db5-4e8d-9979-079e773f2939.png)

![lot_summary](https://user-images.githubusercontent.com/97328622/168377313-a80f72e4-269d-4fa0-a3e9-536141d253a9.png)

* The current manufacturing data meets the design specification of not exceeding 100 psi for Lot 1 and Lot 2.
* Lot3 does not meet the design specification with a variance of 170 psi which exceeds the 100 threshold for this excercise.

## T-Test on Suspension Coils

![t_tests](https://user-images.githubusercontent.com/97328622/168377898-206eea00-351a-4106-a554-2dc01a6ba493.png)

* The p-value of the suspension coil’s PSI is 0.06028, which is above the significance level of 0.05% and therefore demonstrates that it is not statistically different from the mean population PSI results.

* The p-value for Lot1 is larger than the 0.05 significance level.

* The p-value for Lot2 is larger than the 0.05 significance level.

* The p-value for Lot3 is smaller than the 0.05 significance level.

## Study Design Comparing the MechaCar to the Competition
