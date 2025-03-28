# Crowdfunding_ETL Pipeline Project
Project Summary

This project walks through a ETL (Extract, Transform, Load) pipeline using Python. The goal is to demonstrate how to pull in data, clean it up, and prepare it to load into a database for further analysis. Raw datasets are used. e end goal is to load this data into a well-structured format, such CSV files.

Tools & Librarys 

    Python
    Pandas
    Numpy
    Jupyter
    Json


Key Steps

- Extracted `Crowdfunding.xlsx` into a Pandas DataFrame.

- Created two separate DataFrames for categories and subcategories.

- Used list comprehensions and NumPy arrays to assign `category_id` and `subcategory_id`.

- Cleaned and transformed the campaign data:
  - Renamed columns for clarity
  - Merged DataFrames
  - Dropped unnecessary columns

- Exported cleaned data into four CSV files:
  - `campaign.csv`
  - `category.csv`
  - `subcategory.csv`
  - `contacts.csv`

- Designed an Entity Relationship Diagram (ERD).

- Created a SQL table schema based on the ERD.



