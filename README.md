🗽 NYC Taxi Revenue Analysis — Microsoft Fabric Project (2015 Data)
🚕 Project Title: NYC Taxi Revenue Analysis
📊 Tools Used: Microsoft Fabric (Data Factory, Lakehouse, Dataflows Gen2), Power BI
📁 Dataset: NYC Green Taxi Trip Records - January 2015
📦 Source: NYC TLC Trip Record Data

📌 Project Overview
This project showcases an end-to-end data pipeline using Microsoft Fabric. The goal is to ingest raw NYC taxi data, clean and transform it, and visualize revenue insights in Power BI. I focused on fare amount trends, passenger volume, and overall revenue performance for January 2015.

🧩 Key Components
🔄 Data Ingestion with Data Factory
Connected to a CSV dataset stored in OneLake

Set up a pipeline for importing taxi trip records

🧪 Data Transformation with Dataflows Gen2
Cleaned and selected relevant fields: fareAmount, passengerCount, totalAmount, tripDistance, paymentType, etc.

Renamed columns and filtered for January 2015 only

Loaded the cleaned table into a Fabric Lakehouse

🏠 Storage: Lakehouse
Served as the single source of truth for the Power BI semantic model

📊 Dashboard Highlights (Power BI)
🎨 Design Theme
Bright yellow background with a hand-sketched NYC skyline and checkerboard taxi pattern to match the theme

Clean, cartoon-style line graph layout

📈 Visuals
KPI Cards for:

Total Passengers: 13K

Average Fare Amount: $11.85

Total Revenue: $158K

Line Chart comparing:

Total Fare Amount (black line)

Total Passenger Count (yellow line)

Time Frame: January 1–31, 2015

Additional Filter: Payment Type slicer

🧠 Key Insights
Daily fare revenue fluctuated significantly across the month

Highest revenue day: Late January

Average fare price held steady despite passenger volume changes

Visual shows correlation (or lack thereof) between ride volume and revenue

💡 What I Learned
How to orchestrate a full ETL flow in Microsoft Fabric

Hands-on experience with Dataflows Gen2 transformations

Visual storytelling in Power BI with custom background themes

Navigating and debugging export issues with custom visuals

🚧 Limitations & Next Steps
Dataset was limited to just one month (Jan 2015), so trends are short-term

Future: Add full-year or multi-year datasets for seasonal analysis

Explore clustering by vendor, payment method, or trip distance

🔗 Files Included
📁 Power BI .pbix file

📁 Microsoft Fabric screenshots or deployment steps

📁 PDF export of dashboard

📁 README (this file)
