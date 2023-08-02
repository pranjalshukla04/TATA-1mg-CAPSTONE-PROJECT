1Mg Homeopathic Medicine Data Analysis Project
Project Banner

Table of Contents
Introduction
Project Overview
Technologies Used
Data Collection
Data Analysis
Interactive Excel Dashboard
Business Insights
Cost Estimation
Getting Started
Contributors
License
Introduction
Welcome to the 1Mg Homeopathic Medicine Data Analysis Project GitHub repository! This project aims to utilize web scraping techniques, data analysis, and interactive Excel dashboards to provide valuable insights into the world of homeopathic medicine available on the popular online medicine delivery platform, 1mg.

Project Overview
In this project, we have scraped a comprehensive dataset of homeopathic medicines available on the 1mg platform. The dataset consists of two main tables: medicine_name and medicine_details. The former contains general information about the medicines, such as name, size, MRP, and price, while the latter provides detailed attributes like brand name, key benefits, ingredients, user ratings, and more.

Technologies Used
Python
Beautiful Soup (Web Scraping)
Pandas (Data Manipulation)
NumPy (Numerical Computing)
Excel (Data Analysis and Visualization)
Data Collection
We scraped the required data from the 1mg website using Beautiful Soup, a Python library for web scraping. The data was extracted in accordance with the specified attributes for both medicine_name and medicine_details tables.

Data Analysis
The scraped data was extensively analyzed using Python, Pandas, and NumPy to derive meaningful insights. We performed aggregations to generate valuable statistics, such as the number of medicines available for different benefit areas, price ranges, brand specializations, and more.

Interactive Excel Dashboard
To make the insights accessible and interactive, we created dynamic Excel dashboards. These dashboards allow users to filter and visualize the data using Excel's powerful features. Users can explore insights based on different benefit areas, view average prices, ratings, and ingredient-related information.

Business Insights
The analysis yielded several key business insights:

Identification of popular benefit areas and their associated products.
Understanding price distribution for different medicine types.
Brand specialization based on key benefits.
Identifying high-rated medicines and their respective brands.
Cost Estimation
For potential entrepreneurs planning to open a homeopathic medicine store, we provide a cost estimation feature. Using the Excel dashboard, users can filter medicines based on benefit areas to estimate the total cost of opening a store.

Getting Started
To get started with this project, follow these steps:

Clone the repository.
Install the required Python packages using pip install -r requirements.txt.
Run the data collection script using python scrape_data.py.
Open the provided Excel file 1mg_homeopathic_analysis.xlsx to explore the interactive dashboard.
