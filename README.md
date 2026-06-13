# 🚖 Ride Booking Analytics Dashboard

> An end-to-end data analysis project on 1,50,000 ride booking records — from raw data exploration to an interactive Power BI dashboard.

<img width="1150" height="648" alt="Dashboard image" src="https://github.com/user-attachments/assets/de99e0ab-dbfb-4612-b19d-c0d1e07ca292" />



---

## 📌 Project Overview

This project analyzes a ride-hailing dataset of **1,50,000 bookings** across **21 variables** to surface insights in customer behavior, vehicle demand, revenue patterns, cancellation trends, and peak-hour activity.

The final output is an interactive **Power BI dashboard** with dynamic slicers for Date Range, Vehicle Type, Booking Status, and more.

---

## 📊 Dashboard Highlights

| KPI | Value |
|---|---|
| Total Bookings | 1,50,000 |
| Completed Rides | 93,000 (62%) |
| Total Revenue | ₹51.85M |
| Avg Booking Value | ₹508 |
| Avg Ride Distance | 24.64 KM |
| Avg Driver Rating | 4.23 / 5 |

---

## 🔍 Analysis Sections

- **Booking Status Distribution** — Donut chart showing Completed, Cancelled by Driver/Customer, No Driver Found, Incomplete
- **Vehicle Type Distribution** — Auto leads demand; Go Sedan, Bike, Premier Sedan follow
- **Revenue by Vehicle** — Auto generates ₹1.28Cr, highest among all types
- **Payment Method Analysis** — UPI at 44.5%, Cash at 32.1%, Uber Wallet 12.4%
- **Customer Cancellation Reasons** — Wrong address, change of plans, driver not moving
- **Driver Cancellation Reasons** — Customer-related, passenger count, personal issues
- **Peak Booking Hours** — Demand spikes between Hour 14–18
- **Top Pickup Locations** — Anand Vihar (859), Preet Vihar (832), Saket A Block (823)
- **Top Drop Locations** — Uttam Nagar (883), Panchsheel Park (851), Mansarovar Park (844)
- **Rating Analysis** — Grouped column chart comparing Driver vs Customer ratings (1–5 scale)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python (Pandas, Seaborn) | EDA & Data Cleaning |
| Power BI | Dashboard & Visualizations |
| DAX | Measures, KPIs, Calculated Columns |
| Matplotlib | Exploratory charts |

---

## 💡 Key Insight

> **Driver cancellations (18%) are the platform's biggest operational problem** — more than double the customer cancellation rate. Implementing driver monitoring systems and peak-hour incentives could push completion rates above 75%.

---

## 📁 Project Structure

```
ride-booking-analytics/
├── data/
│   └── ride_bookings.csv
├── notebooks/
│   └── EDA_Ride_Booking.ipynb
├── dashboard/
│   └── Ride_Booking_Dashboard.pbix
├── assets/
│   └── dashboard.png
└── README.md
```

---

## 🚀 How to Use

1. Clone this repo
2. Open `EDA_Ride_Booking.ipynb` in Jupyter for Python analysis
3. Open `Ride_Booking_Dashboard.pbix` in Power BI Desktop
4. Use slicers (Date Range, Vehicle Type, Booking Status) to explore the data interactively

---

## 👤 Author

**Nadir Khan** — Data Analyst  
🔗 [LinkedIn](https://linkedin.com/in/nadirkhan-dataanalyst) | 💻 [GitHub](https://github.com/NADIR789259)
