# Bike Sharing system : Prediction of demand for shared bikes
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    1. Which variables are significant in predicting the demand for shared bikes.
    2. How well those variables describe the bike demands


## General Information
Created a multiple linear regression model for the prediction of demand for shared bikes



## Conclusions
Model equation
cnt = 0.267 + 0.609 X temp + 0.115 X season_4 + 0.077 X month_9 + 0.227 X yr_1 - 0.099 X holiday - 0.254 X hum - 0.179 X windspeed - 0.202 X weather_3

Predictor Variables

temp : temperature
yr_1 : year - 2019
season_4 : Season - Winter
month_9 : Month - September
holiday
hum - Humidity
Windspeed
weather_3 - weather - Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
Inference:

Temperature, Season, month and year have postive impact on cnt whereas holiday, humidity, windspeed had negative impact on cnt

Final observations of the model -
The RSquare for training set turned out to be 0.805
The R Square computation with test set is 0.779 which is very close to the 0.80 observed during the training set
The residual are centred around 0, which is ideal
All the linear regression Assumptions are validated


## Contact
Created by venkehv - feel free to contact me!

