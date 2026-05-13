# 📘 Final Group Assignment — Microsoft Fabric End-to-End Retail Analytics Project

# Assignment Overview

You are part of a Data & Analytics Engineering team hired to build a complete modern analytics solution for a retail company using Microsoft Fabric and Power BI.

Your team must design and implement an end-to-end system that ingests raw business data, processes it through a Lakehouse architecture, transforms it into reporting-ready tables, and visualizes the results in Power BI.

---

# 👥 Group Assignments

## Group 1 — Sales Performance

Focus on:

- revenue analysis
- sales trends
- regional performance
- store performance
- order analysis

---

## Group 2 — Customer Analytics

Focus on:

- customer segmentation
- repeat customers
- customer geography
- high-value customers
- customer return behavior

---

## Group 3 — Product & Inventory Analytics

Focus on:

- product performance
- category analysis
- inventory tracking
- low-stock products
- return analysis

---

# 🎯 Your Objective

Build a complete working solution using:

```text
Raw Files
    ↓
Data Pipeline
    ↓
Bronze Layer
    ↓
Silver Layer
    ↓
Gold Layer
    ↓
Semantic Model
    ↓
Power BI Dashboard
```

Your final solution must demonstrate a realistic business workflow where new files can be added and the reporting system updates accordingly.

---

# 🛠️ Required Tasks

# Part 1 — Create Microsoft Fabric Workspace

Create a new Fabric Workspace.

Workspace naming example:

```text
FABRIC_RETAIL_GROUP_1
FABRIC_RETAIL_GROUP_2
FABRIC_RETAIL_GROUP_3
```

---

# Part 2 — Create Lakehouse

Create a Lakehouse named:

```text
RetailLakehouse
```

---

# Part 3 — Create Folder Structure

Inside the Lakehouse Files section, create:

```text
Files/raw/incoming/
Files/processed/
Files/archive/
```

---

# Part 4 — Prepare Data Files

Use retail business data files such as:

```text
customers.csv
products.csv
stores.csv
orders.csv
order_items.csv
inventory.csv
returns.csv
```

Place raw files inside:

```text
Files/raw/incoming/
```

---

# Part 5 — Create Data Pipeline

Create a working pipeline named:

```text
PL_INGEST_RETAIL_DATA
```

Your pipeline must:

- read new incoming files
- load raw data into Bronze tables
- execute transformations
- refresh downstream reporting tables

---

# Part 6 — Create Bronze Tables

Create Bronze tables for raw imported data.

Examples:

```text
bronze_customers
bronze_products
bronze_orders
bronze_order_items
bronze_inventory
bronze_returns
```

Bronze tables should contain raw imported data with minimal changes.

---

# Part 7 — Create Silver Tables

Create Silver tables for cleaned and validated data.

Examples:

```text
silver_customers
silver_products
silver_orders
silver_order_items
silver_inventory
silver_returns
```

Your Silver layer should:

- remove duplicates
- fix inconsistent values
- standardize formatting
- validate data quality

---

# Part 8 — Create Gold Tables

Create Gold tables for reporting and analytics.

Required Gold tables:

```text
dim_customer
dim_product
dim_store
dim_date
fact_sales
fact_returns
fact_inventory
```

---

# Part 9 — SQL Transformations

Create SQL scripts to:

- clean data
- validate records
- aggregate metrics
- create reporting-ready tables

You must be able to explain your SQL logic during the presentation.

---

# Part 10 — Build Semantic Model

Create a semantic model connected to your Gold tables.

You must:

- define relationships
- create measures
- organize reporting fields

---

# Part 11 — Build Power BI Dashboard

Create a professional Power BI report.

Your report must contain:

## Page 1 — Executive Summary

Include:

- Total Sales
- Total Orders
- Total Customers
- Average Order Value
- Return Rate

---

## Page 2 — Group-Specific Analytics

Build visualizations related to your assigned business area.

---

## Page 3 — Technical Architecture

Explain:

- data flow
- pipeline process
- Bronze/Silver/Gold architecture
- semantic model structure

---

# Part 12 — Demonstrate Pipeline Automation

Your group must demonstrate the following workflow:

1. Upload a new CSV file into:

```text
Files/raw/incoming/
```

2. Run the pipeline

3. Show updated Bronze/Silver/Gold tables

4. Refresh the Power BI report

5. Show updated dashboard results

This demonstration is mandatory.

---

# 📊 Required Deliverables

Your group must submit:

## 1. Fabric Workspace

Working workspace with all required assets.

---

## 2. Lakehouse

Working Lakehouse implementation.

---

## 3. Data Pipeline

At least one fully functioning pipeline.

---

## 4. SQL Scripts

All SQL transformation scripts used in the project.

---

## 5. Bronze / Silver / Gold Tables

Fully implemented layered architecture.

---

## 6. Semantic Model

Working semantic model with relationships and measures.

---

## 7. Power BI Dashboard

Professional dashboard with business insights.

---

## 8. Architecture Diagram

Visual diagram explaining the full solution.

---

## 9. Final Presentation

5–10 minute group presentation covering:

- business problem
- architecture
- pipeline
- transformations
- dashboard
- insights
- challenges
- lessons learned

---

# 📋 Evaluation Rubric

| Category | Marks |
|---|---:|
| Workspace & Lakehouse Setup | 10 |
| Pipeline & Automation | 20 |
| Bronze / Silver / Gold Architecture | 20 |
| SQL Transformations | 15 |
| Semantic Model | 10 |
| Power BI Dashboard | 15 |
| Presentation & Communication | 10 |
| Total | 100 |

---

# ⚠️ Important Notes

- Every group member must participate.
- Your pipeline must work during the final demo.
- Your dashboard must use data from your Gold layer.
- Your solution should simulate a realistic business analytics workflow.
- Focus on correctness, structure, and clarity rather than unnecessary complexity.

---

# 🚀 Final Goal

By completing this assignment, you should demonstrate the ability to design and implement a modern end-to-end analytics solution using Microsoft Fabric and Power BI.
