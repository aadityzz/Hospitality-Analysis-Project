# 🏨 Hospitality Business Insights Dashboard

An end-to-end **Hotel Chain Performance Analysis** project built using **Power BI** to analyze hotel bookings, revenue, occupancy, customer booking behavior, cancellation trends, and overall operational performance.

The goal of this project is to transform raw hospitality data into actionable business insights that can support **data-driven decision-making, revenue optimization, and improved room utilization**.

---

## 📌 Project Overview

The hospitality industry generates large volumes of booking and operational data. In this project, I analyzed hotel performance across multiple cities, room categories, booking channels, and time periods.

The analysis focuses on answering important business questions such as:

* How much revenue is the hotel chain generating?
* What is the overall occupancy rate?
* Is customer demand stronger on weekdays or weekends?
* Which city performs best in terms of revenue and RevPAR?
* Which room categories generate the highest revenue efficiency?
* How effectively are confirmed bookings converting into actual check-ins?
* Which booking channels contribute the most to revenue?
* What business actions can improve occupancy and reduce revenue leakage?

---

## 🎯 Business Objective

To evaluate hotel chain performance and identify actionable insights related to:

* Revenue generation
* Occupancy and room utilization
* Average Daily Rate (ADR)
* Revenue Per Available Room (RevPAR)
* Booking conversion / Realisation
* City-wise performance
* Room category performance
* Booking channel performance
* Customer demand patterns
* Revenue optimization opportunities

---

## 🛠️ Tools & Technologies Used

* **Microsoft Excel**
* **Power BI**
* **Power Query**
* **DAX**
* **Data Cleaning & Preprocessing**
* **Data Transformation**
* **Data Modelling**
* **Data Visualization**
* **Interactive Dashboarding**

---

## 🔄 Project Workflow

```text
Data Collection
      ↓
Data Preparation & Cleaning
      ↓
Data Transformation
      ↓
Data Modelling
      ↓
DAX Calculations
      ↓
Interactive Dashboard Development
      ↓
Business Insights
      ↓
Business Recommendations
```

---

## 📂 Dataset Overview

The project uses a star-schema-style dataset consisting of dimension and fact tables.

| Dataset                        | Type      | Columns | Records | Description                              |
| ------------------------------ | --------- | ------: | ------: | ---------------------------------------- |
| `dim_date.csv`                 | Dimension |       4 |      92 | Dates for the analysis period            |
| `dim_rooms.csv`                | Dimension |       2 |       4 | Room categories and types                |
| `dim_hotels.csv`               | Dimension |       4 |      25 | Hotel information                        |
| `fact_aggregated_bookings.csv` | Fact      |       5 |   9,200 | Hotel bookings and room capacity by day  |
| `fact_bookings.csv`            | Fact      |      12 | 134,590 | Detailed booking and revenue information |

### Analysis Scope

* **Analysis Period:** May, June and July
* **Total Weeks:** 13
* **Total Days:** 91
* **Cities:** Bangalore, Hyderabad, Delhi and Mumbai
* **Hotels:** 25

---

## 📊 Dashboard KPIs

The dashboard tracks the following key performance indicators:

| KPI           |         Value |
| ------------- | ------------: |
| 💰 Revenue    | ₹1.69 Billion |
| 🏨 Occupancy  |        57.79% |
| 💵 ADR        |       ₹12.70K |
| 📈 RevPAR     |        ₹7.34K |
| ✅ Realisation |        70.14% |
| 🛏️ DSRN      |          2.6K |
| 📅 DBRN       |         1.46K |

### KPI Definitions

**Revenue**
Total revenue generated from successful bookings.

**Occupancy**
Percentage of available rooms that were occupied.

**ADR — Average Daily Rate**
Average revenue earned per occupied room.

**RevPAR — Revenue Per Available Room**
Measures revenue generated per available room by combining occupancy and pricing performance.

**Realisation**
Percentage of confirmed bookings that resulted in successful check-ins after accounting for cancellations and no-shows.

**DSRN — Daily Sellable Room Nights**
Average number of rooms available for sale each day.

**DBRN — Daily Booked Room Nights**
Average number of rooms booked per day.

---

## 🔍 Key Business Insights

### 1️⃣ Weekend Demand Is Stronger

* Weekend occupancy was **62.64%**
* Weekday occupancy was **55.85%**
* Customer demand was approximately **8% higher during weekends**

This indicates an opportunity to improve weekday demand through targeted promotions and corporate packages.

---

### 2️⃣ Significant Room Inventory Remains Unutilized

The overall occupancy rate was **57.79%**.

This means a considerable portion of available hotel inventory remained unsold during the analysis period, creating an opportunity to improve room utilization.

---

### 3️⃣ RevPAR Was Driven More by Occupancy Than ADR

Across the analyzed weeks:

* ADR remained relatively stable at approximately **₹12.6K–₹12.7K**
* Occupancy increased from approximately **50% to 60%**
* RevPAR increased from approximately **₹6.0K to ₹7.5K**

