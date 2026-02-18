# Sales Order Lifecycle & Vendor Management System

### 📌 Project Overview
This project simulates a high-volume ERP environment—modeled after the **Würth Group**—to manage the end-to-end journey of sales orders. Using a dataset of **50,000+ transactions**, I engineered a system to standardize product data, track order health, and optimize vendor communication.

### 🛠️ Key Technical Features
* **ERP Article Identification:** Developed a master lookup engine using `INDEX/MATCH` to synchronize raw product descriptions with unique **Würth Article Numbers**.
* **Dynamic Order Tracking:** Built automated status triggers to identify **Articles in Backorder**, allowing for real-time monitoring of fulfillment gaps.
* **Vendor Management System (VMS):** Created a prioritized follow-up matrix using **Pivot Tables** and **Slicers** to isolate overdue deliveries and streamline supply chain communication.
* **Operational Dashboard:** Visualized fulfillment health via **Pie Charts** and **Regional Summaries** to provide executive-level insights into warehouse pressure.

### 📊 Visuals & Results
> **Note:** Screenshots of the finalized tools can be found in the [project_snapshot_folder](./project_snapshot_folder).

1. **Article Search Tool:** Streamlines manual order entry and data cleaning by mapping descriptions to specific article codes.
2. **Fulfillment Dashboard:** A visual "Health Check" displaying the ratio of Ready-to-Ship vs. Backordered items.

### 📂 Repository Structure
* **/data**: Contains the Excel workbook (simulated ERP export).
* **/project_snapshot_folder**: Includes high-resolution captures of the final reports and dashboard.

### 🚀 Business Impact
* **Standardization:** Achieved 100% accuracy in mapping disparate sales data to the Article Master.
* **Efficiency:** Automated the identification of supply chain bottlenecks, significantly reducing manual audit time.
* **Transparency:** Provided a visual feedback loop for regional sales performance and vendor reliability.

---
**Role Target:** Sales Support Analyst / Data Coordinator
**Tools Used:** Advanced Excel (XLOOKUP, INDEX/MATCH, Pivot Tables, Logic Functions)
