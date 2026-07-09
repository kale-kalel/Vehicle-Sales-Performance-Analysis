# Vehicle Sales Performance Analysis and Dashboard

## Overview
This project analyzes a dataset from [Kaggle](https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data) to derive sales insights based on different factors such as vehicle condition, brand, body type, and market value (MMR). The raw dataset was loaded into a local SQL database to simulate a real-world querying environment. Data was then cleaned filtered for outliers using MMR-based ratio analysis, and explored through visualizations to answer analytical and business questions. Findings are summarized through an interactive dashboard built in Google Data Studio.


## Dashboard
[View Live Dashboard](https://datastudio.google.com/reporting/c5f8ff80-81ba-466f-85d8-d6f1439d55ca)

## Tools Used
 - Python
    - Pandas
    - Numpy
    - Matplotlib
    - Seaborn
    - SQLAlchemy
 - MySQL
 - Google Data Studio

## Key Findings
 - ***550.2K sales***  were recorded.
 - ***Selling prices are right-skewed***, indicating that majority of the vehicles are sold at lower price points.
 - ***Rolls Royce, Ferrari, and Lamborghini*** lead in average selling prices, all averaging above $100,000.
 - ***Sedan*** is the most sold body type with over 245,000 sales, followed by **SUV** with over 141,000 sales
 - ***Selling price decreases*** as mileage increases.
 - ***Vehicles in excellent condition*** have the highest avereage selling price.
 - ***Selling price decreases*** as vehicle age increase.
 - ***51.4% of the vehicles are sold below MMR***, suggesting a buyer-friendly market.
 - Vehicle sales peaked in ***June 2015***.
 - ***Nissan Infiniti LT*** is the leading seller with nearly 30,000 sales.
