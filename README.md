# Airbnb-Analytics-Dashboard-PowerBI
Interactive Power BI dashboard analyzing Airbnb listings in New York City — insights into listings distribution, pricing, hosts, room types, and neighbourhood performance.

# Airbnb Analytics Dashboard

## 📌 Project Overview
This project delivers a comprehensive Power BI dashboard analyzing Airbnb listings in New York City. It provides actionable insights into listing distribution, pricing, host activity, room types, and neighbourhood performance.

## 🎯 Project Objective
To create an interactive dashboard that enables stakeholders to make data-driven decisions about Airbnb market dynamics in NYC.

## 🏢 Business Problem
Airbnb stakeholders need clear visibility into:
- Which neighbourhoods dominate listings
- How host activity evolves over time
- Pricing variations across neighbourhoods
- Distribution of room and property types
- Geographic spread of listings

## 📊 Dataset Overview
- Source: Inside Airbnb (NYC dataset)
- Records: ~50,000 listings
- Key fields: Host ID, Host Since, Neighbourhood, Room Type, Price, Number of Reviews, Property Type

## 📑 Business Requirements
- Track total listings and unique hosts
- Monitor host growth trends
- Compare average prices across neighbourhoods
- Analyze room type and property type distribution
- Visualize geographic spread of listings

## 📈 Dashboard Overview
The dashboard consists of multiple pages and visuals:
- Listings by Neighbourhood
- Average Price by Neighbourhood
- Room Type Distribution
- Property Type Analysis
- Host Growth Over Time
- Geographic Map of Listings
- KPI Cards for quick insights

## 🔑 KPIs
- Total Listings
- Average Price
- Unique Hosts
- Listings by Neighbourhood
- Average Price by Neighbourhood
- Listings by Room Type
- Property Type
- New Hosts Over Time
- Geographic Distribution

## 🛠 Dashboard Features
- Interactive slicers (Property Type, Room Type, Neighbourhood)
- KPI cards
- Airbnb-branded theme and logo
- Map visualization with bubble sizing and color coding
- Drill-down and tooltips

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
