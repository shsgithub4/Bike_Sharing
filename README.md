# Project Name
Boom Bikes - Multiple linear regression model for the prediction of demand for shared bikes.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

## Conclusions
Important features selected after following RFE technique:
1 Year
2 Working Day
3 Wind Speed
4 Months: January, September, November & December
5 Saturday
6 Seasons: Summer & Spring
7 Weather Situation: Cloudy & Light Rain

Features that are positively increasing the revenue:
1 Year --> Year-on-Year, there is an increase in usage of this service
2 Working Day
3 Month of September
4 Saturday

Features that are negatively influencing the revenue:
1 Windspeed
2 Months of January, November & December repectively
3 Season of Spring & Summer
4 Weather Situation being Cloudy to Light Rain

The best fitting equation of the linear regression model came out to be:
count = 0.535951 + 0.245744 * year + 0.057024 * workingday - 0.192617 * windspeed - 0.118632 * month_dec - 0.123145 * month_jan - 0.112736 * month_nov + 0.055846 * month_sep + 0.066525 * weekday_sat - 0.238120 * season_spring - 0.040292 * season_summer - 0.090099 * weathersit_cloudy - 0.320724 * weathersit_light_rain

Evaluation Results on test data R-Squared: ~79

The error terms are normally distributed
There is a linear relationship between the selected features
All the selected features are independent
Error terms are randomly distributed and homoscedastic in nature

## Contact
Created by [@shsgithub4] - feel free to contact me!
