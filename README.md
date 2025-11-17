# 💼 Unified-Mentor-Sales-Performance-Business-Analyst

📊 Global Revenue, Profit & Segment Analysis | Business Intelligence Dashboard

This project was developed as part of my Business Analyst Internship at **Unified Mentor Pvt. Ltd.**  
The objective was to analyze global financial performance across 6 countries, identify revenue & profit trends, track product/segment contribution, and generate actionable insights using **Power BI**, **DAX**, and **Deneb (Vega-Lite JSON)** for advanced visualizations.

---

## 🧠 Project Objective

The goal of the dashboard is to:

- Analyze revenue, profit, expense (COGS), and growth trends across Brazil, Canada, Germany, Mexico, USA, and France.
- Track MoM & YoY performance using custom DAX measures.
- Identify best-performing **products** and **segments**.
- Forecast revenue & profit using Power BI’s analytics model.
- Generate dynamic **business solutions** using KPI logic.
- Provide a clean, interactive, story-driven BI experience.

---

## ⚙️ Tech Stack

**Power BI** → Dashboard development  
**DAX** → KPIs, growth logic, ranking measures, forecast logic  
**Deneb (Vega-Lite JSON)** → Custom visuals: Bubble Matrix, Donut Gauge, KPI rings  
**Python/Excel / CSV** → Base financial dataset  
**GitHub** → Documentation and version control  

---

## 🧾 Data Sources

| Source | Description |
|--------|-------------|
| `Financial_performance.csv` | Revenue, Profit, COGS, Product sales by month |
| `DateTable` | Calendar table used for time intelligence |
| Power BI Analytics | Built-in forecasting model for prediction page |

---

## 🧩 Dashboard Pages

---

### ➡️ **Page 1 – Financial Performance Overview**

**Focus:** Complete financial summary for the selected country  
**Includes:**

- 📊 Country-wise Revenue & Profit Overview  
- 🗺️ Custom Map & Flag Indicator  
- 🎯 KPI Cards – Revenue Rank, Profit Rank  
- 💠 Deneb Bubble Matrix – Product × Month performance  
- 📈 MoM Growth Donut (Deneb Gauge)  
- 🏆 Best Segment & Best Product Indicators  
- 🧮 KPI Ribbon (Revenue, Profit, YoY, MoM, Expenses)

📸 **Preview:**  
 
<img width="900" height="457" alt="Screenshot 2025-11-17 200206" src="https://github.com/user-attachments/assets/02a54565-375b-4c06-874a-a59c66fffcf6" />


---

### ➡️ **Page 2 – Prediction & Solutions**

**Focus:** Future direction + business actions  
**Includes:**

- 🔮 Revenue Forecast (Power BI Analytics)
- 🔮 Profit Forecast (Power BI Analytics)
- 🥇 Segment Contribution Donut  
- 🥈 Product Profit Contribution Bars  
- 💡 Dynamic “Solution Box” with data-driven recommendations  
  - Revenue/Profit Condition Logic  
  - Segment health  
  - Product improvement suggestions  

📸 **Preview:**  
<img width="895" height="453" alt="Screenshot 2025-11-17 200258" src="https://github.com/user-attachments/assets/165004a8-6283-4dd3-95ce-73682913fb33" />


---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard design, forecasting |
| DAX | Measures for Revenue, COGS, Growth %, Rankings, KPIs |
| Deneb | Custom visuals using Vega-Lite |
| Excel | Data cleaning and structure |
| GitHub | Project documentation |




## 🌐 Project Structure

📂 Unified-Mentor-Financial-Performance
│
├── 📁 data/
│ ├── Financial_performance.csv
│ ├── DateTable.csv
│
├── 📁 powerbi/
│ └── Financial_Performance.pbix
│
└── 📄 README.md


---

## 🧩 Internship Details

**Organization:** Unified Mentor Pvt. Ltd.  
**Domain:** Business Analytics  
**Duration:** Jan 2026 – May 2026  
**Project:** Financial Performance Dashboard  
**Role:** Business Analyst Intern  

---

## 🚀 How to Use

1. Import the `.pbix` file into Power BI  
2. Load dataset from `/data` folder  
3. Refresh Date Table & relationships  
4. Choose any country (Brazil, Canada, Germany, Mexico, USA, France)  
5. Navigate between:
   - **Performance Overview**
   - **Prediction & Solution**

---

## 🧩 Acknowledgement

Special thanks to **Unified Mentor Pvt. Ltd.** for guiding me through real business analytics and dashboard storytelling.

💬 *“Data becomes powerful when it turns into insight — visualization turns insight into action.”*


