# Big Data Analysis – Sales Data Analysis using Hadoop and Spark - Internship Project
Welcome to the official GitHub repository for the Big Data Internship Task focused on processing and analyzing large-scale sales datasets using Apache Spark and PySpark. This internship project showcases a complete big data pipeline – from raw data processing to business insights – performed entirely in a distributed computing environment using Google Colab.

# Project Objective

The primary goal of this project is to:
“Process and Analyze Large Datasets Using Hadoop and Spark”

This task was carried out as part of the internship to strengthen hands-on skills with Spark, PySpark, and large-scale data handling, and produce insightful analytics from raw transactional data.

# Technologies Used

Apache Spark 3.4.0
PySpark (Python API for Spark)
Google Colab (for cloud-based execution)
Python
Pandas & NumPy (for dataframe manipulations)
Matplotlib (for data visualization)
Hdoop environment (via Spark bundled binaries)

# Dataset Overview
Total Records: 500,000

Columns: transaction_id, product_id, customer_id, product_category, product_price, quantity, total_amount, region, date

Size: ~90 MB CSV

Source: Synthetic sales data mimicking e-commerce platform sales logs

 # Data Pipeline Workflow
1. ✅ Spark Environment Setup
Installed OpenJDK, Spark 3.4.0 (Hadoop 3.3 support)

Configured environment variables (JAVA_HOME, SPARK_HOME)

Initialized SparkSession via SparkSession.builder()

2. 📦 Data Ingestion
Loaded CSV data into Spark DataFrame (sales_df)

Inferred schema and verified record counts

3. 🔍 Data Exploration and Preprocessing
Schema inspection and null checks

Basic statistical description of product_price, quantity, and total_amount

4. 📊 Analytical Queries
Performed real-time analytics on:

Regional Performance (sales & transactions by region)

Top 10 Customers (based on spend and order count)

Sales by Category

Monthly Trends

Overall KPIs

5. 📈 Visualization & Insights
Generated meaningful charts using matplotlib:

Pie chart – Sales Distribution by Region

Bar charts – Sales by Category, Transaction Volume by Region

Line graph – Monthly Sales Trends

# Key Analytical Outputs
| Metric      | product\_price | quantity | total\_amount |
| ----------- | -------------- | -------- | ------------- |
| **Mean**    | 504.41         | 4.99     | 2523.06       |
| **Std Dev** | 285.46         | 2.58     | 2069.70       |
| **Max**     | 1000.0         | 9        | 8999.91       |
| **Min**     | 10.0           | 1        | 10.1          |


# Regional Performance
| Region | Total Sales      | Total Transactions |
| ------ | ---------------- | ------------------ |
| West   | \$316,557,807.15 | 125,230            |
| North  | \$316,519,563.72 | 124,989            |
| South  | \$314,722,191.37 | 125,144            |
| East   | \$313,731,679.37 | 124,637            |

# Top 10 Customers
| Customer ID | Total Spent | Total Orders |
| ----------- | ----------- | ------------ |
| 47339       | 74904.54    | 20           |
| 42114       | 74817.61    | 17           |
| 38944       | 73839.16    | 22           |
| ...         | ...         | ...          |

...	...	...

# Sales by Category
| Category    | Total Sales      |
| ----------- | ---------------- |
| Fashion     | \$253,039,082.07 |
| Home        | \$252,610,813.76 |
| Electronics | \$251,293,055.44 |
| Sports      | \$251,948,352.39 |
| Books       | \$251,744,325.00 |


# Monthly Trends (2023)
Peak in July 2023 with ~$1.08B+ sales

Relatively stable volume throughout the year

# Summary Report

================ BIG DATA ANALYSIS SUMMARY REPORT ================

📊 Dataset Overview:
• Total Records Processed: 500,000
• Total Revenue: $1,261,530,341.61
• Average Order Value: $2523.06

📌 Key Insights:
• Best Performing Category: Fashion
• Top Category Revenue: $253,039,082.07
• Best Performing Region: West
• Top Region Revenue: $316,557,807.15

⚡ Technology Used:
• Apache Spark 3.4.0
• PySpark for data processing
• Processed on Google Colab

===================================================================
# How to Reproduce
To run this project on your own system:

1. Open in Google Colab
Upload or clone the notebook in a Colab environment

2. Run All Cells
Ensure all setup commands are executed in order – Spark setup must be done before loading data

3. Replace Dataset (Optional)
To try with your own data, replace the dataset file and adjust schema accordingly

🎓 Internship Task Summary
✅ Internship Theme: Big Data

✅ Task: "Process and Analyze Large Datasets Using Hadoop and Spark"

✅ Tools Used: Apache Spark, PySpark, Google Colab

✅ Result: Successfully completed the task with extensive analysis, visuals, and insights


# output # 

<img width="959" height="595" alt="Image" src="https://github.com/user-attachments/assets/317e6686-d312-46d8-a16c-06a9930d7cca" />
<img width="770" height="378" alt="Image" src="https://github.com/user-attachments/assets/84c8f055-b4c6-4275-8c52-5d80ecfc006c" />
<img width="835" height="669" alt="Image" src="https://github.com/user-attachments/assets/1d990568-c2fc-4eae-bab8-beb69b9f460b" />
<img width="408" height="410" alt="Image" src="https://github.com/user-attachments/assets/8f73e282-5bc6-4c32-bdcf-db694484edbc" />
<img width="583" height="611" alt="Image" src="https://github.com/user-attachments/assets/99c13ccf-859f-47ba-8d9e-e32459ab6eaa" />
<img width="1059" height="359" alt="Image" src="https://github.com/user-attachments/assets/b172e9e8-d938-4e2d-a57b-29d2b0952a4f" />
<img width="968" height="383" alt="Image" src="https://github.com/user-attachments/assets/e97d516b-0a6f-436a-82ef-a6cc910e1bfe" />
<img width="567" height="763" alt="Image" src="https://github.com/user-attachments/assets/2ec88b49-a017-44c3-bdf0-b7fbe6a9ec56" />


