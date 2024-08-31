# World_Weather_Analysis

![weather_image](https://github.com/user-attachments/assets/e89fcd9e-7be2-400f-aff6-2db154964cfc)

# Instructions
This activity is broken down into two deliverables, WeatherPy and VacationPy.
# Part 1: WeatherPy
Create a Python script to visualize the weather of over 500 cities of varying distances from the equator using the OpenWeatherMap APILinks. 
In this Part, I used the WeatherPy.ipynb starter Jupyter notebook provided in the starter folder. 

# Requirement 
1. Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement,the OpenWeatherMap API is uded to retrieve weather data from the cities list generated in the starter code. Next, A series of scatter plots is created  to showcase the following relationships:

   •	Latitude vs. Temperature
   ![Fig1](https://github.com/user-attachments/assets/22d777ba-bc98-4381-8d6b-cf7b2bec6781)

   •	Latitude vs. Humidity
   
   •	Latitude vs. Cloudiness
   
   •	Latitude vs. Wind Speed
![Fig4](https://github.com/user-attachments/assets/ed46ed00-886e-4be9-a4c2-dffff15b3017)

3. Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. The plots are seperated into Northern 
Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 
Next, a series of scatter plots is created and analyised :

   •	Northern Hemisphere: Temperature vs. Latitude
   
   •	Southern Hemisphere: Temperature vs. Latitude
   
   •	Northern Hemisphere: Humidity vs. Latitude
   
   •	Southern Hemisphere: Humidity vs. Latitude
   
   •	Northern Hemisphere: Cloudiness vs. Latitude
   ![Northern_Hemisphere_cloudiness](https://github.com/user-attachments/assets/1ef456e9-886a-478b-a100-8491111d47d2)

   •	Southern Hemisphere: Cloudiness vs. Latitude
   
   •	Northern Hemisphere: Wind Speed vs. Latitude
   
   •	Southern Hemisphere: Wind Speed vs. Latitude
![Southern_Hemisphere_windspeed](https://github.com/user-attachments/assets/8c871384-7654-4c73-a1fc-6335b179e367)

# Part 2: VacationPy
In this part weather data skills was used to plan future vacations. Also, use Jupyter notebooks, the geoViews Python library, and the Geoapify API used used.The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 was provided to help get started. 

# Requirments
1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city. Maps are plotes and analyised.
 
2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
   o	A max temperature lower than 27 degrees but higher than 21
   
   o	Wind speed less than 4.5 m/s
   
   o	Zero cloudiness

3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
   
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
   
5. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
 
# Table of Contents
  1. vacationPy.ipynb: vacation analysis and visualization jupyter notebook.
  2. weatherPy.ipynb: weather analysis and visualization jupyter notebook.
  3. Fig1.png: city latitude vs max temp.
  4. Fig2.png: city latitude vs humidity.
  5. Fig3.png: city latitude vs cloudness
  6. Fig4.png: city latitude vs wind.
  7. cities.csv: csv file with the data needed.
  8. City Humidity Map inside the vacation jupuyter notebook
  9. Hotel Location Map inside the vacation jupuyter notebook
  10. Northern_Hemisphere_cloudniness.png
  11. Southern_Hemisphere_cloudniness.png
  13. Northern_Hemisphere_humididity.png
  14. Southern_Hemisphere_humididity.png
  15. Northern_Hemisphere_windspeed.png
  16. Northern_Hemisphere_windspeed.png
