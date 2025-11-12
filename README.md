📘 Overview

This project focuses on evaluating , enhancing the quality of a “news events” dataset also building a pipeline using Python, SQL, and Tableau.
The objective was to identify key data quality issues, apply systematic cleaning and validation, and visualize the improvements between the raw and cleaned datasets.

🗃️ SQL Data Setup & Cleaning

Structured SQL scripts were developed to create the database schema, manage cleaned data, and track data quality metrics.

Main Tables:

Table Name	                 Description
news_events_cleaned	  Stores cleaned and standardized event data with relevant metadata.
dq_metrics_run	      Captures metrics such as duplicates removed, invalid URLs, and missing counts before and after cleaning.


🐍 Python Data Cleaning (Jupyter Notebook)

The Jupyter Notebook Firmable_assessment.ipynb handled data profiling, cleaning, and validation.

Key tasks included:

1. Profiling for missing values, duplicates, and invalid URLs.

2. Standardizing company names, URLs, and phone numbers.

3. Handling null values and ensuring proper data type conversions.

4. Removing duplicate and invalid records.

5. Exporting the cleaned dataset for Tableau visualization and comparison.

📊 Tableau Visualization

In Tableau, a comparative bar chart was built to showcase data quality improvements between the Raw Data and Cleaned Data.

 Visualized Metrics:

1. Total record count

2. Missing article URLs

3. Missing company names

4. Duplicate records

5. Invalid URLs

6. Missing product details

This visualization clearly demonstrated the improvements achieved through the cleaning process.

🔍 Key Insights

1. Noticeable reduction in missing and invalid values.

2. Duplicate records effectively identified and removed.

3. Standardization achieved across all key fields.

4. Cleaned dataset ready for downstream analytics and reporting.

✅ Conclusion

This assessment successfully demonstrates an end-to-end data quality improvement workflow combining the power of SQL for structure, Python for automation, and Tableau for visualization.
The result is a significantly improved, reliable, and analysis-ready dataset.
