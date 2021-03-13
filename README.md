# Python-API-Challenge

Python script, APIs, and JSON traversals to prove the answer to a fundamental question: "What's the weather like as we approach the equator?"

WeatherPy

Python script to visualize the weather of 500+ cities all over the world. Utilize a Python library, and the OpenWeatherMap API website. 

Thus, create a Python script to show each of the following:

•	Scatter plots to showcase the relationships
	Temperature (F) vs. Latitude
	Humidity (%) vs Latitude
	Cloudiness (%) vs. Latitude
	Wind Speed (mph) vs. Latitude

•	Linear regression on each relationship
		o	Northern Hemisphere – Temperature (F) vs. Latitude
		o	Southern Hemisphere – Temperature (F) vs. Latitude
		o	Northern Hemisphere – Humidity (%) vs Latitude
		o	Southern Hemisphere – Humidity (%) vs Latitude
		o	Northern Hemisphere – Cloudiness (%) vs. Latitude
		o	Southern Hemisphere – Cloudiness (%) vs. Latitude
		o	Northern Hemisphere – Wind Speed (mph) vs. Latitude
		o	Southern Hemisphere – Wind Speed (mph) vs. Latitude


VacationPy

Jupter-gmaps and the Google Places API to visualize the weather of 500+ cities all over the world. Utilize a Python library, and the OpenWeatherMap API website. 

Thus, create a script to show each of the following:

•	Heat map that displays the humidity for every city in WeatherPy
•	Create a Dataframe that indicate
		o A max temperature lower than 265 degrees
		o	Wind speed less than 10 mph
		o	Zero cloudiness
•	Utilize Google Places API to find the first hotel for each city located within 5000 meters of the coordinates
•	Plot the hotels on top of your humidity heatmap with each pin containing the Hotel Name, City, and Country

----------------------------------------------------------------------------------------------------------------

Observations

Per the City Latitude vs High Temperature (03/09/3021) scatter plot, the highest temperature occurs closer to the equator (latitude of 0 – 10) and as we travel both up the northern hemisphere, and down the southern hemisphere, the temperature begins to drop/decrease. This is also supported by the linear regression. Northern Hemisphere vs High Temperature has a r squared of 0.79 indicating that as we travel further away from the equator, the temperature decreases. The Southern Hemisphere vs High Temperature linear regression plot also supports this analysis, as there is a correlation of 0.31. This indicate that as we travel closer to the equator, the temperature increases slightly, but not higher than the equator. 

Per the City Latitude vs Cloudiness (03/09/3021) scatter plot, the result indicates both northern hemisphere and southern hemisphere obtain the percentage of clouds similarly. For example, from the plot, observing the 0 % of cloudiness, both northern and southern hemisphere have about similar number of cities who experience no clouds. This is also supported by the linear regression, indicating no correlation at 0.05 for the Northern Hemisphere and 0.09 for the Southern Hemisphere.  

Per the Northern Hemisphere vs Cloudiness and Southern Hemisphere vs Wind Speed linear regression scatter plots, the result indicates that each hemisphere has no correlation with wind speed, at a R squared of 0.02. Thus, the city has no affect on the wind speed and vice versa. 
