## Project Three: Business Analytics Report

This repository documents the analysis of e-commerce user activity logs to understand user behavior and identify key performance indicators, including conversion funnels and customer cohort analysis.



**Table of Contents for README**

| Section Title | Description |
| :-----------: | ----------- |
| [Description] | Describes the final project’s purpose, software, format, and included visuals.. |
| [Data] |  This section describes the source of the data used in this analysis, including specific files, tables, and relevant fields.. |
| [Assumptions] | This section outlines assumptions provided by TripleTen, as well as those made during data analysis and task execution. |
| [Process] |  This section outlines the analytical approach and the specific tools and technologies employed throughout the project. |
| [Findings] | This section presents the key insights derived from the data analysis. |

**Data**

* **Source:** "raw_user_activity" sheet in the provided Google Spreadsheet.
* **Columns:**
    * user_id: Unique customer IDs
    * event_type: User activity (e.g., page view, cart, purchase)
    * category_code: Category of the product being viewed or purchased
    * brand: Company that makes the product
    * price: Price of the product, in USD
    * event_date: Date of user activity (YYYY-MM-DD)

**Methodology**

* **Conversion Funnel Analysis:** 
    * Created a 3-stage funnel (page view, cart, purchase) using pivot tables.
    * Calculated total conversion rates and conversion rates between each stage.
* **Cohort Analysis:**
    * Filtered data to focus solely on purchase events.
    * Calculated first purchase dates for each user.
    * Grouped users into cohorts based on their first purchase month.
    * Calculated cohort retention rates over time.

**Findings**

* [Insert key findings from the analysis here, e.g., conversion rates, cohort retention trends, etc.]

**Conclusions**

[Summarize key insights and potential implications of the analysis. 
For example: 
* "The analysis revealed a significant drop-off rate between product page views and cart additions, suggesting a need for improvements in product descriptions or user experience."
* "Cohort analysis identified a high initial retention rate, but a decline in retention over subsequent months, indicating a potential need for customer engagement strategies to improve long-term customer loyalty."]

**Change Log/Assumptions**

* [Document any changes made to the analysis or the data.] 
* [List any assumptions made during the analysis.]

**Note:** This README.md provides a high-level overview of the project. Detailed analysis and findings are documented within the associated Google Spreadsheet.
