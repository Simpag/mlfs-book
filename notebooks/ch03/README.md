## Predict Air Quality

This project builds an Air Quality Forecasting Service for an Air Quality sensor available at https://waqi.info/ using weather data.


Public URL: https://simpag.github.io/mlfs-book/


## Different parts

1. Load historical weather and air quality data from a CSV file into Hopsworks.
2. Fetch new weather and air quality data daily.
3. Train a model on historical data to try to predict air quality.
4. Create predictions with the created model based on weather forecasts.

## Two versions one with lags and one without

We also created a second version of the model which also incorporates air quality lags as a feature in the model.
