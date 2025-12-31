# E-commerce Sales Performance Dashboard

## 📖 Project Overview
This project focuses on a comprehensive analysis of e-commerce transactions to drive data-driven decision-making. By transforming raw data into an interactive Power BI dashboard, I’ve enabled stakeholders to track high-level KPIs and drill down into granular performance metrics across categories, payment methods, and geographic regions.

### Business Problem
The goal was to identify which product sub-categories drive the most profit, understand customer payment preferences, and pinpoint geographical regions with the highest sales density to optimize marketing spend.

## 📊 Dashboard Preview
**Figure 1:** Main Sales & Profitability Overview.
![Dashboard Preview](image_screenshort.png)

## 🚀 Key Insights & Findings

### 1. Profitability & Product Performance
*   **Dominant Sub-Category:** Printers emerged as the primary profit driver, generating 8,606 in Total Profit, which accounts for 20.71% of the entire business profit.
*   **Profit Gap:** There is a significant variance in performance; Printers outperformed the lowest-earning sub-category (Furnishings) by 1,167.74%.
*   **Revenue vs. Volume:** While Electronics generated the highest total sales (166,267), Clothing accounted for the largest volume of units sold at 62.6% of total quantity.

### 2. Customer Behavior & Operations
*   **Payment Trends:** Cash on Delivery (COD) is the preferred payment mode for 43.7% of customers, followed by UPI at 20.6%.
*   **Regional Strength:** Maharashtra is the top-performing state, crossing the 100K sales mark, followed closely by Madhya Pradesh.
*   **Seasonality:** Profitability fluctuates throughout the year, with a notable peak in November (reaching 10,253) and a significant dip in May.

## 🛠️ Technical Implementation

### Data Modeling
The project utilizes a **Star Schema** architecture:

*   **Fact Table:** Sales transactions containing metrics like Amount, Profit, and Quantity.
*   **Dimension Tables:** State, CustomerName, Category, and Date.

### DAX & Calculated Measures
Key measures were developed to provide dynamic insights:

| Measure | Description |
| :--- | :--- |
| **Total Profit** | Aggregate of profit across all segments. |
| **Total Sales** | Sum of the 'Amount' column for revenue tracking. |
| **Average Sales per Category** | Calculated using `AVERAGEX` to compare value per transaction (Electronics: 1,001.61 vs. Clothing: 515.44). |

### Visualizations Used
*   **Donut Charts:** For Category and Payment Mode distribution.
*   **Stacked Bar Charts:** For Sub-category profit analysis.
*   **Clustered Column Charts:** For State-wise sales distribution.
*   **Slicers:** Interactive filters for Quarter, Category, and State-level deep dives.

## 📂 Project Structure
```plaintext
├── E-commerce_Sales_Dashboard.pbix  # Main Power BI Project File
├── image_825c77.png                 # Dashboard Screenshot
└── README.md                        # Project Documentation
```

## 💡 Recommendations
1.  **Inventory Optimization:** Increase stock levels for Printers and Electronics during the Q4 peak (November/December) to capitalize on high-profit trends.
2.  **Operational Efficiency:** Since COD is the dominant payment method (43.7%), ensure logistics partners are optimized for cash handling to reduce return-to-origin (RTO) rates.
3.  **Marketing Focus:** Target underperforming states like Sikkim and Tamil Nadu with localized promotions to balance geographic sales distribution.

## 👤 Author
**Pranav Kumar Ganji**

*   **LinkedIn:** [[[Your LinkedIn Profile Link]](https://www.linkedin.com/in/pranav-kumar-g/)]

