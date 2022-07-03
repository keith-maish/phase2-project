# King County real-estate
### Author: Keith Maina

## Overview
In this project we are going to be examining real estate data to perform predective modelling for the sake of being able to gauge the prices of homes that haven't been priced yet.
We also perform a statistical test to know whether the presence of a waterfront affects the price of a home.

## Business Understanding
#### <u>Stakeholder</u>
This project is for a real estate agency that helps homeowners buy and/or sell homes.
#### <u>Business Problem</u>
Create predictive model for prices of homes to be able to easily discern values of houses.
#### <u>Business Question</u>
Is waterfront property more valuable than non- waterfront property?

## Data
This project uses the King County House Sales dataset. We use it because it has information on house pricing and the factors to consider when buying a house.

## Methods
The data provided was fairly clean, to start with. All i had to do was remove the null values, and I chose to do so instead of filling the empty data points with values, because for modelling, I believe that for predictive modeling you should only use original data in order to maximize accuracy.

I also had to remove question marks from the 'sqft_basement' column and replace them with zeros. I assumed the question marks meant that the basement square footage was unknown.

For the statistical test, I split the data into 2 datasets, one containing pricing on houses with a waterfront and one containing pricing on houses without a waterfront.

## Conclusions
I was able to produce a model after 5 iterations and I chose it for having the least Mean Absolute Error when comparing the predicted values of said model with actual test values.

After conducting the test, I was able to come to the conclusion that the presence of a waterfront greatly increases the value of a home.