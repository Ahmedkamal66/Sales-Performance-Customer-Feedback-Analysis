# 📊 Sales Performance & Customer Feedback Analysis

## 📝 Project Overview
This project is an end-to-end data analytics solution designed to evaluate sales performance, track product return rates, and analyze customer satisfaction. By integrating transaction data with customer reviews and return logs, this project provides a holistic view of business health.

The workflow leverages **Python** for initial data handling/analysis and **Power BI** for building an interactive, business-ready dashboard.

---

## 🛠️ Tools & Technologies
* **Data Processing & Analysis:** Python (`Analysis.py`) - *Likely utilizing libraries such as Pandas and NumPy for data manipulation.*
* **Data Visualization & BI:** Microsoft Power BI (`Analysis-Power Bi.pbix`) - *Used for data modeling, DAX calculations, and interactive dashboard creation.*
* **Data Storage:** Excel / CSV files.

---

## 📂 Dataset Structure
The raw data (`sales_project_data.xlsx`) was separated into the following key components for relational modeling:
1. **`Sales.csv`**: Contains transactional data, including revenue, order dates, quantities, and product IDs.
2. **`Returns.csv`**: Logs of returned orders, crucial for calculating return rates and identifying problematic products.
3. **`Reviews.csv`**: Customer feedback and ratings, used to gauge customer satisfaction and product quality.
4. **`Sheet2.csv`**: Supplemental data (e.g., categorical mappings, regional data, or dimensional attributes).

---

## 🔍 Project Workflow

### 1. Data Preparation & Cleaning (Python)
* Imported raw CSV/Excel files.
* Handled missing values, standardized formats (especially dates and currencies), and cleaned textual data in customer reviews.
* Exported the cleaned datasets for visualization.

### 2. Data Modeling (Power BI)
* Imported the cleaned datasets into Power BI.
* Established relationships between the `Sales`, `Returns`, and `Reviews` tables using common keys (like Order ID or Product ID) to create a robust Star Schema.

### 3. Dashboarding & Visualization (Power BI)
* Developed interactive dashboards to visualize key metrics.
* Implemented DAX measures for advanced calculations (e.g., YTD Sales, Return Rate %, Average Rating).

---

## 💡 Key Performance Indicators (KPIs) & Insights
While the specific dashboard visuals depend on the `.pbix` file, the analysis is designed to track:
* **Revenue Trends:** Identifying peak sales periods and best-selling products.
* **Return Rate Analysis:** Pinpointing products with high return rates to investigate potential quality issues.
* **Customer Sentiment:** Correlating customer ratings from the `Reviews` dataset with sales volume.

---

## 🚀 How to Run the Project
1. **Python Script:** Ensure you have Python installed. Install necessary dependencies (like `pandas`) and run `Analysis.py` to view the data preprocessing steps.
2. **Power BI Dashboard:** Open the `Analysis-Power Bi.pbix` file using Power BI Desktop. If prompted, refresh the data sources to point to the local CSV files in your repository.

## power BI Dashboard
1- ## Home

https://github.com/Ahmedkamal66/Sales-Performance-Customer-Feedback-Analysis/blob/main/Home.png?raw=true
