# python-api-challenge

This project utilizes Python APIs, data visualization, and geospatial mapping to analyze weather patterns across different latitudes and plan potential vacation destinations. The project consists of two main components:

WeatherPy - Analyzing weather trends using OpenWeatherMap API.
VacationPy - Visualizing vacation spots based on weather conditions using the Geoapify API and geoViews library.

- Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- SciPy
- ChatGPT

Part 1: WeatherPy
In this section, we retrieve weather data for 500+ cities worldwide using the OpenWeatherMap API. We then analyze the relationships between latitude and various weather conditions.

Objectives:
Generate random geographic coordinates and find the nearest cities.
Retrieve weather data (temperature, humidity, cloudiness, wind speed).
Create scatter plots to analyze relationships between latitude and weather variables.
Perform linear regression for both hemispheres to understand trends.
Plots Generated:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Each scatter plot includes a regression line, the model’s formula, and the R² value to measure correlation.

Part 2: VacationPy
In this section, we use the weather data to identify ideal vacation spots and visualize them on a map.

Objectives:
Filter cities based on ideal weather conditions for vacations.
Use Geoapify API to find nearby hotels for selected destinations.
Create a map displaying cities with hotel locations.
Adjust map points' size based on humidity levels.
