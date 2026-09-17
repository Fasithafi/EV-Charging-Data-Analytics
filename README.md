EV Charging Data Analytics Dashboard

An interactive Power BI dashboard developed to analyze EV charging activity and identify trends in charging sessions, energy consumption, revenue, charger usage, and station performance.
The project analyzes **73K+ EV charging records** and transforms raw charging data into an interactive business intelligence dashboard.

**Project Overview**
The growth of electric vehicles has created an increasing demand for efficient and reliable charging infrastructure.
This project uses data analytics and visualization techniques to understand how EV charging stations are being utilized. The analysis focuses on operational, financial, geographical, and time-based aspects of charging activity.
The final output is an **interactive Power BI dashboard** that allows users to explore charging performance using different filters and visualizations.

**Objectives**
The main objectives of this project are to:
* Analyze EV charging session activity.
* Understand energy consumption patterns.
* Analyze charging revenue.
* Compare different charger types.
* Evaluate charging success rates.
* Monitor station uptime.
* Analyze average charging session duration.
* Identify monthly charging trends.
* Compare charging activity across locations.
* Build an interactive dashboard for data-driven analysis.

**Dataset**
The dataset contains **73K+ records** related to EV charging activity.
**Main Features**

| Feature                      | Description                                    |
| ---------------------------- | ---------------------------------------------- |
| `Station_ID`                 | Unique charging station identifier             |
| `Charger_Type`               | Type of charger used                           |
| `Connector_Type`             | Charging connector type                        |
| `Charging_Sessions`          | Number of charging sessions                    |
| `Charging_Success_%`         | Percentage of successful charging sessions     |
| `Avg_Session_Duration_Min`   | Average charging session duration              |
| `City`                       | City of the charging station                   |
| `State`                      | State of the charging station                  |
| `Date`                       | Date of the recorded activity                  |
| `Month`                      | Month of activity                              |
| `Month_Number`               | Numerical month used for chronological sorting |
| `Year`                       | Year of activity                               |
| `Revenue_INR`                | Revenue generated from charging                |
| `Tariff_per_kWh`             | Charging tariff per kWh                        |
| `Total Energy Consumed(kWh)` | Total energy consumed                          |
| `Station_Uptime_%`           | Percentage of station uptime                   |
| `Peak_Hour_Share_%`          | Share of charging activity during peak hours   |
| `Vehicle_Category`           | Vehicle category                               |
| `Vehicle_Type`               | Vehicle type                                   |

**Tools & Technologies**

* Microsoft Power BI — Dashboard development and visualization
* Microsoft Excel — Dataset inspection and preparation
* Data Analytics — Aggregation, trend analysis, KPI analysis, and exploratory analysis

**Project Workflow**

Raw EV Charging Dataset
          ↓
   Data Inspection
          ↓
   Data Preparation
          ↓
 Data Type Validation
          ↓
   Data Aggregation
          ↓
 Exploratory Analysis
          ↓
 Power BI Visualization
          ↓
 Interactive Dashboard
          ↓
    Data Insights

**Dashboard Features**

The Power BI dashboard provides an interactive view of EV charging performance.

### 🔹 Charging Session Analysis

Analyzes the volume of charging activity across stations and other dimensions.

This helps identify differences in charging demand and station usage.

### 🔹 Energy Consumption

Analyzes the total amount of electrical energy consumed through charging sessions.

The dashboard uses the sum of:

`Total Energy Consumed(kWh)`

to understand overall energy demand.

### 🔹 Revenue Analysis

Analyzes charging revenue using:

`Revenue_INR`

Revenue can be explored across different charging and location-related dimensions.

### 🔹 Charger Type Analysis

The dataset includes multiple charger categories:

* AC
* DC Fast
* DC Ultrafast

These can be compared to understand charging activity across different charger technologies.

### 🔹 Average Session Duration

The:

`Avg_Session_Duration_Min`

field is analyzed using **Average** aggregation to represent typical charging-session duration.

### 🔹 Charging Success Rate

The:

`Charging_Success_%`

metric is used to analyze the percentage of successful charging sessions.

### 🔹 Station Uptime

The:

`Station_Uptime_%`

metric provides an indication of charging station availability and operational performance.

### 🔹 Monthly Trend Analysis

Charging activity can be analyzed over time using the `Month`, `Month_Number`, and `Year` fields.

`Month_Number` is used to maintain the correct chronological order of months rather than alphabetical ordering.

**Interactive Dashboard**

The dashboard includes interactive filtering capabilities.
Users can explore the data using dimensions such as:
* City
* State
* Charger Type
* Vehicle Type
* Vehicle Category
* Year
* Month
Selecting a filter dynamically updates the relevant dashboard visualizations.

**Key KPIs**
The dashboard focuses on several important performance indicators:

| KPI                      | Purpose                                         |
| ------------------------ | ----------------------------------------------- |
| Charging Sessions        | Measures charging activity                      |
| Total Energy Consumed    | Measures electricity consumption                |
| Revenue                  | Measures charging-generated revenue             |
| Charging Success %       | Measures successful charging activity           |
| Station Uptime %         | Measures station availability                   |
| Average Session Duration | Measures typical session length                 |
| Peak Hour Share %        | Indicates charging activity during peak periods |

**Key Insights**
The dashboard enables analysis of several important patterns.
### Charging Activity
Charging sessions can be compared across stations, locations, charger types, vehicle categories, and time periods.
### Energy Demand
The dataset represents energy consumption at the **million-kWh scale**, providing an overview of the electricity demand associated with the recorded charging activity.
### Charger Usage
AC, DC Fast, and DC Ultrafast chargers can be compared to understand differences in charging activity across technologies.
### Operational Performance
Charging success rate and station uptime provide indicators for evaluating charging infrastructure performance.
### Time-Based Trends
Monthly analysis makes it possible to identify changes in charging activity over time.
### Geographic Analysis
City and state fields allow charging activity to be explored geographically.

**Future Improvements**
The current project focuses primarily on descriptive analytics and interactive visualization.
Potential future improvements include:

* Real-time EV charging data integration
* Charging demand forecasting
* Machine learning-based prediction
* Station utilization analysis
* Geographic map visualization
* Revenue forecasting
* Peak-demand prediction
* Automated dashboard refresh
* Advanced DAX measures
* Integration with live charging APIs

**Learning Outcomes**
This project provided practical experience in:

* Data preparation
* Data cleaning
* Data aggregation
* Exploratory data analysis
* KPI development
* Power BI visualization
* Interactive dashboard design
* Time-series analysis
* Business intelligence
* Data storytelling
* Converting raw data into actionable insights

**Author**

**Mohamed Fasith**
Data Analytics | Power BI | Python | Data Science
If you find this project useful or interesting, consider giving the repository a ⭐.
