# 💳 Credit Card Financial Dashboard | Power BI + PostgreSQL

## 📌 Project Overview

This project presents a **Credit Card Financial Analysis Dashboard** built using **Power BI** with data sourced from a **PostgreSQL database**.  
The objective is to analyze credit card transactions and customer demographics to provide **real-time financial insights**, monitor key performance metrics, and support data-driven decision-making.

The dashboard enables stakeholders to track revenue, transaction behavior, interest earnings, and customer segmentation across multiple dimensions.

---

## 🗄️ Data Source & Architecture

- **Database:** PostgreSQL  
- **Data Ingestion:** SQL queries executed on PostgreSQL and loaded into Power BI  
- **Data Update:** Additional transaction data inserted into the database and reflected in Power BI

### Tables Used
- `credit_card` – Card-level and financial attributes  
- `customer` – Customer demographics and income details  
- `credit_card_transactions` – Transaction-level data  

SQL was used to:
- Join customer and transaction data
- Aggregate financial metrics
- Prepare structured datasets for Power BI reporting

---

## 🧹 Data Processing & Modeling

- Data extracted using **custom SQL queries**
- Cleaned and transformed inside **Power BI Power Query**
- Relationships defined between customer, card, and transaction tables
- Optimized model for performance and scalability

### Key Metrics Created
- Total Revenue  
- Total Transaction Amount  
- Total Interest Earned  
- Total Transaction Count  
- Customer Spend Score (CSS)

---

## 📊 Dashboard 1: Credit Card Transaction Analysis

**Objective:** Analyze transaction trends and financial performance.

### Key Insights
- Quarterly revenue and transaction trends
- Revenue distribution by:
  - Expenditure type (Bills, Fuel, Grocery, Travel, etc.)
  - Card category (Blue, Silver, Gold, Platinum)
  - Transaction mode (Swipe, Chip, Online)
- Interest earned by card category
- Transaction volume vs revenue comparison

### Business Value
- Identifies high-revenue spending categories
- Highlights top-performing card types
- Helps monitor transaction behavior and payment modes

---

## 👥 Dashboard 2: Credit Card Customer Analysis

**Objective:** Understand customer demographics and revenue contribution.

### Key Insights
- Revenue by income group (Low, Mid, High)
- Revenue by age group and gender
- Revenue by education level and occupation
- Revenue by marital status and dependent count
- Top 5 revenue-generating states
- Customer income vs revenue contribution

### Business Value
- Identifies profitable customer segments
- Supports targeted marketing and card upgrade strategies
- Helps align credit offerings with customer profiles

---

## 🧠 Key Findings

- Blue card category generates the highest overall revenue
- Swipe transactions dominate revenue contribution
- High-income customers contribute a disproportionate share of revenue
- Certain professions (businessman, white-collar) show higher interest earnings
- Revenue patterns vary significantly by age group and state

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **PostgreSQL**
- **SQL**
- **Power Query**
- **DAX**
- **Data Modeling & Visualization**

---

## 📈 Skills Demonstrated

- SQL-based data extraction and transformation
- Relational data modeling
- Financial and transaction analytics
- Customer segmentation analysis
- Interactive dashboard design
- Translating raw data into business insights

---

## 📌 Conclusion

This project demonstrates an end-to-end **business intelligence workflow**, from querying a relational database to delivering **interactive financial dashboards**.  
It showcases how transaction and customer data can be combined to uncover spending patterns, customer value, and revenue drivers—supporting informed strategic decisions.

---

📁 **Files Included**
- Power BI `.pbix` files
- PostgreSQL SQL scripts
- Dashboard PDF exports
- README documentation
