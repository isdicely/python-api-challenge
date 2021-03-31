In the first part of this project we will attempt to look at what happens to weather across different latitudes. Visualizatiosn will be created to describe effects of:
    Temperature (F) vs. Latitude
    Humidity (%) vs. Latitude
    Cloudiness (%) vs. Latitude
    Wind Speed (mph) vs. Latitude

To further analyze the information the following visualizations will be created to see if any significant relationships occur:
    Northern Hemisphere - Temperature (F) vs. Latitude
    Southern Hemisphere - Temperature (F) vs. Latitude
    Northern Hemisphere - Humidity (%) vs. Latitude
    Southern Hemisphere - Humidity (%) vs. Latitude
    Northern Hemisphere - Cloudiness (%) vs. Latitude
    Southern Hemisphere - Cloudiness (%) vs. Latitude
    Northern Hemisphere - Wind Speed (mph) vs. Latitude
    Southern Hemisphere - Wind Speed (mph) vs. Latitude

In the second part of the project, the data retrieved in the first part will be utilized to select the ideal locations for vacation.

To create a representative model of weather across world cities the Python libray, citipy was used to get coordinates from 1000 cities in random. API requets were made to the OpenWeatherMap API to retrieve weather information. Data analysis and visualizations were done in Jupyter notebook using pandas and matplotlib.

For the second part, the data retrieved and cleaned in the first part was passed in jupyter-gmaps and Google Places API to create a heat map that displays the humidity for every city retrieved. The city data was further narrowed by by selecting only cities that met a narrow criteria making them ideal locations to visit. Google Places API was then used to find the nearest lodging (within 5Km) of the ideal cities. The lodging information was merged with the heat map along with a information box for each lodging retrieved. 

The following files were saved:
    CSV of alal retrieved data
    PNG images for all scatter plots
    PNG images for all regression plot
    PNG images of screen shots of:
        heat map and merged heat map plus lodging markers
    
Observations from the scatter plots and regression plots is embedded in the Jupyter notebook Weathery.ipynb