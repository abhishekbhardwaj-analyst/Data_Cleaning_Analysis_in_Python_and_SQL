# 📊 Data Cleaning and Analysis in Python & SQL with Pandas, SQLAlchemy, and MySQL (CTEs)  

This project demonstrates data cleaning and analysis in Python using Pandas, with a connection to a MySQL database via SQLAlchemy. It leverages Common Table Expressions (CTEs) in MySQL for efficient query execution and structured data analysis.

---

## 🚀 Project Overview  

This repository covers the following:  

1. Data Cleaning in Python using Pandas: Handle missing values, remove duplicates, and standardize data formats.  
2. MySQL Database Integration: Connect to a MySQL database using SQLAlchemy.  
3. Advanced SQL Analysis with CTEs: Use optimized SQL queries for analysis.  
4. Structured Insights: Address key business questions with meaningful analysis.  

---

## ❓ Questions Addressed  

1. Top 10 Highest Revenue-Generating Products: Identify products contributing the most revenue.  
2. Top 5 Highest-Selling Products by Region: Analyze regional sales performance.  
3. Month-Over-Month Growth (2022 vs. 2023): Compare monthly growth trends across two years.  
4. Highest Sales Month by Category: Identify peak sales months for each category.  
5. Sub-Category with Highest Profit Growth: Find the sub-category with the highest profit growth in 2023 compared to 2022.  

---

## ⚙️ Setup and Database Connection  

Ensure proper connection to the MySQL database using SQLAlchemy:  

```python
import sqlalchemy as sal

engine = sal.create_engine('mysql+pymysql://root:abhilead@localhost:3306/sys')
conn = engine.connect()
df.to_sql('df_orders', con=conn, index=False, if_exists='append')
```

---

## 🛠️ Key Steps in the Project  

### 1️⃣ Perform Data Cleaning in Pandas:  
- Handle missing values  
- Remove duplicates  
- Standardize formats 

### 2️⃣ Connect to MySQL Database:  
Establish database connection and load data into MySQL tables.   

### 3️⃣ Use MySQL Common Table Expressions (CTEs):  
CTEs are used for:  
- Aggregating sales and revenue data  
- Monthly comparisons  
- Identifying top-performing categories and products  

---

## 📈 Results and Insights  

- Identified high-revenue products and regions.  
- Evaluated year-over-year sales growth.  
- Pinpointed the most profitable sub-categories.  

This approach combines the power of Python for data processing and MySQL for structured querying, delivering a scalable and efficient analysis workflow.  
## 🧑‍💻 Author
- Abhishek Bhardwaj
- [GitHub Profile](https://github.com/abhishekbhardwaj-analyst)
- [LinkedIn Profile](https://linkedin.com/in/ds-abhishek)  

## 📄 License
This project is licensed under the MIT License.

## 📬 Contact
For questions or feedback, feel free to reach out at abhi.bhardwaj96@gmail.com.

---
