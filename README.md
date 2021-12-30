# MechaCar_Statistical_Analysis

Statisitical analysis of automobile performance with R

## Overview

AutosRUs' new MechaCar is "suffering from production troubles" and the company is hoping that an analytical review may help provide some insight. The goal of this project is to:

discover which variables predict the MPG for vehicle prototypes;
collect summary stats on the PSI of suspension coils;
determine if manufacturing lots are statistically different from the mean population;
design a study to compare the MechaCar performance against vehicles from other manufacturers.

## Results

## Linear Regression to Predict MPG

![Linear Regression to Predict MPG](https://user-images.githubusercontent.com/88639467/147792374-1893a99a-e1a6-4400-98d2-cc7eb8396ad3.PNG)


 - The most significant variables in our dataset which show a non-random effect on the MPG of the MechaCar are the Vehicle Length and the Ground Clearance. As indicated by the purple arrows in the image above, a linear regression model run on these variables against figures for MPG, resulted in p-values of 2.6x10-12 and 5.21x10-8, respectively. The intercept was also statistically significant, indicating that there are likely other factors, not included in our dataset, that have a strong impact on the MPG.
 - The slope of the linear model can not be considered to be zero, as the p-value of 5.35x10-11, indicated by the orange arrow above, is lower than even an extreme level of significance, and thus the null hypothesis must be rejected. This means that the relationship between our variables and the miles per gallon is subject to more than random chance.
 - Although there are still unconsidered factors, this model does predict the mpg of the MechaCar prototype with some relative effectiveness. The r-squared value of 0.7149, highlighted in the blue box, indicates that the model is 71% accurate... though it could probably do better.
