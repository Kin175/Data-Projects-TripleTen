## Zuber Database Project - Business Intelligence Analyst

This repository documents the analysis of a ride-sharing company, Zuber's, database to understand passenger preferences and external factors impacting rides.

**Table of Contents**

* [Description](#description)
* [Data](#data)
* [Tasks](#tasks)
* [Process](#Process)
* [Findings](#findings)

## Description

This project explores the Zuber database to identify patterns in ride-taking behavior and the impact of weather conditions. The analysis aims to:

* Understand user preferences for pickup and drop-off locations.
* Investigate the influence of weather (rain/storm) on ride frequency, particularly for rides between specific locations (Loop to O'Hare).
* Identify opportunities to improve Zuber's services based on data insights.

## Data

The analysis utilizes the following tables from the Zuber database:

* **neighborhoods:** Contains information on city neighborhoods (name, neighborhood_id).
* **cabs:** Stores data on taxis (cab_id, vehicle_id, company_name).
* **trips:** Provides details on rides (trip_id, cab_id, start_ts, end_ts, duration_seconds, distance_miles, pickup_location_id, dropoff_location_id).
* **weather_records:** Includes weather data for each hour (record_id, ts, temperature, description).

## Tasks

The project involved the following tasks:

1. Exploratory data analysis on taxi rides (number of rides by company, popular neighborhoods).
2. Identifying neighborhoods based on name (O'Hare, Loop).
3. Classifying weather conditions (good/bad) based on descriptions containing rain or storm.
4. Analyzing rides from Loop to O'Hare on Saturdays, considering weather and ride duration.

## Process

SQL queries were used to extract and analyze data from the Zuber database. The queries focused on:

* Counting rides by taxi company and filtering based on company names or specific dates.
* Joining tables (trips and weather_records) to link rides with corresponding weather conditions.
* Utilizing CASE statements to categorize weather descriptions as good or bad.
* Filtering rides based on pickup/drop-off locations, day of the week, and presence of weather data.

## Findings

The analysis revealed insights into ride-taking patterns and weather influence:

* Popular taxi companies can be identified based on the number of rides.
* Specific neighborhoods (e.g., O'Hare, Loop) can be located using their names.
* Classifying weather allows for investigation of its impact on rides.
* Rides between Loop and O'Hare on Saturdays may be affected by bad weather (rain/storm).

These findings can be used to develop targeted marketing strategies, optimize service availability in high-demand areas, and potentially adjust pricing based on weather conditions.

## Further Exploration

* Analyze the impact of other weather conditions (e.g., snow) on ride frequency.
* Explore the relationship between ride duration and distance.
* Investigate user demographics and preferences for pickup/drop-off locations.

This README.md provides a high-level overview of the Zuber Database Project. The code for each SQL query can be found in separate files within the repository.
