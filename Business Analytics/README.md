## Project Three: Business Analytics Report


**Table of Contents for Repository Artifacts**

| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | (README.md) | **The current page serving as an overall summary of this repository.** |
| 2 | (Requirements.txt) | **This report presents the requirements for this project for TripleTen.** |
| 3 | (Zuber Database Data.pdf) | **A collection of tables (neighborhoods, cabs, trips, weather_records) containing information on taxi rides, neighborhoods, and weather conditions in Chicago.** |
| 4 | (Zuber Database Report.pdf) | **A collection of SQL queries and results visualizing taxi ride data analysis.** |

**Table of Contents for README**

| Section Title | Description |
| :-----------: | ----------- |
| [Description] | Describes the project’s purpose, software, format, and included visuals.. |
| [Data] |  This section describes the source of the data used in this analysis, including specific files, tables, and relevant fields.. |
| [Assumptions] | This section outlines assumptions provided by TripleTen, as well as those made during data analysis and task execution. |
| [Process] |  This section outlines the analytical approach and the specific tools and technologies employed throughout the project. |
| [Findings] | This section presents the key insights derived from the data analysis. |

**Description**

* This repository documents the analysis of e-commerce user activity logs to understand user behavior and identify key performance indicators, including conversion funnels and customer cohort analysis.

**Data**

* **Source:** "raw_user_activity" sheet in the provided Google Spreadsheet.
* **Columns:**
    * user_id: Unique customer IDs
    * event_type: User activity (e.g., page view, cart, purchase)
    * category_code: Category of the product being viewed or purchased
    * brand: Company that makes the product
    * price: Price of the product, in USD
    * event_date: Date of user activity (YYYY-MM-DD)

**Change Log/Assumptions**

* [List of any changes made to the analysis or the data.] 
* [List of assumptions made during the analysis found in report.]

**Process**

* **Conversion Funnel Analysis:** 
    * Created a 3-stage funnel (page view, cart, purchase) using pivot tables.
    * Calculated total conversion rates and conversion rates between each stage.
* **Cohort Analysis:**
    * Filtered data to focus solely on purchase events.
    * Calculated first purchase dates for each user.
    * Grouped users into cohorts based on their first purchase month.
    * Calculated cohort retention rates over time.

**Findings**

* Conversion rate from views to purchases is at a rate of 10.34%. Conversion rate to next step from shopping_cart to purchase is at a rate of 35.61%.  
* Conversion rate to next step from shopping_cart to purchase is at a rate of 35.61%.  
* Retention rates are the highest in the first monthly cohort of"  "2020-09" and nearly 5% by the next cohort "2020-10".  
* Retention rates in "2020-09" cohort drop nearly half from 12.50% the first cohort_age to 6.25% the next.  
* Then there is a gradual drop in retention rate until a slight nearly 2% uptick.

**Note:** This README.md provides an overview of the project. Detailed analysis and findings are documented within the associated Google Spreadsheet.
