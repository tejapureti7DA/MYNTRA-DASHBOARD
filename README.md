# MYNTRA-DASHBOARD
An interactive Myntra Sales Performance Dashboard built in Power BI that tracks 99.06M in Net Sales against 71.40M in Costs across 10K total items. It provides a regional breakdown of operational costs, fulfillment statuses (Delivered, Returned, Cancelled), and product categories like Accessories, Beauty, and Footwear using dynamic, branded visuals.

🛠️ Tech Stack & Key Features:
Business Intelligence Tool: Power BI Desktop — Used for data ingestion, relationship modeling, and report canvas layout.

Data Modeling & Analytics: DAX (Data Analysis Expressions) — Leveraged to create calculated metrics, such as calculating the Sum of Net Sales, Average Profit, and tracking fulfillment quantities.

Visualizations & Reporting:

KPI Cards: For instant executive summaries of core financial metrics.

Waterfall Chart: Implemented for step-by-step cost accumulation analysis across regions.

Donut & Ribbon/Line Charts: Employed for distribution tracking and multi-dimensional sales analysis.

UX/UI Customization: Custom Theme & Canvas Tooltips — Designed with a branded Myntra magenta palette, background watermarking, and hover-triggered tooltips for granular data extraction without cluttering the main view.


📂 Data Source & Schema
The data used for this dashboard simulates a comprehensive e-commerce retail dataset optimized for multi-dimensional analysis. The underlying data model consists of the following key attributes across sales, logistics, and regional tables:

Financial Metrics: Contains records for Net_Sales, operational Cost, product Unit_Price, and transaction Discount_%.

Logistics & Fulfillment: Tracks Order_ID, Order_Date, and Order_Status categorized into three primary fulfillment phases: Delivered, Returned, and Cancelled.

Customer Preferences: Records customer checkout details including Payment_Mode (comprising COD, Credit Card, Debit Card, Net Banking, and UPI) and customer-submitted Rating scores.

Geographical Data: Segmented by major Indian tier-1 and tier-2 retail hubs, including Pune, Hyderabad, Chennai, Bangalore, Kolkata, Delhi, Mumbai, and Ahmedabad.

Product Catalog: Items categorized by inventory verticals: Accessories, Beauty, and Footwear.

✨ Features & Highlights
Executive Financial Health Snapshot: Provides instant, high-level clarity on business performance using dedicated card visuals for core metrics: Net Sales (99.06M), Total Operational Costs (71.40M), Maximum Inventory Unit Price (8K), and Order Volume (10K quantity).

Granular Multi-Dimensional Tooltips: Features interactive hover tooltips that break down complex data on demand without cluttering the canvas—such as isolating precise transaction volumes by payment type (e.g., Net Banking, UPI, COD) specifically for Cancelled orders.

Geographical Cost Progression Tracking: Integrates a Waterfall Chart mapping out the cumulative operational cost impacts across key retail hubs, including Hyderabad, Chennai, Bangalore, Pune, Kolkata, Mumbai, Ahmedabad, and Delhi.

Volume vs. Profitability Correlation: Features a Donut Chart that cross-examines the total count of net sales against the average profit margin (averaging 2.6K), allowing stakeholders to easily contrast high-volume products against high-margin items.

Cross-Category Regional Analysis: Uses a horizontal matrix bar chart to break down the total unit price across different cities, color-coded by Myntra’s core inventory categories: Accessories, Beauty, and Footwear.

Dynamic UX/UI Controls: Equipped with a dedicated left-hand control panel featuring interactive dropdown slicers for City, Order_ID, Rating, and Discount_%, enabling users to filter the entire report canvas instantly.

Custom Branded Aesthetics: Designed with an enterprise-ready theme utilizing Myntra's signature corporate magenta color palette, complete with a clean background watermark for a polished, professional look.

