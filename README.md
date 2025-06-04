# 🛠️ ETL Project with Faker & MySQL
This project demonstrates a complete ETL (Extract, Transform, Load) pipeline using a synthetically generated dataset via the Faker library. The primary goal is to simulate real-world data processing: generating data, performing cleaning and transformation, normalizing it into relational schemas, and finally loading it into a MySQL database.

📌 Project Overview
Data Generation: Created a fake dataset using the Faker Python library to simulate customer, product, and transaction data.

ETL Pipeline:

Extract: Load the fake dataset into a processing environment (Pandas DataFrame).

Transform: Cleaned, enriched, and normalized the data into multiple related tables.

Load: Stored the normalized data into a MySQL database using SQLAlchemy / mysql-connector-python.

ETL-Project/
├── data_generation.py         # Script to generate fake data using Faker
├── etl_pipeline.py            # Script to perform the ETL steps 
└── README.md                  # Project documentation 


🧰 Technologies Used
Python

pandas

faker

sqlalchemy / mysql-connector-python

MySQL

Jupyter Notebook / IDE (optional for exploration)
