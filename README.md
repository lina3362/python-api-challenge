# python-api-challenge

# WeatherPy

1,Dependencies and Setup
2,Import API key
3,Incorporated citipy to determine city based on latitude and longitude
4,Output File (CSV)
5,Range of latitudes and longitudes

Generate Cities List
1,List for holding lat_lngs and cities
2,Create a set of random lat and lng combinations
3,Identify nearest city for each lat, lng combination
4,Print the city count to confirm sufficient count

Perform API Calls
1,Create a dataframe to store the data
2,Preview the dataframe

creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator
1,set up base url
2,extract results 
3,input data into the dataframe
4,print results

Convert Raw Data to DataFrame
1,read the csv file and sort the columns
2,Decribing the weather data frame

Inspect the data and remove the cities where the humidity > 100%.
1,found 1 line has a humidity over 100, filter it out and re-describing the data frame
2,get indices information on humidity higher than 100
3,find what value might be outliers
4,Make a new DataFrame equal to the city data to drop all humidity outliers by index.
5,according to the result above, only 1 city's humidity is a outlier (290)
6,specify the column Humidity
7,Save the cleaned data csv file



* Temperature (F) vs. Latitude
1,Create Latitude vs. Temperature Plot scatter plot
2,set titles
3,set labels
4,set grid line
5,save the plotted figure

* Humidity (%) vs. Latitude
1,Create Latitude vs. Humidity Plot scatter plot
2,set titles
3,set labels
4,set grid line
5,save the plotted figure

* Cloudiness (%) vs. Latitude
1,Create Latitude vs. Cloudiness Plot scatter plot
2,set titles
3,set labels
4,set grid line
5,save the plotted figure

* Wind Speed (mph) vs. Latitude
1,Create Latitude vs. Wind Speed Plot scatter plot
2,set titles
3,set labels
4,set grid line
5,save the plotted figure

Linear Regression
1,Create Northern and Southern Hemisphere DataFrames
2,Set up x y 
3,set up the linear regression
4,set up regression figure
5,Print out the r-squared value along with the plot.

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude


# VacationPy

1,Dependencies and Setup
2,Import API key
3,read the CSV file

* Create a heat map that displays the humidity for every city
4,Create a poverty Heatmap layer

* Narrow down the DataFrame to find your ideal weather condition.
5,create a new data frame with certain weather conditions

Hotel Map
6,Create DataFrame called hotel_df to store hotel names along with city, country and coordinates
7,Set parameters to search for a hotel
8,Iterate through 
9,Use the search term: "Hotel" and our lat/lng
10,make request and print url
11,convert to json
12,Grab the first hotel from the results and store the name
13,run the data frame with the results
14,Using the template add the hotel marks to the heatmap
15,Store the DataFrame Row
16,Add marker layer ontop of heat map
17,Display figure