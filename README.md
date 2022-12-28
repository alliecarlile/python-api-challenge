This project is a visual analysis illustrating how the weather changes as the equator is approached. The results of the analysis are used to predict the most pleasant vacation locations.

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

This project was completed using the following workflow:

Part 1: WeatherPy
In this deliverable, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. 

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).

Next, create a series of scatter plots. Include the linear regression line, the model's formula, and the r values.

Sample scatter plot with the linear regression line.
Create the following plots:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

Part 2: VacationPy

In this deliverable, use your weather data skills to plan future vacations. Also, use Jupyter notebooks, the geoViews Python library, and the Geoapify API. Use the Geoapify API and the geoViews Python library to create map visualizations.

Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.

Humidity map
Narrow down the city_data_df DataFrame to find your ideal weather condition. 

Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

Add the hotel name and the country as additional information in the hover message for each city on the map.

**Methods used:**

Python

APIs

Jupyter Notebooks

Linear Regression

R values

geoViews

Geoapify API

