# python-api-challenge
To run the WeatherPy.ipynb and VacationPy.ipynb notebooks
create a api_keys.py file in the respective directories and add the weather API key 
and google API key as follows.
# api_keys.py

# OpenWeatherMap API Key
weather_api_key = "YOUR KEY HERE!"

# Google API Key
g_key = "YOUR KEY HERE!"  


Observation :
Trend1: Temperature with Latitude
The temperature and the latitude are correlated. Meaning that, when the Latitude increases or decreases the Temperature changes correspondingly.

Trend2:

The Northern Hemisphere Linear regression shows that it has strong negative corrlation with temperature.When latitude increases the temperature decreases.
The Southern Hemisphere Linear regression shows that it has strong positive corrlation with temperature.When the latitude increases the temperature increases.

Trend3: Humidity,Cloudiness and Windspeed with Latitude

The Humidity,cloudiness and wind speed shows weak or no relationship with Latitude.Which means the Increase in latitude less likely will impact the humidity,cloudiness and windspeed.
