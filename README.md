# Predictive Age Modeling for Abalones

## Question
How does the number of rings an abalone has, and consequently its age, depend on its physical dimensions and weight?

## Introduction

In this project, we will be developing a model that predicts the age of an abalone using easily measurable physical traits. The data set we are using is from the UCI Machine Learning Repository. It contains comma-separated values with no headers and contains 4177 instances. It includes the `sex`, `length (mm)`, `diameter (mm)`, `height (mm)`, `whole weight (grams)`, `shucked weight (grams, meat weight)`, `viscera weight (grams, gut weight after bleeding)`, `shell weight (grams, after drying)`, and `number of rings` of a given abalone. 

The range of the continuous variables has been pre-scaled by dividing by 200. Our target variable is the number of rings, which can then be used to calculate the age of an abalone in years by adding 1.5 to it.




