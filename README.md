# Customer-Churn-Analysis
Customer Churn Analysis


1. Introduction


Customer churn is a major challenge for businesses because losing existing customers can directly affect revenue, growth, and long-term customer relationships. Customer Churn Analysis is a data analytics project designed to analyze customer behavior and identify patterns associated with customer churn.


This project uses Python, SQL, and data visualization techniques to clean, transform, analyze, and visualize customer data. The analysis helps identify important factors that contribute to customer churn and provides meaningful insights that can support customer retention strategies.

________________________________________

2. Project Overview


The Customer Churn Analysis project performs an end-to-end analysis of customer data to understand why customers leave a service.


The project includes:



●	Importing and understanding customer data

●	Exploring the structure and quality of the data

●	Cleaning and preprocessing the data

●	Handling missing and inconsistent values

●	Performing exploratory data analysis

●	Using SQL queries to analyze customer information

●	Identifying churn patterns and important customer characteristics

●	Creating visualizations to communicate analytical findings

●	Generating meaningful business insights from the analysis



The overall workflow follows a practical data analyst approach, starting from raw data and ending with insights and visual representations.

________________________________________

3. Dataset Structure


The project database is organized into separate tables to store customer-related information. The tables and their columns are listed below.


3.1 Customer Table


Customer Table Columns:



●	CustomerID — Unique identification number of each customer

●	Gender — Gender of the customer

●	SeniorCitizen — Indicates whether the customer is a senior citizen

●	Partner — Indicates whether the customer has a partner

●	Dependents — Indicates whether the customer has dependents

●	Tenure — Number of months the customer has stayed with the company

●	PhoneService — Indicates whether the customer has phone service

●	MultipleLines — Indicates whether the customer has multiple phone lines

●	InternetService — Type of internet service used by the customer

●	OnlineSecurity — Indicates whether online security service is subscribed

●	OnlineBackup — Indicates whether online backup service is subscribed

●	DeviceProtection — Indicates whether device protection service is subscribed

●	TechSupport — Indicates whether technical support is subscribed

●	StreamingTV — Indicates whether the customer uses streaming TV

●	StreamingMovies — Indicates whether the customer uses streaming movie services

●	Contract — Type of customer contract

●	PaperlessBilling — Indicates whether the customer uses paperless billing

●	PaymentMethod — Payment method used by the customer

●	MonthlyCharges — Monthly amount charged to the customer

●	TotalCharges — Total amount charged to the customer

●	Churn — Indicates whether the customer has left the company



3.2 Support Table


Support Table Columns:



●	CustomerID — Unique customer identifier used to associate support information with a customer

●	TechSupport — Indicates whether the customer has technical support

●	OnlineSecurity — Indicates whether the customer has online security

●	OnlineBackup — Indicates whether the customer has online backup

●	DeviceProtection — Indicates whether the customer has device protection



3.3 Services Table


Services Table Columns:



●	CustomerID — Unique customer identifier

●	PhoneService — Indicates whether phone service is subscribed

●	MultipleLines — Indicates whether multiple lines are subscribed

●	InternetService — Type of internet service

●	StreamingTV — Indicates whether streaming TV is subscribed

●	StreamingMovies — Indicates whether streaming movies are subscribed





Note: The table names and column descriptions above represent the logical organization of the customer churn data used in the project. If your SQLite database uses different table names or column names, they should be updated to match the actual database schema.



________________________________________

4. Project Workflow


The project follows a structured end-to-end data analytics workflow:


Raw Data → Data Understanding → Data Cleaning → Data Transformation → Exploratory Data Analysis → SQL Analysis → Data Visualization → Insights & Findings


Step 1: Data Collection


The customer dataset is collected and prepared for analysis.


Step 2: Data Understanding


The dataset is examined to understand its rows, columns, data types, categorical variables, numerical variables, and overall structure.


Step 3: Data Cleaning


The raw data is checked for missing values, duplicate records, incorrect data types, inconsistent values, and other data-quality issues.


Step 4: Data Transformation


The data is transformed into a suitable format for analysis. Numerical and categorical fields are prepared according to the requirements of the analysis.


