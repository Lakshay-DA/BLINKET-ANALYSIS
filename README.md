# Blinkit Sales Data Analysis (Python Project)

Project Overview
This project analyzes Blinkit grocery sales data using Python. The objective is to extract meaningful business insights, clean raw data, and visualize key performance indicators to support data-driven decision-making.

## *Objectives*

-Perform data cleaning and preprocessing

-Analyze sales performance across different categories

-Identify trends based on outlet types, sizes, and locations

-Generate visual insights using charts



## *Tech Stack*

-Python

-Pandas (data manipulation)

-NumPy (numerical operations)

-Matplotlib (data visualization)


*Dataset*

The dataset includes the following fields:


-Item Type

-Item Fat Content

-Sales

-Rating

-Outlet Size

-Outlet Location

-Outlet Establishment Year



*Data Cleaning*

-Standardized inconsistent values in Item Fat Content:

 
 'LF', 'low fat' → Low Fat
 
 'reg' → Regular

-Checked for missing values and data types

-Verified unique values



*Key Performance Indicators*

-Total Sales

-Average Sales

-Number of Items Sold

-Average Rating



*Data Analysis and Visualizations*


Sales by Fat Content


-Comparison of Low Fat and Regular product sales




Sales by Item Type


-Identification of top-performing categories




Fat Content by Outlet Location


-Sales distribution across different outlet tiers




Sales by Outlet Establishment Year


-Trend analysis over time




Sales by Outlet Size


-Performance comparison across outlet sizes





*Insights*


1.Certain item types generate higher revenue than others


2.Outlet size and location significantly affect sales


3.Low Fat and Regular products show different demand patterns


4.Older outlets demonstrate more stable sales trends



How to Run
pip install pandas numpy matplotlib
df = pd.read_csv("your_file_path.csv")
jupyter notebook

Project Structure
Blinkit-Analysis/│├── blinket_project.ipynb├── blinkit_data.csv└── README.md

*Future Improvements*


-Add interactive dashboards using Power BI or Tableau


-Use Seaborn for enhanced visualization


-Apply machine learning models for prediction


-Deploy as a web-based dashboard



*Author
Lakshay Singh
Aspiring Data Analyst
Skills: Python, Excel, Data Analysis, Gen AI Fundamentals*

