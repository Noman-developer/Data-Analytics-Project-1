# Data Analytics Project 1

This is my first data analytics project. I worked with a sales dataset and the task was to write up business insights from it.

## About this project

This project is from Week 1 of my data analytics course. The task was to act as a data analyst for ShopEase, an online retail company. The goal was to clean the sales data, look for trends, make charts, and write a short insights report with advice for the business.

This repo has the project brief, the raw dataset, and the course notes I used. The finished analysis is not here yet. I will add it later.

## Files in this repo

- **Project 1 - Data Analysis for Business Insights.pdf** - The project brief from the course. It explains the task: clean the data, explore it, make at least three charts, study customer behaviour, think about data privacy (GDPR), and write a final insights report.
- **sales_data.xlsx** - The raw sales dataset used in the project. It has 20 sales transactions from January to June 2024.
- **Project Coversheet.docx** - The blank template from the course where the final answers were supposed to be written. It has the project rules and formatting guidelines.
- **Theory/Week 1 - Foundations of Data Analysis (1).pdf** - The course slides for Week 1. They cover the basics: data collection, cleaning, exploration, and visualisation. They also cover big data, data types, data ethics and privacy, and storytelling with data.
- **Interview Qs/20 DA Interview Questions - Week 1 Foundations of Data Analysis.pdf** - 20 common data analyst interview questions with example answers. Topics include the steps of data analysis, cleaning vs exploration, handling missing data, visualisation techniques, and data storytelling.

## The dataset

The dataset is `sales_data.xlsx`. It has one sheet with 20 rows of sales transactions and 10 columns:

- Transaction_ID
- Date
- Customer_ID
- Product
- Category
- Quantity
- Price
- Total_Amount
- Payment_Method
- Region

The products fall into 3 categories: Books, Clothing, and Electronics. There are 8 products in total, 4 regions (North, South, East, West), and 4 payment methods (Cash, Credit Card, Debit Card, PayPal). Dates run from January to June 2024. One row has a missing value in Total_Amount, which is one of the cleaning tasks in the brief.

## Tools used

- Microsoft Excel
- Python (pandas, openpyxl for reading the data)
- PDF and Word for the project documents

## Author

Noman Javed
