# MechaCar-Statistical-Analysis
### Overview of the analysis
#### The purpose of this project is to help AutosRUs’ newest prototype, the MechaCar, from production troubles that are blocking the manufacturing team’s progress. The project will focus on reviewing the production data for insights that may help the manufacturing team.


### Deliverable 1: Linear Regression to Predict MPG
![Deliverable1](https://user-images.githubusercontent.com/82552516/129606909-36d4e495-5450-4c18-afe3-3781bec28cd3.png)
![deliverable1-2](https://user-images.githubusercontent.com/82552516/129606921-58ce67b2-0d75-49c6-87ef-dbef1978fd26.png)
#### This analysis focuses on analyzing the test results for 50 prototypes of Mechacars to identify ideal vehicle performance.
### 1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
#### The Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to our results, ground clearance and vehicle_weight (as well as intercept) are statistically unlikely to provide random amounts of variance to the linear model.
### 2. Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not zero. The p-value (7.712e-11) is smaller than the assumed significance level (0.05%). Thus we can reject the null hypothesis.
### 3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
#### The linear model predict mpg of MechaCar prototypes effectively. According to the R-squared value (0.7119), this shows that 71.19% of the variations in mpg can be explained by the changes of other variables.


### Deliverable 2: Summary Statistics on Suspension Coils
 ![deliverable2](https://user-images.githubusercontent.com/82552516/129607786-4de540e9-af73-4009-a1cd-660fecbe81d6.png)
 ![deliverable2-2](https://user-images.githubusercontent.com/82552516/129607789-465473b8-5989-4471-911d-d77205c86f40.png)
#### In this dataset, we are analyzingn the weight capacities of multiple suspension coils to determine if the manufacturing process is consistent across production lots.
#### From the total summary, the variance is 62.29356 which is lower than 100 pounds per square inch. Thus meets the design specification (in total). From the lot summary, lot 1 and 2 meets the specification while lot 3 has a high variance (170.2861224), which does not meet the design specification.


### Deliverable 3: T-Tests on Suspension Coils
#### The p-value for all lots is 0.06028 which is greater than 0.05. We fail to reject the null hypothesis.
# ![deliverable3](https://user-images.githubusercontent.com/82552516/129608620-1f89c877-c63e-46eb-b0a0-914f64cfdb1a.png) 
#### The p-value for lot 1 is 1 which is greater than 0.05. We fail to reject the null hypothesis.
# ![deliverable3-2](https://user-images.githubusercontent.com/82552516/129608615-d6c5e12d-3b5b-4da5-95d4-067dd69759dc.png)
#### The p-value for lot 2 is 0.6072 which is greater than 0.05. We fail to reject the null hypothesis.
# ![deliverable3-3](https://user-images.githubusercontent.com/82552516/129608618-c9fb56d2-facb-43ba-a5d8-a8e0b90dab8c.png)
#### The p-value for lot 3 is 0.04168 which is greater than 0.05. We reject the null hypothesis.
# ![deliverable3-4](https://user-images.githubusercontent.com/82552516/129608619-36232bfa-b606-401d-ac4e-0574dd6f58ff.png)


### Deliverable 4: Study Design: MechaCar vs Competition
### What metric or metrics are you going to test?

#### A few metrics that would be necessary to test would be: cost, city or highway fuel efficiency, horse power, maintenance cost, safety rating, enginne type, selling price and other upgrade features (types of seats, wheels, etc).

### What is the null hypothesis or alternative hypothesis?
#### Null Hypothesis: MechaCars have no difference in pricing compared to its competitors based on its perforamce of key factors.
#### Alternative Hypothesis: MechaCars have different pricing in comparison to competitors based onn its performance of key factors.

### What statistical test would you use to test the hypothesis? And why?
#### A multiple linear regression test can be used to determine the factors that have the highest correlation and/or predictability with a dependent factor like the selling price. This can determine which combination has the greatest impact on price.

### What data is needed to run the statistical test?
#### In order to carry out this statistical test, we will need to get data on each of the metrics from MechaCar and its competitors.

