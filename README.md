# 📊 Blinkit Sales Dashboard (Power BI)

### 🚀 Project Overview
This project is an interactive **Power BI Dashboard** created to analyze and visualize sales performance data for **Blinkit**, India’s last-minute delivery app.  
The dashboard provides insights into **total sales, average sales, item performance, outlet types, and customer ratings** — enabling data-driven decision-making for business optimization.

---

## 🧩 Key Features
- **💰 Total Sales Analysis:** Displays total revenue ($1.20M) and highlights top-performing categories.
- **📦 Item Insights:** Visualizes the number of items sold and average ratings.
- **🏪 Outlet Performance:** Compares sales across outlet sizes, types, and locations.
- **📈 Trend Analysis:** Tracks total sales growth over the years.
- **🥛 Fat Content Segmentation:** Breaks down sales by low-fat vs. regular products.
- **⚙️ Interactive Filters:** Allows users to slice data by:
  - Outlet Location Type
  - Outlet Size
  - Item Type

---

## 📁 Data Model
The dataset includes the following key fields:
- **Outlet Type**
- **Outlet Size**
- **Outlet Location Type**
- **Item Type**
- **Fat Content**
- **Total Sales**
- **Number of Items**
- **Average Sales**
- **Average Ratings**

Data is cleaned, transformed, and modeled within Power BI using DAX measures and relationships.

---

## 🧮 DAX Measures Used
Some custom DAX measures used in this dashboard include:
```DAX
Total Sales = SUM(Sales[Total])
Avg Sales = AVERAGE(Sales[Total])
No of Items = COUNT(Sales[Item])
Avg Ratings = AVERAGE(Sales[Rating])
