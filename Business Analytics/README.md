## Zuber Database Project: Business Intelligence Analysis

This repository documents the analysis of a ride-sharing company, Zuber's, database to understand user preferences and external factors impacting rides (focusing on Loop-to-O'Hare trips and weather).

**Table of Contents**

* [Data](## Data)
* [Process](## Process)
* [Findings](## Findings)
* [Assumptions](## Assumptions)
* [Zuber Database Description](## Zuber Database Description) (Optional)

**Data**

* Source: Zuber Database
* Tables:
    * neighborhoods: city neighborhoods (name, neighborhood_id)
    * cabs: taxi data (cab_id, vehicle_id, company_name)
    * trips: ride details (trip_id, cab_id, start_ts, end_ts, duration_seconds, distance_miles, pickup_location_id, dropoff_location_id)
    * weather_records: weather data (record_id, ts, temperature, description)

**Process**

SQL queries were used to analyze the Zuber database, focusing on:

* Ride frequency by taxi company
* Pickup/drop-off locations
* Impact of weather (rain/storm) on rides, particularly Loop-to-O'Hare rides on Saturdays

**Findings**

* User preferences for pickup and drop-off locations can be identified.
* Weather can influence ride frequency, especially for specific locations and weather conditions.

**Assumptions**

* Analyzing ride frequency by company reveals the most popular ones.
* Frequent pickup/drop-off locations provide insights into travel patterns.
* Classifying weather as "good" or "bad" captures the impact of weather on rides.
* Loop-to-O'Hare rides on Saturdays represent weekend travel patterns and weather effects.
* The data reflects the overall ride-hailing landscape in the city.

**Optional: Zuber Database Description**

Provide a detailed description of the Zuber database schema (tables, fields, relationships).
