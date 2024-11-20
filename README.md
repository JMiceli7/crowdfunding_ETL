# Crowdfunding: Extract Transfer Load

This project involved designing and implementing an ETL pipeline to process crowdfunding data using Python and Pandas. The pipeline extracted data from Excel files, transformed it into well-structured DataFrames, and exported them as CSV files for database integration. Key steps included:

Data Extraction and Transformation

Created a Category DataFrame with unique category IDs and titles.
Built a Subcategory DataFrame with unique subcategory IDs and titles.
Transformed campaign data to include relevant fields such as cf_id, description, goal, launch_date, and relational keys (category_id, subcategory_id).
Extracted and cleaned contact information, splitting names into first and last names.
Database Design and Integration

Designed an ERD and schema for a PostgreSQL database.
Imported the transformed data from the CSV files into relational tables in the database, ensuring proper use of primary and foreign keys.
The completed pipeline demonstrates the ability to extract, transform, and load data efficiently, culminating in a fully operational PostgreSQL database that supports structured analysis of crowdfunding campaigns.
