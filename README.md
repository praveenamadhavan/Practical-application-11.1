# Practical-application-11.1
 Berkeley Haas AIML - What drives the price of a car

 OVERVIEW

In this application, you will explore a dataset from kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. Your goal is to understand what factors make a car more or less expensive. As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car

-Objective

The goal of this bussiness is to access the variables and features that influence on the decision when a consumer is purchasing an used car. The success is associated with the purchase of the right inventory with the lowest price in a car category that can have high purchase/selling turn over. -Analyze the situation

The resources available for this project involves a huge dataset, however, these entries might not carry clean data. The cost benefit with this project can imporve the logistics of the bussiness in accessing the righ inventory purchase to increase purchase/selling turnover.

-Data mining

The data mining will involve looking for the 3 most important features/variables that guides the price of a used car.

-Prepare a projectplan

We will start developing a model to indentify cars that are below the average price and that can optimize the earning upon selling. We will take in consideration the year, odometer and car condition. The future plan is to send apply this model in cars announced in the area and send a car mechanic for vehicle appraisal. To create the model we will use linear regression models and gridCV search to look for the lowest MSE in the training and testing dataset.

After trying Linear Regression, Lasso and Ridge models with different feature combinations, below are the findings


    Year - Newer the car the price is higher
    Manufacturer - Most of the cars available are by Chevrolet or Ford
    Odometer - Majority of the cars have run less than 50,000
    Fuel - Majority of the available used cars has gas

Recommendation Looking at the prices and the features listed, we can conclude that the main features that affect the car price mode than the others are 'Manufacturer' (specifically Totota or Volvo) and 'Type' of vehicles prices are higher for pickup and SUVs than offroad ones.
