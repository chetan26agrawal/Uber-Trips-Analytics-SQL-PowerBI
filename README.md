# 🚕 Uber Trips Analytics | SQL & Power BI

A data analytics project focused on exploring NYC Green Taxi Trip Records using SQL and Power BI. This project analyzes trip trends, revenue patterns, passenger behavior, geographic distribution, payment methods, and tips to generate meaningful business insights.

---

## 📑 Table of Contents

1. [Project Overview](#project-overview)
2. [Project Objectives](#project-objectives)
3. [Dataset Description](#dataset-description)
4. [Tools and Technologies](#tools-and-technologies)
5. [Business Questions](#business-questions)
6. [SQL Analysis](#sql-analysis)
7. [Power BI Dashboard](#power-bi-dashboard)
8. [Trip and Revenue Overview](#trip-and-revenue-overview)
9. [Time-Based Demand Analysis](#time-based-demand-analysis)
10. [Geographic Patterns](#geographic-patterns)
11. [Passenger and Distance Insights](#passenger-and-distance-insights)
12. [Payment and Tips Insights](#payment-and-tips-insights)
13. [Key Business Insights](#key-business-insights)
14. [Business Recommendations](#business-recommendations)
15. [Project Structure](#project-structure)
16. [How to Use This Project](#how-to-use-this-project)
17. [Conclusion](#conclusion)
18. [About Me](#about-me)

---

<a id="project-overview"></a>
## 1. 🚀 Project Overview

The **Uber Trips Analytics** project focuses on analyzing NYC Green Taxi trip records to understand transportation trends, revenue performance, customer behavior, and operational patterns.

SQL is used to query and analyze the dataset, while Power BI is used to build an interactive dashboard that presents the findings through visualizations and KPIs.

The project aims to convert raw trip data into meaningful insights that can support data-driven business decisions.

---

<a id="project-objectives"></a>
## 2. 🎯 Project Objectives

- Analyze yearly and monthly trip trends.
- Understand revenue performance over time.
- Identify peak trip days and hours.
- Explore pickup and drop-off geographic patterns.
- Analyze passenger distribution and trip distances.
- Understand payment method preferences.
- Evaluate tipping behavior and high-tip routes.
- Build an interactive Power BI dashboard.
- Generate actionable business recommendations.

---

<a id="dataset-description"></a>
## 3. 📂 Dataset Description

**Dataset:** NYC Green Taxi Trip Records

The dataset contains taxi trip-level information that can be used to analyze transportation activities, trip revenue, passenger details, payment methods, and geographic patterns.

The analysis uses the available dataset fields and their corresponding records.

*Note: Actual results depend on the dataset and the data-cleaning and transformation steps performed during the project.*

---

<a id="tools-and-technologies"></a>
## 4. 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| SQL | Data querying and business analysis |
| Power BI | Interactive dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | Measures and KPI calculations |
| Microsoft Excel | Data inspection and preparation |
| GitHub | Project documentation and portfolio |

---

<a id="business-questions"></a>
## 5. 💡 Business Questions

The project addresses the following business questions:

1. How do yearly trips change over time, and what is the year-over-year growth?
2. What is the monthly revenue trend?
3. Which days and hours experience the highest trip demand?
4. How are pickups distributed across different boroughs?
5. What are the most frequently used pickup and drop-off routes?
6. How does passenger load vary by borough?
7. What is the average trip distance across pickup and drop-off boroughs?
8. What is the distribution of payment types, and what is the average fare for each?
9. Which routes generate the highest tips?
10. How does revenue vary across different borough-to-borough combinations?

---

<a id="sql-analysis"></a>
## 6. 🗄️ SQL Analysis

SQL is used to explore the dataset and answer the business questions through queries and aggregations.

The analysis covers:

- Yearly trip trends and year-over-year comparisons.
- Monthly revenue analysis.
- Peak demand by day and hour.
- Borough-wise pickup distribution.
- Top pickup and drop-off routes.
- Passenger load analysis by borough.
- Average trip distance analysis.
- Payment type distribution and average fare.
- High-tip route identification.
- Revenue analysis by borough pairs.

These queries help identify patterns in trip demand, revenue generation, passenger activity, and customer payment behavior.

---

<a id="power-bi-dashboard"></a>
## 7. 📊 Power BI Dashboard

An interactive Power BI dashboard is developed to present the analysis in five pages.

The dashboard is organized into the following sections:

---

<a id="trip-and-revenue-overview"></a>
## 8. 💰 Trip and Revenue Overview

This page provides a high-level view of overall trip activity and revenue performance.

It focuses on:

- Total trips.
- Total revenue.
- Average fare.
- Trip and revenue trends.
- Overall performance indicators.

---

<a id="time-based-demand-analysis"></a>
## 9. ⏰ Time-Based Demand Analysis

This page focuses on understanding how trip demand changes over time.

It covers:

- Year-wise trip trends.
- Monthly trip patterns.
- Day-wise demand.
- Hour-wise trip activity.
- Peak demand periods.

---

<a id="geographic-patterns"></a>
## 10. 📍 Geographic Patterns

This page explores the geographic distribution of taxi trips.

It includes:

- Pickup distribution across boroughs.
- Popular pickup and drop-off locations.
- Frequently used routes.
- Borough-wise trip patterns.
- Revenue patterns across borough combinations.

---

<a id="passenger-and-distance-insights"></a>
## 11. 🚖 Passenger and Distance Insights

This page focuses on passenger activity and trip distance patterns.

It includes:

- Passenger load analysis.
- Average trip distance.
- Distance comparisons across boroughs.
- Passenger-related trip patterns.

---

<a id="payment-and-tips-insights"></a>
## 12. 💳 Payment and Tips Insights

This page analyzes payment behavior and tipping patterns.

It covers:

- Payment type distribution.
- Average fare by payment type.
- Tip analysis.
- High-tip routes.
- Customer payment preferences.

---

<a id="key-business-insights"></a>
## 13. 🔍 Key Business Insights

The SQL analysis and Power BI dashboard are designed to help identify:

- Changes in trip demand over time.
- Revenue patterns across different periods.
- High-demand days and hours.
- Geographic areas with greater trip activity.
- Popular pickup and drop-off routes.
- Differences in passenger load and trip distance.
- Payment method preferences.
- Routes associated with higher tips.

*The actual findings should be interpreted from the results generated by the project queries and dashboard.*

---

<a id="business-recommendations"></a>
## 14. 📈 Business Recommendations

Based on the patterns identified through the analysis, businesses can use the findings to:

- Improve fleet availability during high-demand periods.
- Plan driver schedules according to trip demand.
- Identify areas that require better vehicle availability.
- Monitor revenue performance across different periods.
- Understand customer payment preferences.
- Evaluate route-level performance.
- Use trip and tipping patterns to improve operational planning.

---

<a id="project-structure"></a>
## 15. 📁 Project Structure

The repository can be organized as follows. Adjust the folder and file names to match the files actually uploaded to your repository.

```text
Uber-Trips-Analytics-SQL-PowerBI/
│
├── Dataset/
│   └── NYC_Green_Taxi_Trip_Records
│
├── SQL/
│   └── SQL_Analysis_Queries.sql
│
├── PowerBI/
│   └── Uber_Trips_Analytics_Dashboard.pbix
│
├── Dashboard_Screenshots/
│   └── Dashboard_Images
│
└── README.md
```

---

<a id="how-to-use-this-project"></a>
## 16. ▶️ How to Use This Project

1. Clone or download this repository.
2. Download or access the NYC Green Taxi Trip Records dataset.
3. Load the dataset into your SQL environment.
4. Execute the SQL queries to perform the analysis.
5. Open the Power BI dashboard file.
6. Refresh the data if required.
7. Explore the dashboard pages and their visualizations.

---

<a id="conclusion"></a>
## 17. 🏁 Conclusion

The Uber Trips Analytics project demonstrates how SQL and Power BI can be used together to analyze transportation data and extract useful business insights.

Through SQL-based analysis and interactive Power BI visualizations, the project explores trip demand, revenue performance, geographic patterns, passenger activity, payment behavior, and tipping trends.

This project strengthened practical skills in data analysis, SQL querying, data visualization, dashboard development, and business-oriented problem-solving.

---

<a id="about-me"></a>
## 18. 👨‍💻 About Me

**Chetan Agrawal**

I am an aspiring Data Analyst interested in transforming raw data into meaningful insights using data analytics and visualization tools.

**Connect with me:**

- 💼 LinkedIn: [Chetan Agrawal](https://www.linkedin.com/in/chetan-agrawal-725428162/)
- 🐙 GitHub: [chetan26agrawal](https://github.com/chetan26agrawal)

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
