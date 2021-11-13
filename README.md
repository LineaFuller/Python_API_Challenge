# Python_API_Challenge

## Background 
What are the best cities to travel too with the best weather? 
I was able to definitevly answer these questions with representative visualizations of data by successfully constructing multiple API calls. For this challenge, I created analytical visualizations of the weather across 500+ cities worldwide and examined their vacation potential using the Google Maps API. 

## Weather
Utilizing Python Library and OpenWeatherMap API, I constructed a series of scatterplots comparing and explaining the following relationships:

<<Temperature (F) vs. Latitude>>
<<Humidity (%) vs. Latitude>>
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

Then, I ran a linear regression and further analyzed the results from my calculations regarding the following relationships: 

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

## Vacation
I located ideal vacation destinations using jupyter gmaps and Google Places API. I first created a heatmap based on the humidity levels of each city. Then, I filtered my dataframe by locking cities with ideal weather conditions, such as the following:

A max temperature lower than 80 degrees but higher than 70
Wind speed less than 10 mph
Zero cloudiness
Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal

I located the first hotel within a 5000 meter radius of the coordinates for each city. After pulling my results, I plotted the location of the hotels with markers. 
