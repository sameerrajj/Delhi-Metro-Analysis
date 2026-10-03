# Delhi Metro Analysis

## 📊 Project Overview

**Delhi Metro Analysis** is an end-to-end data analytics project focused on analyzing metro passenger activity, routes, ticket types, revenue, profitability, fares, and travel distance.

The project uses **Excel, Python, and Power BI** to demonstrate the complete analytics workflow — from data preparation and cleaning to exploratory analysis and interactive dashboard development.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel** – Data preparation, basic analysis and validation
- **Python** – Data cleaning, exploratory data analysis and statistical analysis
  - Pandas
  - NumPy
  - Matplotlib
- **Power BI** – Interactive dashboard, KPIs, filters and data visualization

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Excel
Data Preparation & Initial Analysis
     ↓
Python
Data Cleaning & Exploratory Data Analysis
     ↓
Power BI
Interactive Dashboard & Business Insights
```

---

## 📁 Project Structure

```text
Delhi-Metro-Analysis/
│
├── Data/
│   └── delhi_metro_updated.csv
│
├── Python/
│   └── Delhi_Metro_Analysis.ipynb
│
├── Excel/
│   └── Delhi_Metro_Analysis.xlsx
│
├── PowerBI/
│   └── Delhi_Metro_Analysis.pbix
│
├── Dashboard/
│   └── Delhi_Metro_Dashboard.png
│
├── Presentation/
│   └── Delhi_Metro_Analysis_Project_Presentation_Sameer_Raj.pptx
│
└── README.md
```

---

## 🧹 Data Cleaning

The dataset contains approximately **1,50,000 records**.

The following cleaning steps were performed using Python:

- Removed unnecessary columns
- Identified missing values
- Filled missing passenger values using the mean
- Filled missing ticket types using the mode
- Filled missing remarks using the mode
- Checked data types
- Verified that no missing values remained after cleaning
- Exported the cleaned dataset for further analysis

---

## 🔎 Exploratory Data Analysis

The Python analysis focused on:

### Passenger Analysis
- Passenger trends by year
- Passenger trends by month
- Passenger trends by day
- Passenger distribution by ticket type

### Station Analysis
- Top starting stations
- Top ending stations
- Route-level passenger analysis

### Revenue & Profitability
- Fare analysis
- Cost per passenger analysis
- Revenue calculation
- Profit calculation

### Operational Analysis
- Analysis of peak, off-peak, weekend, festival and maintenance periods

---

## 📈 Power BI Dashboard

The final Power BI dashboard provides an interactive view of the Delhi Metro dataset.

### Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Passengers | 40,00,000+ |
| Total Revenue | ₹43,51,60,000+ |
| Total Profit | ₹19,04,60,000+ |
| Total Trips | 1,50,000 |
| Average Fare | ₹105.12 |
| Average Distance | 5.49 km |

### Dashboard Visualizations

- Passenger Trend by Year
- Passengers by Month
- Passenger Trend by Day
- Total Passengers by Route
- Passenger Distribution by Ticket Type
- Total Revenue by Route

### Interactive Filters

The dashboard includes filters for:

- Year
- Month
- Day
- Ticket Type
- From Station
- To Station

---

## 💰 Revenue & Profit Calculation

Since the **Fare** and **Cost_per_passenger** values are on a per-passenger basis, total revenue and profit were calculated at the trip/passenger level.

### Total Revenue

```text
Total Revenue = Fare × Passengers
```

### Total Profit

```text
Total Profit = (Fare − Cost per Passenger) × Passengers
```

In Power BI, `SUMX` was used to calculate these row-level values before aggregating them.

---

## 📌 Key Findings

- The dataset contains approximately **1.5 lakh trips**.
- Total passenger volume is approximately **40 lakh**.
- Total revenue is approximately **₹43.52 crore**.
- Total profit is approximately **₹19.05 crore**.
- Average fare is approximately **₹105** per passenger.
- Average travel distance is approximately **5.49 km**.
- Tourist Card represents the largest passenger share among the ticket types in the dashboard.
- Route-level analysis identifies high-volume routes and high-revenue routes.
- Passenger activity was compared across different months, weekdays and operational conditions.

---

## 🎯 Business Questions Answered

This project helps answer questions such as:

1. Which year had the highest passenger volume?
2. Which month generated the highest passenger activity?
3. Which day of the week had the highest passenger volume?
4. Which routes carried the most passengers?
5. Which routes generated the highest revenue?
6. Which ticket type contributed the largest passenger share?
7. What is the average fare paid per passenger?
8. What is the average distance travelled?
9. How do operational conditions such as peak, weekend, festival and maintenance periods affect passenger activity?
10. What is the overall revenue and profitability of the metro trips?

---

## 📷 Dashboard Preview

Add the Power BI dashboard screenshot to the `Dashboard` folder and name it:

```text
Delhi_Metro_Dashboard.png
```

Then use:

```markdown
![Delhi Metro Power BI Dashboard](Dashboard/Delhi_Metro_Dashboard.png)
```

---

## 📚 Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Excel
- Python
- Pandas
- NumPy
- Data Visualization
- Power BI
- DAX
- KPI Development
- Interactive Dashboard Design
- Business Analysis
- Data Storytelling

---

## 👤 Author

**Sameer Raj**

**Project:** Delhi Metro Analysis

**Tools:** Excel | Python | Power BI
