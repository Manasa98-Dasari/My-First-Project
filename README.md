🌟 Used Car Price Analysis in India

A complete end-to-end Data Analytics project using Python, Web Scraping, Pandas, Excel & Power BI

🚗 Project Overview

The used car market in India is expanding rapidly with the growth of digital marketplaces. Prices differ widely based on brand, model, year, mileage, fuel type, and city—making it difficult for customers to choose the right car.

This project analyzes real-time used car listings to understand how different factors influence price. The goal is to help users make data-driven decisions using insights derived from data analytics and visualization.

🧠 Objectives

✔ Identify factors that heavily impact used car pricing
✔ Compare price variations across brands, years, and fuel types
✔ Understand location-based pricing differences
✔ Present insights through clear and interactive dashboards

🛠️ Tech Stack Used
Area	Tools Used
Web Scraping	Python, Requests, BeautifulSoup
Data Cleaning	Pandas, NumPy
Data Storage	CSV, Excel
Visualization	Power BI
Documentation	PowerPoint, PDF

📁 Project Folder Structure
Used-Car-Price-Analysis/
│
├── Code/
│   ├── scraping_used_cars.py
│   └── cleaning_and_transformation.py
│
├── Data/
│   ├── used_car_data.csv
│   └── raw_data/ 
│
├── Reports/
│   └── Used_Car_Analysis_Dashboard.pbix
│
└── Documentation/
    ├── Used_Car_Analysis_Presentation.pptx
    └── Project_Report.pdf

🔄 End-to-End Workflow
1️⃣ Web Scraping

Selected a reliable online marketplace for used car listings

Extracted:
✔ Car brand & model
✔ Manufacture year
✔ KM driven
✔ Fuel type
✔ Transmission
✔ Location
✔ Final price

Data extracted using:

BeautifulSoup

Requests

HTML parsing techniques

2️⃣ Data Cleaning & Transformation

Performed in Python using Pandas:

Removed duplicates

Removed missing values

Converted price & mileage to numeric

Standardized categories (Fuel, Brand, Model)

Added new columns for:
✔ Car Age
✔ Price per KM

3️⃣ Data Visualization (Power BI)

Dashboards include:

Brand-wise price comparison

Average price by manufacturing year

Fuel type vs Price

KM driven vs Price relationship

City-wise price distribution

Top affordable vs premium brands

The multi-page dashboard helps users compare brands, models, and price ranges quickly.

📊 Key Insights

📌 1. Toyota, Honda, and Hyundai retain higher resale value consistently.
📌 Maruti Suzuki offers the most affordable and reliable options.
📌 Cars older than 7–8 years show a steep price depreciation.
📌 Diesel cars dominate older listings; Petrol cars dominate newer models.
📌 Metro cities like Delhi, Mumbai, Bengaluru show higher price averages compared to tier-2 cities.
📌 Cars with lower mileage (KM driven) always command premium pricing.

🧾 Conclusion

This project provides a clear understanding of the Indian used car market by combining web scraping, data cleaning, and business intelligence dashboards.
The insights are valuable for:

Car buyers

Dealers

Market analysts

Auto industry researchers

Future enhancements:

Add ML-based price prediction

Expand data to multiple websites

Add brand reliability scoring
