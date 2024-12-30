# Data Cleaning in Python with Pandas and MySQL Using SQLAlchemy and Common Table Expressions (CTEs)
## Question:-
### Q1. Find top 10 highest reveue generating products 
### Q2. Find top 5 highest selling products in each region
### Q3. Find month over month growth comparison for 2022 and 2023 sales eg : jan 2022 vs jan 2023
### Q4. For each category which month had highest sales
### Q5. Which sub category had highest growth by profit in 2023 compare to 2022

## Data Cleaning in Python with Pandas and MySQL Using SQLAlchemy and Common Table Expressions (CTEs)

This project demonstrates data cleaning in Python using the Pandas library, with a connection to a MySQL database through SQLAlchemy. It leverages Common Table Expressions (CTEs) in MySQL for efficient query execution and data manipulation.

### Key Steps:
1. Connect to MySQL Database  
   ```python
   import sqlalchemy as sal

   engine = sal.create_engine('mysql+pymysql://root:abhilead@localhost:3306/sys')
   conn = engine.connect()
   df.to_sql('df_orders', con=conn, index=False, if_exists= 'append')
   ```
2. Perform Data Cleaning in Pandas  
   - Handle missing values  
   - Remove duplicates  
   - Standardize data formats  

3. Use MySQL Common Table Expressions (CTEs)  
   - Write optimized queries for data extraction and transformation.

This approach combines the power of Python for data processing and MySQL for structured querying, providing a robust solution for data cleaning and analysis workflows. 🚀
