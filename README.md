# Crowdfunding_ETL
## Project 2 - Data Bootcamp

This repo contains the following files,
- Resources directory containing the Excel sheets we use to extract our campaign and contacts data, and eventually transform and load them into 4 separate CSVs.
    - contacts.xlsx (included with starter file)
    - crowdfunding.xlsx (included with starter file)
    - campaign.csv
    - category.csv
    - contacts.csv (generated through pandas and regex)
    - subcategory.csv
- The main ETL Mini Project notebook, where you'll find the code that converts the Excel data into CSV data using Python and Pandas.
- The Crowdfunding Database that exemplifies my skills in understanding relational databases. Here, you'll find,
    - A text file showing the entity relationship diagram between the 4 tables created (crowdfunding_erd_schema.txt)
    - A SQLite file containing the code that creates the 4 tables required on Postgres, indicating primary & foreign keys (crowdfunding_db_schema.sql)
    - An ERD showing the relationship between 4 tables indicating data types, primary & foreign keys. (crowdfunding_erd.png)
    - A SQLite file showing the code I used to verify the data was correctly imported into the 4 tables (crowdfunding_verification.sql). The data retrieved with these queries are presented as screenshots in the Images folder.

-----

Sources
 - [Regex Cheat Sheet](https://cheatography.com/davechild/cheat-sheets/regular-expressions/)
 - [How to use Regex with Pandas](https://kanoki.org/2019/11/12/how-to-use-regex-in-pandas/)
 - [NumPy arrange()](https://realpython.com/how-to-use-numpy-arange/)
 - [Python JSON](https://www.w3schools.com/python/python_json.asp)
