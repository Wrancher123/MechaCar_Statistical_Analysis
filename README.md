# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![image](https://github.com/Wrancher123/MechaCar_Statistical_Analysis/blob/main/Image/Linear%20Regression%20to%20Predict%20MPG.png)

#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

* Since these variables significantly affect the vehicle's fuel economy, their individual p-values are taken into account to determine the amount of variance they can provide. If the p-value is below 0.05, the variance generated by these variables will not be random.
The following factors contribute to the overall performance of a vehicle: ground clearance, vehicle length, and intercept. They generated a non-random amount of variance that can be used to estimate the vehicle's overall performance. When an intercept is significantly significant, it means that other factors or effects are also contributing to the variation in the vehicle's fuel economy.

* intercept (p-value = 5.08e-8), ground clearance (p-value = 5.21e-8), and vehicle length (p-value = 2.60e-12)

#### Is the slope of the linear model considered to be zero? Why or why not?

* The p-value of our study is 5.35e-11, which is significantly smaller than the significance level of 0.05%. This means that our hypothesis can be rejected. It also shows that the linear model of the car is not zero. This means a significant relationship exists between the variables and the vehicle's fuel economy.

#### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

* The Multiple R-squared:  0.7149 and p-value: 5.35e-11 of the study are two of the most important factors that we need to analyze in order to confirm if the linear model can predict the vehicle's fuel economy. The results of the study show that the model has a strong positive relationship with the variables.

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

### Total Summary
![image](https://github.com/Wrancher123/MechaCar_Statistical_Analysis/blob/main/Image/Total%20Summary.png)

* The data collected from the various manufacturing facilities in the country meet the design specification for the vehicle. According to the study's results, the variance of 62.293 psi is within the vehicle's fuel economy requirements and does not exceed 100 psi.

### Lot Summary
![image](https://github.com/Wrancher123/MechaCar_Statistical_Analysis/blob/main/Image/Lot%20Summary.png)

* The data collected for each lot's manufacturing facilities partially meet the design specification. According to the results, the data for Lot 1 and 2 meet the design specification requirements. However, the data for Lot 3 shows that it exceeds the needs of the design specification, which is 100 psi. 

## T-Tests on Suspension Coils

If we reject or fail to reject the hypothesis, the p-value is a statistical measure determining if the sample's population mean and the presumed population means differ. The result of the p-value is shown as 0.060 for all manufacturing lots. The p-value for lot 1 is 1.000, for lot 2, it is 0.607, and lot 3 is 0.042. In all cases, the p-value is above the assumed significance level of 0.05. Therefore, there is enough evidence and can reject the hypothesis, meaning that the two means are statistically different. 

### ALl Lots
![image](https://github.com/Wrancher123/MechaCar_Statistical_Analysis/blob/main/Image/All%20Lots.png)

### 1 Lots
![image](https://github.com/Wrancher123/MechaCar_Statistical_Analysis/blob/main/Image/Lot%201.png)

### 2 Lots
![image](https://github.com/Wrancher123/MechaCar_Statistical_Analysis/blob/main/Image/Lot%202.png)

### 3 Lots
![image](https://github.com/Wrancher123/MechaCar_Statistical_Analysis/blob/main/Image/Lot%203.png)

## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

#### What metric or metrics are you going to test?

* Safety features and rating on vehicles 2022 versus 2000.

#### What is the null hypothesis or alternative hypothesis?
* Null Hypothesis: Today vehicles safety feature are better than previous 20 years ago.
* Alternative Hypothesis: Today vehicles safety feature are not better than previous 10 years ago.

#### What data is needed to run the statistical test?

* Safety rating and their individual features ratings 
* The module and type of the vehicles
* Customer Ratings. 






