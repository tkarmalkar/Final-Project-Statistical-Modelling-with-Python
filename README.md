# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Accessing data using CityBikes, Foursquare and Yelp APIs
Cleaning and transforming data using Python
Loading data into a database using Python
Performing EDA, including using both statistics and visualizations
Identifying trends and patterns in data using statistical models
Interpreting the results of the statistical models


## Process

Part 1:
    Access data using CityBikes ✅
    Visualized & filtered data using Postman
    City Chosen = Toronto
    Parsed through response to get bike stations
    Number of bike stations = 650+
    Stored the result in a dataframe & CSV

Part 2:
    Imported the citybikes CSV file
    Iterated through first 100 bike stations to obtain information from Yelp & Foursquare
    Explored and extracted few attributes from both API response
    Saved responses to CSV files

Part 3:
    Imported all three CSV files
    Trimmed lat/long to increase join match rate
    Merged the data
    Performed LDA on the data
    Stored in database

Part 4:
    Imported data from database
    Cleaned/dropped unwanted columns
    Ran regression model
    Used ELI5 to explain model results

## Results
    The Yelp API had better information as compared to Foursquare API

## Challenges 
    Making API calls for all 650 bike stations was challenging as response was breaking in between
    The attributes available from API response were not consistent

## Future Goals
    Spend more time on data analysis and transformation
