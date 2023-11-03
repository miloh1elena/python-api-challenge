# python-api-challenge

## Weather Data Visualization and Hotel Search

This Python script allows to visualize weather data and search for hotels in cities around the world. It utilizes several libraries, including Pandas, Folium, OpenWeatherMapAPI and Geoapify API. The process is broken down into the following steps:

1. **Weather Data Retrieval**: Retrieving weather data for a list of cities using the OpenWeatherMap API. The data includes information such as city, country, coordinates, temperature, humidity, and more.

2. **Data Filtering**: To find ideal weather conditions, filter the data based on criteria like temperature, humidity, wind speed, and cloudiness. The filtered data is stored in a Pandas DataFrame.

3. **Hotel Search**: se the Geoapify API to search for hotels near the coordinates of each city that meets our criteria. The hotel names are retrieved and added to the DataFrame.

4. **Map Visualization**: Folium is used to create an interactive map with markers for each city. The markers include a popup with details about the city, country, humidity, and hotel name. The markers are color-coded based on hotel availability (green if found, red if not).

5. **Map Legend**: The map includes a legend for marker colors, allowing to easily distinguish between cities with and without hotels.

6. **Popup Details**: Hovering over a city marker reveals additional information such as latitude, longitude, and a link to the hotel's website if available.

This script provides a convenient way to explore ideal travel destinations based on weather conditions and find nearby hotels for trip planning needs.