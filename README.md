# 🏨 Pakistan Tourism & Hotel Performance Analytics Dashboard

<!-- Animated Profile / Project Banner -->
<p align="center">
  <video
    src="./assets/pakistan-tourism-dashboard-preview.mp4"
    autoplay
    loop
    muted
    playsinline
    width="100%"
  >
    Your browser does not support the video tag.
  </video>
</p>

> **An end-to-end data analytics project featuring raw data processing, data cleaning & transformation, dynamic KPI Scorecard modeling, and an interactive executive dashboard.**

---

## 📸 Interactive Dashboard Preview

To highlight the full analytics lifecycle, this project showcases the progression from unformatted raw data to executive-ready business insights.

| 1. Messy / Raw Data | 2. Cleaned & Structured Dataset |
| :---: | :---: |
| ![Raw Data](https://github.com/mj-awad17/Pakistan-Tourism-Hotel-Performance-Analytics-Dashboard/blob/main/messy_data.png) | ![Cleaned Data](https://github.com/mj-awad17/Pakistan-Tourism-Hotel-Performance-Analytics-Dashboard/blob/main/clean_data.png) |
| *Raw records with unformatted metrics and missing structures* | *Cleaned sheet with proper data types, conditional formatting & formulas* |

| 3. Dynamic KPI Scorecards | 4. Executive Dashboard |
| :---: | :---: |
| ![KPI Scorecards](https://github.com/mj-awad17/Pakistan-Tourism-Hotel-Performance-Analytics-Dashboard/blob/main/KPIs_cards.png) | ![Executive Dashboard](https://github.com/mj-awad17/Pakistan-Tourism-Hotel-Performance-Analytics-Dashboard/blob/main/Executive_Dashboard.png) |
| *Calculated metrics including Total Revenue and ADR* | *Interactive view with dynamic slicers for City, Province & Season* |

---

## 💡 Business Problem & Objectives

The hospitality sector across Pakistan faces seasonal demand fluctuations and complex guest demographic variations. Hotel stakeholders needed a centralized business intelligence view to track revenue drivers, room occupancy rates, and customer demographics across major cities.

### **Key Objectives:**

1. **Revenue Management:** Analyze Total Revenue (**PKR 1.16 Billion+**) and Average Daily Rate (ADR) across different booking sources.
2. **Occupancy & Demand Modeling:** Evaluate monthly revenue trends and seasonal demand distributions across Winter, Spring, Summer, and Autumn.
3. **Guest Segmentation:** Understand customer booking behavior across Business, Family, Tour Group, and Individual segments, including Local vs. Foreign visitors.
4. **Regional Performance Tracking:** Identify top-performing cities including Islamabad, Karachi, Lahore, Rawalpindi, Peshawar, Quetta, Multan, and Faisalabad.

---

## 📊 Dataset Overview

The underlying dataset tracks key operational performance metrics across hotels in Pakistan with the following main attributes:

- **Geographic & Location:** `Hotel_ID`, `Hotel_Name`, `City`, `Province`, `Latitude`, `Longitude`
- **Time Periods:** `Year` (2020–2025), `Month`, `Season` (Winter, Spring, Summer, Autumn)
- **Financial & Revenue:** `Room_Rate_PKR`, `Total_Revenue` (PKR)
- **Operational Metrics:** `Total_Rooms`, `Rooms_Booked`, `Avg_Occupancy_%`, `Overall_Occupancy_Ratio`, `Staff_Count`, `Amenities_Count`
- **Guest & Booking Insights:** `Customer_Type`, `Booking_Source`, `Foreign_Visitors`, `Local_Visitors`, `Total_Guests`, `Customer_Rating`, `Avg_Stay_Duration_Days`

### **Booking Sources**

- Booking.com
- Airbnb
- Travel Agency
- Walk-in
- Website

---

## 🔍 Key Insights & Findings

- **Overall Revenue Benchmark:** Total generated revenue stands at **PKR 1,165,959,138** across all analyzed hotel properties.
- **Pricing & ADR:** The overall Average Daily Rate (ADR) across properties is **PKR 14,083**, maintaining an average stay duration of approximately **3 days**.
- **Primary Booking Channels:** Online platforms such as **Booking.com** and **Airbnb** drive a significant share of total bookings compared to direct walk-ins.
- **Customer Segment Highlights:** Family and Tour Group segments account for a major proportion of the total guest volume, with **81,776 total guests**.

---

## 📈 KPIs & Analytical Approach

### 1. Key Metrics & Dynamic Formulas

#### 💰 Total Revenue

$$
\text{Total Revenue} = \sum \text{Total Revenue}
\quad (\text{PKR } 1,165,959,138)
$$

#### 🏷️ Average Daily Rate (ADR)

$$
\text{ADR} = \text{AVERAGE}(\text{Room Rate PKR})
\quad (\text{PKR } 14,083)
$$

#### ⭐ Average Customer Rating

$$
\text{Average Rating} = \text{AVERAGE}(\text{Customer Rating})
\quad (3.72 / 5.0)
$$

#### 👥 Total Guest Count

$$
\text{Total Guests} =
\sum \text{Foreign Visitors}
+
\sum \text{Local Visitors}
\quad (81,776 \text{ Guests})
$$

---

### 2. Analytical Workflow

1. **Data Cleaning & Standardization:** Resolved inconsistent data types, standardized currency representations (`PKR`), and created calculated columns such as `Total_Guests` and `Overall_Occupancy_Ratio`.

2. **Data Transformation & Calculations:** Applied formulas and calculations to prepare the dataset for meaningful business analysis and KPI reporting.

3. **Pivot Aggregations:** Created structured summary tables for:
   - Revenue by Booking Source
   - Regional Visitor Share
   - Seasonal Demand Distribution
   - Customer Segment Analysis

4. **Dashboard Development:** Designed an interactive executive dashboard with dynamic KPIs, charts, and slicers.

5. **UI/UX & Visual Design:** Built the dashboard using a **Navy Blue Executive Palette** (`#1B2A4A`) paired with dynamic interactive slicers.

---

## 🛠️ Tools & Technologies Used

- Microsoft Excel
- Data Cleaning & Transformation
- Excel Formulas
- Pivot Tables
- Pivot Charts
- Conditional Formatting
- KPI Scorecards
- Interactive Slicers
- Business Intelligence
- Data Visualization

---

## 🚀 How to Use / Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
````

### 2. Navigate to the Project Folder

```bash
cd your-repo-name
```

### 3. Open the Dashboard File

Open the Excel workbook containing the cleaned dataset, analytical calculations, pivot tables, and interactive dashboard.

### 4. Explore the Dashboard

Use the available slicers and filters to analyze hotel performance by:

* 🏙️ City
* 🗺️ Province
* 🍂 Season
* 📅 Time Period
* 👥 Customer Type
* 🌐 Booking Source

---
<!--
## 📁 Project Structure

```text
Pakistan-Tourism-Hotel-Analytics/
│
├── assets/
│   ├── pakistan-tourism-dashboard-preview.mp4
│   ├── raw-data.png
│   ├── cleaned-data.png
│   ├── kpi-scorecards.png
│   └── executive-dashboard.png
│
├── data/
│   └── pakistan_tourism_hotel_dataset.xlsx
│
├── dashboard/
│   └── Pakistan_Tourism_Hotel_Dashboard.xlsx
│
└── README.md
```

> **Note:** Update the image and video file paths according to your actual repository folder structure.
-->

## 🎯 Project Highlights

- ✨ End-to-end data analytics workflow
- 🧹 Raw data cleaning and transformation
- 📊 Dynamic KPI scorecards
- 💰 Revenue and ADR analysis
- 👥 Customer segmentation
- 🌍 Regional hotel performance analysis
- 🍂 Seasonal demand analysis
- 📈 Interactive executive dashboard
- 🎛️ Dynamic slicers and filters

---

# 🙌 Thank You for Visiting!

Thank you for taking the time to explore this project! ❤️
<!--
I hope this project helped you understand how **raw hospitality and tourism data can be transformed into meaningful business insights** through:
* 🧹 Data Cleaning
* 🔄 Data Transformation
* 📊 Data Analysis
* 📈 KPI Development
* 📉 Data Visualization
* 🎯 Interactive Dashboarding
If you found this project **helpful, interesting, or valuable**, please consider supporting it:
### ⭐ Star This Repository
If this project helped you, don't forget to give the repository a **Star ⭐**. Your support helps the project reach more people and motivates me to continue building and sharing useful projects.
-->
### 👤 Follow for More Projects

Follow my profile to stay updated with more projects and content related to:

* 📊 Data Analytics
* 🤖 Machine Learning
* 🧠 Artificial Intelligence
* 📈 Data Visualization
* 💻 Python
* 🚀 Real-World Data Projects

### 💬 Feedback Is Always Welcome

Feel free to share your feedback, suggestions, or ideas. Every contribution and suggestion is highly appreciated! 🙌

---

<p align="center">
### 🌟 If you found this project helpful, please ⭐ Star the repository and 👤 Follow for more amazing projects!
**Your support motivates me to keep learning, building, and sharing. ❤️**
</p>
<p align="center">Made with ❤️ for Data Analytics & Business Intelligence</p>
