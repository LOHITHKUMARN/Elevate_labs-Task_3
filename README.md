# 🚗 Interactive Sales Dashboard (Tableau)

### 📊 Overview
This project showcases an **interactive car sales dashboard** built in **Tableau**, using a cleaned dataset from Kaggle.  
The dashboard visualizes profitability, sales trends, and performance KPIs to help business stakeholders make data-driven decisions.

---

### 🧠 Objective
To design an **interactive, visually appealing dashboard** that highlights:
- Sales performance over time  
- Profitability (Above / Below Market)  
- Key business KPIs  
- Interactive filtering by car make, year, and state  

---

### 🧰 Tools & Technologies
- **Tool:** Tableau Desktop / Tableau Public  
- **Dataset:** `car_prices_cleaned.csv`  
- **Language:** No coding required (Drag-and-drop visual design)

---

### 🪜 Steps Followed

#### Step 1: Connect and Prepare Data
Imported `car_prices_cleaned.csv` into Tableau.  
Ensured correct data types for fields like `saledate`, `sellingprice`, and `mmr`.

#### Step 2: Create Calculated Fields
Created key calculated metrics:
- **Profit:** `[sellingprice] - [mmr]`  
- **% Above Market:** `([sellingprice] - [mmr]) / [mmr] * 100`  
- **Profit Category:** Categorized cars as “Above Market” / “Below Market”.  
- **Sale Month:** Extracted month name from the sale date.

#### Step 3: Build Visual Sheets
Developed multiple visuals:
- **Sales Trend** – Line chart showing total sales over time.  
- **Profitability Distribution** – Bar chart comparing profit categories.  
- **Top Car Makes** – Sorted bar chart of highest selling brands.  

#### Step 4: KPI Summary Cards
Created 3 KPI sheets showing:
- Total Cars Sold  
- Average Selling Price  
- Average % Above Market  

#### Step 5: Add Filters / Slicers
Added interactive drop-down filters for:
- `make`  
- `year`  
- `state`  
- `Profit Category`

#### Step 6: Dashboard Design
Combined all sheets and filters into a single dashboard layout.  
Arranged KPIs on top, visuals in the middle, and filters on the right.

#### Step 7: Formatting & Publishing
Applied a consistent color theme, renamed titles, and published the dashboard to Tableau Public.

---

### 📈 Insights
- Cars with strong resale value appear “Above Market”.  
- Seasonal trends visible across months and years.  
- KPIs allow for quick performance comparison across brands and regions.

---

### 📁 Files Included
- `car_prices_cleaned.csv` — Cleaned dataset used in Tableau.  
- `README.md` — Project documentation (this file).  
- `Tableau Dashboard` — Packaged Tableau workbook (`.twbx`) *(optional upload)*  

---

### 🚀 Outcome
This dashboard demonstrates how to transform raw sales data into **actionable business insights** using Tableau’s interactive visualization tools.
