# python-api-challenge
## GA Tech Data Science Analytics Boot Camp Module 6
### Description: WeatherPy
By utilizing DataFrames and the OpenWeatherMap API, 500+ cities will be used to display a series of scatter plots to show the following:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

To fulfill the second requirement, the linear regression is computed for each relationship. The scatterplots will display the same relationships for the northern hemisphere and the southern hemisphere as well as the linear regression line and its equation. 
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

The scatterplots will be saved as PNG image files and a generated CSV file output will contain all of the retrieved data.

### Description: VacationPy
Using the data stored in the CSV file from WeatherPy and GMAP library, a heatmap will be generated to display the humidity levels of the WeatherPy processed cities. 

Subsequently, pins containing Hotel Name, City, and Country will be plotted on top of the Heatmap. These pins are determined using the Google Places API to locate the closest hotel within a 5000 mile radius. 

From the list of 500+ cities, the cities used for the pins are cities where the max temp is less than 290 degrees F, humidity is less than 75%, wind speed is less than 4 mph, and cloudiness is less than 10%.

### Submission Requirements
* WeatherPy Jupyter notebook
* WeatherPy Scatterplot Images
* WeatherPy CSV file with data retrieved from API
* VacationPy Jupyter notebook
* VacationPy Heatmap Images
