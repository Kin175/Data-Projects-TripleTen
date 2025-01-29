## Project Three: Business Analytics Report

![image alt](https://github.com/Kin175/Data-Projects-TripleTen/blob/33d7f53c99d610570024b6d89c3157c33e0e8807/.images/Project%20Three%20Executive%20Summary%20screenshot.png)

**Table of Contents for Repository Artifacts**

| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Project Three_ Business Analytics Data.pdf](https://github.com/Kin175/Data-Projects-TripleTen/blob/main/Business%20Analytics/GitHub%20Project%20Three_%20Business%20Analytics%20Data.pdf) | **The collection data for this Business Analytics Project.** |
| 2 | [Project Three_ Business Analytics Report.pdf](https://github.com/Kin175/Data-Projects-TripleTen/blob/main/Business%20Analytics/GitHub%20Project%20Three_%20Business%20Analytics%20Report.pdf) | **The Final Report for this project.** |
| 3 | [README.md](https://github.com/Kin175/Data-Projects-TripleTen/blob/main/Business%20Analytics/README.md) | **The current page serving as an overall summary of this repository.** |
| 4 | [Requirements.txt](https://github.com/Kin175/Data-Projects-TripleTen/blob/main/Business%20Analytics/Requirements.txt) | **This report presents the requirements for this project for TripleTen.** |


**Table of Contents for README**

| Section Title | Description |
| :-----------: | ----------- |
| [Description] | Describes the project’s purpose, software, format, and included visuals.. |
| [Data] |  This section describes the source of the data used in this analysis, including specific files, tables, and relevant fields.. |
| [Assumptions] | This section outlines assumptions provided by TripleTen, as well as those made during data analysis and task execution. |
| [Process] |  This section outlines the analytical approach and the specific tools and technologies employed throughout the project. |
| [Findings] | This section presents the key insights derived from the data analysis. |

**Description**

* This project documents the analysis of e-commerce user activity logs to understand user behavior and identify key performance indicators, including conversion funnels and customer cohort analysis.

**Data**

* **Source:** "raw_user_activity" sheet in the provided Google Spreadsheet.
* **Columns:**
    * user_id: Unique customer IDs
    * event_type: User activity (e.g., page view, cart, purchase)
    * category_code: Category of the product being viewed or purchased
    * brand: Company that makes the product
    * price: Price of the product, in USD
    * event_date: Date of user activity (YYYY-MM-DD)

**Assumptions**

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
