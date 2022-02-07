# Bike_sharing_Demand_Linear_Regression
> Using multiple linear regression to understand shared bikes rental demand.


## Table of Contents
* [Bike_demand_linear Regression](#general-information)
* [Multiple Linear Regression](#technologies-used)
* [Conclusions](#conclusions)
* [UpGrad - assignment](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- # Bike Sharing Assigment (Linear Regression)
- ### Problem Statement
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

- ### Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Conclusions
- ### Final Equation (Multiple Linear Regression)
- ### cnt (Rental count) = 0.123  + 0.492 * temp + 0.234 * yr - 0.204 * weathersit_Bad(light snow/rain) - 0.150 * windspeed + 0.082 * season_winter + 0.080 * weathersit_good(clear) + 0.072 * mnth_Sep - 0.068 * season_spring + 0.048 * season_summer - 0.048 * mnth_Jul - 0.045 * Weekday_Sun
- ### >>> top 3 featured effecting bike rentals are
- #### --> temperature: if temperature is higher then bike rentals increase
- #### --> if weather situation is light snow/rain then bike rentals decrease
- #### --> yearly demand is increasing so coming years post pandemic we can expect more bike rental
- ### company can take help of weather and temperature predictions and arrange for more bikes when weather is good and temperature is high, and company can utilize days when weather situation is bad to serivice bikes and keep bikes ready



## Technologies Used
- python
- Numpy
- Pandas
- Seaborn
- Matplotlib
- stats model
- sklearn


## Acknowledgements

- This project was based on [assignment for upGrad]

## Contact
Created by [@PruthviRajuV] - feel free to contact me!

