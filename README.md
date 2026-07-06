# ABC
ABC Analysis with Power BI Optimization


# Inventory Optimization using ABC Analysis in Power BI

## 📂 Project File
You can download and explore the fully interactive Power BI desktop file directly from this repository:
* 📥 **[Download Transformed ABC.pbit](Transformed%20ABC.pbit)** *(Requires Power BI Desktop to open)*

---

## 📊 Project Overview
This project focuses on **Inventory Optimization and Data Analytics** using a custom-built Power BI solution. By implementing an advanced **ABC Analysis**, this model cross-tabulates product sales velocity (`Units Rank`) with financial performance (`Profit Rank`). 

The goal is to provide supply chain managers and stakeholders with actionable insights to reduce holding costs, eliminate stockouts of critical items, and maximize warehouse efficiency.

---

## 💡 Key Features & Framework
* **Interactive Matrix View:** Dynamically categorizes 12 product types based on volume vs. profitability.
* **Color-Coded Visual Hierarchy:** Uses conditional formatting to highlight product performance at a glance (Champions vs. Low-Mobility assets).
* **Multi-Dimensional Analysis:** Incorporates a Donut Chart, Treemap, and Bar Chart for a comprehensive understanding of the product inventory mix.
* **Live Slicers:** Full interactivity allowing users to filter data down to specific combined ABC codes.

## 🧠 Business Insights & Strategy Applied
* **AAA Category (e.g., Baby Food):** High volume + High profit. Designated for strict safety stock management and optimal warehouse positioning.
* **ABA/AAC Category (e.g., Meat, Beverages):** High velocity but lower margins. Optimized via bulk-shipping and automated replenishment.
* **CAA Category (e.g., Household):** Low velocity but high margins. Managed through Just-In-Time (JIT) methods to prevent tying up valuable capital.

---

## 🛠️ Tech Stack
* **Tool:** Power BI Desktop
* **Methodology:** ABC Inventory Classification, Data Modeling, DAX (Count/Distinct Logic)
