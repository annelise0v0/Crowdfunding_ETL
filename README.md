# 📊 Crowdfunding_ETL
Project 2


---

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Data Cleaning & Transformation](#data-cleaning--transformation)
- [Output Files](#output-files)
- [Tools & Technologies Used](#tools--technologies-used)
- [Team Members](#team-members)


---

<a id="project-overview"></a>
## 📁 Project Overview

This project processes and transforms crowdfunding campaign and contact data using Python and the Pandas library. It reads from Excel files, cleans and restructures the data, and exports the results into CSVs for use in analysis or databases.
---

<a id="data-sources"></a>
## 📊 Data Sources
- Resources/crowdfunding.xlsx - campaign input file for transformation
- Resources/contacts.xlsx - contact data input file for transformation

---

<a id="d#data-cleaning--transformation"></a>
## 🧹 Data Cleaning & Transformation
- ✅ Category/Subcategory
    - Splits category & sub-category
    - Creates lookup tables with unique cat and subcat IDs

- ✅ Campaign Data
    - Renames columns
    - Converts dates and currency to proper formats
    - Merges category and subcategory info
    - Drops irrelevant fields

- ✅ Contact Info
    - Parses JSON strings into structured format
    - Extracts first/last names
    - Provides two methods: json.loads() and regex
      
- ✅ Crowdfunding Database
    - Uses cleaned CSV files to build a PostgreSQL database for analysis and querying
    - An Entity Relationship Diagram (ERD) was created using QuickDBD to visualize the table relationships
    - SQL schema is saved in: crowdfunding_db_schema.sql

---

<a id="output_files"></a>
## 📈 Output Files
- Resources/category.csv
- Resources/subcategory.csv
- Resources/campaign.csv
- Resources/contacts.csv

---

<a id="tools--technologies-used"></a>
## 🛠 Tools & Technologies Used

- Python 
- Pandas
- NumPy  
- JSON  
- Regex  
- Jupyter Notebook or Visual Studio Code
- ChatGPT for ReadMe formatting assisstance
- PostGreSQL
- QuickDBD

---

<a id="team-members"></a>
## 👥 Team Members
- Matthew Guy
- Anna Howell
- Denisa Iordache
- Sanja Romanishan

