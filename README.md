# Unlocking Societal Trends in Aadhaar Demographic Updates

This repository contains the complete analytical work developed for the **UIDAI Data Hackathon 2026**.  
The project analyzes aggregated Aadhaar demographic update data to uncover regional trends, demographic behavior, and operational insights that support proactive and privacy-compliant service planning.

---

## 📌 Problem Statement

Aadhaar demographic updates (such as address, mobile number, and age-related changes) reflect underlying population mobility, lifecycle events, and administrative demand.  
However, service planning and resource deployment are often reactive, leading to congestion during peak periods and uneven service availability across regions.

This project aims to identify meaningful patterns and trends in aggregated Aadhaar demographic update data and translate them into actionable insights that support informed governance and operational decision-making.

---

## 📊 Dataset Overview

- **Source:** UIDAI-approved aggregated Aadhaar Demographic Update dataset  
- **Granularity:** State, District, and PIN code level  
- **Time Dimension:** Date-based (Year, Quarter, Month)  
- **Demographic Attributes:** Age-wise update counts (Youth 5–17, Adult 18–60)  
- **Privacy:** No individual-level or personally identifiable information used

---

## ⚙️ Tools & Technologies

- **Power BI Desktop**
- **Power Query Editor (M Language)**
- **DAX (Data Analysis Expressions)**

---

## 🔄 Methodology

1. **Data Ingestion**
   - Imported aggregated CSV data from UIDAI-approved sources

2. **Data Cleaning & Validation**
   - Schema validation
   - Geographic name standardization
   - Missing value handling
   - Duplicate removal
   - Logical checks (non-negative counts)

3. **Data Transformation**
   - Time-based feature engineering (Year, Quarter, Month)
   - Multi-level aggregation (State, District, PIN)
   - Age-wise structuring and density indicators

4. **Prepared Analytical Dataset**
   - Optimized for descriptive, comparative, and trend-based analysis

---

## 📈 Key Analytical Measures

- Total Updates
- Average Updates per Day
- Month-over-Month (MoM) Growth Rate
- Youth vs Adult Update Distribution
- Migration Intensity (Proxy using update density)

All metrics are derived using **aggregated data only**, ensuring full compliance with UIDAI data privacy principles.

---

## 📊 Visual Analysis

The project includes:
- Univariate analysis (top districts, volume distribution)
- Bivariate analysis (state-wise updates and migration category)
- Trivariate analysis (time × geography × age interactions)
- Interactive Power BI dashboards for intuitive insight communication

---

## 🌍 Impact

- Supports **citizen-centric Aadhaar service delivery**
- Enables **proactive infrastructure and staffing planning**
- Identifies **regional demand hotspots**
- Scalable and deployable using existing UIDAI data systems
- Fully privacy-compliant and governance-ready

---

## 📁 Repository Structure

