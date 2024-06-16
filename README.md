# Air-Quality-Prediction-in-Major-Cities-of-India
In this project, I developed a machine learning model predicting AQI in India using historical data, meteorological factors, and pollution sources, achieving 89% accuracy. This project aids in mitigating urban air pollution and deals with  predictive modeling, data preprocessing, feature engineering, time-series analysis, and model evaluation.

# Business Question:
What effect do meteorological variables have on air quality measures such as PM2.5 and PM10 levels?

# Description of Data:
This collection contains real-time weather data for key cities in India. In contrast to forecast data, this dataset provides a full range of characteristics reflecting current weather conditions.
It has over 40 characteristics, including measures of temperature, wind, pressure, precipitation, humidity, visibility, and air quality. This dataset is an invaluable resource for assessing current weather patterns in India and investigating the links between various weather factors.

# Plan for Analysis with the data:
Effect of meteorological variables such as temperature and humidity have on air quality measures such as PM2.5 and PM10 levels. Meteorological conditions that cause higher levels of Carbon Monoxide or Nitrogen Dioxide. Businesses, public health authorities, and politicians may make educated decisions to enhance air quality and limit the impact of weather-induced air pollution by examining the link between meteorological conditions and air quality data. We're employing a dataset rich with weather data in the "India Weather Insights 2023" project. This information assists us in understanding and forecasting the weather in various Indian cities. Our objective is to find the best approach for making accurate weather predictions. To do this, we will analyse and compare many ways before picking the most dependable one. This project will provide crucial information on India's weather patterns.

# Information on Data Provenance:
This collection includes real-time meteorological information for key Indian cities, with over 40 attributes indicating current weather conditions. The information is current as of August 29, 2023.
•	country: Country of the weather data
•	location_name: Name of the location (city)
•	region: Administrative region of the location
•	latitude: Latitude coordinate of the location
•	longitude: Longitude coordinate of the location
•	timezone: Timezone of the location
•	last_updated_epoch: Unix timestamp of the last data update
•	last_updated: Local time of the last data update
•	temperature_celsius: Temperature in degrees Celsius
•	temperature_fahrenheit: Temperature in degrees Fahrenheit
•	condition_text: Weather condition description
•	wind_mph: Wind speed in miles per hour
•	wind_kph: Wind speed in kilometers per hour
•	wind_degree: Wind direction in degrees
•	wind_direction: Wind direction as 16-point compass
•	pressure_mb: Pressure in millibars
•	pressure_in: Pressure in inches
•	precip_mm: Precipitation amount in millimeters
•	precip_in: Precipitation amount in inches
•	humidity: Humidity as a percentage
•	cloud: Cloud cover as a percentage
•	feels_like_celsius: Feels-like temperature in Celsius
•	feels_like_fahrenheit: Feels-like temperature in Fahrenheit
•	visibility_km: Visibility in kilometers
•	visibility_miles: Visibility in miles
•	uv_index: UV Index
•	gust_mph: Wind gust in miles per hour
•	gust_kph: Wind gust in kilometers per hour
•	air_quality_Carbon_Monoxide: Air quality measurement: Carbon Monoxide
•	air_quality_Ozone: Air quality measurement: Ozone
•	air_quality_Nitrogen_dioxide: Air quality measurement: Nitrogen Dioxide
•	air_quality_Sulphur_dioxide: Air quality measurement: Sulphur Dioxide
•	air_quality_PM2.5: Air quality measurement: PM2.5
•	air_quality_PM10: Air quality measurement: PM10
•	air_quality_us-epa-index: Air quality measurement: US EPA Index
•	air_quality_gb-defra-index: Air quality measurement: GB DEFRA Index
•	sunrise: Local time of sunrise
•	sunset: Local time of sunset
•	moonrise: Local time of moonrise
•	moonset: Local time of moonset
•	moon_phase: Current moon phase
•	moon_illumination: Moon illumination percentage
