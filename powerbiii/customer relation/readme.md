# 📊 Customer Success & Support Analytics (Power BI)

## 📌 Project Overview
This Power BI project provides an interactive analytics dashboard designed to analyze **customer success, subscription behavior, and support performance**.  
It enables stakeholders to monitor customer distribution, support workload, escalation trends, and device usage across regions.

The dashboard is divided into three main analytical views:
1. **Customer Overview**
2. **Support Performance**
3. **Geographic & Device Analysis**

---

## 🧩 Dataset Summary
The dataset represents customer and support ticket data with the following key attributes:

- Customer count and tenure
- Subscription type (Basic, Premier)
- Customer roles (Administrator, Consumer, Publisher)
- Support ticket volume and duration
- Escalation rates
- Geographic distribution
- Device usage (Browser, Mobile, Tablet)

---

## 📊 Dashboard Pages & Key Insights

### 1️⃣ Customer Overview
**Purpose:** Understand customer distribution and subscription trends.

**Key KPIs**
- **Total Customers:** 45K  
- **Average Tenure:** 16.7  
- **Average Original Score:** 7.42  

**Visuals Included**
- Subscription Type Breakdown (Basic vs Premier)
- Role Distribution (Donut Chart)
- Company Size vs Subscription Matrix
- Customer Count by Continent & Country
- Role Distribution by Subscription

**Insights**
- Premier subscriptions dominate the customer base
- Publishers represent the largest user role
- Most customers belong to mid-sized organizations

---

### 2️⃣ Support Performance
**Purpose:** Measure support efficiency and workload.

**Key KPIs**
- **Total Tickets:** 127K  
- **Average Ticket Duration:** 3.67  
- **Tutorial Usage Rate:** 0.56  

**Visuals Included**
- Ticket Count by Month (Trend Analysis)
- Average Duration by Subscription Type
- Escalated Tickets by Country-Region
- Company-level Ticket Performance Table

**Insights**
- Ticket volume peaks mid-year and drops sharply in December
- Premier customers show slightly higher average resolution times
- Escalation rates remain consistent across regions

---

### 3️⃣ Geographic & Device Analysis
**Purpose:** Analyze customer distribution and device preferences.

**Visuals Included**
- Total Customers by Country-Region (Map)
- Customer Count by Device Type

**Insights**
- Europe leads in total customer count
- Browser usage is the dominant access method
- Mobile and tablet users form a significant secondary segment

---

## 🎛 Filters & Interactivity
The dashboard supports dynamic filtering by:
- Continent
- Country-Region
- Subscription Type
- Role
- Device
- Escalation Status
- Theme

All visuals update interactively based on selected filters.

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **DAX Measures**
- **Power Query (ETL)**
- **Microsoft Bing Maps / OpenStreetMap**
- **Custom Visuals (Donut, KPI, Matrix)**

---

## 📁 Repository Structure
```text
├── Customer_Success_Support_Analytics.pbix
├── README.md
├── assets/
│   ├── customer_overview.png
│   ├── support_performance.png
│   └── geographic_device_analysis.png
