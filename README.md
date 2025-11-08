# Sparking Growth: A Data-Driven Strategy for Shri Hari Electric and Electronics

This repository contains the analysis and implementation for the BDM capstone project. The project focuses on optimizing sales, inventory, and logistics for Shri Hari Electric And Electronics through a data-driven approach.

##  Table of Contents
* [About the Business](#-about-the-business)
* [Problem Statement](#-problem-statement)
* [Project Objectives](#-project-objectives)
* [Methodology](#-methodology)
* [Technology Stack](#-technology-stack)
* [Project Timeline](#-project-timeline)
* [Expected Outcomes](#-expected-outcomes)
  

---

##  About the Business

**Shri Hari Electric And Electronics** is a B2C retail store founded in 2022 by Mr. Santlal Maurya in Mariyahu, Jaunpur. It serves the local community as a one-stop shop for electronics, furniture, and home wiring supplies. The store's key differentiator is its unique product mix, catering to customers furnishing existing homes and those building new ones from the ground up.

* ** Location:** Mariyahu near Railway Fatak, Jaunpur, Uttar Pradesh 222161
* ** Operating Hours:** 9:00 AM to 9:00 PM daily
* ** Team Size:** 4, including the owner

---

##  Problem Statement

The business faces significant operational challenges that hinder its growth. These problems stem from a reliance on manual processes and intuition-based decisions, combined with external market pressures like seasonal purchasing behavior. This results in three critical issues:

1.  **Significant Revenue Volatility:** Sales are heavily concentrated in festive seasons, leading to unpredictable cash flow and sharp revenue declines during off-season months.
2.  **Inefficient Inventory Management:** The lack of a systematic stocking policy causes overstocking of slow-moving items and stockouts of high-demand products, blocking capital.
3.  **Sub-optimal Transportation Logistics:** A reactive and unplanned delivery process leads to inefficient routes, excessive fuel consumption, and potential service delays.

---

##  Project Objectives

To address the problems, this project aims to achieve the following quantifiable goals:

* **Revenue:** Design and validate a strategy to **increase average monthly sales during non-festival seasons by 15%** within six months of implementation.
* **Inventory:** Develop a dynamic inventory model to **reduce overall holding costs by 10%** and **minimize stockouts of key items to less than 5%**.
* **Logistics:** Streamline transportation operations to achieve a **15% reduction in delivery-related costs** and improve the **on-time delivery rate to over 95%**.

---

##  Methodology

A three-pronged analytical approach will be used to tackle each objective.

### 1. Revenue Stabilization
* **Methods:**
    * **RFM (Recency, Frequency, Monetary) Analysis** for customer segmentation and targeted promotions.
    * **Market Basket Analysis** to identify product associations for bundling and cross-selling.
    * **Sales Forecasting** using a Moving Average model to set a performance baseline.
* **Data:** Transactional sales data from July 2024 to July 2025 (Transaction_ID, Customer_ID, Date, Product_SKU, Quantity, Price).

### 2. Inventory Optimization
* **Methods:**
    * **ABC-XYZ Analysis** to create a multi-criteria inventory classification matrix based on revenue contribution and demand volatility.
    * **Reorder Point (ROP) Calculation** to determine optimal stock levels for high-value items.
* **Data:** Historical product sales data, supplier lead times, and item costs from July 2024 to July 2025.

### 3. Logistical Enhancement
* **Methods:**
    * **Grid-Based Zone Analysis** to group daily deliveries into geographical zones.
    * **Nearest Neighbor Heuristic** to determine an efficient delivery sequence within each zone.
    * **Cost-Benefit Analysis** to compare the in-house delivery model against outsourcing.
* **Data:** Delivery logs, vehicle expense reports, and quotes from local logistics providers.

---

## Technology Stack

The analysis for this project will be conducted using the following tools:

* **Python:** For data manipulation, modeling, and analysis.
    * **Pandas & NumPy:** For data processing and quantitative analysis.
* **MS Excel:** For initial data structuring and the cost-benefit model.

---

## Project Timeline

The project is executed over an 11-week timeline, broken down into three main phases:

1.  **Initiation & Planning:** (Approx. Sep 2025) - Talking to the owner, submitting the project proposal, and collecting data.
2.  **Analysis & Mid-Term Reporting:** (Approx. Oct 2025) - Data cleaning, insight generation, and mid-term submissions.
3.  **Solution & Final Delivery:** (Approx. Nov 2025) - Finding solutions, preparing the final report, and Viva presentation.

---

## Expected Outcomes

The successful implementation of this project is expected to deliver:

* **Enhanced Profitability:** Stabilized revenue streams and more predictable year-round cash flow.
* **Optimized Capital Allocation:** Reduced inventory holding costs and freed-up capital for reinvestment in high-demand products.
* **Increased Operational Efficiency:** Measurable cost savings in logistics and improved customer satisfaction through reliable, timely deliveries.

---

