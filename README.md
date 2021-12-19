# Data on Cars used for Testing Fuel Economy
## by kourosh sadeghi


## Dataset

The test data used to determine fuel economy is derived from vehicle testing done at
EPA's National Vehicle and Fuel Emissions Laboratory in Ann Arbor, Michigan,
and by vehicle manufacturers who submit their own test data to EPA.
this dataset contains 832 rows with 13 features that shows properties about varieties of cars in 2018
sume of these features about model cars are: kind of fuel of car,
number of engine cylinders, number of wheel Drive, vehicle classes and ...


## Summary of Findings

in this exploration I found some perfect relationships between variables. 
the correlation between displ and city_mpg and hwy_mpg are approximately strong negative.
corelation between displ and greenhouse gas score is approximately negative.
we have other positive relation coefficient between greenhouse gas score and city_mpg and hwy_mpg.
one of the biggest exploration in this dataset is negative relation between greenhouse gas score and displ.
we found negative relation between number of engine cylinders and city_mpg, hwy_mpg and approximately greenhouse gas score.
both of 2WD and 4WD have the same air pollution score, but for greenhouse gas score, we have this score for 4WD less than 2WD
we find out standard SUV car has minimum rating in all of numeric variables. before this class of car,
trend of these variables the trends have been almost upward


## Key Insights for Presentation

for this presentation, I want to focus most relationship between numeric variables and ordinal variables
air pollution score and grean house score and fuel can have effect making decision to produce cars using other features.
that is why, we beside some other numeric variables, we focus on pollution score and grean house.
first of all, I drawed some frequency of each variables. for numeric I used histogram and for ordinal
variables I drawed countplot. after that I compared each two numeric variables together, and compare with categorical
variables. (used vilion plot and boxplot to compare number of engine with all numeric variables, number of wheel drive with
all numeric variables
finally, we did Bivariate Exploration: air_pollution_score and city_mpg in kind of car classes,
air_pollution_score and city_mpg in kind of fuel, greenhouse_gas_score and displ in kind of car classes,
 greenhouse_gas_score and displ in kind of fuel, greenhouse_gas_score and fuel in kind of car classes.