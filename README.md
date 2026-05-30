# 📊 UPI Transaction Analysis Dashboard | Power BI

## 📌 Project Overview

This project analyzes UPI (Unified Payments Interface) transactions using Power BI to understand transaction trends, payment behavior, bank performance, and remaining balance patterns.

The dashboard provides an interactive and data-driven view of UPI transactions, helping users explore transaction volumes, payment methods, merchant activity, device usage, and account balances through dynamic visualizations.

---

## 🎯 Business Problem

With the rapid growth of digital payments, financial institutions and businesses need insights into:

- Monthly transaction trends
- Popular payment methods
- Transaction type distribution
- Bank-wise transaction activity
- Merchant performance
- User behavior across devices
- Remaining balance analysis
- Regional transaction patterns

The objective was to transform raw transaction data into meaningful business insights through interactive Power BI dashboards.

---

## 📂 Data Source


**Source Type:** Excel Workbook (.xlsx)

The dataset contains information related to:

- Transaction ID
- Transaction Date
- Bank Name Sent
- Bank Name Received
- Transaction Amount
- Remaining Balance
- City
- Gender
- Device Type
- Merchant Name
- Payment Method
- Transaction Type
- Purpose

---

## 🧹 Data Cleaning & Transformation

Data preparation was performed in **Power Query Editor**.

### Transformations Applied

✔ Removed unnecessary columns

✔ Renamed columns

✔ Changed data types

✔ Split columns where required

✔ Created custom columns

✔ Standardized categorical values

✔ Date formatting and transformation

Power Query Data Profiling tools were used to assess data quality:

### Column Quality

- Checked valid values
- Identified errors
- Detected empty values

## 📐 DAX Calculation Column Created

### Feature Engineering

- Created a custom Age Group column using conditional logic:
- A1: Age < 25
- A2: Age 25–34
- A3: Age ≥ 35
- Used the new category for demographic analysis and dashboard filtering.

## 🔧 Power Query (M Code)

Power Query M Language was used for:

Data Transformation:

Used Power Query M code to remove unnecessary records and clean the dataset.

## 📊 Dashboard Features

### Page 1: Transaction Analysis

- Monthly Transaction Trend
- Line Chart Analysis
- Column Chart Analysis
- Dynamic Bookmarks
- Interactive Slicers


### Page 2: Remaining Balance Analysis

- Remaining Balance Trend
- City-wise Analysis
- Matrix View
- Comparative Reporting

## 🎨 Interactive Features Implemented

### Bookmarks

Used bookmarks to switch between:

- Line Chart View
- Column Chart View
- Remaining Balance Views

### Selection Pane

Used for:

- Managing visual visibility
- Bookmark control
- Layer management

### Sync Slicers

Implemented slicer synchronization across report pages for consistent filtering.

## 📈 Key Insights Generated

- Identified months with highest transaction volumes
- Compared transaction amounts across months
- Analyzed remaining balance trends
- Evaluated bank transaction performance
- Studied payment method preferences
- Examined city-wise transaction behavior
- Compared transaction types and merchant activity

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|--------|--------|
| Power BI Desktop | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | Calculations & KPIs |
| Excel | Data Source |
| M Language | Data Transformation |
| Bookmarks | Dynamic Navigation |
| Sync Slicers | Cross-page Filtering |

## 📷 Dashboard Screenshots

### Transaction Trend Dashboard

(Add Screenshot Here)





















