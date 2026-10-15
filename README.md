# Customer Shopping Behavior Analysis

An end-to-end data analytics project uncovering key patterns in customer shopping behavior, purchasing trends, and segment dynamics to optimize retail marketing and product strategies.

---


## 📌 Business Problem Statement

A leading retail company wants to better understand its customers' shopping behavior in order to improve sales, customer satisfaction, and long-term loyalty. The management team noticed shifts in purchasing patterns across demographics, product categories, and sales channels. They are particularly interested in uncovering which factors—such as discounts, reviews, seasons, or payment preferences—drive consumer decisions and repeat purchases.

### 🎯 Core Business Question
> *"How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"*

---

## 📦 Project Deliverables

1. **Data Preparation & Modeling (Python):** Cleaned, preprocessed, and transformed the raw transaction records for downstream analysis.
2. **Data Analysis (SQL):** Structured the data in a relational database, running analytical queries to extract insights on customer segments, loyalty, and purchase drivers.
3. **Visualization & Insights (Power BI):** Developed an interactive BI dashboard highlighting trends, KPIs, and purchasing patterns to enable data-driven business decisions.
4. **Business Reporting & Presentation:** Prepared an executive project report (`.pdf`) and an interactive stakeholder presentation deck (`.pptx`) created using Gamma and PowerPoint.
5. **Version Control & Repository Management:** Well-documented GitHub repository structuring all Python scripts, SQL queries, Power BI models, and report assets.

---

## 📊 Power BI Dashboard

<img width="1289" height="703" alt="Screenshot 2026-10-14 174534" src="https://github.com/user-attachments/assets/3b336ed4-f86a-4368-a792-74ecf9d168fe" />

---

## 📂 Dataset
- **File:** `customer_shopping_behavior.csv`
- **Key Attributes:**
  - **Demographics:** Customer ID, Age, Gender, Location
  - **Purchasing Details:** Item Purchased, Category, Purchase Amount (USD), Season, Size, Color
  - **Behavioral Metrics:** Review Rating, Subscription Status, Shipping Type, Discount Applied, Promo Code Used, Previous Purchases, Preferred Payment Method, Frequency of Purchases

---

## 🛠️ Tools & Tech Stack

- **Data Wrangling & EDA:** Python (`pandas`, `numpy`, `matplotlib`, `seaborn`)
- **Database & Querying:** MySQL / PostgreSQL
- **Business Intelligence & Dashboards:** Microsoft Power BI (DAX, Data Modeling)
- **Reporting & Presentations:** Gamma App, Microsoft PowerPoint, Word / PDF
- **Version Control:** Git & GitHub

---

## 🚀 End-to-End Workflow

### Step 1: Data Cleaning & EDA (Python)
- Loaded raw data via Jupyter Notebook (`Customer_Behavior_Analysis.ipynb`).
- Evaluated missing data, verified data types, handled anomalies, and generated descriptive statistics.
- Plotted distributions for age groups, purchase amounts, and product categories to detect initial behavioral correlations.

### Step 2: Relational Modeling & SQL Analytics
- Imported cleaned dataset into a relational database schema (`customer_behavior_analysis.sql`).
- Executed SQL queries using CTEs, window functions, and aggregations to answer specific business questions:
  - Customer lifetime value and segment distribution.
  - Subscription vs. non-subscription purchase frequencies and spending amounts.
  - Seasonal revenue contributions and promo/discount impact on transaction volume.

### Step 3: Interactive Dashboard Development (Power BI)
- Imported and modeled data inside Power BI (`customer_shopping_behaviorDB.pbix`).
- Formulated custom DAX measures (Total Revenue, AOV, Repeat Purchase Rates, Customer Count).
- Built interactive visuals, dynamic filters, and slicers across demographics, sales channels, and product categories.

### Step 4: Executive Reporting & Presentation
- Summarized insights into an executive project report (`Customer Shopping Behavior Analysis.pdf`).
- Designed a presentation deck (`Customer-Shopping-Behavior-Analysis.pptx`) using Gamma App and MS PowerPoint to communicate findings to management.

---

## 📈 Key Insights & Recommendations

- **Subscription Impact:** Subscribed customers display higher repeat purchase frequency and greater customer lifetime value.
- **Seasonal Demand:** Clear category spikes across seasons suggest pre-season targeted inventory and promotional campaigns.
- **Discount & Retention Drivers:** Review ratings correlate directly with repeat purchasing behavior; personalized discounts encourage dormant customer tiers to re-engage.
