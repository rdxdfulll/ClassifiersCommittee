# Dataset

## https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package?resource=download

---------------

## About Dataset
### Context
Ever wondered if you should carry an umbrella tomorrow? With this dataset, you can predict **next-day rain** by training classification models on the target variable **RainTomorrow**.

### Content
This dataset comprises about 10 years of daily weather observations from numerous locations across Australia.

**RainTomorrow is the target variable to predict. It answers the crucial question: will it rain the next day? (Yes or No).**

- This column is marked 'Yes' if the rain for that day was 1mm or more.

### Coverage
- **Temporal Coverage Start Date:** 30/10/2007
- **Temporal Coverage End Date:** 23/06/2017
- **Geospatial Coverage:** Australia

### Provenance
- **Sources:** http://www.bom.gov.au/climate/data



### Source & Acknowledgements
The observations were gathered from a multitude of weather stations. You can access daily observations from http://www.bom.gov.au/climate/data.
For example, you can check the latest weather observations in Canberra here: Canberra Weather.

Definitions have been adapted from the Bureau of Meteorology's Climate Data Online.
Data source: Climate Data and Climate Data Online.

Copyright Commonwealth of Australia 2010, Bureau of Meteorology.

---------------

## Columns:
- **Date**: The date of observation
- **Location**: The common name of the location of the weather station
- **MinTemp**: The minimum temperature in degrees celsius
- **MaxTemp**: The maximum temperature in degrees celsius
- **Rainfall**: The amount of rainfall recorded for the day in mm
- **Evaporation**: The so-called Class A pan evaporation (mm) in the 24 hours to 9am
- **Sunshine**: The number of hours of bright sunshine in the day.
- **WindGustDir**: The direction of the strongest wind gust in the 24 hours to midnight
- **WindGustSpeed**: The speed (km/h) of the strongest wind gust in the 24 hours to midnight
- **WindDir9am**: Direction of the wind at 9am
- **WindDir3pm**: Direction of the wind at 3pm
- **WindSpeed9am**: Wind speed (km/hr) averaged over 10 minutes prior to 9am
- **WindSpeed3pm**: Wind speed (km/hr) averaged over 10 minutes prior to 3pm
- **Humidity9am**: Humidity (percent) at 9am
- **Humidity3pm**: Humidity (percent) at 3pm
- **Pressure9am**: Atmospheric pressure (hpa) reduced to mean sea level at 9am
- **Pressure3pm**: Atmospheric pressure (hpa) reduced to mean sea level at 3pm
- **Cloud9am**: Fraction of sky obscured by cloud at 9am. This is measured in "oktas", which are a unit of eigths. It records how
- **Cloud3pm**: Fraction of sky obscured by cloud (in "oktas": eighths) at 3pm. See Cload9am for a description of the values
- **Temp9am**: Temperature (degrees C) at 9am
- **Temp3pm**: Temperature (degrees C) at 3pm
- **RainToday**: Boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0
- **RainTomorrow**: The amount of next day rain in mm. Used to create response variable RainTomorrow. A kind of measure of the "risk".
