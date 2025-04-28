# 📊 Production Monitoring Dashboard

A data-driven Power BI dashboard that enables **real-time monitoring of key production metrics**, helping factories optimize performance and drive operational efficiency.

---

### 🔧 Features
- Live visualization of **OEE (Overall Equipment Effectiveness)**
- Shift-wise analysis of **downtime**, **availability**, **performance**, and **quality**
- Integration with **SQL backend** for automated data feeds
- Simulation of factory sensor data using **Python**
- Clear, interactive dashboards for operators and managers

---

### 🛠 Tech Stack
- **Power BI** – Dashboard and data modeling  
- **SQL** – Backend data storage and queries  
- **Python** – Data simulation and pre-processing  
- **Excel** – Template for importing test data  
- **Lean Manufacturing** – Principles guiding KPI structure

---

### 📸 Screenshots

| Dashboard Overview | Shift Breakdown |
|--------------------|-----------------|
| ![overview](../screenshots/powerbi-dashboard.png) | ![shifts](../screenshots/powerbi-shift.png) |

---

### 📈 Use Case
This project is ideal for:
- **Production engineers** looking to digitize KPI tracking  
- **Operations teams** needing shift performance breakdowns  
- **Continuous improvement teams** identifying bottlenecks

---

### 🚀 How It Works
1. Simulated sensor data is generated using Python
2. Data is stored in a structured SQL database
3. Power BI connects to the database for dynamic visualization
4. KPIs are calculated in real-time and displayed with filters for shift, line, and date

---

### ✅ Outcomes
- Reduced reporting overhead by automating manual data collection
- Enabled faster decision-making with visual analytics
- Provided a scalable framework for integration with real-world PLC and IoT devices

---

### 📂 Folder Structure
```
01_production_dashboard_powerbi/
├── README.md
├── powerbi_dashboard.pbix
├── sql_database_setup.sql
├── data_simulation.py
└── sample_data.xlsx
```
