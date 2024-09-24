##WeatherPy
#Overview
The WeatherPy project aims to analyze weather data for over 500 cities around the world. Using Python libraries, the OpenWeatherMap API, and linear regression analysis,
we study the relationship between various weather parameters (temperature, humidity, wind speed, and cloudiness) and geographic coordinates (latitude).

#Features
Generate a list of random geographic coordinates and corresponding cities using the citipy library.
Retrieve real-time weather data for each city using the OpenWeatherMap API.
Analyze the relationships between latitude and weather conditions such as:
- Temperature
- Humidity
- Cloudiness
- Wind speed
Perform linear regression analysis on the Northern and Southern Hemispheres separately for each weather factor.
Plot scatter plots and regression lines to showcase these relationships.

#Project Dependencies
Python 
Pandas for data handling and manipulation.
NumPy for generating random coordinates.
Matplotlib for creating visualizations.
Requests for fetching data from the OpenWeatherMap API.
SciPy for performing linear regression.
Citipy for determining the nearest cities based on latitude and longitude coordinates.

#Running the Code
To run the code:
Generate the cities list by creating random latitude and longitude values and using the citipy library to find the nearest cities.
Use the OpenWeatherMap API to fetch weather data for each city.
Create scatter plots showing the relationship between latitude and:
- Temperature
- Humidity
- Cloudiness
- Wind speed
Perform linear regression to identify trends for cities in the Northern and Southern Hemispheres.
Export the results as images.

#Conclusion
This project provides insights into global weather patterns and helps demonstrate how latitude can affect temperature, humidity, cloudiness, and wind speed. 
The generated plots and regression analyses allow for a deeper understanding of how weather behaves in different parts of the world.



