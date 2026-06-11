# Intelligent Document Processing (IDP) & Loan Analytics Dashboard

An end-to-end data pipeline that extracts unstructured text fields from commercial invoices, normalizes the data into structured tabular formats, and serializes the records into a Power BI business intelligence dashboard for risk assessment and application processing analytics.

---

## 📸 Pipeline & Execution Results

The pipeline successfully automates data extraction from source documents and visualizes application trends, risk profiles, and financial metrics.

### 1. Source Document Ingestion
The extraction engine processes unstructured files (such as commercial invoices or applications) to isolate key entities and metadata.

<p align="left">
  <img src="Screenshot%202026-06-10%20145608.png" alt="Source Document Invoice" width="550">
</p>

### 2. Structured Key-Value Normalization
Extracted data fields (including `Invoice Number`, `Buyer Company`, and transactional line items) are parsed and mapped into structured Excel schemas.

<p align="left">
  <img src="Screenshot%202026-06-10%20145700.png" alt="Normalized Tabular Output" width="550">
</p>

### 3. Power BI Credit Risk & Application Dashboard
The final structured dataset is ingested into Power BI to monitor application metrics, credit score distributions, loan allocations, and automated system decisions.

<p align="left">
  <img src="Screenshot%20(31).png" alt="Power BI Loan Analytics Dashboard" width="100%">
</p>

---

## 📊 Dashboard Analytics Architecture

The Power BI dashboard provides a holistic overview of the application funnel using key metrics and data visualizations:

* **KPI Summary Tiles**: Monitors high-level operational metrics including total application volume (`22`), aggregate income pools (`1M`), total loan requests (`489K`), and calculated risk tracking metrics (`Average of Credit_Score: 614.55`).
* **System Action Funnel**: A breakdown donut chart monitoring automated processing logic (`Auto_Reject`, `Auto_Approve`, `Manual_Review`).
* **Credit Score Matrix**: A clustered bar chart mapping applicant credit health across distinct application identification sequences (`APX 2026-020` to `APX 2026-004`).
* **Multivariate Trend Analyzer**: A dual-axis line and scatter plot system displaying relationships between an applicant's annual income, requested loan amounts, and credit limits.

---

## 🚀 Repository Asset Placement Note

> [!IMPORTANT]
> To ensure all interface snapshots render correctly on your repository landing page, save your image assets directly in your root directory matching these exact filenames:
> * `Screenshot 2026-06-10 145608.png`
> * `Screenshot 2026-06-10 145700.png`
> * `Screenshot (31).png`
