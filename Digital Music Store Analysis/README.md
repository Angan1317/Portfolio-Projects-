# Digital Music Store Analysis

### Project Overview

This data analysis project demonstrates the process of analyzing the Digital Music Store Database using data analysis. Using SQL, I analyzed the dataset and provided the store with insights into its business growth by responding to straightforward and intricate queries about geographic expansion, purchasing power, overall revenue, music band popularity, genre performance, best city for revenue, and best customer for purchase rate. The stakeholders will gain valuable knowledge from this study to help them make wise and sensible decisions.

### Data Sources

As my primary datasets, I have used these 12 .csv files [Datasets](https://github.com/Angan1317/Portfolio-Projects-/tree/main/Digital%20Music%20Store%20Analysis/Datasets)

### Tools

- MS Excel - Data Cleaning 
  - [Download Here](https://www.microsoft.com/en/microsoft-365/excel)
- PostgreSQL (PgAdmin4) - Data Analysis
  - [PostgreSQL](https://www.postgresql.org/download/)
  - [pgAdmin4](https://www.pgadmin.org/download/)
- MS Word - Results and Outcome Documentation
  - [Download Here](https://www.microsoft.com/en/microsoft-365/word?market=af)


### Data Cleaning/Preparation 

In the initial data preparation phase, I performed the following tasks :
1. Data loading and inspection
2. Handling missing values
3. Data cleaning and formatting

### Data Analysis

Here are some interesting SQL codes I worked with: 

SELECT name, milliseconds
FROM track
WHERE milliseconds > (
    SELECT AVG(milliseconds) AS avg_track_length
    FROM track)
ORDER BY milliseconds DESC;


### Problem Statements 
Some of the problem statements for this project are:
1. Who is the senior most employee based on job title?
2. Which city has the best customers?
3. Which countries have the most Invoices?

### Results/Findings

Some of the analysis results are summarized as follows :
1. Mohan Madan is the senior most employee and his job title is senior general manager
2. Prague City has the best customers based on most sales
3. USA has the most invoice



### Schema Diagram 
<img width="594" alt="schema_diagram" src="https://github.com/Angan1317/Portfolio-Projects-/assets/138960103/41f53c32-da58-4459-8029-e7ccdc32e7c3">
