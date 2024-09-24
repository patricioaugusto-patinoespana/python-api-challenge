# WeatherPy
## Overview
The WeatherPy project aims to analyze weather data for over 500 cities around the world. Using Python libraries, the OpenWeatherMap API, and linear regression analysis,
we study the relationship between various weather parameters (temperature, humidity, wind speed, and cloudiness) and geographic coordinates (latitude).

## Features
Generate a list of random geographic coordinates and corresponding cities using the citipy library.
Retrieve real-time weather data for each city using the OpenWeatherMap API.
Analyze the relationships between latitude and weather conditions such as:
- Temperature
- Humidity
- Cloudiness
- Wind speed
Perform linear regression analysis on the Northern and Southern Hemispheres separately for each weather factor.
Plot scatter plots and regression lines to showcase these relationships.

## Project Dependencies
Python 
Pandas for data handling and manipulation.
NumPy for generating random coordinates.
Matplotlib for creating visualizations.
Requests for fetching data from the OpenWeatherMap API.
SciPy for performing linear regression.
Citipy for determining the nearest cities based on latitude and longitude coordinates.

## Running the Code
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

## Conclusion
This project provides insights into global weather patterns and helps demonstrate how latitude can affect temperature, humidity, cloudiness, and wind speed. 
The generated plots and regression analyses allow for a deeper understanding of how weather behaves in different parts of the world.

# VacationPy
VacationPy is a data analysis project that visualizes weather data to help you find your ideal vacation destination based on specific weather criteria. The project uses various Python libraries for data manipulation, visualization, and interaction with APIs to identify ideal vacation spots and nearby hotels.

## Overview
VacationPy leverages weather data from multiple cities around the world and visualizes it on an interactive map. Based on certain weather conditions (such as temperature, wind speed, and cloudiness), the project narrows down the cities that match ideal vacation weather. Using the Geoapify API, the app also finds hotels near the selected cities, helping users to plan their ideal getaway.

## Technologies
This project uses the following technologies:
- Python
- Pandas
- hvPlot
- Geoapify API
- CSV

## Running the Code
- Display City Points on Map:
An interactive map is created that displays points for each city, where the size of the point corresponds to the humidity of the city.
- Narrow Down Cities with Ideal Weather Conditions:
The cities are filtered to meet the following weather criteria:
Max Temperature between 20°C and 70°C
Wind Speed below 10 km/h
Cloudiness below 20%
Any cities with missing data are dropped.
- Create Hotel DataFrame:
A new DataFrame (hotel_df) is created to store the city name, country, coordinates (latitude and longitude), and humidity. An empty column for hotel names is added.
- Use Geoapify API to Find Hotels:
For each city in the hotel_df, the Geoapify API is used to find the nearest hotel within a 10,000-meter radius.
The name of the nearest hotel is stored in the Hotel Name column of the DataFrame. If no hotel is found, it is marked as "No hotel found".
- Display Hotel Info on the Map:
The hotel name and country are included in the hover message for each city on the interactive map.

## Conclusion
VacationPy provides an interactive and visually engaging way to explore potential vacation destinations based on specific weather preferences. By leveraging Python's data analysis and visualization tools, as well as the Geoapify API for finding nearby hotels, the project not only identifies ideal vacation spots but also offers practical insights for travel planning. Whether you're searching for a sunny getaway or a cool escape, VacationPy makes the process intuitive and efficient. This project demonstrates how weather data and mapping technologies can be combined to create useful, real-world applications for travel enthusiasts.