Step 5: Data Analysis


Exploratory analysis is performed to identify relationships and patterns between customer characteristics and churn.


Step 6: SQL Analysis


SQL queries are used to extract, filter, group, aggregate, and analyze customer information from the database.


Step 7: Data Visualization


Charts and graphs are created to present important patterns and make the analysis easier to understand.


Step 8: Insights


The analytical results are interpreted to identify the major factors and customer characteristics associated with churn.

________________________________________

5. Data Cleaning


Data cleaning is an important stage of the project because the quality of the analysis depends on the quality of the underlying data.


The cleaning process includes:



●	Checking for missing values

●	Identifying duplicate records

●	Checking and correcting data types

●	Handling blank or inconsistent entries

●	Converting numerical fields into appropriate formats

●	Validating categorical values

●	Ensuring the churn field is correctly represented

●	Preparing the cleaned dataset for further analysis



Special attention is given to fields such as TotalCharges, where values may require conversion from text to numerical format before performing calculations.

________________________________________

6. Data Analysis


The cleaned dataset is analyzed to understand customer behavior and determine the characteristics associated with churn.


The analysis focuses on areas such as:



●	Overall customer churn rate

●	Churn based on gender

●	Churn among senior citizens

●	Relationship between tenure and churn

●	Churn based on contract type

●	Churn based on payment method

●	Churn based on internet service

●	Impact of monthly charges on churn

●	Relationship between total charges and churn

●	Effect of additional services on customer retention

●	Comparison of churned and non-churned customers



The analysis helps identify patterns that can be useful for understanding customer retention and improving business strategies.

________________________________________

7. Data Visualization


Data visualization is used to communicate the analytical findings in a simple and understandable manner.


Different charts and graphs are used to compare churned and non-churned customers across different attributes.


The visual analysis helps identify:



●	Churn distribution

●	Customer demographic patterns

●	Contract-wise churn

●	Payment-method-wise churn

●	Tenure-related churn patterns

●	Monthly-charge-related churn patterns

●	Service usage patterns

●	Differences between retained and churned customers



Visualization makes it easier to identify trends, compare categories, and communicate business insights effectively.

________________________________________

8. Technology Used


Programming Language



●	Python



Libraries



●	Pandas — Data manipulation and analysis

●	NumPy — Numerical operations

●	Matplotlib — Data visualization

●	Seaborn — Statistical data visualization



Database & Query Language



●	SQLite

●	SQL



Development Environment



●	Jupyter Notebook



Version Control



●	Git & GitHub


________________________________________

9. Project Files


The project repository contains the following files:


File Name	Description
Churn Analysis.ipynb	Jupyter Notebook containing Python-based data cleaning, analysis, and visualization
Customer Churn	Raw customer churn database containing the original customer data
Exported Churn Data	Exported customer data generated during the project
Test Database SQLite.sql	SQL file containing database queries used for customer churn analysis

________________________________________

10. Objective


The primary objective of this project is to analyze customer churn and identify the factors that influence customers to leave a service.


The project aims to:



●	Understand customer churn behavior

●	Identify high-risk customer segments

●	Discover patterns associated with customer attrition

●	Analyze customer demographics and service usage

●	Evaluate the relationship between pricing, tenure, contracts, and churn

●	Use SQL and Python for practical data analysis

●	Present findings through effective data visualizations

●	Generate actionable insights that can help businesses improve customer retention


________________________________________

11. Conclusion


The Customer Churn Analysis project demonstrates a complete data analytics workflow, from raw customer data preparation to data cleaning, SQL analysis, exploratory analysis, visualization, and business-oriented insights.


By examining customer demographics, tenure, contracts, payment methods, services, and billing characteristics, the project provides a structured approach to understanding customer churn. The combination of Python, SQL, SQLite, and data visualization demonstrates practical skills required for real-world data analyst projects.


The insights generated from this analysis can help businesses recognize customers who may be more likely to churn and develop appropriate customer retention strategies. Overall, the project showcases the ability to transform raw data into meaningful information that can support data-driven decision-making.


