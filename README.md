# 🚕 Uber Trips Analytics | SQL & Power BI Capstone Project

![Project](https://img.shields.io/badge/Project-Capstone-yellow)
![SQL](https://img.shields.io/badge/SQL-Advanced-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Interactive%20Dashboard-yellow)
![Domain](https://img.shields.io/badge/Domain-Data%20Analytics-green)

**An End-to-End Data Analytics Project on NYC Green Taxi Trip Records**

---

## 📑 Table of Contents

1. [Project Overview](#-project-overview)
2. [Business Problem](#-business-problem)
3. [Project Objectives](#-project-objectives)
4. [Dataset Information](#-dataset-information)
5. [Tools & Technologies](#-tools--technologies)
6. [Dataset Fields](#-dataset-fields)
7. [Project Methodology](#-project-methodology)
8. [Part 1: Advanced SQL Analysis](#-part-1-advanced-sql-analysis)
9. [Part 2: Power BI Dashboard](#-part-2-interactive-power-bi-dashboard)
10. [Key Performance Indicators](#-key-performance-indicators)
11. [Key Business Insights](#-key-business-insights)
12. [Business Recommendations](#-business-recommendations)
13. [Project Outcomes](#-project-outcomes)
14. [Repository Structure](#-repository-structure)
15. [How to Run This Project](#-how-to-run-this-project)
16. [Future Scope](#-future-scope)
17. [Conclusion](#-conclusion)
18. [About Me](#-about-me)

---

## 📌 Project Overview

Uber Trips Analytics is an end-to-end Data Analytics Capstone Project focused on analyzing New York City Green Taxi trip records.

The objective of this project is to uncover meaningful business insights from historical taxi trip data using **Advanced SQL and Power BI**.

The analysis covers trip volumes, revenue patterns, geographic distribution, passenger behavior, payment preferences, and operational efficiency.

The project demonstrates how data analytics can help businesses make informed decisions regarding fleet management, pricing optimization, and customer experience.

### 🔑 Key Focus Areas

- 🚕 Trip Trends & Volume Analysis
- 💰 Revenue & Fare Analysis
- 📍 Geographic & Route Analysis
- 👥 Passenger Behavior Analysis
- 💳 Payment & Tip Analysis
- 📈 Demand Forecasting Scope

---

## 🎯 Business Problem

The Uber Taxi & Limousine Commission needs to analyze Green Taxi trip data to identify trends, improve operational efficiency, optimize fleet management, set pricing, and enhance customer experience in New York City.

Understanding trip patterns, revenue trends, geographic demand, and passenger behavior is essential to improve operational performance and support data-driven decisions.

### Business Goals

- Improve fleet allocation and scheduling.
- Identify peak demand periods.
- Optimize pricing strategies.
- Understand customer travel behavior.
- Analyze revenue and payment patterns.
- Improve passenger experience.

---

## 🎯 Project Objectives

1. Analyze historical trip volumes and revenue trends.
2. Identify peak demand days, hours, and high-demand locations.
3. Understand geographic trip distribution and popular routes.
4. Analyze passenger count and trip distance patterns.
5. Examine payment methods and tip behavior.
6. Develop interactive dashboards for business monitoring.
7. Provide actionable recommendations for operational efficiency.
8. Explore predictive demand forecasting.

---

## 📂 Dataset Information

**Dataset:** NYC Green Taxi Trip Records

**Source:** New York City Taxi & Limousine Commission (TLC)

**Dataset Link:** [Download Uber Taxi Trips - NYC](https://wscubetechpvtltd-my.sharepoint.com/:u:/g/personal/ayushi_jain_wscubetech_com/IQBQxgFAOtljWyiNHKoult5oAcO2H5i9KMp2Hd9W0_COEqo?e=tzT7hL)

The dataset contains historical taxi trip records with information about:

- Pickup and drop-off timestamps.
- Pickup and drop-off boroughs.
- Pickup and drop-off zones.
- Passenger count.
- Trip distance.
- Fare amount.
- Tip amount.
- Payment type.
- Total trip amount.

**SQL Analysis Period:** 2017–2020.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| SQL | Data analysis and business problem solving |
| MySQL | Query execution and data analysis |
| Power BI | Interactive dashboards and visualizations |
| CSV | Dataset storage and data import |

### SQL Concepts Used

- Common Table Expressions (CTEs)
- UNION ALL
- Aggregate Functions
- GROUP BY
- ORDER BY
- JOIN Operations
- Window Functions
- LAG()
- Date and Time Functions
- Percentage Calculations
- ROUND()

---

## 📊 Dataset Fields

| Column | Description |
|---|---|
| `tpep_pickup_datetime` | Pickup date and time |
| `tpep_dropoff_datetime` | Drop-off date and time |
| `pickup_borough` | Pickup borough |
| `dropoff_borough` | Drop-off borough |
| `pickup_zone` | Pickup zone |
| `dropoff_zone` | Drop-off zone |
| `passenger_count` | Number of passengers |
| `trip_distance` | Trip distance |
| `fare_amount` | Trip fare |
| `tip_amount` | Tip amount |
| `payment_type` | Payment method |
| `total_amount` | Total trip amount |

---

## ⚙️ Project Methodology

The project follows a structured data analytics workflow.

**1. Data Collection**
- Collected NYC Green Taxi trip records.
- Imported CSV files into SQL.
- Organized yearly staging tables.

**2. Data Cleaning**
- Handled missing values.
- Checked duplicate records.
- Prepared data for analysis.
- Performed data type conversions.

**3. SQL Analysis**
- Combined yearly trip records.
- Solved 10 business questions.
- Analyzed trip trends, revenue, routes, passenger behavior, and payment patterns.

**4. Dashboard Development**
- Created five interactive Power BI dashboard pages.
- Developed KPI cards and charts.
- Added interactive filters and navigation.

**5. Business Insights**
- Identified demand and revenue patterns.
- Analyzed passenger and payment behavior.
- Developed business recommendations.

---

# 💻 Part 1: Advanced SQL Analysis

The SQL analysis focuses on answering 10 business questions to understand taxi operations, demand patterns, revenue, and operational efficiency.

### 1️⃣ Yearly Trip Trends

**Business Question:**
Calculate total trips per year and percentage change year-over-year.

**Analysis:**
- Calculated yearly trip volumes.
- Compared trips across different years.
- Used the LAG() window function to calculate year-over-year changes.

### 2️⃣ Monthly Revenue Insights

**Business Question:**
Find monthly total revenue and average revenue per trip.

**Analysis:**
- Calculated monthly revenue.
- Analyzed average revenue per trip.
- Compared revenue patterns across months.

### 3️⃣ Peak Day & Time Analysis

**Business Question:**
Identify the day of the week and hour of the day with the highest average trip volumes.

**Top Demand Time Slots from SQL Results:**

| Day | Time Slot | Average Trips |
|---|---|---:|
| Friday | 17:00–18:00 | 1166.86 |
| Friday | 19:00–20:00 | 1120.03 |
| Thursday | 18:00–19:00 | 1115.69 |
| Friday | 16:00–17:00 | 1086.65 |
| Thursday | 17:00–18:00 | 1085.39 |

### 4️⃣ Borough Trip Distribution

**Business Question:**
Find the percentage of trips starting in each pickup borough.

**SQL Results:**

| Pickup Borough | Total Trips | Percentage |
|---|---:|---:|
| Manhattan | 6,241,731 | 33.40% |
| Brooklyn | 5,784,791 | 30.96% |
| Queens | 5,409,427 | 28.93% |
| Bronx | 1,210,186 | 6.48% |
| Unknown | 36,326 | 0.19% |

### 5️⃣ Top Pickup-Dropoff Routes

**Business Question:**
Identify the top 10 most frequent pickup-zone to drop-off-zone combinations.

**Analysis:**
- Joined pickup and drop-off zone information.
- Counted trips for each route.
- Ranked routes by trip frequency.

### 6️⃣ Passenger Load Patterns

**Business Question:**
Find the average passenger count for trips in each borough.

**SQL Results:**

| Borough | Average Passengers |
|---|---:|
| Manhattan | 1.2887 |
| Brooklyn | 1.3283 |
| Queens | 1.4010 |
| Bronx | 1.2909 |
| Unknown | 1.2381 |

### 7️⃣ Trip Distance Distribution

**Business Question:**
Determine the average trip distance for each pickup borough and drop-off borough.

**Analysis:**
- Analyzed trip distances.
- Grouped records by pickup and drop-off borough.
- Calculated average trip distance.

### 8️⃣ Payment Method Analysis

**Business Question:**
Calculate the percentage share of each payment type and their average fare amount.

**SQL Results:**

| Payment Type | Total Trips | Percentage Share | Average Fare |
|---|---:|---:|---:|
| 1 | 9,397,280 | 53.28% | 15.22 |
| 2 | 7,174,453 | 40.68% | 10.69 |
| 3 | 82,897 | 0.47% | 3.01 |
| 4 | 36,487 | 0.21% | 3.97 |
| 5 | 663 | 0.00% | 10.74 |

### 9️⃣ High-Tip Routes

**Business Question:**
Find the top 5 pickup-dropoff combinations with the highest average tip amount.

**Top 5 Routes:**

| Pickup Zone | Drop-off Zone | Trips | Average Tip |
|---|---|---:|---:|
| Washington Heights South | Heartland Village/Todt Hill | 11 | 17.71 |
| Morningside Heights | Eltingville/Annadale/Prince's Bay | 11 | 17.71 |
| LaGuardia Airport | DUMBO/Vinegar Hill | 13 | 17.67 |
| Flatbush/Ditmas Park | Newark Airport | 10 | 17.51 |
| Flushing | Newark Airport | 10 | 17.39 |

### 🔟 Revenue by Borough Pairs

**Business Question:**
Calculate total amount earned for each pickup borough to drop-off borough pair.

**SQL Results:**

| Pickup Borough | Drop-off Borough | Total Trips | Total Revenue |
|---|---|---:|---:|
| Manhattan | Manhattan | 5,220,727 | 65,094,919.30 |
| Brooklyn | Brooklyn | 4,273,039 | 62,748,454.98 |
| Queens | Queens | 4,465,151 | 57,802,084.18 |
| Brooklyn | Manhattan | 774,284 | 22,919,660.33 |
| Bronx | Bronx | 807,010 | 12,735,130.67 |

---

# 📈 Part 2: Interactive Power BI Dashboard

Developed five interactive dashboard pages to visualize trip trends, revenue breakdowns, demand patterns, geographic insights, passenger behavior, and payment preferences.

## 1️⃣ Trip & Revenue Overview

**KPIs:**
- Total Trips
- Total Revenue
- Average Fare per Trip
- Year-over-Year Trip Change

**Visualizations:**
- Monthly Revenue Analysis
- Yearly Trip Trends
- Fare Distribution

**Objective:** Understand overall trip performance and revenue trends.

## 2️⃣ Time-Based Demand Analysis

**KPIs:**
- Peak Day
- Peak Hour
- Trip Volume by Time

**Visualizations:**
- Trips by Day
- Trips by Hour
- Time-Based Demand Analysis

**Objective:** Identify peak demand periods and understand trip patterns throughout the day.

## 3️⃣ Geographic Patterns

**KPIs:**
- Top Pickup Boroughs
- Top Drop-off Boroughs

**Visualizations:**
- Borough Trip Distribution
- Top Pickup-Dropoff Routes
- Borough-Level Geographic Analysis

**Objective:** Understand geographic trip distribution and identify high-demand locations.

## 4️⃣ Passenger & Distance Insights

**KPIs:**
- Average Passengers per Trip
- Average Trip Distance

**Visualizations:**
- Passenger Count Distribution
- Average Trip Distance by Borough

**Objective:** Analyze passenger behavior and trip distance characteristics.

## 5️⃣ Payment & Tips Insights

**KPIs:**
- Payment Type Share
- Average Tip by Route

**Visualizations:**
- Payment Method Distribution
- High-Tip Routes
- Tips Analysis

**Objective:** Understand payment preferences and tip patterns.

### 🎛️ Dashboard Filters & Interactivity

- Date Range
- Borough
- Payment Type
- Passenger Count
- Zone-Level Drill-Down
- Interactive Dashboard Navigation

---

## 📌 Key Performance Indicators

The following values are displayed in the Power BI dashboards.

| KPI | Value |
|---|---:|
| Total Trips | 18M |
| Total Revenue | 292.31M |
| Average Fare per Trip | 18.45 |
| YOY Trips | -4E-16 |
| Average Trip Distance | 4.58 |
| Total Zones | 262 |
| Total Boroughs | 7 |
| Average Passengers per Trip | 1.33 |
| Average Tip | 1.04 |
| Payment Type Share | 1.00 |

*Note: Values are reproduced in the format displayed in the project dashboard.*

---

## 🔍 Key Business Insights

**🚕 Trip & Demand Analysis**
- Friday evening time slots show high average trip volumes in the SQL results.
- Peak-hour analysis helps identify periods requiring additional fleet availability.

**💰 Revenue Analysis**
- Total revenue displayed in the dashboard is 292.31M.
- Average fare per trip is 18.45.
- Monthly revenue analysis helps understand revenue patterns.

**📍 Geographic Analysis**
- Manhattan contributes 33.40% of pickup trips.
- Brooklyn contributes 30.96%.
- Queens contributes 28.93%.
- Borough and zone analysis helps identify important travel locations.

**👥 Passenger Analysis**
- Average passengers per trip is 1.33.
- Average trip distance is 4.58.
- Passenger distribution provides insights into travel behavior.

**💳 Payment Analysis**
- Payment Type 1 contributes 53.28% of trips.
- Payment Type 2 contributes 40.68%.
- Average tip displayed in the dashboard is 1.04.

---

## 💡 Business Recommendations

### 🚕 1. Fleet Scheduling

- Allocate more drivers and vehicles during peak days and peak hours.
- Focus on high-demand routes.
- Adjust fleet distribution across boroughs based on trip demand.

### 💰 2. Pricing Optimization

- Review pricing strategies based on monthly revenue and trip value trends.
- Analyze average fare per trip.
- Consider demand patterns when evaluating pricing strategies.

### 👥 3. Passenger Service Improvement

- Improve service availability on popular routes.
- Enhance customer experience for longer trips.
- Use passenger and distance insights to improve service planning.

---

## 🏆 Project Outcomes

- Analyzed NYC Green Taxi trip data using SQL and Power BI.
- Solved 10 business questions using SQL.
- Developed five interactive Power BI dashboards.
- Analyzed trip trends, revenue patterns, and passenger behavior.
- Identified peak demand periods and popular routes.
- Evaluated borough-wise trip distribution.
- Analyzed payment preferences and tip patterns.
- Developed data-driven business recommendations.

---

## 📁 Repository Structure

```text
Uber-Trips-Analytics-SQL-PowerBI/
│
├── Dataset/
│   └── Green_Taxi_Trip_Data.csv
│
├── SQL/
│   ├── Question_01_Yearly_Trip_Trends.sql
│   ├── Question_02_Monthly_Revenue_Insights.sql
│   ├── Question_03_Peak_Day_Time_Analysis.sql
│   ├── Question_04_Borough_Trip_Distribution.sql
│   ├── Question_05_Top_Pickup_Dropoff_Routes.sql
│   ├── Question_06_Passenger_Load_Patterns.sql
│   ├── Question_07_Trip_Distance_Analysis.sql
│   ├── Question_08_Payment_Method_Analysis.sql
│   ├── Question_09_High_Tip_Routes.sql
│   └── Question_10_Revenue_By_Borough_Pairs.sql
│
├── PowerBI/
│   └── Uber_Trips_Analytics.pbix
│
├── Dashboard_Screenshots/
│   ├── Trip_Revenue_Overview.png
│   ├── Time_Based_Demand_Analysis.png
│   ├── Geographic_Patterns.png
│   ├── Passenger_Distance_Insights.png
│   └── Payment_Tips_Insights.png
│
├── Reports/
│   └── Uber_Trips_Analytics_Project.pdf
│
└── README.md
```

*Note: This is a suggested folder structure. Update filenames according to the actual files uploaded to GitHub.*

---

## 🚀 How to Run This Project

**Step 1: Clone the Repository**

```bash
git clone https://github.com/chetan26agrawal/Uber-Trips-Analytics-SQL-PowerBI.git
```

**Step 2: Download the Dataset**

Download the NYC Green Taxi dataset using the dataset link provided above.

**Step 3: Import Dataset into MySQL**

- Open MySQL Workbench.
- Create a database.
- Import the CSV dataset.
- Prepare the required staging tables and zone lookup data.

**Step 4: Execute SQL Queries**

Run the 10 SQL scripts available in the SQL folder.

**Step 5: Open Power BI Dashboard**

- Open Power BI Desktop.
- Load the `.pbix` file.
- Configure the data source if required.
- Explore all five dashboard pages.

**Step 6: Explore Business Insights**

Analyze KPI cards, charts, filters, trip patterns, and business recommendations.

---

## 🔮 Future Scope

The project can be extended through:

- Developing a predictive demand forecasting model.
- Analyzing seasonal demand variations.
- Improving real-time fleet allocation.
- Exploring advanced pricing optimization.
- Performing deeper geographic demand analysis.
- Applying machine learning for future trip demand prediction.

*Note: Predictive forecasting is part of the project objective and future scope; a completed forecasting model is not documented in the submitted project presentation.*

---

## 📝 Conclusion

This Uber Trips Analytics project demonstrates how SQL and Power BI can be used together to transform raw taxi trip records into meaningful business insights.

By analyzing trip trends, revenue patterns, geographic distribution, passenger behavior, payment preferences, and tip patterns, the project provides a comprehensive understanding of taxi operations in New York City.

The 10 SQL business questions and five interactive Power BI dashboards support data-driven decision-making for improved fleet scheduling, pricing optimization, operational efficiency, and passenger experience.

---

# 👨‍💻 About Me

## Chetan Agrawal

🎯 **Aspiring Data Analyst | SQL | Python | Power BI | Data Analytics**

I am passionate about data analytics, exploring datasets, solving real-world business problems, and transforming raw data into meaningful insights.

I enjoy working with SQL, Python, and Power BI to analyze data, identify trends, and communicate actionable business insights.

### 🌐 Connect With Me

🐙 **GitHub Profile:**

https://github.com/chetan26agrawal

💼 **LinkedIn Profile:**

https://www.linkedin.com/in/chetan-agrawal-725428162/

---

⭐ If you find this project interesting, feel free to explore the repository and share your feedback!

**Thank You for Visiting My Project! 🚀**
