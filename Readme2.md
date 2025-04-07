Method 3: Using Python (Recommended for Automation)
Install required libraries:

pip install pandas openpyxl mysql-connector-python
Python script:

import pandas as pd
import mysql.connector

# Connect to MySQL
conn = mysql.connector.connect(
    host='localhost',
    user='your_username',
    password='your_password',
    database='your_database'
)

# Query
query = "SELECT * FROM your_table"
df = pd.read_sql(query, conn)

# Export to Excel
df.to_excel("output.xlsx", index=False)

conn.close()
