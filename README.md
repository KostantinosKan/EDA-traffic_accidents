# Exploratory Data Analysis of A Countrywide Traffic Accident Dataset (2016 - 2020)
In this project I will investigate the traffic accidents that happened in U.S.A between the years 2016-2020. By performing an Exploratory Data Analysis I will try to understand the causality that leads to an accident and attempt to answer questions like When, Where, and Why accidents tend to happen.

## Getting Insights in 4 Steps

### Step 1 - Data Cleaning
* Deal with missing values.
* Drop irrelevant columns.
* Proceed to data preprocessing.

### Step 2 - Data Preprocessing
* Convert boolean object features to numerical values 0 and 1.
* Convert "Start_Time" and "End_Time" features to timestamps.
* Add additional columns for starting hour, day_of_week, month, year, and date.
* Proceed to Exploratory Data Analysis.

### Step 3 - Exploratory Data Insights
Answering to the following questions:
1. Which States, Cities and Streets have the most traffic accidents?
2. What is the time of the day, the day of the week and the month with the higher number of accidents?
3. How many accidents per year? And what is the trend, increasing or decreasing?
4. What are the most common weather conditions on the days of the accidents and how they affect the accidents?
5. How many accidents have a severity level of 1, 2, 3 and 4?

### Step 4 - Interactive Dashboard
* Create plotly graphs using the graph_object library.
* Create choropleth map using the folium library.
* Create an Indicator of the total number of accidents.
* Integrate all the above in a Dash application. 
