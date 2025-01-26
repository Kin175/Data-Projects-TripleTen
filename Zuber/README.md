## Zuber Database Project - Business Intelligence Analyst

- [ ] ![image alt](https://github.com/Kin175/Data-Projects-TripleTen/blob/1b3413d71f85da790dc93987f629652d4983aaa7/.images/Project%20Two%20The%20Zuber%20Database%20Table%20Scheme%20Screenshot.png)

This repository documents the analysis of a ride-sharing company, Zuber's, database to understand passenger preferences and external factors impacting rides.

**Table of Contents for Repository Artifacts**

| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | (README.md) | This collection of data dictionaries provides detailed information about the Airbnb dataset used for the Manhattan vacation rental market analysis. |
| 2 | (Requirements.txt) | This report presents the findings of an analysis on the Manhattan vacation rental market using Airbnb data. |
| 3 | (Zuber Database Data.pdf) | This README.md documents a project analyzing Airbnb data for Manhattan vacation rentals Sprint 1: Spreadsheet Data Analysis for TripleTen. |
| 4 | (Zuber Database Report.pdf) | This requirements document outlines the scope and objectives of an analysis on the Manhattan vacation rental market using Airbnb data. |

**Table of Contents for README**

| Section Title | Description |
| :-----------: | ----------- |
| [Description] | Describes the final project’s purpose, software, format, and included visuals.. |
| [Data] |  This section describes the source of the data used in this analysis, including specific files, tables, and relevant fields.. |
| [Assumptions] | This section outlines assumptions provided by TripleTen, as well as those made during data analysis and task execution. |
| [Process] |  This section outlines the analytical approach and the specific tools and technologies employed throughout the project. |
| [Findings] | This section presents the key insights derived from the data analysis. |

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

## Assumptions

* **Assumption 1:** Analyzing ride frequency by taxi company will reveal the most popular and successful companies in the market.
* **Assumption 2:** Identifying the most frequent pickup and drop-off locations will provide valuable insights into passenger travel patterns and demand.
* **Assumption 3:** Classifying weather conditions as "good" or "bad" based on the presence of "rain" or "storm" in the description will effectively capture the impact of adverse weather on ride demand.
* **Assumption 4:** Analyzing rides from Loop to O'Hare on Saturdays will provide a representative sample of rides influenced by weekend travel patterns and potential weather impacts.
* **Assumption 5:** The available data accurately reflects the overall ride-hailing landscape in the city and is representative of typical travel patterns.

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

