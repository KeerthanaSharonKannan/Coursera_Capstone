# Coursera_Capstone

## Introduction 
The goal of the project is to identify the different cuisine restaurants that are frequently visited in the Manhattan city and its neighborhood by converting the addresses into their equivalent latitude and longitude coordinates. This analysis will help people who are planning to open a restaurant within Manhattan city and its neighborhood. By identifying the frequently visited restaurants, and analyzing the data, we can recommend that a new hotel can be opened in a particular neighborhood where it will be received better. I am using Foursquare location data to explore the neighborhoods of Manhattan city. With the help of Foursquare API, I get the most common venue categories in each neighborhood filter to choose the restaurants among those venues and then use this feature to group the neighborhoods into clusters by utilizing the K-means clustering algorithm. With the help of Folium library, neighborhoods in Manhattan city can be visualized along with their emerging clusters. 

## Data
New York dataset is in Json format. The dataset is available on the web for free access. I use ‘wget’ command to access the data. For this project I am using the Jupyter notebook from IBM Watson Cloud. 
The New York dataset has total of 5 boroughs and 306 neighborhoods. The latitude and longitude coordinates of each neighborhood is needed to segment the neighborhoods and explore them. Among the five boroughs I am choosing the Manhattan borough since Manhattan is one of the busy places with most number of restaurants in New York when compared to other boroughs. My objective is to explore the different cuisines (e.g. American, Italian, Mexican, etc.,.) in that borough and neighborhood. The Foursquare API is used for obtaining the venues around the coordinates. Python is the primary language used for the analysis and by mainly utilizing a library called Pandas.  Since the dataset is in JSON format, the values are in key-value format. Some of the main Keys are Features like ID, coordinates, name. I convert this Json file to pandas Dataframe for analysis. 
