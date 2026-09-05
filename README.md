# 👟 Maru Footwear Sales Performance Dashboard

An interactive business intelligence dashboard designed to analyze the sales performance of Maru Footwear across multiple e-commerce marketplaces.

---

## 📊 Project Overview

Maru Footwear is an e-commerce footwear business that sells products through several marketplace platforms, including **Shopee, Tokopedia, Lazada, and Blibli**.

This project analyzes transaction data to evaluate sales performance, revenue contribution, product performance, and refund activity during **1 February – 31 March 2025**.

The analysis is presented through an interactive dashboard built using **Google Looker Studio**, allowing users to explore sales performance through marketplace, product category, refund status, product, and date filters.

---

## 🎯 Business Objectives

The dashboard was developed to answer the following business questions:

1. Which e-commerce marketplace contributes the most revenue?
2. How much refund value was generated during the analysis period?
3. How did daily revenue change throughout March 2025, and when did sales peaks occur?
4. Which product categories generated the highest quantity of sales?
5. Which products had the highest quantity sold?

---

## 🗂️ Dataset

The dataset contains transaction-level sales information from Maru Footwear.

The analysis focuses on transactions recorded between:

**1 March 2025 – 31 March 2025**

The dataset contains information related to:

- Order ID
- Order Date
- Marketplace
- Product ID
- Product Name
- Product Category
- Quantity
- Unit Price
- Order Value
- Discount
- Shipping Cost
- Order Status
- Refund Status
- Refund Amount

---

## 🛠️ Tools & Technologies

- **Microsoft Excel** — Data preparation and validation
- **Google Looker Studio** — Interactive dashboard and data visualization
- **Data Cleaning** — Preparing transaction data for analysis
- **Exploratory Data Analysis (EDA)** — Identifying sales patterns and performance
- **Business Intelligence** — Translating data into business insights

---

## 📈 Dashboard Preview

![Maru Footwear Sales Dashboard](<E-COMMERCE_PERFORMANCE_DASHBOARD (5)-1.png>)

---

## 🔗 Interactive Dashboard

👉 **[View Interactive Dashboard](https://datastudio.google.com/reporting/fc2eef59-2328-4714-9f55-a080625e2884)**

The interactive dashboard allows users to filter and explore the data by:

- Marketplace
- Product Category
- Product Name
- Refund Status
- Date Range
- Unit Price
- Discount

---

## 📌 Key Performance Indicators

The dashboard provides several key performance indicators (KPIs):

| KPI | Description |
|---|---|
| **Total Revenue** | Total sales revenue generated during the analysis period |
| **Total Orders** | Total number of transactions |
| **Total Quantity Sold** | Total number of products sold |
| **Total Refund Value** | Total monetary value of refunded transactions |
| **Average Order Value (AOV)** | Average revenue generated per order |
| **Refund Value Rate** | Percentage of revenue represented by refund value |

### March 2025 Performance

| Metric | Result |
|---|---:|
| Total Revenue | **Rp3.0 Billion** |
| Total Quantity Sold | **9.2K Units** |
| Total Refund Value | **Rp39.17 Million** |
| Average Order Value | **Rp961.96K** |
| Refund Value Rate | **1.3%** |

---

## 📊 Dashboard Components

### 1. Revenue by Marketplace

**Purpose:**  
Compare revenue contribution across Shopee, Tokopedia, Lazada, and Blibli.

This visualization helps identify which marketplace generates the largest contribution to overall revenue.

---

### 2. Daily Revenue Trend

**Purpose:**  
Analyze daily revenue movement throughout March 2025.

The visualization helps identify:

- Revenue growth and decline
- Sales peaks
- Changes in daily performance
- Potential periods requiring further investigation

---

### 3. Quantity Sold by Product Category

**Purpose:**  
Compare the number of products sold across different product categories.

This analysis helps identify product categories with the highest sales volume.

---

### 4. Top Products by Quantity Sold

**Purpose:**  
Identify products with the highest sales volume.

This information can support decisions related to:

- Inventory planning
- Product promotion
- Product prioritization
- Sales strategy

---

### 5. Order Transaction Details

**Purpose:**  
Provide detailed transaction-level information, including order date, order ID, quantity, and revenue.

This table allows users to drill down from aggregated performance metrics into individual transactions.

---

## 🔍 Key Findings

Based on the March 2025 analysis:

### Marketplace Performance

**Shopee** generated the largest revenue contribution among the analyzed marketplaces, followed by Tokopedia, Lazada, and Blibli.

This indicates that marketplace performance is not evenly distributed and that some platforms contribute more significantly to overall sales.

### Product Category Performance

The **Formal** category recorded the highest quantity sold among the analyzed product categories, followed by Sports, Outdoor, and Casual categories.

### Refund Performance

The total refund value reached approximately **Rp39.17 million**, representing around **1.3% of total revenue**.

Although the refund value represents a relatively small portion of total revenue, products or transactions with higher refund values may require further investigation.

### Sales Trend

Daily revenue fluctuated throughout March 2025, with several periods showing higher sales activity.

The revenue trend can be used as a starting point for investigating potential factors behind sales peaks, such as promotions, marketplace campaigns, product availability, or customer purchasing patterns.

---

## 💡 Business Recommendations

Based on the analysis, several recommendations can be considered:

### 1. Optimize High-Performing Marketplaces

Focus on maintaining and improving sales performance on marketplaces that contribute the largest share of revenue.

Possible actions include:

- Optimizing product listings
- Improving promotional strategies
- Monitoring marketplace campaigns
- Evaluating advertising performance

### 2. Prioritize High-Volume Product Categories

The highest-selling product categories can be prioritized for inventory planning and promotional activities.

Maintaining sufficient stock for high-demand categories may help reduce the risk of lost sales.

### 3. Monitor High-Performing Products

Products with high sales volume should be monitored regularly to understand their contribution to revenue and inventory requirements.

These products may also be suitable candidates for:

- Promotional campaigns
- Bundling
- Cross-selling
- Stock prioritization

### 4. Investigate Refund Patterns

Although the refund value rate is relatively low, transactions and products with unusually high refund values should be investigated further.

Possible areas of investigation include:

- Product quality
- Product descriptions
- Customer expectations
- Order fulfillment
- Product category
- Marketplace

---

## 📁 Repository Structure

```text
maru-footwear-sales-dashboard/
│
├── README.md
│
├── data/
│   └── Data_Maru Footwear Sales.xlsx
│
├── dashboard/
│   └── E-COMMERCE_PERFORMANCE_DASHBOARD (5)-1.png
│
└── documentation/
    └── analysis.md

