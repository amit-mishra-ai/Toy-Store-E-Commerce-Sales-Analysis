# 📦 Toy Store E-Commerce Analytics Dashboard & EDA

## 📌 Project Overview
This project is a complete **E-commerce Business Intelligence & Analytics solution** built using **Python, SQL concepts, and Power BI** on a Toy Store E-commerce dataset.

The project combines:

- 📊 Exploratory Data Analysis (EDA) using Python
- 📈 Interactive Power BI Dashboards
- 🛒 Revenue & Sales Analytics
- 🌐 Website Traffic Analysis
- 🔄 Conversion Funnel Analysis
- 💰 Refund & Profitability Analysis
- 🎯 Product Performance Analysis

---
### Live Dashboard Link : https://app.fabric.microsoft.com/view?r=eyJrIjoiMDliOGYwYmEtNmM2Mi00OWJmLWIyYTEtYzJlOTAzNDgxZGI4IiwidCI6IjYyOTZhNGQzLTZiNjgtNGY3NC05ZWRhLWIxMDAzMzkyYzAxOCJ9
---

The objective of this project is to transform raw e-commerce data into actionable business insights that help stakeholders understand:

- Revenue performance
- Customer behavior
- Marketing effectiveness
- Website conversion efficiency
- Product profitability
- Customer engagement
- Refund leakage

---

# 📁 Dataset Information

The project uses multiple relational datasets:

| Table Name | Description |
|---|---|
| `orders` | Customer order-level information |
| `order_items` | Product-level transaction data |
| `products` | Product catalog details |
| `website_sessions` | Website visit/session information |
| `website_pageviews` | Customer browsing behavior |
| `order_item_refunds` | Product refund information |

---

# 🎯 Business Problems Solved

This project answers important e-commerce business questions such as:

## Revenue & Sales
- What is the total revenue generated?
- Which products generate the highest sales? 
- What are the yearly and monthly revenue trends?

## Customer Behavior
- How users move through the website funnel?
- What is the overall session-to-order conversion rate?
- How do desktop and mobile users behave differently?

## Marketing Performance
- Which traffic sources drive the highest conversions?
- Which campaigns generate the most revenue?

## Refund & Profitability
- Which products have the highest refund rates?
- How much revenue is lost due to refunds?

## Product Analytics
- Which products are top-performing?
- Which product combinations drive cross-sell opportunities?

---

# 🐍 Exploratory Data Analysis (EDA)

The EDA portion of the project was performed using **Python** to uncover hidden business insights before dashboard development.

## 📌 EDA Objectives
- Understand customer purchase behavior
- Analyze conversion funnels
- Identify refund-heavy products
- Measure marketing channel performance
- Compare device-based performance
- Discover product contribution to revenue

---

# 📊 Key EDA Insights

## 1️⃣ Conversion Funnel Analysis
- Overall **session-to-order conversion rate: 6.8%**
- Major drop-offs occur between:
  - Product Page → Cart
  - Cart → Shipping

### 💡 Insight
The checkout process contains friction points reducing completed purchases.

---

## 2️⃣ Revenue Analysis
- Total Revenue Generated: **$1.94M+**
- Revenue peaks observed during high-traffic periods.

### 💡 Insight
Revenue growth strongly correlates with increased website traffic and successful campaigns.

---

## 3️⃣ Refund Analysis
- Total Refunds: **$85K+**
- Certain products contribute disproportionately to refunds.

### 💡 Insight
Refund-heavy products likely suffer from:
- Product expectation mismatch
- Poor descriptions
- Quality issues

---

## 4️⃣ Device Performance
- Desktop users convert significantly higher than mobile users.

### 💡 Insight
The mobile shopping experience needs optimization.

---

## 5️⃣ Traffic Source Performance

### Top Performing Channels
- `gsearch`
- `bsearch`

### Lowest Conversion Source
- `socialbook`

### 💡 Insight
Organic/search traffic generates better ROI than social traffic.

---

## 6️⃣ Product Performance

### Top Revenue Drivers
- The Original Mr. Fuzzy
- The Forever Love Bear

### 💡 Insight
A small group of products contributes most of the revenue.

---

# 📈 Power BI Dashboard Overview

The project includes a **3-page professional interactive Power BI dashboard** designed for executive-level business reporting.

---

