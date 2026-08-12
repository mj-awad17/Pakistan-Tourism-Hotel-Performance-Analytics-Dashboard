# 🏨 Pakistan Tourism & Hotel Performance Analytics Dashboard

![Project Banner](https://github.com/mj-awad17/Pakistan-Tourism-Hotel-Performance-Analytics-Dashboard/blob/main/interactive_dashboard.jpg)

> **An end-to-end data analytics project featuring raw data processing, data cleaning & transformation, dynamic KPI Scorecard modeling, and an interactive executive dashboard.**

---

## 📸 Interactive Dashboard Preview

To highlight the full analytics lifecycle, this project showcases the progression from unformatted raw data to executive-ready business insights.

| 1. Messy / Raw Data | 2. Cleaned & Structured Dataset |
| :---: | :---: |
| ![Messy Data](https://github.com/mj-awad17/Pakistan-Tourism-Hotel-Performance-Analytics-Dashboard/blob/main/messy_data.png) | ![Clean Data](https://github.com/mj-awad17/Pakistan-Tourism-Hotel-Performance-Analytics-Dashboard/blob/main/clean_data.png)
| *Raw records with unformatted metrics and missing structures* | *Cleaned sheet with proper data types, conditional formatting & formulas* |

| 3. Dynamic KPI Scorecards | 4. Executive Dashboard |
| :---: | :---: |
| ![KPI Cards](https://github.com/mj-awad17/Pakistan-Tourism-Hotel-Performance-Analytics-Dashboard/blob/main/KPIs_cards.png) |
| *Calculated metrics (Total Revenue: PKR 1.16B, ADR: PKR 14k)* | *Interactive view with dynamic slicers for City, Province & Season* |

---

## 💡 Business Problem & Objectives

The hospitality sector across Pakistan faces seasonal demand fluctuations and complex guest demographic variations. Hotel stakeholders needed a centralized business intelligence view to track revenue drivers, room occupancy rates, and customer demographics across major cities.

**Key Objectives:**
1. **Revenue Management:** Analyze Total Revenue (PKR 1.16 Billion+) and Average Daily Rate (ADR) across different booking sources.
2. **Occupancy & Demand Modeling:** Evaluate monthly revenue trends and seasonal demand distributions (Winter, Spring, Summer, Autumn).
3. **Guest Segmentation:** Understand customer booking behavior across types (Business, Family, Tour Group, Individual) and origin (Local vs. Foreign visitors).
4. **Regional Performance Tracking:** Identify top-performing cities (Islamabad, Karachi, Lahore, Rawalpindi, Peshawar, Quetta, Multan, Faisalabad).

---

## 📊 Dataset Overview

The underlying dataset tracks key operational performance metrics across hotels in Pakistan with the following main attributes:

* **Geographic & Location:** `Hotel_ID`, `Hotel_Name`, `City`, `Province`, `Latitude`, `Longitude`
* **Time Periods:** `Year` (2020–2025), `Month`, `Season` (Winter, Spring, Summer, Autumn)
* **Financial & Revenue:** `Room_Rate_PKR`, `Total_Revenue` (PKR)
* **Operational Metrics:** `Total_Rooms`, `Rooms_Booked`, `Avg_Occupancy_%`, `Overall_Occupancy_Ratio`, `Staff_Count`, `Amenities_Count`
* **Guest & Booking Insights:** `Customer_Type`, `Booking_Source` (Booking.com, Airbnb, Travel Agency, Walk-in, Website), `Foreign_Visitors`, `Local_Visitors`, `Total_Guests`, `Customer_Rating`, `Avg_Stay_Duration_Days`

---

## 🔍 Key Insights & Findings

* **Overall Revenue Benchmark:** Total generated revenue stands at **PKR 1,165,959,138** across all analyzed hotel properties.
* **Pricing & ADR:** The overall Average Daily Rate (ADR) across properties is **PKR 14,083**, maintaining a steady average length of stay of **~3 days**.
* **Primary Booking Channels:** Online platforms (**Booking.com** and **Airbnb**) drive the highest share of total bookings compared to direct walk-ins.
* **Customer Segment Highlights:** Family and Tour Group segments account for the largest proportion of total guest volume (**81,776 total guests**).

---

## 📈 KPIs & Analytical Approach

- **Total Revenue:** $1165959138\ \text{PKR}$

### 1. Key Metrics & Dynamic Formulas
* **Total Revenue:**

$$\text{Total Revenue} = \sum \text{Total\_Revenue} \quad (\text{PKR } 1,165,959,138)$$

* **Average Daily Rate (ADR):** 
  $$\text{ADR} = \text{AVERAGE}(\text{Room\_Rate\_PKR}) \quad (\text{PKR } 14,083)$$
* **Average Customer Rating:** 
  $$\text{Avg Rating} = \text{AVERAGE}(\text{Customer\_Rating}) \quad (3.72 / 5.0)$$
* **Total Guest Count:** 
  $$\text{Total Guests} = \sum \text{Foreign\_Visitors} + \sum \text{Local\_Visitors} \quad (81,776 \text{ Guests})$$

### 2. Analytical Workflow
1. **Data Cleaning & Standardization:** Resolved inconsistent data types, formatted currency representations (`PKR`), applied icons, and generated calculated columns (`Total_Guests`, `Overall_Occupancy_Ratio`).
2. **Pivot Aggregations:** Created structured summary tables for Revenue by Booking Source, Regional Visitor Share, and Seasonal Demand Distributions.
3. **UI/UX & Visual Palette:** Designed the dashboard with a **Navy Blue Executive Palette** (`#1B2A4A`) paired with dynamic interactive Slicers.

---

## 🚀 How to Use / Run the Project

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
