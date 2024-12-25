# Bike-sharing-assignment


## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

## Conclusions

1. R2 value is 0.81 which is good and the model is able to explain 81% of the variance in the target variable
2. The p-values of the coefficients are less than 0.05
3. The VIF values are less than 5
4. The residuals are normally distributed
5. The actual vs predicted values are linearly related

### Significant variables are
1. atemp
2. yr
3. Season(Spring, Winter)
4. Month(Dec, Jul, Mar, Nov, Sept)
5. WeatherSit(Bad, Good)
6. Humidity
