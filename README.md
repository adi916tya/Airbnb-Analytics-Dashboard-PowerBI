# Airbnb-Analytics-Dashboard-PowerBI
Interactive Power BI dashboard analyzing Airbnb listings in New York City — insights into listings distribution, pricing, hosts, room types, and neighbourhood performance. Built using Power BI, DAX, SQL, Databricks, Genni, and GitHub.

# Airbnb Analytics Dashboard

## 📌 Project Overview
A comprehensive Power BI dashboard analyzing Airbnb listings in New York City. It provides actionable insights into listing distribution, pricing, host activity, room types, and neighbourhood performance.

## 🎯 Project Objective
To create an interactive dashboard that enables stakeholders to make data-driven decisions about Airbnb market dynamics in NYC.

## 🛠 Technologies Used
- Power BI Desktop (visualization & dashboard design)
- DAX (advanced calculations)
- SQL (data modeling & transformation)
- Databricks (data engineering & pipeline management)
- Genni (AI‑powered analytics automation)
- GitHub (version control & documentation)

## 📈 Dashboard KPIs
- Total Listings
- Average Price
- Unique Hosts
- Listings by Neighbourhood
- Average Price by Neighbourhood
- Listings by Room Type
- Property Type
- New Hosts Over Time
- Geographic Distribution

## 💡 Key Business Insights
- Manhattan dominates listings volume.
- Brooklyn shows diverse room type distribution.
- Average prices vary significantly by neighbourhood.
- Host growth has accelerated since 2015.
- Entire homes dominate revenue share, while private rooms provide affordability.

## 📈 Business Recommendations
- Focus marketing on Manhattan for premium listings.
- Promote Brooklyn for diverse room types and affordability.
- Adjust pricing strategies to neighbourhood benchmarks.
- Encourage new hosts in underrepresented areas.

## 🧹 Data Cleaning
- Removed duplicates
- Handled missing values in Price and Reviews
- Standardized neighbourhood names

## 🔄 Data Transformation
- Converted Host Since to weekly buckets
- Normalized Price field to currency format
- Created calculated columns for time-based analysis

## 🏗 Data Modeling
- Star schema with Listings fact table
- Dimension tables: Neighbourhood, Room Type, Property Type

## 📐 DAX Measures
- `Record Count = SUM(nyc[Number of Records])`
- `Average Price = AVERAGE(nyc[Price])`
- `Unique Host Count = DISTINCTCOUNT(nyc[Host Id])`

## 📊 Calculated Columns
- Host Since Week Starting
- Price Buckets (Low, Medium, High)

## 📉 Power BI Visuals Used
- Clustered Bar Chart
- Area Chart
- Donut Chart
- Horizontal Bar Chart
- 100% Stacked Bar Chart
- Map Visual
- KPI Cards
- Slicers

## 💡 Key Business Insights
- Manhattan dominates listings volume.
- Brooklyn shows diverse room type distribution.
- Average prices vary significantly by neighbourhood.
- Host growth has accelerated since 2015.
- Entire homes dominate revenue share, while private rooms provide affordability.

## 📈 Business Recommendations
- Focus marketing on Manhattan for premium listings.
- Promote Brooklyn for diverse room types and affordability.
- Adjust pricing strategies to neighbourhood benchmarks.
- Encourage new hosts in underrepresented areas.

## ⚙️ Challenges
- Handling missing values in Price and Reviews
- Formatting visuals consistently
- Balancing bubble sizes in map visualization

## 🚀 Future Improvements
- Add predictive analytics for pricing
- Integrate review sentiment analysis
- Automate dataset refresh
- Add drill-through pages for detailed host analysis

## 📂 Folder Structure
Airbnb-Analytics-Dashboard-PowerBI/
│
├── Dataset
├── PowerBI_File
├── Screenshots
├── Reports
├── SQL_Scripts
├── Documentation
└── README.md


## 🛠 Technologies Used
- Power BI Desktop
- DAX
- SQL
- Excel/CSV

## 📷 Project Screenshots
<img width="1367" height="787" alt="airbnb dashbord" src="https://github.com/user-attachments/assets/009fd78b-935e-4022-91f3-22f941fb40a6" />




