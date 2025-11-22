📊 Walmart Sales Analysis — Python + MySQL Project

A complete end-to-end data analytics pipeline using:

Python → Data cleaning, preprocessing, feature engineering

MySQL → Advanced SQL analytics

Jupyter Notebook → Documentation & EDA

This project replicates real industry workflows using ETL + SQL-based business analysis.

🚀 Project Workflow (ETL Pipeline)
1. Data Source (Kaggle)

Download the dataset manually or using Kaggle API, place into:

data/walmart_raw_data.csv

2. Python EDA & Data Cleaning (Jupyter Notebook)

Performed:

Inspect datatypes

Handle missing values

Remove duplicates

Clean currency columns

Convert date & time formats

Extract date parts

Create total_amount column

Create shift column (Morning/Afternoon/Evening/Night)

The final cleaned dataset is stored at:

data/walmart_cleaned_data.csv

3. MySQL Database Load

Using SQLAlchemy:

Create database: walmart_db

Load table: walmart

Clean dataset → inserted into MySQL table for analysis.

4. Business SQL Analysis (15 Questions)

All queries stored in:

sql/walmart_mysql_queries.sql


Includes:

Payment method insights

Best-selling categories

Rating analysis per branch

YOY revenue decline

Shift-wise sales analysis

Profitability insights

Highest revenue day per month

Category revenue contribution

Rating vs sales behavior

📁 Repository Structure
data/
    walmart_raw_data.csv
    walmart_cleaned_data.csv

notebooks/
    walmart_analysis.ipynb

sql/
    walmart_mysql_queries.sql

scripts/
    main.py

images/
    walmart_project.png
    walmart_pipeline.png

requirements.txt
README.md

🧩 Tech Stack
Languages

Python

SQL

Databases

MySQL

Python Libraries

pandas

numpy

sqlalchemy

mysql-connector-python

jupyter

📈 Key Insights

Highest revenue categories & branches

Payment methods customers prefer

Best-rated vs worst-rated categories

Most profitable branches

Sales distribution by time of day

Monthly peak revenue days

Category contribution % to total revenue

🔮 Future Roadmap

Power BI / Tableau dashboard

Automated pipeline (Airflow / Prefect)

Add weather & holiday datasets

Build API to expose SQL results

📝 License

MIT License

🙏 Acknowledgements

Dataset sourced from Kaggle
Business case inspired by Walmart analytics case studies
