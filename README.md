# 🚚 India Delivery Logistics Multipartner Performnace Dashboard

![Dashboard Preview](dashboard_screenshot.png)

## 📌 Project Overview
An interactive Excel dashboard analyzing **25,000 delivery records** 
across **9 Indian logistics partners** to track delivery performance, 
cost efficiency, and customer satisfaction.

---

## 📊 Dataset Details
| Field | Value |
|-------|-------|
| Source | Kaggle — Indian Delivery Logistics Dataset |
| Total Records | 25,000 |
| Delivery Partners | 9 |
| Regions | 5 |
| Vehicle Types | 6 |
| Time Period | Multi-month |

---

## 🎯 Key Insights Found
- **78.1%** of deliveries completed on time
- **FedEx** has highest on-time rate among all partners
- **West region** has highest total logistics cost
- **EV Van** is most expensive vehicle per KM
- **Scooter** is most cost-efficient vehicle type
- Only **5.3%** deliveries failed across all partners

---

## 📈 Dashboard Features
- ✅ 5 KPI Cards — Total, On-Time %, Rating, Cost, Failed
- ✅ 6 Interactive Charts
- ✅ 5 Slicers — Region, Partner, Weather, Vehicle, Mode
- ✅ Connected Pivot Tables
- ✅ Professional header banner


---

## 📉 Charts Included
| Chart | Type | Insight |
|-------|------|---------|
| Delivery Status Breakdown | Doughnut | 73% delivered, 22% delayed, 5% failed |
| On-Time Deliveries by Partner | Bar | FedEx leads, Amazon lowest |
| Total Logistics Cost by Region | Column | West highest cost |
| Orders by Delay Category | Bar | 19,534 on time |
| Average Rating by Partner | Bar | All between 3.6–3.7 |
| Cost per KM by Vehicle | Column | EV Van most expensive |

---

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| Power Query  | Data cleaning, column creation |
| Microsoft Excel | Dashboard, Pivot Tables, Slicers |

---

## 📁 Files in This Repository
| File | Description |
|------|-------------|
| `Delivery_Dashboard.xlsx` | Main Excel Dashboard |
| `Delivery_Logistics_Clean.csv` | Cleaned Dataset |
| `dashboard_screenshot.png` | Dashboard Preview Image |

---

## 🔍 Data Cleaning Done
- Fixed corrupted Delivery ID (250.99 → 250)
- Extracted hours from nanosecond timestamp format
- Added 4 derived columns: delay_hours, time_status, Cost_per_km, delay_category
- Removed PII columns (SSN, Name)
- Flagged 1,218 suspect delivery time records

---

## 👤 Connect
Made by: Kabeer Khan
LinkedIn: www.linkedin.com/in/kabeer-khan-analyst
