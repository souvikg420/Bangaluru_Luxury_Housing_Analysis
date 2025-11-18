# Bangaluru_Luxury_Housing_Analysis
A data analytics project using Python, MySQL, and Power BI to analyze luxury housing trends.
🏡 Luxury Housing Market Analysis — Bangalore

📊 Power BI • 🐍 Python • 🗄️ MySQL • 📁 GitHub

A complete end-to-end data analytics project analyzing the luxury housing market across Bangalore’s micro-markets.


---

🚀 Project Overview

This project aims to analyze the luxury housing market using:

Python for data cleaning, feature engineering, preprocessing

MySQL for database storage and querying

Power BI for building interactive dashboards

GitHub for version control and portfolio presentation


The dashboard helps users answer key business questions like:

Which micro-markets show rising booking trends?

Which builders generate the highest revenue?

Do amenities influence booking conversion?

Which configurations are most in demand?

Which sales channels perform best?
🧹 Data Cleaning & Feature Engineering (Python)

Performed using Pandas, NumPy, and SQLAlchemy:

✔ Removing nulls and extreme values
✔ Cleaning ticket price and unit size
✔ Adding quarter labels
✔ Creating new features:

Booking_Status

Booking_Count

Booking_Conversion_Rate

Price_per_Sqft


✔ Exporting cleaned data to MySQL


---

🗄️ Database (MySQL)

Tables include:

luxury_housing_data (cleaned dataset)

Additional analytics tables (optional)


Python connection snippet used:

engine = create_engine(
    f"mysql+mysqlconnector://root:password@localhost/luxury_housing"
)


---

📊 Power BI Dashboard Highlights

1️⃣ Market Trends

Quarter-wise bookings across micro-markets
(Line Chart: Quarter_Label vs Booking_Count segmented by Micro_Market)

2️⃣ Builder Performance

Top builders by total and average ticket price
(Bar Chart)

3️⃣ Amenity Impact

Amenity score vs booking conversion
(Scatter Plot)

4️⃣ Booking Conversion

Which areas convert the most buyers?
(Stacked Column Chart)

5️⃣ Configuration Demand

Most booked configurations
(Pie/Donut Chart)

6️⃣ Sales Channel Efficiency

Sales channel performance
(100% Stacked Column)

7️⃣ Quarterly Builder Contribution

Builder revenue by quarter
(Matrix)

8️⃣ Possession Status Impact

Impact of ready-to-move vs under-construction
(Clustered Column Chart)

9️⃣ Geographic Insights

Bookings by micro-market (map visual)

🔟 KPI Cards

Total Revenue

Total Bookings

Avg Ticket Price

Top 5 Builders
🛠️ How to Run This Project

1. Clone the repository

git clone https://github.com/yourusername/luxury-housing-analysis.git

2. Install Python dependencies

pip install pandas sqlalchemy mysql-connector-python numpy

3. Import SQL tables

Open MySQL Workbench and run the .sql files from SQL/ folder.

4. Open the Power BI file

Connect it to your local MySQL server → Refresh → Dashboard loads.
🎯 Key Business Insights

(You can update these after completing your dashboard)

North Bangalore has the highest quarterly growth

3BHK dominates demand with highest booking counts

Builder revenue highly varies across quarters

Amenity Score shows strong positive correlation with conversion rate
👤 Author

Souvik Ghosh
Data Science Learner | Python | SQL | Power BI
(GUVI Upskilling Program)
