# Crowdfunding ETL Project

In this ETL mini project, crowdfunding data was transformed via the ETL pipeline, using applications such as Python and PostgreSQL. The project involved several key tasks:

## Data Extraction

Data was extracted from Excel files (crowdfunding.xlsx and contacts.xlsx).

## Data Transformation

The data from the crowdfunding spreadsheet was converted into three unique DataFrames using Pandas in Python:
- Category DataFrame
- Subcategory DataFrame
- Campaign DataFrame
Each DataFrame was saved as a CSV file.

The data from the contacts spreadsheet was converted into one unique DataFrame using Pandas in Python:
- Contacts DataFrame
This DataFrame was also saved as a CSV file.

## Database Design and Creation
An Entity Relationship Diagram (ERD) was designed to represent the relationships between the data tables represented across all four CSV files.
The ERD was used to create a PostgreSQL schema, which created tables in the database corresponding to each file.

## Data Loading

In the new PostgreSQL database with the generated schema, the CSV data was loaded into the corresponding tables, ensuring data integrity and proper relationships through foreign keys.
