\# Executive Sales \& Performance Report: End-to-End Data Pipeline

<img width="873" height="492" alt="image" src="https://github.com/user-attachments/assets/451b927d-4fa6-4222-8fc4-5a30a04c1f6f" />




\## 📌 Project Overview

This repository contains a full data analytics project designed to optimize business decision-making by consolidating, cleaning, and visualizing core sales, CRM, and product return metrics. The objective was to transform fragmented data across multiple source files into a unified data model, enabling executive-level tracking of financial performance and customer behavior.



The final dynamic dashboard tracks key metrics such as product revenue, unit demand, transactional volume, and an analytical breakdown of product returns.



\---



\## 📊 Business Metrics Tracked

\* \*\*Total Income / Revenue:\*\* Overall financial yield across all product lines ($151.08K).

\* \*\*Sold Products:\*\* High-level volume monitoring of total physical units dispatched (349 units).

\* \*\*Total Transactions:\*\* Comprehensive order count ensuring system integrity (171 transactions).

\* \*\*Product Returns Tracking:\*\* Segmentation analysis covering return motivations (e.g., "Arrepentido", "Defectuoso", "Talla Incorrecta").



\---



\## 🛠️ Data Architecture \& Pipeline

To maintain an agile, scalable, and lightweight reporting model inside Power BI, the data cleansing and relational logic were handled prior to visualization, utilizing structured data tables:



\### 1. Data Model \& Schema (Source Tables)

\* \*\*`ventas\_consolidadas\_PRO`:\*\* The transactional core table centralizing all physical and digital checkout records.

\* \*\*`tasas\_cambio\_PRO`:\*\* Manages currency exchange rates to normalize international financial transactions into a baseline currency.

\* \*\*`clientes\_crm\_PRO`:\*\* Handles customer data integrity, email validation, and geographical segmentation.

\* \*\*`productos\_catalogo\_PRO`:\*\* Catalog master list binding product IDs, names, and base unit pricing.

\* \*\*`metodos\_pago\_PRO`:\*\* Normalizes financial acquisition channels and payment formats.

\* \*\*`Sheet1` / `Sheet1 (2)` (Returns \& Auditing):\*\* Centralizes operational failure metrics, return motivations, and compliance variances.



\### 2. Data Transformation (ETL Process)

\* \*\*Backend Consolidation:\*\* Instead of heavily overloading Power BI with massive DAX processing or complex multi-directional relationships, data schemas were structured via explicit primary/foreign keys.

\* \*\*Data Sanitization:\*\* Handled text inconsistencies, null structures, and standardized mixed strings into uniform categories to ensure zero metric scattering during visual aggregation.



\---



\## 📈 Visual Insights \& Dashboard Layout

The frontend interface features a clean executive design divided into targeted data matrices:

\* \*\*Product Performance:\*\* Horizontal bar chart displaying product lines by gross revenue (Led by "Laptop Pro 15").

\* \*\*Volume Distribution:\*\* Vertical column chart cross-referencing total physical units sold per product.

\* \*\*Operational Control:\*\* Multi-segmented donut chart evaluating the distribution of revenue leakages based on return causes.

\* \*\*Dynamic Slicers:\*\* Interactive criteria filters to isolate metrics between "Físico" (In-store) and "Web" (E-commerce) channels.



\---



\## 🚀 How to Run the Project

1\. Clone this repository to your local path or Google Drive directory.

2\. Review the structural layout of the source data sets.

3\. Open the `.pbix` template file to examine the data schema, measures, and interactive UI layout.