# 🖥️ Dashboard Pages

---

# 1️⃣ Revenue Overview Dashboard

## 🎯 Purpose
Provides a high-level business summary for executives and stakeholders.

## 📌 KPIs Included
- Total Revenue
- Total Orders
- Gross Margin %
- Average Order Value
- Refund Rate
- Total Refunds

## 📊 Visuals Included
- Revenue Trend Over Time
- Product Revenue vs Refunds
- Revenue & Profit by Year
- Refund Rate by Product
- Product Performance Summary
- Single vs Multi-item Orders

## 💡 Business Insights
- Revenue growth trends
- Most profitable products
- Refund leakage analysis
- Order purchasing patterns

---

# 2️⃣ Website Traffic & Session Analysis

## 🎯 Purpose
Analyzes customer behavior and website funnel performance.

## 📌 KPIs Included
- Total Sessions
- Bounce Rate
- Average Pages per Session
- Session Conversion Rate
- New vs Repeat Sessions

## 📊 Visuals Included
- Conversion Rate by Traffic Source
- Traffic Source Distribution
- Device-wise Sessions
- Session-to-Order Funnel
- Website Pageview Analysis

## 💡 Business Insights
- Funnel drop-off identification
- Website engagement analysis
- Traffic source efficiency
- Device behavior comparison

---

# 3️⃣ Conversion & Product Performance Dashboard

## 🎯 Purpose
Combines conversion metrics with product and cross-sell analytics.

## 📌 KPIs Included
- Desktop Conversion Rate
- Mobile Conversion Rate
- Revenue per Session
- Cross-sell Orders
- Cross-sell Rate

## 📊 Visuals Included
- Conversion Summary Table
- Desktop vs Mobile Conversion Trends
- Revenue by Product (YoY)
- Top Cross-sell Product Pairs

## 💡 Business Insights
- Mobile optimization opportunities
- Best cross-sell combinations
- Product-level revenue growth
- Channel-wise conversion performance

---

# ✨ Dashboard Features

## Interactive Features
- Dynamic slicers
- Cross-filtering visuals
- Drill-down analysis
- Interactive filtering
- Responsive navigation

## Slicers Used
- Date Range
- Device Type
- Product
- Traffic Source
- Campaign

---

# 🛠️ Tools & Technologies Used

## 📊 Data Analysis
- Python
- Pandas
- NumPy

## 📈 Data Visualization
- Matplotlib
- Seaborn
- Power BI

## 📚 Analytics Techniques
- Exploratory Data Analysis (EDA)
- Funnel Analysis
- Conversion Analysis
- Product Performance Analysis
- Cross-sell Analysis
- Customer Behavior Analytics

---

# 💼 Skills Demonstrated

- Business Intelligence
- Dashboard Design
- Data Cleaning & Transformation
- Data Modeling
- DAX Calculations
- Data Visualization
- KPI Reporting
- Business Storytelling
- Analytical Thinking

---

# 🚀 Business Recommendations

## 1️⃣ Improve Checkout Funnel
- Reduce checkout steps
- Enable guest checkout
- Improve payment reliability

---

## 2️⃣ Optimize Mobile Experience
- Improve mobile UI/UX
- Reduce mobile page load time
- Simplify mobile checkout

---

## 3️⃣ Reduce Refunds
- Improve product descriptions
- Add better product images
- Strengthen quality control

---

## 4️⃣ Focus on High-Performing Channels
- Increase investment in search traffic
- Reduce spending on low-converting campaigns

---

## 5️⃣ Increase Repeat Purchases
- Loyalty programs
- Personalized recommendations
- Email remarketing campaigns

--
# 📌 Outcome

This project demonstrates how data can be transformed into meaningful business insights through:

- Data analysis
- Business intelligence
- Interactive dashboards
- KPI monitoring
- Executive storytelling

The final solution showcases the complete workflow of a modern data analyst:

➡️ Raw Data → Analysis → Insights → Dashboard → Business Recommendations

---

# 👨‍💻 Author

## Amit Kumar Mishra
### Data Analyst | Python | SQL | Power BI | Business Analytics

- Passionate about transforming data into actionable insights
- Focused on Business Intelligence & Analytics projects

---

# ⭐ If You Like This Project

- Star this repository ⭐
- Connect with me on LinkedIn
- Share feedback & suggestions

---
