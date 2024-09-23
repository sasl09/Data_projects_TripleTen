
## The Zuber Database: Data Exploration

## Introduction:

Zuber is a new ride-sharing company that's launching in Chicago. The main goal of this analysis is to find patterns in the available information. It is necessary to understand passenger preferences and the impact of external factors on rides, by analyzing data from competitors and investigate the impact of weather on ride frequency. <br>

This dataset is located on the Tripleten online teaching platform and it contains 4 tables: Neighborhoods, Cabs, Trips and Weather_records. Trips is the largest table, as it contains 1,691,670 rows.

## Process
Data exploration tasks:

![Task 1](images/sql1.png)
<br>

![Task 2](images/sql2.png)
<br>

![Task 3](images/sql3.png)
<br>

![Task 4](images/sql4.png)
<br>

![Task 5](images/sql5.png)
<br>

![Task 6](images/sql6.png)

The table columns should be in the following order: 

## Content

### Tables:
neighborhoods table: data on city neighborhoods <br>
name: name of the neighborhood <br>
neighborhood_id: neighborhood code <br>

### cabs table: data on taxis
cab_id: vehicle code <br>
vehicle_id: the vehicle's technical ID <br>
company_name: the company that owns the vehicle <br>

### trips table: data on rides
trip_id: ride code <br>
cab_id: code of the vehicle operating the ride <br>
start_ts: date and time of the beginning of the ride (time rounded to the hour) <br>
end_ts: date and time of the end of the ride (time rounded to the hour) <br>
duration_seconds: ride duration in seconds <br>
distance_miles: ride distance in miles <br>
pickup_location_id: pickup neighborhood code <br>
dropoff_location_id: dropoff neighborhood code <br>

### weather_records table: data on weather
record_id: weather record code <br>
ts: record date and time (time rounded to the hour) <br>
temperature: temperature when the record was taken <br>
description: brief description of weather conditions, e.g. "light rain" or "scattered clouds" <br>

Data Modeling:

![Data Model](DataModel.png)

## Conclusion and Recommendations:

- There are 6 Cab companies over 9,000 trips each in 2 days. It is recommended to focus on how those companies offer their services, the number and state of their units and the type of service of their drivers, 
in order to establish best practices for all companies. <br>

- From November 1-7th, Flash Cab and Taxi Affiliation Services made more trips than all of the trips made by all other companies. In fact, Flash Cab made almost twice as many. Further analysis of the characteristics mentioed above should be performed on these two.

## Link to Report:

https://drive.google.com/file/d/11WPsahG1b0mh0C2gqZ8mqQ4o-XktMhGu/view?usp=sharing

## Project Files

-README.md<br>
-The Zuber Database Data Exploration.pdf<br>
-DataModel.png<br>
-images

## Author

Saul Solis
