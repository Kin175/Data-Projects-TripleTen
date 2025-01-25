- [ ] **Sprint 1: Spreadsheet Data Analysis for TripleTen.**
![Alt Text](path/to/image.png)
- [ ] **Description**
    
    This project analyzes Airbnb data to guide investment decisions in the Manhattan vacation rental market. The primary objectives are to identify the most attractive neighborhoods and property sizes for vacation rentals, estimate their revenue potential, and provide data-driven recommendations to the client.

- [ ] **Process.**

    The analysis involved data cleaning, pivot table creation, and calculations to answer key questions:
        * **Most Attractive Neighborhoods:** Cleaned neighborhood data, analyzed review counts in the last 12 months, and identified the top 10 most attractive neighborhoods. 
            * **[Screenshot: Top 10 Neighborhoods Pivot Table]**
        * **Most Popular Property Sizes:** Cleaned bedroom data, analyzed rental frequency across different property sizes, and determined the most popular size in each neighborhood. 
            * **[Screenshot: Bedrooms Pivot Table]**
        * **Revenue Potential:** Identified top-performing listings based on neighborhood and property size, calculated daily and annual revenue, and ranked listings by their estimated annual income. 
            * **[Screenshot: Annual Revenue Pivot Table]**
        * **Occupancy Rate:** Analyzed average occupancy rates across different neighborhoods and property types.
            * **[Screenshot: Average Occupancy Rate Pivot Table]**
        * **Demand Patterns:** Identified the most popular rental days of the week.
            * **[Screenshot: Most Popular Days Pivot Table Bar Chart]**

- [ ] **Data**

    This data was scraped from the Airbnb database.
    NYC Airbnb Data:
        * data_dictionary
        * listings
        * calendar
        
- [ ] **Assumptions**

    *I placed filters for minimum requirement of 7 days for listings and calendar data sheets to focus more on vacation rentals.
    *Filtered out rentals in the listings and calendar data to exclude those with no reviews in the past 12 months because they are most likely inactive.
    *Finding the neighborhoods with the top 10 most reviews will give us the top 10 neighborhoods to analyze.
    *The number of bedrooms tells us the property size.
    *Filtering out blanks in the bedroom column gets rid of properties with no bedrooms.
    *Calculating occupancy will show which neighborhoods have the most customer traffic.
    *Calculating which weekdays have the highest usage rate will help for a more targeted marketing scheme.
    *Filtering for super hosts, properties being actively rented over the past year, filtering out super luxury and extremely low-priced rentals will give us more of what an investor would gladly invest in.
    
- [ ] **Findings**

    *I have discovered the most popular days for Airbnb's in NYC, top 10 neighborhoods, the most popular rental sizes, and why Lower East Side is the most fortuitous investment opportunity.
    *The most popular size rentals for the top 10 Nyc Neighborhoods are one-bedroom.
    *The popular days of the week for rentals are Fridays & Saturdays.
    *The most ideal neighborhood to invest in is Lower East Side.