This suggests that improvements in **occupancy had a stronger impact on RevPAR** than changes in room pricing during the analysis period.

---

### 4️⃣ Mumbai Was the Strongest-Performing Market

Mumbai generated:

* Highest Revenue: **₹660.64M**
* Highest ADR: **₹15.38K**
* Highest RevPAR: **₹8.90K**

Delhi achieved the highest occupancy at **60.44%**, indicating strong customer demand despite a comparatively lower ADR.

Hyderabad recorded the lowest ADR and RevPAR, indicating weaker revenue efficiency compared with other cities.

---

### 5️⃣ Premium Room Categories Generated Higher Revenue Efficiency

The **Presidential** room category achieved:

* Highest ADR: **₹23.43K**
* Highest RevPAR: **₹13.86K**

The **Standard** room category recorded:

* Lowest ADR: **₹8.05K**
* Lowest RevPAR: **₹4.65K**

This indicates that higher room categories generated greater revenue primarily through **premium pricing rather than significantly higher occupancy**.

---

### 6️⃣ Booking Conversion Represents a Major Opportunity

The overall Realisation rate remained around **70.14%**.

This means that nearly **30% of confirmed bookings did not convert into actual check-ins**.

The consistency of this trend across cities, months, and weeks suggests that booking losses may be a **systemic issue rather than a location-specific problem**.

---

### 7️⃣ Booking Channel Revenue Was Mainly Driven by Volume

The **Others** booking channel generated the highest booking volume and revenue contribution.

The **Direct Offline** channel recorded the lowest booking volume and revenue contribution.

ADR and Realisation remained relatively consistent across channels, suggesting that revenue differences were primarily driven by **booking volume rather than pricing or conversion efficiency**.

---

## 💡 Business Recommendations

### 📅 Improve Weekday Occupancy

Introduce:

* Targeted weekday promotions
* Corporate packages
* Business traveler offers

This can help utilize room inventory during lower-demand periods.

### 📈 Implement Demand Forecasting and Dynamic Pricing

Use demand forecasting to anticipate changes in customer demand and optimize pricing while maintaining healthy ADR levels.

### 🏨 Prioritize Occupancy Growth

Since occupancy had a strong impact on RevPAR, focus on demand-generation initiatives instead of relying only on price adjustments.

### 🌆 Benchmark High-Performing Markets

Analyze Mumbai's pricing and revenue management practices and evaluate whether suitable strategies can be adapted for lower-performing markets such as Hyderabad.

### ⭐ Promote Premium Room Upgrades

Use personalized offers and upselling opportunities to encourage customers to upgrade to higher room categories.

### ✅ Reduce Booking Leakage

Improve booking conversion through:

* Automated booking reminders
* Better cancellation management
* Flexible cancellation policies
* Selective prepaid/non-refundable booking options

### 📢 Optimize Booking Channel Strategy

Focus marketing investment on high-performing channels while evaluating the cost-effectiveness of low-performing channels.

---

## 📁 Repository Structure

```text
Hospitality-Analysis-Project/
│
├── HospitalityBI.pbix
├── HospitalityBIDashboard.pdf
├── Hotel_Chain_Performance_Executive_Report.pdf
├── dim_date.csv
├── dim_hotels.csv
├── dim_rooms.csv
├── fact_aggregated_bookings.csv
├── fact_bookings.csv
└── README.md
```

---

## 📊 Dashboard Features

The interactive Power BI dashboard allows users to analyze hotel performance using filters such as:

* City
* Room Type
* Month
* Week

The dashboard provides insights into:

* Revenue
* Occupancy
* ADR
* RevPAR
* Realisation
* DSRN
* DBRN
* Room category performance
* Booking platform performance
* City-wise performance
* Weekly performance trends

---

## 🚀 How to Use This Project

1. Clone this repository:

```bash
git clone https://github.com/aadityzz/Hospitality-Analysis-Project.git
```

2. Open `HospitalityBI.pbix` using **Power BI Desktop**.

3. Explore the interactive dashboard using the available filters.

4. Review the CSV files to understand the underlying data model.

5. Check the executive report PDF for detailed business insights and recommendations.

---

## 📈 Key Learnings

Through this project, I gained hands-on experience in:

* Data cleaning and transformation
* Power Query
* Data modelling
* Building relationships between fact and dimension tables
* Writing DAX measures
* KPI development
* Revenue and occupancy analysis
* Interactive dashboard development
* Business insight generation
* Translating data into actionable recommendations

---

## 👨‍💻 Author

**Aditya Tiwari**

Aspiring Data Analyst | Data Analytics | Power BI | SQL | Excel | Python

### 🔗 Connect With Me

* **GitHub:** https://github.com/aadityzz
* **LinkedIn:** https://www.linkedin.com/in/aadityzz

---

⭐ **If you found this project interesting, consider giving the repository a star!**
