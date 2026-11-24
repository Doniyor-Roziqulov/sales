# 📊 Sales Performance Dashboard - Power BI Analytics

## 📌 Project Overview

This project presents an interactive **Sales Performance Dashboard**
developed in Power BI. It is designed to provide a comprehensive
overview of sales performance, customer activity, product categories,
branch performance, sales channels, and payment methods.

The dashboard helps businesses monitor key performance indicators,
identify sales trends, and make data-driven decisions.

### 📈 Key Performance Indicators (KPIs)

* **Total Sales:** 278.46 billion UZS
* **Total Customers:** 4,494
* **Total Products:** 150
* **Total Orders:** 38,161
* **Prior-Year Comparison:** KPI comparison labels for annual performance.

**Reporting Period:** January 2025 – October 2026.

---

## 🛠️ Technical Stack & Tools

* **Tool:** Microsoft Power BI Desktop
* **Modeling:** Star Schema Architecture
* **DAX:** Business KPI calculations and dynamic measures
* **Data Source:** CSV files
* **ETL:** Power Query
* **Version Control:** Git & GitHub

---

## 📐 Data Engineering & Modeling

The project is based on a fact-and-dimension data structure,
with a central sales fact table and five dimension tables.

| Table | Description |
|-------|-------------|
| Fact_Sales | Sales transactions |
| Dim_Customer | Customer information |
| Dim_Product | Products and categories |
| Dim_Branch | Branch and city information |
| Dim_Channel | Sales channels |
| Dim_Payment | Payment methods |

This architecture supports multidimensional analysis,
interactive filtering, and business performance reporting.

---

## 📊 Dashboard Features

* **Sales Trend:** Monthly sales performance analysis.
* **Product Category Analysis:** Sales distribution across
  electronics and household appliances.
* **Branch Performance:** Comparison of sales across cities.
* **Sales Channel Analysis:** Performance of offline stores,
  online websites, and marketplaces.
* **Payment Method Share:** Analysis of customer payment preferences.
* **Interactive Slicers:** Year, month, date range, branch,
  channel, product category, and payment method.
* **Dynamic KPIs:** Sales, customers, products, and orders.

---

## 💡 Key Business Insights

* Electronics accounts for **79.34%** of total sales.
* Household appliances contribute **20.66%** of total sales.
* Tashkent leads the displayed cities with **96.8 billion UZS**
  in sales.
* Offline stores represent the largest sales channel
  with **54.7%**.
* Online websites account for **30.5%** of the sales channel share.
* Marketplaces account for **14.8%**.
* Bank cards are the most popular payment method,
  representing **62.11%**.
* December 2025 recorded the highest monthly sales
  in the displayed period.

---

## 📸 Dashboard Preview

![Sales Performance Dashboard](assets/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-11-24%20201230.png)

---

## 📁 Repository Structure

```text
sales/
├── assets/
│   └── Dashboard screenshot
├── data/
│   ├── Dim_Branch.csv
│   ├── Dim_Channel.csv
│   ├── Dim_Customer.csv
│   ├── Dim_Payment.csv
│   ├── Dim_Product.csv
│   └── Fact_Sales.csv
├── src/
│   └── Sales Performance Dashboard.pbix
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/Doniyor-Roziqulov/sales.git
   ```

2. Open the `src` folder.

3. Open `Sales Performance Dashboard.pbix` using Power BI Desktop.

4. If necessary, update the CSV file paths in Power Query.

5. Refresh the data and explore the interactive dashboard.

---

## 🎯 Project Objectives

* Transform raw sales data into meaningful business insights.
* Analyze sales performance across multiple dimensions.
* Identify top-performing products, branches, and sales channels.
* Develop an interactive and user-friendly business dashboard.
* Demonstrate data analysis, data modeling, and visualization skills.

---

## 👨‍💻 Author

**Doniyor Roziqulov**

* GitHub: [Doniyor-Roziqulov](https://github.com/Doniyor-Roziqulov)

---

⭐ If you find this project useful, feel free to star the repository!
