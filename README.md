# 🚕 Uber Trips Analytics | SQL & Power BI

![Project](https://img.shields.io/badge/Project-Capstone-yellow)
![SQL](https://img.shields.io/badge/SQL-Advanced-blue)
![Power%20BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-green)

## 📌 Project Overview

**Uber Trips Analytics** is an end-to-end data analytics capstone project focused on analyzing New York City Green Taxi trip data.

The project aims to uncover meaningful insights from trip records to understand trip volume, revenue patterns, geographic distribution, passenger behavior, payment preferences, and operational performance.

Using **Advanced SQL and Power BI**, this project transforms historical taxi trip data into actionable business insights that can support better fleet management, dynamic pricing strategies, operational efficiency, and improved passenger experience.

---

## 📑 Table of Contents

1. [Project Overview](#-project-overview)
2. [Business Problem](#-business-problem)
3. [Project Objectives](#-project-objectives)
4. [Dataset Information](#-dataset-information)
5. [Tools & Technologies](#-tools--technologies)
6. [Key Dataset Fields](#-key-dataset-fields)
7. [Project Methodology](#-project-methodology)
8. [Part 1: Advanced SQL Analysis](#-part-1-advanced-sql-analysis)
9. [Part 2: Power BI Dashboard](#-part-2-power-bi-dashboard)
10. [Key Performance Indicators](#-key-performance-indicators)
11. [Dashboard Insights](#-dashboard-insights)
12. [Business Recommendations](#-business-recommendations)
13. [Project Outcomes](#-project-outcomes)
14. [Repository Structure](#-repository-structure)
15. [How to Explore This Project](#-how-to-explore-this-project)
16. [Future Scope](#-future-scope)
17. [Conclusion](#-conclusion)
18. [Author](#-author)

---

## 🎯 Business Problem

The Uber Taxi & Limousine Commission needs to analyze Green Taxi trip data to identify trends, improve operational efficiency, optimize fleet management, set dynamic pricing, and enhance customer experience in New York City.

Understanding trip patterns, revenue trends, geographic demand, and passenger behavior is essential to:

- Improve fleet allocation.
- Optimize pricing strategies.
- Increase revenue and operational efficiency.
- Reduce passenger waiting times.
- Enhance passenger satisfaction.

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze historical trip volume and revenue trends.
- Identify peak demand days, hours, and high-demand locations.
- Analyze fare, tips, and payment patterns.
- Understand passenger behavior and trip characteristics.
- Identify popular pickup and drop-off routes.
- Provide data-driven recommendations for fleet scheduling and pricing strategies.
- Explore demand forecasting to support future resource planning.

---

## 📂 Dataset Information

**Dataset Name:** NYC Green Taxi Trip Records

**Dataset Source:** New York City Taxi & Limousine Commission (TLC)

**Dataset Link:** [Uber Taxi Trips – NYC](https://wscubetechpvtltd-my.sharepoint.com/:u:/g/personal/ayushi_jain_wscubetech_com/IQBQxgFAOtljWyiNHKoult5oAcO2H5i9KMp2Hd9W0_COEqo?e=tzT7hL)

The dataset contains historical Green Taxi trip records from New York City with information related to:

- Pickup and drop-off dates and times.
- Pickup and drop-off boroughs.
- Pickup and drop-off zones.
- Trip distance.
- Passenger count.
- Fare amount.
- Tip amount.
- Payment type.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| SQL | Data analysis and solving business questions |
| Power BI | Interactive dashboard development |
| Power Query | Data transformation and preparation |
| DAX | KPI calculations and dashboard metrics |
| CSV | Dataset storage and data import |

---

## 🗂️ Key Dataset Fields

The following fields were used for the analysis:

| Column Name | Description |
|---|---|
| `tpep_pickup_datetime` | Pickup date and time |
| `tpep_dropoff_datetime` | Drop-off date and time |
| `pickup_borough` | Pickup borough |
| `dropoff_borough` | Drop-off borough |
| `pickup_zone` | Pickup zone |
| `dropoff_zone` | Drop-off zone |
| `passenger_count` | Number of passengers |
| `trip_distance` | Trip distance in miles |
| `fare_amount` | Trip fare |
| `tip_amount` | Tip amount |
| `payment_type` | Payment method |

---

## ⚙️ Project Methodology

The project follows a structured data analytics workflow:

**1. Data Collection**
- Importing CSV data into SQL.

**2. Data Cleaning**
- Handling missing values.
- Removing duplicate records.
- Data type conversion.
- Preparing data for analysis.

**3. SQL Analysis**
- Solving 10 business questions using SQL queries.
- Analyzing trip trends, revenue, routes, passenger behavior, and payment patterns.

**4. Dashboard Development**
- Creating 5 interactive Power BI dashboards.
- Developing KPIs and visualizations.
- Adding interactive filters and navigation.

**5. Insights & Recommendations**
- Identifying important business patterns.
- Providing actionable recommendations for fleet scheduling, pricing, and passenger service improvements.

---

## 💻 Part 1: Advanced SQL Analysis

The SQL analysis focuses on extracting actionable insights from taxi trip records.

### 🔍 Business Questions Solved

**1. Yearly Trip Trends**
- Calculate total trips per year.
- Calculate percentage change year-over-year.

**2. Monthly Revenue Insights**
- Find monthly total revenue.
- Calculate average revenue per trip.

**3. Peak Day & Time Analysis**
- Identify the day of the week with the highest average trip volumes.
- Identify the hour of the day with the highest average trip volumes.

**4. Borough Trip Distribution**
- Calculate the percentage of trips starting in each `pickup_borough`.

**5. Top Pickup-Dropoff Routes**
- Identify the top 10 most frequent pickup-zone to drop-off-zone combinations.

**6. Passenger Load Patterns**
- Calculate the average `passenger_count` for trips in each borough.

**7. Trip Distance Distribution**
- Determine the average `trip_distance` for each pickup borough and drop-off borough.

**8. Payment Method Analysis**
- Calculate the percentage share of each `payment_type`.
- Calculate the average `fare_amount` for each payment type.

**9. High-Tip Routes**
- Identify the top 5 pickup-drop-off combinations with the highest average `tip_amount`.

**10. Revenue by Borough Pairs**
- Calculate total `total_amount` earned for each pickup-borough to drop-off-borough pair.

---

## 📊 Part 2: Interactive Power BI Dashboard

Developed **5 interactive dashboard pages** to visualize trip trends, revenue breakdowns, geographic patterns, and passenger behavior.

### 1️⃣ Trip & Revenue Overview

<details>
<summary><b>View Dashboard Details</b></summary>

**KPIs:**
- Total Trips
- Total Revenue
- Average Fare per Trip
- Year-over-Year Trip Change

**Visualizations:**
- Monthly Revenue Analysis
- Year-over-Year Growth
- Fare Distribution

**Purpose:** Understand overall trip performance and revenue trends.

</details>

### 2️⃣ Time-Based Demand Analysis

<details>
<summary><b>View Dashboard Details</b></summary>

**KPIs:**
- Total Trips
- Average Trip Distance
- Average Fare per Trip
- Total Zones

**Visualizations:**
- Trips by Day
- Trips by Hour
- Time-Based Demand Distribution

**Purpose:** Identify peak demand periods and understand trip patterns across different days and hours.

</details>

### 3️⃣ Geographic Patterns

<details>
<summary><b>View Dashboard Details</b></summary>

**KPIs:**
- Total Zones
- Total Boroughs
- Average Trip Distance
- Total Trips

**Visualizations:**
- Trips by Borough
- Borough Analysis
- Average Trips by Pickup Zone and Drop-off Zone

**Purpose:** Understand geographic trip distribution and identify important pickup and drop-off locations.

</details>

### 4️⃣ Passenger & Distance Insights

<details>
<summary><b>View Dashboard Details</b></summary>

**KPIs:**
- Average Passengers per Trip
- Average Trip Distance

**Visualizations:**
- Total Trips by Passenger Count
- Average Trip Distance by Borough

**Purpose:** Analyze passenger load patterns and trip distance characteristics across boroughs.

</details>

### 5️⃣ Payment & Tips Insights

<details>
<summary><b>View Dashboard Details</b></summary>

**KPIs:**
- Average Tip
- Payment Type Share

**Visualizations:**
- Payment Type Distribution
- Tips by Borough

**Purpose:** Understand payment preferences and analyze tip patterns across different boroughs.

</details>

### 🎛️ Dashboard Interactivity

The Power BI dashboards include:

- Interactive page navigation.
- Year and month filters.
- Day of week and time filters.
- Borough and zone filters.
- Payment type filters.
- Cross-filtering between visuals.

---

## 📈 Key Performance Indicators

The following KPI values are displayed in the Power BI dashboards:

| KPI | Dashboard Value |
|---|---:|
| Total Trips | 18M |
| Total Revenue | 292.31M |
| Average Fare per Trip | 18.45 |
| Average Trip Distance | 4.58 |
| Total Zones | 262 |
| Total Boroughs | 7 |
| Average Passengers per Trip | 1.33 |
| Average Tip | 1.04 |
| Payment Type Share | 1.00 |

*Note: Values are presented as displayed in the project dashboards.*

---

## 🔎 Dashboard Insights

The dashboards provide the following analytical observations:

- **Trip & Revenue Trends:** Monthly revenue and year-over-year trip trends provide an overview of business performance.
- **Time-Based Demand:** Daily and hourly trip patterns help identify periods of higher demand.
- **Geographic Distribution:** Borough-wise trip distribution and zone-level analysis highlight popular travel locations.
- **Passenger Behavior:** Passenger count and average trip distance provide insights into travel characteristics.
- **Payment & Tips:** Payment type distribution and borough-wise tip analysis help understand customer payment preferences and tipping patterns.

---

## 💡 Business Recommendations

Based on the SQL analysis and Power BI dashboards, the following recommendations were developed.

### 🚕 1. Fleet Scheduling

- Allocate more drivers and vehicles during peak days and peak hours.
- Focus on high-demand routes and improve service quality on those routes.
- Adjust fleet distribution across boroughs based on trip demand.

### 💰 2. Pricing Optimization

- Review pricing strategies based on monthly revenue and trip value trends.
- Use average revenue per trip to understand earning patterns.
- Consider demand patterns when evaluating pricing strategies.

### 👥 3. Passenger Service Improvement

- Enhance customer experience for longer trips and preferred payment methods.
- Promote preferred payment methods to increase usage and revenue.
- Use passenger and distance insights to improve service planning.

---

## 🏆 Project Outcomes

Through this capstone project:

- Analyzed Uber Green Taxi trip data using SQL and Power BI.
- Solved 10 business questions using SQL analysis.
- Created 5 interactive Power BI dashboards.
- Analyzed trip trends, revenue patterns, and passenger behavior.
- Identified peak times, popular routes, borough-wise distribution, payment methods, and tip patterns.
- Developed actionable recommendations for fleet management, pricing, and passenger service improvements.

---

## 📁 Repository Structure

A suggested structure for organizing the project files:

```text
Uber-Trips-Analytics-SQL-PowerBI/
│
├── 📂 Dataset/
│   └── green_taxi_trips.csv
│
├── 📂 SQL/
│   ├── 01_yearly_trip_trends.sql
│   ├── 02_monthly_revenue_insights.sql
│   ├── 03_peak_day_time_analysis.sql
│   ├── 04_borough_trip_distribution.sql
│   ├── 05_top_pickup_dropoff_routes.sql
│   ├── 06_passenger_load_patterns.sql
│   ├── 07_trip_distance_analysis.sql
│   ├── 08_payment_method_analysis.sql
│   ├── 09_high_tip_routes.sql
│   └── 10_revenue_by_borough_pairs.sql
│
├── 📂 PowerBI/
│   └── Uber_Trips_Analytics.pbix
│
├── 📂 Dashboard_Screenshots/
│   ├── Trip_Revenue_Overview.png
│   ├── Time_Based_Demand_Analysis.png
│   ├── Geographic_Patterns.png
│   ├── Passenger_Distance_Insights.png
│   └── Payment_Tips_Insights.png
│
├── 📂 Reports/
│   └── Uber_Trips_Analytics_Project.pdf
│
└── README.md
```

*Note: This is the recommended repository structure. Add only the files that are actually included in your GitHub repository.*

---

## 🚀 How to Explore This Project

1. Clone or download this repository.
2. Download the NYC Green Taxi dataset from the dataset source.
3. Import the CSV dataset into your SQL environment.
4. Execute the SQL queries to explore the 10 business questions.
5. Open the Power BI `.pbix` file using Power BI Desktop.
6. Explore the five interactive dashboard pages.
7. Review the dashboard insights and business recommendations.

---

## 🔮 Future Scope

The project can be further extended through:

- Developing a predictive demand forecasting model using historical trip data.
- Analyzing seasonal demand variations.
- Improving real-time fleet allocation strategies.
- Exploring advanced pricing optimization techniques.
- Building more detailed geographic demand analysis.

---

## 📝 Conclusion

This project demonstrates how SQL and Power BI can be used together to transform raw taxi trip records into meaningful business insights.

By analyzing trip trends, revenue patterns, geographic distribution, passenger behavior, and payment preferences, the project provides a comprehensive understanding of taxi operations.

The five interactive Power BI dashboards and SQL-based analysis support data-driven decision-making for better fleet management, pricing strategies, operational efficiency, and passenger experience.

---

## 👨‍💻 Author

**Chetan Agrawal**

🎯 Aspiring Data Analyst | SQL | Python | Power BI | Data Analytics

- 🐙 **GitHub:** [github.com/chetan26agrawal](https://github.com/chetan26agrawal)
- 💼 **LinkedIn:** [linkedin.com/in/chetan-agrawal-725428162](https://www.linkedin.com/in/chetan-agrawal-725428162/)

---

⭐ If you find this project interesting, feel free to explore the repository and share your feedback!

**Thank You! 🚀**
