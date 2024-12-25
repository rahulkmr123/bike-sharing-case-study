# Bike-sharing-assignment


## General Information
BoomBikes, a US bike-sharing provider, has faced revenue drops due to the COVID-19 pandemic. To recover, they aim to understand the factors affecting bike demand post-lockdown. They seek to identify significant variables predicting bike demand and how well these variables describe the demand.

## Business Goal:
Model the demand for shared bikes using available independent variables. This model will help management understand demand dynamics and adjust business strategies to meet customer expectations and capture new market opportunities.

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
