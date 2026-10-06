# 📊 Retail Apparel – Sample OTD & Production Performance Dashboard

An interactive **Power BI dashboard** developed for a retail apparel company to monitor **Sample On-Time Delivery (OTD), production performance, quality, and operational delays** across the product development lifecycle. Please note the dataset generated is a fake dataset, the purpose of the project is to demostrate the analytics capabilities, domain expertise and Power BI Dashboarding skills, and the project can be scaled by replacing the fakedataset with original data.

<img width="1095" height="610" alt="image" src="https://github.com/user-attachments/assets/b9601f93-aed0-4fcf-903a-2e9d0c853cf8" />


---

## 🎯 Project Overview

In apparel manufacturing, delays at any stage of the sample development process can impact production schedules, customer commitments, and product launches.

This dashboard was designed to provide stakeholders with a **single source of truth for monitoring sample delivery performance**, identifying bottlenecks, and understanding the root causes behind delays.

The analysis connects:

**OTD Performance → Production Stages → Delay Reasons → Sample-Level Actions**

---

## 📌 Key Business Questions

The dashboard helps answer:

- Are samples being delivered on time?
- How is OTD performing compared with last month and last year?
- Which production stages are causing the biggest delays?
- What are the major reasons for delayed samples?
- How much rework is taking place?
- Are production levels meeting demand?
- Which samples are at risk of missing their required dates?

---

## 📊 Dashboard Components

### 1. OTD Performance
- Sample OTD %
- Customer OTD %
- Month-over-month and year-over-year comparison
- Total samples
- On-time samples

### 2. Production Speed
- Average Delay Days
- Average Cycle Time
- Stage-level OTD performance
- Performance across Sales/MR, Material, Pattern, Cutting, VAP, Sewing, Washing, CFT and Logistics

### 3. Quality Performance
- Rework %
- Number of samples reworked
- Rework-related delays

### 4. Production Performance
- SAH Actual
- Demand vs Projection
- Fill Rate
- Production Efficiency

### 5. Delay Root-Cause Analysis

The dashboard breaks down delays into operational categories such as:

- Material Late Arrival
- Material Quality Issues
- Merchant Late / Wrong Handling
- PDC Late / Wrong Handling
- Sales Late / Wrong Handling
- Other operational delays

This allows teams to move beyond **"How late are we?"** to **"Why are we late?"**

### 6. Sample-Level Monitoring

Individual samples can be tracked using:

- Sample Number
- Expected Completion Date
- Required Sample Date
- OTD Prediction
- Current Status

Samples are categorized as:

🟢 **On Schedule**  
🟡 **Just-in-Time**  
🔴 **Miss Alert**

---

## 🛠️ Tools & Technologies

| Technology | Application |
|---|---|
| **Power BI** | Dashboard & visualization |
| **DAX** | KPI calculations & business logic |
| **Power Query** | Data transformation |
| **Excel** | Data preparation |
| **Data Modeling** | Analytical relationships & reporting |

---

## 📈 Business Value

The dashboard enables operations and merchandising teams to:

- Identify **production bottlenecks**
- Detect **at-risk samples**
- Understand **root causes of delays**
- Monitor **quality and rework**
- Compare performance across **brands, seasons and factories**
- Support faster, data-driven operational decisions

Rather than functioning as a static reporting dashboard, the solution connects **high-level KPIs with stage-level and sample-level analysis**.

---

## 🧠 Analytics Approach

```text
Operational Data
       ↓
Data Cleaning & Transformation
       ↓
Data Modeling
       ↓
DAX Measures & KPIs
       ↓
Stage-Level Analysis
       ↓
Delay Root-Cause Analysis
       ↓
Sample-Level Monitoring
       ↓
Interactive Power BI Dashboard
