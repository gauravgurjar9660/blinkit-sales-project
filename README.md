# 🛒 Blinkit Sales & Grocery Data Analysis Dashboard (Power BI)

A comprehensive, end-to-end business intelligence project that transforms raw retail data into actionable insights using **Python** (for data cleaning & preprocessing) and **Power BI** (for interactive dashboards, custom DAX measures, and dynamic slicers).

---

## 📊 Project Overview

This project simulates a real-world retail analytics pipeline for **Blinkit**. The goal is to analyze grocery sales performance, customer preferences, and item attributes to track key performance indicators (KPIs) like total revenue, average sales, item ratings, and outlet efficiencies. 

---

## 🛠️ Tech Stack & Tools Used

* **Data Preprocessing:** Python (Pandas, NumPy)
* **Business Intelligence & Visualization:** Power BI Desktop (`.pbix`)
* **Data Modeling & Calculations:** DAX (Data Analysis Expressions)
* **Version Control:** Git & GitHub

---

## 🧹 Data Cleaning & Preprocessing (Python)

Before visualization, the raw dataset underwent rigorous cleaning and transformation using Python:
* **Missing Value Imputation:** Handled null or missing entries in critical columns (such as item weights and outlet sizes) using statistical imputation.
* **Data Type Correction:** Standardized numeric fields (sales, ratings) and categorical text attributes.
* **Text Standardization:** Cleaned categorical inconsistencies (e.g., standardizing item fat content labels like `"Low Fat"` vs `"LF"`).
* **Duplicate & Outlier Handling:** Removed duplicate records to ensure accurate aggregations in Power BI.

---

## 📈 Power BI Dashboard Features & Highlights

The interactive Power BI dashboard is built with modern design principles and advanced analytical features:

* **Key Performance Indicators (KPI Cards):** Dynamic tracking of *Total Sales*, *Average Sales*, *Total Items Sold*, and *Average Rating*.
* **Advanced DAX Measures:** Extensive use of custom DAX measures for complex metric calculations, dynamic titles, and conditional formatting.
* **Interactive Slicers:** Multi-level slicers allowing users to filter data dynamically by *Outlet Location Type*, *Outlet Tier*, *Item Fat Content*, and *Grocery Category*.
* **Visual Breakdown:**
  * Sales distribution across different product categories and fat types.
  * Tier-wise and establishment-wise outlet performance comparison.

---

## 📥 Installation & Running Instructions

To view, test, and interact with the Power BI dashboard locally on your system, please follow these steps sequentially:

### Step 1: Download the Project
1. Go to the top of this repository main page.
2. Click on the green **`<> Code`** button.
3. Select **`Download ZIP`** (or clone the repo using Git in your terminal: `git clone https://github.com/gauravgurjar9660/blinkit-sales-project.git`).
4. Extract the downloaded ZIP folder to your local machine.

### Step 2: Open and Run the Dashboard
1. Ensure you have **Microsoft Power BI Desktop** installed on your computer (available for free via the Microsoft Store).
2. Inside the extracted folder, locate the Power BI file:
   * **`BLINKIT PROJECT.pbix`**
3. Double-click the `.pbix` file to open it directly in Power BI Desktop.
4. If prompted to load or refresh data connections, click **Refresh/Enable** so that the model connects smoothly with the underlying dataset (`BlinkIT Grocery Data.xlsx`).

---

## 📁 Repository Structure

```text
├── BLINKIT PROJECT.pbix       # The interactive Power BI dashboard file
├── BlinkIT Grocery Data.xlsx  # Cleaned dataset used for analysis
└── README.md                  # Project documentation
