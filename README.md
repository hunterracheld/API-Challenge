# API-Challenge

In this project, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I used a simple Python library, the OpenWeatherMap API to create a representative model of weather across world cities.

My objective was to build a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

The final notebook:
  - Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.
  - Performs a weather check on each of the cities using a series of successive API calls.
  - Includes a print log of each city as it's being processed with the city number and city name.
  - Saves both a CSV of all data retrieved and png images for each scatter plot.

My observations are included at the top of my jupyter notebook
